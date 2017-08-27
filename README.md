# Adventure Works Knowzy Backlog

There are four User Stories that we are focusing on for this iteration. Each User Story is split into multiple deliverables that each contains several tasks. You will find two types of tasks:

* Required - we've done our research, you just need to implement the work and learn the technology along the way
* Optional - we like this idea, but we have not decided on the implementation, it's up to you

User stories are mostly self contained and can be completed in parallel. However, as you get farther along in a specific user story, you might run into tasks that depend on other User Stories. Therefore, the recommendation is to assign the user stories to members of your team and to tackle them in parallel.

If you are blocked, a representative from the leadership team is always there to help, don't be afraid to reach out.

The source code for our applications is all open source and can be found on [our github account](https://github.com/Knowzy/KnowzyInternalApps).

* [**Machine Setup Instructions**](https://github.com/cheahengsoon/BuildTourHack/blob/master/stories/0/0_Setup.md)

* **User Story** - The shipping department has a fast, responsive, and powerful application for managing day to day duties

  * **Deliverable** - Make app more responsive
    * [1.1.1 \[Required\] - Build a responsive Web App](https://github.com/cheahengsoon/BuildTourHack/blob/master/stories/1/111_BuildWebApp.md)
    * [1.1.2 \[Required\] - Generate Progressive Web App \(d. 1.1.1\)](stories/1/112_GeneratePWA.md)
    * [1.1.3 \[Required\] - Update Web App to PWA \(d. 1.1.1\)](stories/1/113_ConfigureSW.md)
    * [1.1.4 \[Required\] - Test Your App \(d. 1.1.1\)](stories/1/114_Test_App.md)
  * **Deliverable** - Add Native functionality
    * [1.2.1 \[Required\] - Add Live Tile \(d. 1.1.1\) ](stories/1/121_Add_WIndows_Feature.md)
    * [1.2.2 \[Optional\] - Add Share and Secondary Pinning \(d. 1.1.2\)](stories/1/122_BONUS-RenoFeatures.md)
    * [1.2.3 \[Optional\] - Make PWA Linkable \(d. 1.1.2\)](stories/1/123_BONUS-APP-Links.md)
    * [1.2.4 \[Optional\] - Add In-Memory Caching](stories/1/124_BONUS_InMemoryCaching.md)

* **User Story** - The product department has a modern, secure and forward-looking platform for managing product development life cycle

  * **Deliverable** - Enable integration of UWP APIs
    * [2.1.1 \[Required\] - Add Desktop Bridge support in Visual Studio](stories/2/211_Centennial.md)
    * [2.1.2 \[Required\] - Debugging a Windows Desktop Bridge App \(d. 2.1.1\)](stories/2/212_Debugging.md)
    * [2.1.3 \[Required\] - Adding UWP APIs to a Desktop Bridge App \(d. 2.1.2\)](stories/2/213_AddUwp.md)        
    * [2.1.4 \[Required\] - Integrate Windows Hello authentication \(d. 2.1.3\)](stories/2/214_WindowsHello.md)
  * **Deliverable** - Add UWP XAML support
    * [2.2.1 \[Required\] - Create a new XAML view as part of app package \(d. 2.1.1\)](stories/2/221_XAMLView.md)
    * [2.2.2 \[Required\] - Add support for other apps to share images and create new items \(d. 2.1.1\)](stories/2/222_Share.md)
    * [2.2.3 \[Required\] - Create a new UWP app that integrates with App Services \(d. 2.1.1\)](stories/2/223_AppServices.md)
  * **Deliverable** - Build enhanced UWP experience \(d. 2.2.\*\)
    * [2.3.1 \[Optional\] - Add support for ink \(d. 2.2.\*\)](stories/2/231_Inking_Dial.md)
    * [2.3.2 \[Optional\] - Add complete support for Windows Hello Authentication \(d. 2.1.3\)](stories/2/232_Windows_Hello.md)
    * [2.3.3 \[Optional\] - Add support for more UWP features \(d. 2.2.\*\)](stories/2/233_Extend.md)

* **User Story** - Consumers have a fun mobile experience

  * **Deliverable** - Create a UWP and Android mobile app
    * [3.1.1 \[Required\] - Create a Xamarin.Forms app with shared UI](stories/3/311_XamarinForms.md)
    * [3.1.2 \[Required\] - Integrate native camera to capture image for each platform \(d. 3.1.1\)](stories/3/312_Camera.md)
    * [3.1.3 \[Required\] - Add InkCanvas support for UWP \(d. 3.1.2\)](stories/3/313_InkCanvas.md)
  * **Deliverable** - Add intelligence to the mobile app
    * [3.2.1 \[Required\] - Set up Cognitive Services Custom Vision Service](stories/3/321_CustomVisionService.md)
    * [3.2.2 \[Required\] - Set up Cognitive Services Emotion Service \(d. 3.2.1\)](stories/3/322_EmotionAPI.md)
    * [3.2.3 \[Required\] - Update Xamarin App to call Cognitive Services APIs \(d. 3.2.2\)](stories/3/323_IntegrateCogSvc.md)
  * **Deliverable** - Create a fun social experience
    * [3.3.1 \[Optional\] - Support sharing images to Social Networks \(d. 3.2.3\)](stories/3/331_Social.md)
    * [3.3.2 \[Optional\] - Support cross device scenarios \(Project Rome\) \(d. 3.3.1\)](stories/3/332_Rome.md)
  * **Deliverable** - Add automatic image analysis
    * [3.4.1 \[Optional\] - Set up Cognitive Services for image face analysis in Azure \(d. 323\)](stories/3/341_CognitiveServices.md)
    * [3.4.2 \[Optional\] - Create an Azure Function to analyze an image and return nose location to automatically position in app \(d. 3.4.1\)](stories/3/342_AzureFunction.md)
  * **Deliverable** - Set up Continuous Integration and Deployment
    * [3.5.1 \[Optional\] - Set up Continuous Integration and Deployment for the Windows App using Visual Studio Mobile Center](stories/3/351_CICD_WindowsApp.md)
    * [3.5.2 \[Optional\] - Set up Continuous Integration and Deployment for the Android App using Visual Studio Mobile Center](stories/3/352_CICD_AndroidApp.md)
    * [3.5.3 \[Optional\] - Add Custom Event Logging using Visual Studio Mobile Center](stories/3/353_EventLogging.md)
  * **Deliverable** - Create a chat bot for support and for order status management 
    * [3.6.1 \[Optional\] - Create a bot using the Microsoft Bot Framework](stories/3/361_Bot.md)

* **User Story** - All platform services are integrated in one platform

  * **Deliverable** - Unify and Publish all services
    * [4.1.1 - \[Required\] Create a shared CosmosDB to store all data](stories/4/411_CosmosDB.md)
    * [4.1.2 - \[Required\] Create API endpoint for shipping services \(d. 4.1.1\)](stories/4/412_OrdersAPI.md)
    * [4.1.3 - \[Required\] Create API endpoint for product services \(d. 4.1.1\)](stories/4/413_ProductsAPI.md)
    * [4.1.4 - \[Required\] Create Docker images \(d. 4.1.2, 4.1.3\)](stories/4/414_Docker.md)
    * [4.1.5 - \[Required\] Configure Kubernetes and publish to Azure \(d. 4.1.4\)](stories/4/415_Kubernetes.md)
    * [4.1.6 - \[Optional\] Integrate Website and APIs \(d. 4.1.5\)](stories/4/416_Integrate.md)
  * **Deliverable** - Set up Continuous Delivery
    * [4.2.1 - \[Optional\] Set up Visual Studio Team Services](stories/4/421_SetupVSTS.md)
    * [4.2.2 - \[Optional\] Continuous Delivery to Kubernetes using VSTS \(d. 4.1.5, 4.2.0\)](stories/4/422_DevopsKubernetes.md)
  * **Deliverable** - Set up Telemetry
    * [4.3.1 - \[Optional\] Set up telemetry for the web app and APIs](stories/4/431_Telemetry.md)

Good luck!

