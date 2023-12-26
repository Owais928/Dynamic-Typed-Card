# Dynamic-Typed-Card
The Dynamic Typed Card plugin is a unique region plugin that brings an engaging and interactive element to your APEX applications. It combines static text and dynamic typing effects using the typed.js library, elegantly presented within a card layout.

# Features

**Typing Animation:** Leverages the popular typed.js library to create a smooth and customizable typing effect.

**Static Text Integration:** Allows for a combination of static and dynamic text within the same card, offering both stability and motion.

**Flexible Card Layout:** Adapts to various screen sizes and layouts, ensuring a consistent look across different devices.

**Customizable Appearance:** Offers options to customize the look and feel of the text and card to match your application's theme.

# Use Cases

**Dashboards:** Add an animated introduction or highlight key information dynamically.

**Landing Pages:** Create an eye-catching hero section with animated text to engage visitors.

**Data Presentation:** Use alongside data-driven regions to add explanatory text or dynamic annotations.

# How to Install

Download the plugin file from the GitHub repository.

Import the plugin into your Oracle APEX application.

Add a new region, select the Dynamic Typed Card as Type Of Region.

Change the Type of the source of the region to **SQL Query** or **TABLE Based** according to your need.

**Parameters** Involved in the query should be like below

```
SELECT 'MUHAMMAD AWAIS' as HEADER_TEXT,'i''m Oracle' as STATIC_TEXT,
'Apex Developer,Forms Developer,Reports Developer,Cloud Administrator,Autonomous Database Administrator,Technology Consultant' as TYPED_TEXT,
'true' as loop_enabled,30 as type_speed,50 as back_speed,1500 as back_delay
from dual;
```


# Configuration Options

**Text Content:** Define the **Header**, **static** and **typed** text to be displayed.

**Typing Speed:** Adjust the speed of the typing animation.

**Loop Typing Effects:** Set Value to **true** or **false** to **enable/disable** loop.

**Back Speed:** Adjust the speed of the backspace animation.

**Back Delay:** Set value to stop the cursor for specific time before starting backspace animation.
