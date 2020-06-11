# Re-arrage Elements for SPAs Extension

This extension allows re-arranging elements on SPAs that break or have problems with the standard Re-Arrange feature of Optimizely's Visual Editor and/or other known JavaScript methods to move elements in the DOM.

(**_Note_**: This extension should work with most websites, but it may not work with all websites. This will depend on the structure of the DOM to change).

## Install the "_Re-arrage Elements for SPAs_" Extension

1. In your Optimizely account, navigate to "**_Implementation > Extensions_**".

2. Click Create New... and select "**_Using JSON_**".

![Image description](https://github.com/luis-colman/text-changes-for-spas/blob/master/images/create_extension.png)

3. Copy the content of the JSON of the repository [Re-arrage Elements for SPAs](https://github.com/luis-colman/Re-arrage-Extension-for-SPAs/blob/master/config.json).

4. Paste the code in the "**_Create Extension From JSON_**" field and click "**_Create Extension_**".

![Image description](https://github.com/luis-colman/text-changes-for-spas/blob/master/images/create_extension_from_json_file.png)

5. If you want to see how the extension is built, simply click the extension name "**_Re-Arrange Elements for SPAs_**". In the "**_Editable Fields_**" panel, you can see and change the current fields the extension contains. Here you can also see the JavaScript code the extension uses by clicking on "**_Apply JS_**", where adjustments can be made - if needed/desired.

6. Before you can use this extension, you need to enable it. After uploading the JSON file the extension will be in "**_draft_**" state. To enable the extension, navigate to "**_Implementation > Extensions_**" and click the **_..._** icon for the "**_Re-Arrange Elements for SPAs**_" extension and select "**_Enable_**".

![Image description](https://github.com/luis-colman/text-changes-for-spas/blob/master/images/enable_optimizely_extension.png)

7. To start using your extension in experiments, simply go into the variation where you want to use this extension and click "**_Create_**" (as you normally do for any other visual change).

8. Under "**_Create Options_**", select "**_Re-Arrange Elements for SPAs_**".

9. Select the element to move.

10. Select the type of re-arrangement you would like to perform (before, after, at the beginning of, at the end of).

11. Select the reference element

10. Save your changes and test the outcome.


**_-- END --_**
