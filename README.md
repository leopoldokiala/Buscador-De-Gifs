# Buscador de GIFs (Flutter + Giphy API)

Aplicativo desenvolvido com **Flutter** que permite **pesquisar e visualizar GIFs animados em tempo real**, utilizando a **API do Giphy**. É possível navegar por GIFs em alta, procurar por palavras-chave, compartilhar com um clique e visualizar em tela cheia.

---

## #✨ Funcionalidades

- Pesquisa de GIFs por palavras-chave (usando a API do Giphy)
- Exibição dos GIFs mais populares quando nenhum termo de busca é informado
- Visualização de GIF em tela cheia ao tocar
- Compartilhamento rápido de GIFs via botão de ação ou toque longo
- Paginação com botão **"Carregar mais..."** ao final da lista de resultados
- Imagens carregadas com efeito de transição suave (FadeInImage)
- Interface elegante com tema escuro

---

## 🧱 Tecnologias utilizadas

- [Flutter](https://flutter.dev/)
- [Dart](https://dart.dev/)
- [HTTP](https://pub.dev/packages/http) – para chamadas REST à API do Giphy
- [Giphy API](https://developers.giphy.com/)
- [Share Plus](https://pub.dev/packages/share_plus) – para compartilhar GIFs
- [Transparent Image](https://pub.dev/packages/transparent_image) – placeholder transparente para imagens em transição

---

## Como executar o projeto

1. Certifique-se de ter o **Flutter SDK** instalado.
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/buscador-de-gifs.git

Navegue até o diretório do projeto:
cd buscador-de-gifs

Instale as dependências:
flutter pub get

Execute o app em um emulador ou dispositivo:
flutter run
