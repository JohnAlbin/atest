# A Test Style Guide

This style guide documents the designs of this website which are built with component-based styles and Sass variables, functions and mixins. To ensure it is always up-to-date, this style guide is automatically generated from comments in the Sass files.

## Organization

Design components are reusable designs that can be applied using just the CSS class names specified in the component. We categorize our components to make them easy to find.

<dl>
<dt>**Defaults**</dt>
<dd>`components/base` — The default “base” components apply to HTML elements. Since all of the rulesets in this class of styles are HTML elements, the styles apply automatically.</dd>
<dt>**Layouts**</dt>
<dd>`components/layouts` — Layout components position major chunks of the page. They just apply positioning, no other styles.</dd>
<dt>**Global**</dt>
<dd>`components/global` — Global components are design components that appear on all pages of the site.</dd>
<dt>**Navigation**</dt>
<dd>`components/navigation` — Navigation components are specialized design components that are applied to website navigation.</dd>
<dt>**Common**</dt>
<dd>`components/common` — Miscellaneous components are grouped together, but feel free to further categorize these.</dd>
<dt>**Forms**</dt>
<dd>`components/forms` — Form components are specialized design components that are applied to forms or form elements.</dd>
<dt>**Utility**</dt>
<dd>`components/utility` — Utility components are specialized components that are often used to easily fix complex CSS problems.</dd>
</dl>

In addition to the components, our component library also contains these folders:

<dl>
<dt>**Colors and Sass**</dt>
<dd>`components/init` — This Sass documents the colors used throughout the site and various Sass variables, functions and mixins. It also initializes everything we need for all other Sass files: variables, 3rd-party libraries, custom mixins and custom functions.</dd>
<dt>**Style guide helper files**</dt>
<dd>`components/style-guide` — files needed to build this automated style guide; includes some CSS overrides for the default KSS style guide</dd>
</dl>
