---
title: Time Picker
hide_title: true
---

# Time Picker

A UI component for picking a time of the day, hours and minutes. It works both as a text input where you can type the time, and as a drop down of quick picks. On Mobile the native time picker can be used if the clock icon is clicked.

<div className="ndl-image-with-background">

![](/library/prefabs/time-picker/time-picker.png)

</div>

Below is a screenshot of the quick pick drop down.

<div className="ndl-image-with-background">

![](/library/prefabs/time-picker/time-picker-drop-down.png)

</div>

After importing the module you will see a component called **Time Picker** in your project.

The example below shows how to hook the **Time Picker** up to data in an **Object**, in this case a **Function** node is used to write back the hours and minutes to the object using the **Changed** signal.

<div className="ndl-image-with-background xl">

![](/library/prefabs/time-picker/time-picker-nodes.png)

</div>
