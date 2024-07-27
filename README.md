This are Demos about Media Quaries for bringing responsiveness is Web Development project.
syntax===> @media
we can use max-width and as well as min-width 
so the syntax will be @media screen and (max-width: Xpx) or (min-width: Ypx)
we also set the max-width and min-width as a range X<=width<=Y
where X is the min-width & Y is the max-width
so the query will be @ media screen (X <= width <= Y)

why you might use the screen keyword in an @media query:

Device-Specific Styles: You can define styles that are tailored for devices with screens,
as opposed to other media types like print. This allows you to optimize the user experience for screen readers, 
ensuring that content is displayed appropriately on various devices.

Responsive Design: By using screen in combination with other conditions like min-width and max-width, 
you can create responsive designs that adapt to different screen sizes.
This is essential for creating layouts that work well on mobile devices, tablets, and desktops.

Excluding Print Styles: If you have specific styles for print (e.g., using the print keyword in another @media query), 
using screen helps ensure that certain styles are only applied to screens and not when the content is printed.
