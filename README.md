### Resumo

Esta modificação foi desenvolvida no formato OCMod, e incrementa o preenchimento automático da url amigável no momento do cadastro ou edição de produtos, departamentos, páginas de informações e marcas.

Uma das grandes vantagens desta modificação é que a url amigável é gerada em tempo real, ou seja, no ato do preenchimento do cadastro ou edição.

A url amigável é gerada utilizando as melhores regras para sua composição, dispensando a preocupação de preenchimento e ajustes por parte do usuário final.

Caso deseje doar um valor para contribuir com este trabalho continuo e sempre gratuito, clique no botão abaixo:

[![alt tag](https://www.paypalobjects.com/pt_BR/BR/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7G9TR9PXS6G5J)

### Instalação

 1. Baixe a modificação no link: https://github.com/opencartbrasil/url-amigavel-automatica/releases. Localize a versão mais atual e compatível do arquivo "url-amigavel-automatica.ocmod.zip".
 2. Na administração da loja acesse o menu Extensions->Extension Installer (Extensões->Instalador).
 3. Na página do instalador, clique no botão Upload e selecione o arquivo 'url-amigavel-automatica.ocmod.zip' (que você baixou deste repositório), e aguarde a conclusão da instalação automática.
 5. Após a instalação, acesse o menu Extensions->Modifications (Extensões->Modificações) e clique no botão Refresh (Atualizar), para que a modificação instalada seja incrementada na loja, lembrando que não é o botão "Atualizar" do navegador, e sim o botão "Atualizar" na cor azul ao lado do botão laranja e vermelho na tela do próprio OpenCart.

### Utilização

Após a instalação nenhuma outra configuração é necessária. Caso utilize mais de um idioma na loja, o idioma padrão da loja, será o idioma utilizado para gerar a url amigável.

### Desinstalação

Para desinstalar a modificação, na administração da loja, acesse o menu Extensions->Modifications (Extensões->Modificações) e selecione a modificação com o nome 'Adiciona a url amigável automaticamente no cadastro ou edição', depois clique no botão Delete (Excluir), e no botão Refresh (Atualizar).

### Atualização

Acesse a administração da loja e execute o procedimento de Desinstalação, depois execute o procedimento de Instalação.

### Dúvidas

O OCMod (OpenCart Modification) é nativo do OpenCart, ou seja, não é necessário instalar nenhum complemento no OpenCart para utilizar modificações ou extensões no formato OCMod, para mais informações sobre o OCMod, segue o link:

https://github.com/opencart/opencart/wiki/Modification-System

### Os arquivos alterados virtualmente através do OCMod são:

admin/view/template/common/header.tpl

admin/controller/catalog/product.php

admin/view/template/catalog/product_form.tpl

admin/controller/catalog/category.php

admin/view/template/catalog/category_form.tpl

admin/controller/catalog/information.php

admin/view/template/catalog/information_form.tpl

admin/view/template/catalog/manufacturer_form.tpl

### Como contribuir

 1. Faça um Fork do projeto e edite os arquivos que desejar.
 2. Faça um Pull para que suas sugestões de melhorias sejam avaliadas e aceitas, caso aprovadas.
 3. Abra uma Inssue com sua dúvida ou sugestão.

### Licença

[GNU General Public License version 3 (GPLv3)](https://github.com/opencartbrasil/url-amigavel-automatica/blob/master/LICENSE)
