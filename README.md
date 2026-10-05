# Android PWA Maker

Site simples e escuro para preparar um PWA Android a partir da URL de um site.

## Recursos

- Detecta título e favicon via metadados do site.
- Permite ajustar o nome e a cor do aplicativo.
- Gera manifest, página inicial, service worker e instruções.
- Interface responsiva com foco em instalação pelo Chrome Android.

## Limitações

O navegador não pode empacotar um aplicativo Android nativo nem alterar o site original. O resultado é um pacote PWA que deve ser hospedado em HTTPS. Alguns sites bloqueiam leitura por CORS; nesses casos o nome é derivado do domínio e o favicon padrão é usado.

## Uso

Abra `index.html` em um servidor HTTPS, informe uma URL e baixe o pacote gerado.