# guardAppPOC
Repo with mocked db.
This repo contains `db.json` file that represents backend data.
The backend data is a little bit redundant and not serialized, for the sake of simplicity when developing mobile app.
In the feature a proper contract is required to keep data consistant.

## The data that is available under
1. Assets: https://my-json-server.typicode.com/Solnick/guardAppPOC/assets
2. Persons: https://my-json-server.typicode.com/Solnick/guardAppPOC/persons

It is exposed via json-server which can handle simple params queries.
For example obtaining asset data by `id`:
https://my-json-server.typicode.com/Solnick/guardAppPOC/assets?id=here_goes_id

## To change the data please
1. Clone the repository
2. Change the data in `db.json`. If you are adding asset, please generate qr code which contains asset id and add it to repository as image file.
3. Commit changes and push it to `master` branch.
4. After successful `push`, the data is available throug the mobile app and directly through above links.
