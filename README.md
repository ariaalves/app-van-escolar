# 🚐 Projeto Van Mobile (Gestão de Transporte Escolar)

Aplicativo Android moderno desenvolvido para facilitar a gestão de transporte escolar. O sistema permite o cadastro e gerenciamento de alunos, responsáveis, escolas, turmas e equipe, otimizando a rotina de motoristas e administradores de vans.

## 📱 Funcionalidades

O aplicativo oferece um conjunto completo de ferramentas para gestão:

*   **Gestão de Alunos:** Cadastro completo de estudantes.
*   **Gestão de Responsáveis:** Vínculo entre alunos e seus pais/guardiões.
*   **Gestão de Escolas:** Cadastro de instituições de ensino com busca automática de endereço.
*   **Gestão de Turmas:** Organização dos alunos por turno ou escola.
*   **Gestão de Equipe:** Cadastro de motoristas e monitores.
*   **Integração com API:** Preenchimento automático de endereço via CEP.

## ✍🏽 Protótipo
* [Figma](https://www.figma.com/design/Js2SG7wAaemI8yGyMoUBqX/Rotando?node-id=0-1&t=A3BZcOQOVRQ3O3UR-1)

## 🛠️ Tecnologias e Bibliotecas

O projeto segue as melhores práticas de desenvolvimento Android moderno, utilizando **Kotlin** e **Jetpack Compose**.

### Interface (UI/UX)
*   **[Jetpack Compose](https://developer.android.com/jetpack/compose):** Toolkit moderno para criar interfaces nativas de forma declarativa.
*   **[Material Design 3](https://m3.material.io/):** Sistema de design do Google para componentes visuais padronizados.
*   **[Navigation Compose](https://developer.android.com/jetpack/compose/navigation):** Gerenciamento de navegação entre telas e fluxo do aplicativo.
*   **Material Icons Extended:** Biblioteca de ícones vetoriais.

### Rede e Integração (API)
*   **[Retrofit 2](https://square.github.io/retrofit/):** Cliente HTTP type-safe para Android. Utilizado para realizar requisições à API externa.
*   **[Gson Converter](https://github.com/google/gson):** Serialização e desserialização automática de JSON para objetos Kotlin.
*   **[ViaCEP API](https://viacep.com.br/):** Webservice público gratuito para consulta de Código de Endereçamento Postal (CEP).

### Arquitetura e Dados
*   **MVVM (Model-View-ViewModel):** Padrão arquitetural para separação de responsabilidades.
*   **[Room Database](https://developer.android.com/training/data-storage/room):** Biblioteca de persistência que fornece uma camada de abstração sobre o SQLite (Banco de dados local).
*   **Coroutines & Flow:** Para programação assíncrona e fluxos de dados reativos.

## 📡 Integração com ViaCEP (Exemplo)

Para facilitar o cadastro de escolas, o projeto utiliza o **Retrofit** para consumir a API do ViaCEP.

### 🚀 Como rodar o projeto

Clone este repositório.2.Abra o projeto no Android Studio Ladybug (ou superior).3.Aguarde a sincronização do Gradle baixar as dependências.4.Certifique-se de ter o JDK 17 configurado nas configurações do Gradle.5.Execute o projeto em um Emulador ou Dispositivo Físico.
