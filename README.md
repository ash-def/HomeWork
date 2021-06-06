
# This program contains an ARM templates for storage accounts and for a virtual machine server.

# What is an Azure Resource Manager Template?
Azure Resource Manager templates are JavaScript Object Notation (JSON) files that define your project's infrastructure and configuration.
Templates use declarative syntax. In this way, you can specify what to deploy without writing a series of commands that specify how to deploy it. 
Templates specify the resources to be deployed and the properties of those resources.The template is ready for deployment only after it is validated by Resource Manager. This makes it unlikely that the deployment will fail midway.
The template includes the following parts:
Parameters - values that allow you to use the same template in different environments during deployment.
Variables - values to be reused in different templates. Variables can use values from parameters.
User-Defined Functions - lets you define customized elements to simplify templates.
Resources - specifies Azure resources to be deployed.
Outputs - the return value of the deployed resource.



# pipeline using Azure Devops was lunched and created a yaml file.

# YAML basic elements is given here: 

Comments in YAML begins with the (#) character.

Comments must be separated from other tokens by whitespaces.

Indentation of whitespace is used to denote structure.

Tabs are not included as indentation for YAML files.

List members are denoted by a leading hyphen (-).

List members are enclosed in square brackets and separated by commas.

Associative arrays are represented using colon ( : ) in the format of key value pair. They are enclosed in curly braces {}.

Multiple documents with single streams are separated with 3 hyphens (---).

Repeated nodes in each file are initially denoted by an ampersand (&) and by an asterisk (*) mark later.

YAML always requires colons and commas used as list separators followed by space with scalar values.

Nodes should be labelled with an exclamation mark (!) or double exclamation mark (!!), followed by string which can be expanded into an URI or URL.

