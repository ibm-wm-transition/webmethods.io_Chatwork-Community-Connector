# webmethods.io_Chatwork-Community-Connector

This is a Webmethods.io community connector for [Chatwork](https://ja.wikipedia.org/wiki/ChatWork).Chatwork is a cloud-based business chat tool provided by Chatwork Inc. Not only exchange of messages, task management, file sharing, and the like are possible video calls. The connector uses the [Chatwork REST API](https://download.chatwork.com/ChatWork_API_Documentation.pdf) to make HTTP requests to access or modify a resource. The actions supported by this community connector are:

#### 1. [Get my status](https://download.chatwork.com/ChatWork_API_Documentation.pdf)
#### 2. [Get info](https://download.chatwork.com/ChatWork_API_Documentation.pdf)
#### 3. [Get the list of your contacts](https://download.chatwork.com/ChatWork_API_Documentation.pdf)
#### 4. [Get the list of all chats on your account ](https://download.chatwork.com/ChatWork_API_Documentation.pdf)
#### 5. [Add new message to the chat](https://download.chatwork.com/ChatWork_API_Documentation.pdf)


Learn about other supported actions [here](https://download.chatwork.com/ChatWork_API_Documentation.pdf).

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
This connector requires any [Node](https://nodejs.org/dist/) version between 8.14.0 and 10.14.0

Note: If you have installed any other Node version on your system, you can:
1. Use tools to switch between different versions of Node

  - For Windows, use [nvm-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades).
  
  - For Mac, use [homebrew](https://brew.sh/).
2. Build your app using your existing Node version and then transpile your code using a transpiler like [Babel](https://babeljs.io/).

The connector has been built with [wmiocli](https://docs.webmethods.io/integration/developer_guide/connector_builder/#gsc.tab=0), webmethod.io's iPaaS Connector Builder CLI tool, which must be installed. 

### Getting the API key 
Follow this link -->
[API Key](https://www.chatwork.com/service/packages/chatwork/subpackages/api/token.php)
Login to your Chatwork Account.
Enter your Chatwork password to generate the API Key.

### Installing
1. Clone the repo `git@github.com:SoftwareAG/webmethods.io_insightly-Community-Connector.git`.
2. Run `npm install -g @webmethodsio/wmiocli`.
3. Login to your webmethods.io tenant using `wmio login`.
4. Execute `wmio init` to get started.
5. Finally, execute `wmio deploy` to deploy this connector to your tenant.

Once deployed, it’ll be automatically registered with webMethods.io Integration and will be available to you locally in the Connectors panel under the Services tab.

## Running the tests
To test, you can execute `wmio test`.

## Deployment
Execute `wmio deploy` to deploy this connector to your webmethods.io tenant. And `wmio unpublish` to unpublish the published connector app along with triggers and actions associated with the app.

![Chatwork Connector](https://github.com/SoftwareAG/webmethods.io_Chatwork-Community-Connector/blob/master/a.png)

## Built With
Node v8.14.0 and [wmiocli](https://docs.webmethods.io/integration/developer_guide/connector_builder/#gsc.tab=0), webmethod.io's iPaaS Connector Builder CLI.

## Contributors
[Anshuman Saikia](https://github.com/anshu96788) |
[Dipankar Dutta](https://github.com/DipankarDDUT) |
[Nawajish Laskar](https://github.com/Nawajish)

## License
This project is licensed under the Apache 2.0 License - see the [LICENSE.md](https://github.com/SoftwareAG/webmethods-microservicesruntime-samples/blob/master/LICENSE) file for details
