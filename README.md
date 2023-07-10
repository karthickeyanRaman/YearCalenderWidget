# YearCalenderWidget

The Year-Calendar widget offers a visually engaging and interactive way to present data. Users can easily navigate through events and their respective dates. By selecting a specific date, users can instantly access the corresponding event name and description displayed below. This widget provides an interactive method to present data, enhancing the user experience.

Description
Year - Calendar controller with below abilities:
•	Show dates in the calendar between the start and end date and event name.
Typical usage scenario
1.	 in the settings tab:
1.	Specify the date attribute you want to use.
2.	Specify the minimum date and maximum date to show the calendar view depending on them.
3.	Specify the date format in order to show the selected date as selected format.

Features and limitations
features:
1.	Show dates in the calendar only between the start and end date.
2.	Create/update/cancel events
3.	Contains simple logging of events
limitation:
1.	It builds on default styling, so if you need customer style, then you should add your style to the widget.
 
Usage
Property descriptions:
•	Show label
Enables default Mendix label behavior
•	Label caption
Custom text for the label
•	Date/time attribute (required)
The attribute for this widget
•	Editable
Control whether the widget is editable, using default Mendix behavior
•	Read-only style
Controls how the widget displays when not editable
•	Visible
Control whether the widget is visible, using default Mendix behavior
•	Input style
Select between the standard text and special number input boxes.
•	Required
When yes, causes Mendix validation to fail when the date attribute is empty.
•	Required message
The error message to show when the required validation fails.

Screenshots

 ![image](https://github.com/karthickeyanRaman/YearCalenderWidget/assets/131262691/1d5f0148-0cef-4b80-99d2-ccc72a7a389c)
 ![image](https://github.com/karthickeyanRaman/YearCalenderWidget/assets/131262691/2fc25a60-0d83-44cf-8d33-6127e5d83cc3)


 

Use cases:
The Year-Calendar widget is a versatile tool that can be utilized in various Mendix applications requiring data representation over time. It is particularly well-suited for applications such as project management tools and event planning apps, where visualizing data in a calendar format is essential.
