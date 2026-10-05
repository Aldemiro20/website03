# Juntos Somos Mais Fortes — Landing page 3D

Uma única página (`index.html`) em HTML, CSS e JavaScript, com Three.js carregado por CDN (cdnjs, versão r128).

## Como usar
Abra `index.html` no navegador (com ligação à internet, para carregar o Three.js e as fontes) ou envie o ficheiro para qualquer alojamento web.

## Como funciona a cena 3D
Um campo de partículas muda de forma à medida que se faz scroll, uma forma por capítulo:
1. Unidos: três anéis entrelaçados (o símbolo da marca)
2. Ubuntu: um globo, em que cada ponto é uma pessoa
3. Serviços: um cubo, com uma face por serviço
4. Valores: quatro pilares
5. Impacto: uma onda que se propaga
6. Contacto: os anéis voltam a unir-se

As formas estão definidas no script, no bloco "Formas-alvo". A posição e a escala de cada forma por capítulo estão em `frames`.

## A substituir antes de publicar
- [EMAIL], [TELEFONE] e [ENDEREÇO] na secção de contacto
- Confirmar os números de impacto (+10, +50, +30)
