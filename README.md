# docusarus

To create docusaurus do follow below doc

```
 https://docusaurus.io/
```` 
Install Node.js version >= 12.13.0 or above (which can be checked by running node -v).

```
# cd ~
# curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
# bash nodesource_setup.sh
# apt update
# apt install nodejs
```
create docusaurus with my-website

```
# npx @docusaurus/init@latest init my-website classic
# cd my-website
# npm install
# npm run build
# npm run serve
```
