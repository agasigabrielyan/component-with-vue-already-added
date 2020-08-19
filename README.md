# component-with-vue-already-added
Template of component with vue for small applications for bitrix website
1) In .description.php need to be written ID of your namespace
2) In /lang/ru/.description need to be written correct names of lang variables
3) Output component in right place with the help of code
$APPLICATION->IncludeComponent(
 yournamespace:componentname,
 '.default',
 array(), // parameters if there are they in component
 false
);
