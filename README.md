# Configurando o Ambiente de Desenvolvimento React Native

## Pré-requisitos

1. **Node.js:** Antes de começar, você precisará ter o Node.js instalado em sua máquina. Você pode baixá-lo [aqui](https://nodejs.org/en/download/).

2. **Expo CLI:** O Expo é um conjunto de ferramentas e serviços construídos em torno do React Native. Para instalar o Expo CLI, execute o seguinte comando no terminal:

```bash
npm install -g expo-cli
```
## Criação do Projeto

1. **Crie um novo projeto React Native:** Execute o seguinte comando para criar um novo projeto React Native chamado "AwesomeProject":

```bash
expo init AwesomeProject
```
2. **Navegue até o diretório do projeto:** Use o comando cd para navegar até o diretório do projeto que você acabou de criar:

```bash
cd AwesomeProject
```
3. **Inicie o servidor de desenvolvimento:** Execute o seguinte comando para iniciar o servidor de desenvolvimento:

```bash
expo start
```

## Executando seu aplicativo React Native

1. **Instale o aplicativo Expo Go em seu dispositivo:** O Expo Go permite que você execute seu aplicativo React Native em um dispositivo físico sem instalar os SDKs nativos do iOS e Android. Instale o Expo Go em seu dispositivo iOS ou Android.

2. **Conecte-se à mesma rede sem fio:** Certifique-se de que seu dispositivo e seu computador estejam conectados à mesma rede sem fio.

3. **Abra seu projeto:** No Android, use o aplicativo Expo Go para escanear o código QR do seu terminal para abrir seu projeto. No iOS, use o scanner de código QR integrado do aplicativo de câmera padrão do iOS.

## Modificando seu aplicativo

Agora que você executou com sucesso o aplicativo, vamos modificá-lo. Abra `App.js` em seu editor de texto de escolha e edite algumas linhas. O aplicativo deve recarregar automaticamente quando você salvar suas alterações.

## Executando seu aplicativo em um simulador ou dispositivo virtual

Se você deseja executar seu aplicativo no iOS Simulator ou em um dispositivo virtual Android, você precisará instalar o Xcode (para iOS) ou o Android Studio (para Android).

1. **Xcode:** O Xcode é a IDE oficial para o desenvolvimento de aplicativos para Mac e iOS. Você pode baixá-lo na App Store.

2. **Android Studio:** O Android Studio é a IDE oficial para o desenvolvimento de aplicativos para Android. Você pode baixá-lo [aqui](https://developer.android.com/studio).

Depois de instalar o Xcode ou o Android Studio, você pode lançar seu aplicativo em um dispositivo virtual Android executando `npm run android`, ou no iOS Simulator executando `npm run ios` (apenas macOS).

## Conclusão

Parabéns! Você executou e modificou com sucesso seu primeiro aplicativo React Native. Agora você está pronto para começar a desenvolver seus próprios aplicativos com React Native. Lembre-se de que a prática leva à perfeição. Continue experimentando e aprendendo!
