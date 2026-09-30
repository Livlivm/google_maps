# Google Maps Flutter

O uso de mapas interativos está presente em diferentes tipos de aplicações que trabalham com localização, como sistemas de transporte, entregas, mobilidade e serviços baseados em posição geográfica.

Neste projeto, foi desenvolvida uma aplicação em Flutter integrada ao Google Maps, permitindo visualizar uma localização inicial e selecionar novos pontos diretamente sobre o mapa. A partir da seleção, o sistema apresenta automaticamente as coordenadas do local escolhido.

---

## Proposta do Projeto

A aplicação foi criada para colocar em prática a utilização de mapas dentro de um projeto Flutter, explorando recursos de localização e interação com o usuário.

Ao iniciar o sistema, uma posição inicial é apresentada no mapa. O usuário pode clicar em qualquer região disponível e selecionar um novo ponto. Após a seleção, suas coordenadas são identificadas e exibidas na tela.

### Funcionalidades Desenvolvidas:

- Exibir um mapa interativo;
- Definir uma localização inicial;
- Apresentar um marcador de origem;
- Permitir a seleção de novos pontos no mapa;
- Identificar latitude e longitude;
- Exibir as coordenadas selecionadas;
- Adicionar um marcador no ponto escolhido;
- Atualizar as informações conforme a interação do usuário;
- Utilizar gerenciamento de estado com `setState`;
- Executar o projeto através do Flutter Web.

---

## Prints

<img width="1221" height="906" alt="Google Maps Flutter" src="COLOQUE_AQUI_O_LINK_DA_IMAGEM" />

---

## Tecnologias Utilizadas

- **Flutter**
- **Dart**
- **Google Maps API**
- **`google_maps_flutter`**
- **Flutter Web**

---

## Interface da Aplicação

A interface foi desenvolvida de maneira simples e objetiva, apresentando as informações necessárias para a interação com o mapa.

Na tela são apresentados:

- Coordenadas da localização inicial;
- Informação sobre o ponto selecionado;
- Mapa interativo;
- Marcador da origem;
- Marcador do ponto escolhido.

---

## Interação com o Mapa

Ao iniciar a aplicação, uma coordenada é utilizada como referência para posicionar a câmera do mapa.

```dart
static const LatLng pontoInicial = LatLng(
  -22.7130000,
  -46.8180000,
);
