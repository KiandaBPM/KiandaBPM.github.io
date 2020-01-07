# Introduction to rules with Kianda

Business rules are what makes Kianda forms come alive. They represent the actual actions users intend to perform when they interact with form components.

> There are 56 default business rules in Kianda and you might easily create more.

In Kianda, we categorise business rules in the below categories:

- **Workflow** - Enables you to execute actions that might change the flow of the information within a process. 
- **Communications** - Enables sending emails or meeting requests or even user (push) notifications.
- **Data** - This is an important and flexible rule group because it allows you to configure CRUD (Create, Read, Update and Delete) actions to configured data sources.
- **File Management** - Allows operations such as the generation of a word document and conversion to PDF and more.
- **Tables** - Provides specialised rules to enable working with tables like sorting, copying table rows to another table and more.
- **Dates** - Enables convenient date calculation with advanced options like ignoring weekends or special dates.

## Conditions

Flexible and dynamic conditions form an important component to make forms fully dynamic. It enables you  to create natural language conditions when rules should be triggered.

![Conditiion Editor](images\condition-editor.png)

## Workflow rules

Kianda workflow rules represents the actions a user intend to perform when they interact with form components. Below are the workflow rules:

1. **Hide or disable:** This rule is used to hide, disable, show or enable a field or a component on the Kianda forms.
2. **Go to form:** Go to form rule navigates the user from the current form to the destination form. This rule could also set the destination form's display mode (Auto / Edit mode / Read mode).
3. **Assign form:** This rule could define a form owner by assigning a user or a group to a form. You could also choose to override or append the form owner.
4. **Process security:** This rule defines the security of the entire process. Using this rule, you could add any user or group with the right permissions to view/update any instances.
5. **Start a process:** Start a process rule helps you create a new instance of the same process or a different process. You could also map the inputs from the current instance to a new instance.
6. **Schedule a rule:** This rule helps you schedule a rule/rules to be triggered one time, hourly, daily, weekly, monthly or immediately. For example, this rule could be used to schedule a daily reminder email to a user if the task is not complete.

## Data rules

Kianda data rules display the actual flow of data while interacting with form components. The flow of data could be internally or externally connected to different data-connectors.

1. **Set form field:** Using this rule you could set a field value of any field. The field value could be a simple text, current date or currently logged in user.
2. **Find items:** This rule is used to find an item from your data-connections. To find an item, you could use a data source filter which acts like a conditional bridge between Kianda and data-connections. If the condition is true, you could map the data source field or text to the Kianda form field.
3. **Create item:** The create item rule is used to create an item on your data-connection. This is a straight forward rule which allows you to connect to your data source and map inputs. Also, you could map a data source field or text back to kianda on success or store an error message on failure.
4. **Update item:** At any point, if you would like to update any item on your data connection, this rule does it. To find an item to update, you could use a data source filter and map the input fields or text.
5. **Delete item:** This rule works exactly like Update item rule. To delete an item from your data connection, you could use a data source filter and map data source field or text from a data connection to Kianda form field.

## Custom rules

Under custom rules, you will find any custom-developed rules available under your developer section. Custom rules provide access to rules that are built for extensibility of Kianda capabilities. This is particularly used in situations when existing rules do not provide the required functionality.

Custom rules have the purpose of providing a user interface for the end-users. If you need to build "a rule" then you should use a custom rule widget.

It allows a developer to quickly build a reusable component that would then be used by process designers in real processes.

Check-out the [development](development.md) section for more details on how to build custom widgets in Kianda.

## Advanced techniques

> [!WARNING]
>
> In Progress

