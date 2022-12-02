# Understanding App Hierarchy and Interitence

## Introduction <a id="introduction"></a>

⭐ Whenever you create an app in **Emgage**, it is always associated to a parent. 

⭐ Under every new child app, further child apps can be created. This hierarchical structure can be extended to any level as per requirement.

⭐ This hierarchical management of apps offers superior flexibility and gives effective control over the app resources.

⭐ In this page, you will get to know how these hierarchies work and how to benefit from them.


<BR>



## App Hierarchy <a id="apphierarchy"></a>
<BR>

1. From the Dashboard, navigate to;  ``Left Nav Bar``  and click the ``Select App`` button. You will see a screen as shown below.

    ![](../resources/2.5New.png)

<BR>

2. At the root, there is a system defined app called **Global**.
    - **Global** app is the parent of all apps created in **Emgage**
    - All child apps inherit properties, resources or controls defined in the **Global** app.
    - If you want to create an app that inherits resources defined in the Global app only, then choose the **Global** app and refer to [ Create a New Child App Guide](1.createnewchildapp.md) for further details.

<BR>

3. Endless hierarchy levels can be created in **Emgage**. 

    - Refer to the above screenshot, The app **Project- Chip Design** is created under the parent named **Customer - Intel**, which is created under the parent **Cybersecurity Provider**.
    - Note that the parent application named **Cybersecurity Provider** lies under the source app named **Global**.

<BR>

4. No app can be created above **Global**. <BR>


## Inheritence in Hierarchy <a id="InheritenceinHierarchy"></a>
<BR>

1. In simple terms, Inheritance means reception of resources or properties from parent to the child. 

1. When a child app is created in ****Emgage****, all properties, resources or controls of the parent are automatically available in the child app.

1. New properties, resources or controls created in the child app are available to the child app only and are not reflected in any other app or its parent app.

    ![](../resources/2.5New.png)

1. Refer to the Hierarchy Levels in the figure above, the Inheritance of app resources for the **Project- Chip Design** are;
    - All the resources available in the app named **Customer - Intel**. 
    
    - All the resources available in the app named **Cybersecurity Provider**.

    - All the resources available in the app named **Global**.

1. The Inheritance of app resources for the **Customer - Intel** are;
   
    - All the resources available in the app named **Cybersecurity Provider**.

    - All the resources available in the app named **Global**.


1. **Global** is the parent of all apps.

