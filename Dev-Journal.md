установка библиотек:

sudo npm install --save electron react react-dom

sudo npm install express socket.io webrtc

sudo npm install pg

sudo npm install react-router-dom

npm install --save-dev @babel/plugin-proposal-private-property-in-object


--- --- --- --- --- --- --- --- --- --- --- --- --- --- ---

начнем с локальной реализации
фронтэнд

общий (планируемый) функционал уже определен, поэтому на данном этапе требуется продумать клиентскую часть, хотя бы ориентировочно, основу для старта.
в дальниейшем к ней будет добавляться функционал и далее будет необходимо будет связать всё с беком



создание начального проекта:


sudo chown -R $(whoami) ~/.npm

npx create-react-app .

npm run build

npm start

npm run electron


на данном этапе создан макет приложения уровня hello word. в приложении две странички с парой строк текста. успешно запускается реакт и элекшн
