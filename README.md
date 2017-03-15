# Maven using Nexus OPS Toolchain

This Hello World application uses Java and includes a DevOps toolchain that is preconfigured for continuous delivery, source control, and 
integration with a user-provided Nexus server. The OPS toolchain expects to find the modules in the Nexus server, provided by 
the [Maven using Nexus Development Toolchain](https://github.com/open-toolchain/dev-maven-toolchain).

To get started, click **Create toolchain**. You will need to fill in six items in the Nexus integration:
- _Integration URL_: The console URL for your Nexus server.
- _User ID_: Your Nexus userid.
- _Authentication token_: Your Nexus password.
- _Release URL_: Your Maven release repository.
- _Snapshot URL_: Your Maven snapshot repository.
- _Mirror or public URL_: Your virtual repository that can serve your private repositories as well as Maven Central.


[![Deploy To Bluemix](https://console.ng.bluemix.net/devops/graphics/create_toolchain_button.png)](https://console.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/open-toolchain/ops-maven-toolchain)

For more information about toolchains, see [Custom toolchains in one click with IBM Bluemix DevOps Services](https://developer.ibm.com/devops-services/2016/06/16/open-toolchain-with-ibm-bluemix-devops-services/).

