# Ad Skipper usando electron.js

La idea es usando la propiedad [webContents][1] para ejecutar JavaScript y poder hacer click en el elemento de Saltar Anuncio de YouTube.

Para esto podría usar los siguientes métodos de la API [webContents][1] de Electron.js

[WebRTC][5]

### Links

[1]: https://www.electronjs.org/docs/latest/api/web-contents "Documentación de la API webContents de Electrons"
[2]: https://www.electronjs.org/docs/latest/api/web-contents#contentsexecutejavascriptcode-usergesture "Método `ExecuteJavaScript` de la API webContents"
[3]: https://www.electronjs.org/docs/latest/api/web-contents#contentsselectall "Método `selectAll` de la API webContents"
[4]: https://www.electronjs.org/docs/latest/api/web-contents#contentsfindinpagetext-options "Método `findInPage` de la API webContents"
[5]: https://browserleaks.com/webrtc "Como obtener la IP Publica y Local del Usuario usando chrome y **WebRTC**"