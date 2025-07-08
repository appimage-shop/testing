# App.json - Catálogo de Aplicativos AppImage (Versão de Testes)

Este repositório contém uma **versão de testes** do arquivo `app.json`, que serve como a fonte de dados para o **AppImage Shop**. Ele é usado para experimentação, testes de novas entradas de aplicativos e validação antes que as alterações sejam incorporadas ao catálogo principal.

-----

## O que é `app.json`?

O `app.json` é um arquivo JSON que organiza e lista os metadados de todos os AppImages disponíveis através do AppImage Shop. Ele permite que o AppImage Shop exiba informações detalhadas sobre cada aplicativo, gerencie instalações, atualizações e remoções.

-----

## Como Usar:

O **AppImage Shop** utiliza um arquivo `app.json` remoto como seu catálogo principal de aplicativos. Este repositório de testes é uma cópia desse conceito, mas destinada a:

  * **Testar novas entradas:** Adicionar novos aplicativos ou versões para verificar a formatação e a funcionalidade antes de adicioná-los ao arquivo principal.
  * **Experimentar alterações na estrutura:** Propor e testar modificações na estrutura do próprio JSON.
  * **Colaboração em testes:** Permitir que contribuidores testem suas sugestões de AppImages de forma isolada.

### Usando este `app.json` de Testes no AppImage Shop

Para que o AppImage Shop utilize este catálogo de testes em vez do catálogo padrão, você pode alterar a URL da fonte de dados nas configurações do aplicativo.

1.  Abra o **AppImage Shop**.
2.  Navegue até o **menu de configurações**.
3.  Selecione a aba Downloads.
4.  Procure pela opção "URL do json de aplicativos".
5.  Altere o valor para:
    ```
    https://raw.githubusercontent.com/appimage-shop/testing/refs/heads/main/app.json
    ```
6.  Salve as alterações e atualize a AppImage Shop para que o novo catálogo seja carregado.

-----

## Contribuição

Sua contribuição é muito bem-vinda para este repositório de testes\!

  * **Envie sugestões de novos AppImages:** Se você tem um AppImage que gostaria de ver no AppImage Shop, pode adicioná-lo a este `app.json` de testes via um **Pull Request**.
  * **Teste novas funcionalidades:** Se houver alguma nova funcionalidade no AppImage Shop que dependa de alterações na estrutura do `app.json`, este é o lugar para testá-las.
  * **Reporte problemas:** Se encontrar algum erro na estrutura ou nos dados, por favor, abra uma **Issue**.

-----

Com este repositório, esperamos facilitar a colaboração e o aprimoramento do catálogo de aplicativos AppImage para o AppImage Shop\!
