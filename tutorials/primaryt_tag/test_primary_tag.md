---
title: tutorial with primary tag
description: Learn how to insert labels into the detail view of your app and add additional fields.
tags: [ tutorial>HANA ]
primary_tag: tutorial>HANA
auto_validation: true
---

## Prerequisites
 - **Proficiency:** Beginner
 - **Tutorials:** [Deploy your mobile web app to SAP HANA Cloud Platform](http://go.sap.com/developer/tutorials/hcp-deploy-mobile-web-app.html)

## Next Steps
 - [Round the currency field using JavaScript](http://go.sap.com/developer/tutorials/hcp-webide-round-currency.html)

## Details

### You will learn
When you built the app in previous tutorial series, the template added two fields in the detail view header (`UnitsInStock` and `UnitsOnOrder`). Those fields appear in the detail view without labels, so you will add some for them.

 ![Application fields requiring labels](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-add-labels-field/mob2-1_0.png)

To explore a bit more of SAP Web IDE, you will use the Web IDE search feature to identify which file to edit.

You will also learn how to add a field to your app. This is useful since the template can quickly generate a working app for you, but you are not restricted to what it generates.

### Time to Complete
**<5 min**

### Adding labels to the Detail View1

---

1. In SAP Web IDE, click on the **Search icon** (the magnifying lens icon at the top of the right-hand toolbar), enter `UnitsInStock` in the search field and click **Search**.

    ![Activating the SAP Web IDE search pane](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-add-labels-field/mob2-1_label_1.png)

2. In the search results, and you will see two files were found. One is in the **Detail.view.xml** file which is in the view folder. Since you want to change the detail view part of the app – that is the file to edit.

    >Tip: If you hover your cursor over an item in the search result list, a window opens to show some context around that item.

    ![SAP Web IDE search pane results](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-add-labels-field/mob2-1_label_2.png)


3. Double-click the UnitsInStock line in **Detail.view.xml** to open that file in the edit pane.

    >Notice that the search term is highlighted in the source file. You can click on the **Search icon** again to close the search pane.

    ![Clicking on SAP Web IDE search pane results](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-add-labels-field/mob2-1_label_3.png)

4. You will need to modify two **ObjectAttribute** lines in the header: **UnitsInStock** and **UnitsOnOrder**.

    ![XML view elements to modify](https://raw.githubusercontent.com/SAPDocuments/Tutorials/master/tutorials/hcp-webide-add-labels-field/mob2-1_label_4.png)

5. Insert the titles as attributes into the ObjectAttribute areas highlighted on the right below. You can type in the `title="xyz"` strings, or replace the lines entirely with the text below. The edited lines should look like the screenshot below.

[ACCORDION-BEGIN [STEP 1](Test 1)]
[VALIDATE_1]
[ACCORDION-END] 

[ACCORDION-BEGIN [STEP 2](Test 2)]
[VALIDATE_2]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 3](Test 3)]
[VALIDATE_3]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 4](Test 4)]
[VALIDATE_4]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 5](Test 5 - Http)]
[VALIDATE_5]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 6](Test 6 - without question)]
[VALIDATE_6]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 7](Test 7 - single choice)]
[VALIDATE_7]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 8](Test 8 - multiple choice)]
[VALIDATE_8]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 9](Test 9 - id - updated)]
[VALIDATE_9]
[ACCORDION-END]

[ACCORDION-BEGIN [STEP 9](Test 10 - You are done)]
[DONE]
[ACCORDION-END]
