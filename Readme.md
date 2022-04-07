
<!-- =================================================================================================== -->

https://github.com/mvonbodun/vtex-cli-utils/releases

<!-- =================================================================================================== -->
<!-- Acessar a pasta e dar permições para rodar os comandos -->
chmod +x ./vtex_impex

<!-- =================================================================================================== -->
<!-- Documentação da API -->
https://developers.vtex.com/vtex-rest-api/reference/catalog-api-post-category

<!-- =================================================================================================== -->
<!-- Video e planilhas exemplos -->
https://drive.google.com/drive/folders/13Pdqwt3LdY8MsxAY3OBbBbiEcBFeOzAU?usp=sharing

<!-- =================================================================================================== -->
create file .env 

ACCOUNT_NAME={conta}
ENVIRONMENT=vtexcommercestable
VTEX_API_APPKEY={chave}
VTEX_API_APPTOKEN={token}

<!-- =================================================================================================== -->
<!-- Exemplo de comandos -->
upload files command:

RUST_LOG=info ./vtex_impex help

RUST_LOG=info ./vtex_impex category -a import -f data/Categories.csv
RUST_LOG=info ./vtex_impex brand -a genbrandfile -f data/out/Brands.csv --product_file data/Products.csv