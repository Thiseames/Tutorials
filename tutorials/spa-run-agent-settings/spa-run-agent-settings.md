---
title:  Agent Management Settings to Execute the Process with an Automation
description: Create an agent attribute in the tenant to add it to your agent and project
auto_validation: true
time: 15
tags: [ tutorial>beginner, software-product>sap-business-technology-platform, tutorial>free-tier]
primary_tag: software-product>sap-process-automation
---

## Prerequisites
 - Access to a [SAP BTP tenant with SAP Process Automation](spa-subscribe-booster)

## Details
Agent attributes allow you to sort agents  and make sure that a specific agent executes the job of your choice.

### You will learn
  - How to create an Agent Attribute in the tenant.
  - How to add the attribute to your agent.
  - How to add the attribute to your project.

---

Agent attributes allow you to sort agents registered within the same tenant and make sure that a specific agent executes the job of your choice.

[ACCORDION-BEGIN [Step 1: ](Create an Agent Attribute in the Tenant)]

Now that you have your project free of errors, ready to be released, you need to add an **Attribute** to your project. But first, you need to create an Agent Attribute.

To do so, please follow these steps:

1. Select **Settings**.

2. Choose **Agent Attributes**.

3. Choose **Create Attribute**.

4. In the **Create Agent Attribute** dialog box, please enter **My Agent Attribute** in the **Name** field.

5. From the **Type** dropdown list, select **Predefined** if you wish to add values or else leave **Free** as **Type**.

    > - **Free** – With this type of attribute, you won't be able to add any predefined value. Whenever you want to use this attribute, you will be able to parametrize the value of this attribute.
    > - **Predefined** – With this type of attribute, you will be able to populate values for any specific attribute.

6. In the **Values** field, you may enter any value you wish (i.e. employee ID).

7. Choose **Create**.

    !![Create Agent Attribute](01-Settings-create-agent-attribute.png)  

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 2: ](Add the Attribute to your Agent)]

1. Choose **Agent List**, then search for your agent and verify that it is idle or ready and connected in unattended mode then click on it.

    !![Settings Agents List](01-Settings.png)

2. Choose **Manage Attributes**.

3. In the **Manage Matching Attributes** dialog box, add your attribute:

      - From the drop-down list, select **My Agent Attribute**
      - Enter the value you selected previously in the **Values** field and press **ENTER**
      - Choose **Confirm**

    !![Settings Add Attribute](01-Settings-agent-attributes-add.png)

[DONE]
[ACCORDION-END]

[ACCORDION-BEGIN [Step 3: ](Add the Attribute to your Project)]

1. Navigate back to your project in the Process Builder.

2. Choose **Settings**.

3. Select **Attributes**.

4. From the dropdown list, select **My Agent Attribute**.

5. Enter your value in the **Values** field and press **ENTER**.

6. Choose **Save**.

7. Choose **Close**.   

      !![Release](00-adding-attribute-value.png)

[VALIDATE_1]
[ACCORDION-END]      

[ACCORDION-BEGIN [Step 4: ](Desktop Agent in Unattended Mode)]

When you are running the process make sure to have the Desktop Agent in unattended mode.

!![Agent in background](Agentbackground.png)

[DONE]
[ACCORDION-END]




---
