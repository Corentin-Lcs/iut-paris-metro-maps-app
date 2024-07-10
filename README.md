<h1 align="center">Paris Metro Maps App · IUT de Paris - Rives de Seine</h1>

The "Paris Metro Maps App" GitHub project is an intuitive and interactive way to navigate the Paris metro system. This app offers detailed maps, precisely calculated travel times using the Dijkstra algorithm, and essential information for travelers and commuters using the Paris metro.

> [!IMPORTANT]  
> The project has been developed exclusively in a professional context, with the specific aim of promoting learning. It is carried out as a project for the University of Paris.

<p align="center">
  <img src="https://github.com/Corentin-Lcs/iut-paris-metro-maps-app/blob/main/DesCartographie.png" alt="DesCartographie.png"/>
</p>

## Usage

The application offers user account management. Users can login in two ways:

- Traditional authentication using an email address and password,
- Google OAuth 2.0 authentication, providing a simplified login without the need for a password.

> [!NOTE]
> For security reasons, the `client_secret_SECRET_CHARACTER_STRING_HERE.apps.googleusercontent.com.json` file is not included in this directory.

After logging in, users can use the application to save and delete routes, associating them with names. There is a dedicated user area for these functionalities.

> For more details regarding Google OAuth 2.0 authentication and related information, here are some useful links:
>
> Link 1 : <https://developers.google.com/identity/protocols/oauth2> [EN]
>
> Link 2 : <https://www.oauth.com/oauth2-servers/signing-in-with-google> [EN]
>
> Link 3 : [https://medium.com/guide-to-using-oauth-2-0-to-access-google-apis-dead94d6866d](https://medium.com/@tony.infisical/guide-to-using-oauth-2-0-to-access-google-apis-dead94d6866d) [EN]

## Project's Structure

```
iut-paris-metro-maps-app/
├─ README.md
├─ LICENSE
├─ DesCartographie.png
└─ src/
    ├─ index.html
    ├─ api.php
    ├─ composer.json
    ├─ composer.lock
    ├─ .htaccess
    ├─ assets/
    │   ├─ css/
    │   │   └─ style.css
    │   ├─ imgs/
    │   │   ├─ favicon.png
    │   │   ├─ google-logo.png
    │   │   ├─ map-icon.png
    │   │   └─ lines/
    │   │       ├─ alert.png
    │   │       ├─ arrow.png
    │   │       ├─ arrow/
    │   │       │   ├─ 1.png
    │   │       │   ├─ 2.png
    │   │       │   ├─ ...
    │   │       │   ├─ 13.png
    │   │       │   └─ 14.png
    │   │       ├─ connection.png
    │   │       ├─ default/
    │   │       │   ├─ 1.png
    │   │       │   ├─ 2.png
    │   │       │   ├─ ...
    │   │       │   ├─ 13.png
    │   │       │   └─ 14.png
    │   │       ├─ empty/
    │   │       │   ├─ 1.png
    │   │       │   ├─ 2.png
    │   │       │   ├─ ...
    │   │       │   ├─ 13.png
    │   │       │   └─ 14.png
    │   │       └─ selected.png
    │   ├─ js/
    │   │   ├─ index.js
    │   │   ├─ map.js
    │   │   └─ path.js
    │   └─ json/
    │       ├─ interconnection.json
    │       └─ stations.json
    ├─ database/
    │   └─ descartographiedb.sql
    └─ vendor/
        ├─ autoload.php
        ├─ composer/
        ├─ ...
        ├─ google/
        └─ symfony/
```

## Meta

Created by [@Corentin-Lcs](https://github.com/Corentin-Lcs). Feel free to contact me !

Distributed under the GNU GPLv3 license. See [LICENSE](https://github.com/Corentin-Lcs/iut-paris-metro-maps-app/blob/main/LICENSE) for more information.
