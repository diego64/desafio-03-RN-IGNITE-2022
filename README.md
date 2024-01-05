<p align="center">
  <img width="200px" alt="Project Marketspace Logo" title="Project Marketspace Logo" src="./mobile/src/assets/logo.svg" />
  
  <h1 align="center">Marketspace</h1>

Nesse desafio o objetivo é aplicar conceitos como, Estados, Context API, Consumo de API, Manipulação de imagens, Formulários e Navegação. O aplicativo tem como alvo final ser uma aplicação de anuncio de produtos com o objetivo de vender o mesmo. Os pricipais objetivos do desafio é a inserir as seguintes funcionalidades:

- Login e cadastro de usuários
- Gerenciamento de produtos
- Listagem de produtos com busca e filtros
- Envio de múltiplas imagens

</p>

## Tecnologias

- React Native
- Expo
- TypeScript
- NativeBase
- React Navigation - Native Stack and Bottom Tabs
- Axios
- Expo ImagePicker
- React Hook Form
- Yup
- AsyncStorage
- Phosphor Icons
- React Native Modalize
- React Native Portalize
- React Native Reanimated Carousel

## Layout

Caso queira dá uma olhada no layout, [Figma](https://www.figma.com/file/81TRIMvQ0qhaEXyIC1f8YP/Marketspace-%E2%80%A2-Desafio-React-Native-(Copy)?type=design&mode=design)

## Estrutua das pastas

```plainText
mobile
.
├── assets                      # Images for expo
├── src                         # Source files
│   ├── @types                  # Contains all global definitions of types and interfaces
│   ├── assets                  # Contains Js bundles assets. e.g: icons, splash, images etc...
│   ├── components              # Contains all global react components
│   ├── contexts                # All contexts
│   ├── dtos                    # Models Data Base
│   ├── hooks                   # Application hooks
│   ├── routes                  # Contains application routes
│   ├── screens                 # Contains application screens
│   ├── services                # Config service api
│   ├── storage                 # Contains saving data in locations.
│   ├── theme                   # Contains the theme of the application
│   ├── utils                   # Class utils for system
.
.
├── App                         # Bundle entry
.
```

## 🚀 Running the Project

Clone the project

```bash
  git clone https://github.com/diego64/desafio-03-RN-IGNITE-2022.git
```

### Back-end

Entre na pasta do server

```bash
  cd marketspace-desafio-03-RN-IGNITE-2022/server
```

Instale as dependencias

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

### Mobile

Enter the project directory

```bash
  cd marketspace-desafio-03-RN-IGNITE-2022mobile
```

Instale as dependencias

```bash
  npm install
```

Verifique os aquivo "src/services/api.ts" e coloque o endereço IP do seu computador

Start the server

```bash
  npm run start
```

## 🌎 License

This project is under the MIT license. See the [LICENSE](https://github.com/diego64/desafio-03-RN-IGNITE-2022/blob/main/LICENSE) file for more details.