# Appian
Welcome to the Appian Projects repository! This Git repository is dedicated to storing detailed notes, documentation, and information related to our Appian projects. Whether you're a developer, project manager, or stakeholder, this repository serves as a central hub for tracking and sharing insights about Appian implementations.

Appian official Website 
https://appian.com/

What is Appian? 
  The trusted company and platform for AI process automation.
      https://appian.com/about/explore/overview.html
      https://appian.com/blog/2018/5-benefits-of-a-platform-as-a-service.html
  Appian is a software company that automates business processes. The Appian AI Process Platform includes everything you need to design, automate, and optimize even the most complex processes, from start to finish. 
  The world's most innovative organizations trust Appian to improve their workflows, unify data, and optimize operations—resulting in better growth and superior customer experiences.

The Appian Guarantee.
  Fast to build, fast to learn.
  Your first app delivered in 8 weeks with a flat services fee. It’s the Appian Guarantee. We also guarantee that anyone with a technical background can be trained as an Appian Developer in just 2 weeks.

# My Appian Profile

https://community.appian.com/members/anurags5053 
https://community.appian.com/members/anurags8175

# Design Patterns for new Project
https://community.appian.com/success/w/guide/3066/antipatterns-solution-design-mistakes-to-avoid-in-appian
https://community.appian.com/success/w/guide/3064/how-to-create-flexible-processes
https://community.appian.com/success/w/article/3048/how-to-create-memory-efficient-models
https://community.appian.com/success/w/guide/3314/best-practices-appian-user-stories#heuristics_of_complex_user_stories
https://community.appian.com/success/w/guide/3294/sql-scripts-that-can-be-rerun
https://community.appian.com/success/w/guide/3058/frequently-reused-appian-components
https://community.appian.com/success/w/guide/3491/add-error-handling-to-stored-procedures
https://community.appian.com/success/w/guide/3253/integrating-with-docusign

# Certifications
Source / Links to view updated Appian Policies regarding certifications - 

https://community.appian.com/learn/certifications
https://community.appian.com/learn/certifications/p/faqs
https://community.appian.com/learn/certifications/p/policies
https://community.appian.com/learn/certifications/p/recertification

Appian professionals have the option to pursue various Appian certifications, including Analyst, Associate Developer (Project Ready), Senior Developer {Project Independant}, and Lead Developer {Project Lead}, each of which is currently priced at $200.

If practitioners have any inquiries or concerns regarding certifications, they can contact Appian support at certifications@appian.com

Your Appian certification remains valid as long as you adhere to the recertification guidelines. For further details on maintaining your certification, refer to the Appian Recertification Guidelines page.

New developers often tend to gather resources for preparing for Appian certifications from various sources, even though all the necessary information and preparation resources are available on the Appian Community. It is advisable to rely on the official documentation provided by Appian. For accurate and updated details, please refer to the following official links:

https://community.appian.com/learn/certifications/p/certified-analyst
https://community.appian.com/learn/certifications/p/associate-developer
https://community.appian.com/learn/certifications/p/senior-developer
https://community.appian.com/learn/certifications/p/lead-developer

# Appian Best Practices

## Integrations


When creating integrations in Appian, it's essential to follow best practices to ensure efficient and effective design. Here are some key best practices for designing and creating integrations in Appian based on the provided sources:

1. **Naming and Configuration**:
   - Follow the recommended naming standard when naming the integration.
   - Provide a brief description of the integration to enhance clarity.
   - Save the integration in an appropriate folder for easy organization and management[1][3].

2. **Connection Details and Parameters**:
   - Select a connected system or provide authentication details based on the integration requirements.
   - Define request body, content type, parameters, and headers as needed for the integration method (e.g., POST, PUT, PATCH)[1][3].

3. **Testing and Troubleshooting**:
   - Test the integration thoroughly to ensure proper functionality.
   - View details about the request, response, errors, and recommended next steps in the integration designer.
   - Define inputs for reusability and configure default test values for efficient testing[3].

4. **Error Handling**:
   - Add custom error handling within the integration to construct custom error messages.
   - Use a!integrationError() to return errors when needed, ensuring proper error handling and management[3].

5. **Automatic Parsing**:
   - Configure automatic parsing for JSON responses to convert results into Appian values automatically.
   - This feature simplifies data handling and allows for easy access to response data using dot notation and index()[3].

By adhering to these best practices, you can design and create integrations in Appian that are well-structured, efficient, and robust, facilitating seamless data exchange and integration with external systems.

Citations:
[1] https://docs.appian.com/suite/help/24.1/Create_an_Integration.html

## Portals


Best Practices for Portal Creation:
1. **Naming and Configuration**:
   - Enter a name following the recommended standard for the portal object.
   - Define a display name for the portal visible to end-users.
   - Assign a unique web address identifier for the portal.
   - Provide a description for the portal object.
   - Ensure proper configurations for publishing the portal and setting up the web address[1].

2. **Security**:
   - Control access to the portal using service accounts.
   - Implement design-time and runtime security protections to safeguard the portal.
   - Define different permission levels for administrators, editors, and viewers to manage portal actions[1].

3. **Design Guidance**:
   - Follow design guidance recommendations and warnings to reinforce best practices.
   - Address warnings related to invalid parameters, misconfigured data stores, missing document permissions, and connected system plug-ins.
   - Update rule inputs and configurations as needed to maintain optimal portal performance[3].

4. **Compatibility and Integration**:
   - Ensure compatibility with portals by using components and functions that are compatible with portal environments.
   - Utilize integration objects and web APIs to connect partially compatible capabilities to the portal.
   - Create custom integrations to bridge the portal with Appian and allow seamless data flow[2].

5. **Performance Optimization**:
   - Avoid unnecessary database queries in interfaces, expression rules, and other objects.
   - Optimize looping functions by using the Choose() function instead of nested IF conditions.
   - Implement paging and filtering for records to enhance performance and avoid loading all items at once[4].

6. **User Experience**:
   - Design the portal interface considering time zones and localization.
   - Ensure a seamless experience for users accessing the portal without the need to log in.
   - Use low-code tools to create web apps that connect users to information and processes efficiently[5].

By following these best practices, you can design and create an Appian object Portal that is secure, efficient, and user-friendly, meeting the needs of your organization and audience effectively.

Citations:
[1] https://docs.appian.com/suite/help/24.1/portal-object.html
[2] https://docs.appian.com/suite/help/24.1/portals-design.html
[3] https://docs.appian.com/suite/help/24.1/appian-recommendations.html
[4] https://community.appian.com/discussions/f/best-practices/23534/best-practices-to-improve-performance-of-each-appian-object
[5] https://docs.appian.com/suite/help/24.1/sail/ux-portals.html

###############Step-by-Step Guide for Creating a Portal Object:

**1. Accessing the Portal Builder:**

* Navigate to the **Build** view within your Appian application.
* Click on **NEW** and then select **Portal**.

**2. Configuring Portal Properties:**

* **Name:** Enter a unique name that adheres to your organization's naming conventions (developers only see this name).
* **Display Name:** Provide a user-friendly name that will be displayed in the browser tab and potentially the navigation bar (visible to end-users).
* **Web Address Identifier:** Appian automatically generates a unique identifier based on the display name. You can modify it if necessary to create a more descriptive URL.

**Best Practice:**

*  Choose clear and concise names for both Name and Display Name that reflect the portal's purpose.

**3. Creating the Portal (Click "Create")**

**4. Defining Portal Content:**

* After creating the portal object, you'll be presented with configuration options. Here's where you build the actual user interface:
    * **Pages:**  
        * A portal can have one or more pages.  
        * Click the **Plus** icon to add a new page and define its title.
        * Alternatively, select an existing interface to reuse a pre-built layout. 
    * **Page Group:**  
        * Page groups allow you to create a nested menu of pages under a page group title in your portal's navigation bar for an additional level of navigation.
    * **Interfaces:**  
        * Interfaces are the building blocks of your portal pages. They define the layout and user interaction elements like forms, buttons, and data displays.  
        *  Within a page, you can build a new interface from scratch using drag-and- drop functionality or select an existing interface for reuse.

**Best Practices:**

*  Organize your portal content logically with clear page structures. 
*  Utilize pre-built interfaces whenever possible to save development time and maintain consistency.

**5. Configuring Branding (Optional):**

* Appian allows you to customize the look and feel of your portal to match your brand identity. 
* You can define elements like:
    * Logo
    * Colors
    * Fonts

**6. Setting Up Service Account:**

* A service account acts on behalf of portal users, granting the portal access to specific Appian processes and information. 
    * To create a service account, you'll need system administrator permissions.
*  **Permissions:** 
    *  Carefully configure the service account's record type permissions. 
    *  Only grant access to the specific data and processes required by the portal functionalities.

**Best Practices:**

*  Maintain a separate service account specifically for your portal to manage permissions effectively.
*  Assign the least privilege principle - grant only the minimum permissions necessary for the service account to function.

**7. Previewing and Publishing:**

* Once you've configured the portal, you can preview it using the **Branding Preview** option to ensure everything looks as intended.
* When satisfied, click **Publish** to make the portal accessible to end-users through the generated web address.

**Additional Best Practices:**

* **Security:** Regularly review and update portal security configurations, especially service account permissions.
* **Testing:** Thoroughly test the portal's functionality before publishing to identify and resolve any issues.
* **Usability:** Design the portal with user-friendliness in mind, ensuring intuitive navigation and clear instructions.
* **Maintenance:** Regularly update and maintain your portal content to keep it accurate and relevant.
* Use **record types** to connect your Appian data to your portal, as this is the recommended way to work with data in a portal.
* Avoid using incompatible functions or components in your interface.
* Ensure that the **Web Address Identifier** is unique across your environments.
* Consider **branding** and **progressive web app (PWA)** settings to enhance user experience.
* Regularly **test** your portal during development to catch any issues early.


By following these steps and best practices, you can effectively create a secure and user-friendly portal in Appian that facilitates interaction with your Appian applications for external users.

For further reference, you can refer to the official Appian documentation on Portals: [https://docs.appian.com/suite/help/24.1/portal-object.html](https://docs.appian.com/suite/help/24.1/portal-object.html)
