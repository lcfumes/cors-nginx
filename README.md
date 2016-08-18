# cors-nginx
Enable CORS with 204 in OPTION

Using Axios (https://github.com/mzabriskie/axios) I had to adapt the NgInx.

The server must inform which Methods and Headers are enabled in the Server. This informations is required by OPTIONS.
After the OPTIONS response the next requisition (POST, PUT, PATCH, DELETE) is to the application.

To see more details, you can look this website: http://enable-cors.org/
