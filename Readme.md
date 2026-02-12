<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128585213/16.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T466430)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* **[CustomContainers.xaml](./CS/DXDiagram.CreateCustomContainers/CustomContainers.xaml) (VB: [CustomContainers.xaml](./VB/DXDiagram.CreateCustomContainers/CustomContainers.xaml))**
* [MainWindow.xaml](./CS/DXDiagram.CreateCustomContainers/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DXDiagram.CreateCustomContainers/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/DXDiagram.CreateCustomContainers/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DXDiagram.CreateCustomContainers/MainWindow.xaml.vb))
<!-- default file list end -->
# How to create custom diagram containers and register them in the toolbox and ribbon gallery


<p>In this example, we show how to create containers with custom headers and padding. <br>DiagramControl supports a special language for defining containers. The root element that contains a container description is <em>ContainerShapeTemplate</em>. This element describes a container contour and may contain several segments

* <em>Start</em>. Specifies the start point
* <em>Line</em>. Defines a line with start and end points
* <em>Arc</em>. Defines an arc with start and end points<br><br>To define a container's header editor position, use the EditorBounds property. To specify a padding, set the ActualPadding property.<br>To register custom containers in the ribbon gallery, use the DiagramContainerGalleryRegistrator.RegisterContainerShapes method.</p>

<br/>


<!-- feedback -->
## Does This Example Address Your Development Requirements/Objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-diagram-create-custom-diagram-containers&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=wpf-diagram-create-custom-diagram-containers&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
