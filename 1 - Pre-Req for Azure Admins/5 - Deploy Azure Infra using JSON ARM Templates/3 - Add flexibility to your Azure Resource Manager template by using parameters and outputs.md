# 3 - Add flexibility to your Azure Resource Manager template by using parameters and outputs

## 🎯 Goal:
Learn how to make your ARM templates more flexible by using parameters and outputs.

## 🧠 1. Break it Down
### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
- Parameters allow customization of templates during deployment.
- Outputs return values after deployment to use in other processes.

### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key Features**
- Use parameters for environment-specific values.
- Secure sensitive data using `secureString` or `secureObject`.

### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**
- Parameters can be used to adjust resource names, SKUs, and other settings.
- Outputs allow you to capture values from deployed resources, like a storage account’s endpoint.


The available properties for a parameter are:

| Example        |
|----------------|
| "parameters": { |
|   "<parameter-name>": { |
|     "type": "<type-of-parameter-value>", |
|     "defaultValue": "<default-value-of-parameter>", |
|     "allowedValues": [ |
|       "<array-of-allowed-values>" |
|     ], |
|     "minValue": <minimum-value-for-int>, |
|     "maxValue": <maximum-value-for-int>, |
|     "minLength": <minimum-length-for-string-or-array>, |
|     "maxLength": <maximum-length-for-string-or-array-parameters>, |
|     "metadata": { |
|       "description": "<description-of-the-parameter>" |
|     } |
|   } |
| } |


The allowed types of parameters are:
- string
- secureString
- integers
- boolean
- object
- secureObject
- array

## 🔍 2. Summary
Parameters make your ARM templates flexible by allowing input for different deployments, while outputs enable easy access to deployed resource data.

## 🔥 3. Analogy
Think of parameters like filling in a form before submitting it — you input your specifics, and the template adjusts accordingly. Outputs are like getting a receipt with important details from your purchase.
