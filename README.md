* Clone this project
* Run: ./gradlew generate

This will run the dummy Builder implementation located here:[SampleSDKBuilder.java](src/main/java/com/liferay/mobile/sample/SampleSDKBuilder.java). Start your own implementation by changing this class.

[gradle.properties](gradle.properties) contains the necessary parameters to fetch information about the remote service. The `platform` value must match the [builder.properties](src/main/resources/builder.properties) key that contains your Builder implementation class name.
