# Step 2 - Obtenir un certificat d'authentification pour OrionD

En visitant le [PKI](https://pki.orionet.re/) vous aurez le choix de pouvoir s'authentifier avec le certificat généré durant la partie 1.

![Image of the browser prompting the user for certificate](./img/certificate_auth_prompt.png)

Puis sélectionnez "Client Certificate" comme méthode d'authentification:

![Image of the client certificate auth choice](./img/certificate_auth_method.png)

Vous pouvez ensuite aller dans l'onglet `Request Certificate`:

![Image of the PKI main menu](./img/pki_menu.png)

Et sélectionnez `OrionD Member Certificate`:

![Image of the PKI OrionD Certificate Type](./img/pki_oriond_certificate.png)

Puis choisir l'option "Generate Key on PKI":

![Image of the PKI choice](./img/pki_generate_pki.png)

Vous devez spécifier votre numéro de membre Orion:

![Image of the memberid prompt](./img/pki_memberid_prompt.png)

Des informations supplémentaires vous seront demandées (attention: Ces informations sont succeptibles d'être publiées sur la dashboard de Orion dans le futur):

![Image of the memberid prompt](./img/pki_user_info.png)

Par la suite, envoyez la demande de certificat:

![Image of the memberid prompt](./img/pki_submit_request.png)

Par la suite, un mot de passe sera généré, ce qui sera utilisé pour récupérer la clé privée dans les prochaines étapes:

![Image of the memberid prompt](./img/pki_password.png)

A présent vous devez prévenir un administrateur du réseau Orion afin d'attester la signature de votre certificat
Quand c'est fait, vous serez sur cet écran:

![Image of the memberid prompt](./img/pki_certificate_issued.png)

Vous pourrez ensuite télécharger la clé privée du certificat:

![Image of the memberid prompt](./img/pki_privatekey_download.png)

Pensez bien a mettre les certificats ci dessous pour le téléchargement:

![Image of the memberid prompt](./img/pki_privatekey_download_screen.png)

Vous pouvez ensuite télécharger le "bundle" contenant la chaîne de certificats:

![Image of the memberid prompt](./img/pki_download_chain.png)

## Fin

Vous avez désormais des certificats valables pour l'installation et le fonctionnement de OrionD