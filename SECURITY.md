# Télécharger et installer nvm :
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# au lieu de redémarrer le shell
\. "$HOME/.nvm/nvm.sh"

# Télécharger et installer Node.js :
nvm install 24

# Vérifiez la version de Node.js :
node -v # Doit afficher "v24.8.0".

# Vérifier la version de npm :
npm -v # Doit afficher "11.6.0".
# Security Policy

## Reporting a Vulnerability

Instead of opening a GitHub issue for security vulnerabilities, refer to our security.txt: https://expo.dev/.well-known/security.txt
