


# lib_Amazon

Amazon AWS Connector
## Symbols

| Symbol                          | Usage                      |
|---------------------------------|----------------------------|
| `lib_amazon.AWS_ACCESS_KEY`     | Your AWS Access Key        |
| `lib_amazon.AWS_ACCESS_KEY.secret` | Your AWS Access Secret Key |
| `lib_amazon.AWS_REGION`         | The AWS Region             |




For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Sequences](#sequences)
    - [EcsListServices](#ecslistservices)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_Amazon=https://github.com/convertigo/c8oprj-lib-amazon.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_Amazon=https://github.com/convertigo/c8oprj-lib-amazon/archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_Amazon__ project


## Sequences

### EcsListServices

List services from a Cluster

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>cluster</td><td>Cluster  Name</td>
</tr>
</table>



