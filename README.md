# Kontent.ai Custome Element Samples

A collection of simple custom elements for Kontent.ai to demonstrate the capabilities of the Kontent.ai Custom Element and the Kontent.ai Custom Element SDK.

The examples are written in vanilla JavaScript and are intended to be used as a starting point for your own custom elements. Where necessary, the examples will use JQuery to simplify the code.

## Instructions

1. Clone the repository
1. Run migration scripts in the migration folder.
1. Run `dotnet serve -S -p 5001` (or simialr command) to serve the files
1. Use the custom element URL in the Kontent.ai Custom Element configuration

## Custom Elements

1. [Simple Text Input](#simple-text)
1. [Reading Elements](#reading-elements)
1. [3rd Party API Integration](#3rd-party-api)

### Simple Text Input <a name="simple-text"></a>

Contains a basic text input element that can be used to store a single line of text. This illustrates the basic structure of a custom element. Changing the element between **Required** and **Optional** will change the validation of the element.

### Reading Elements <a name="reading-elements"></a>

Takes the example further by reading information about the element and the content item. This example shows how to read the element name, the element codename, the content item name and the content item codename.

### 3rd Party API Integration <a name="3rd-party-api"></a>

Show a simple case of an external API beng used to provide data to the custom element. This example uses the Open Breweries API to provide a list of random breweries. The user can select a brewery from the list and the custom element will store the brewery details.