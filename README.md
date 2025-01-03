# Custom Design Request

This is an HTML form for submitting a custom design request using HTML and CSS. The form includes customizable fields such as the identity name, material type, power, lighting type, and lighting color.

## Features
- **Support for Arabic and English languages:** Allows users to switch between the two languages with a simple link.
- **Multi-field form:** The form contains a set of fields to gather information such as name, type, power, lighting, and product details.
- **Support for uploading identity image:** Users can upload an identity image using the file upload field.
- **Data submission via Formspree:** The data entered in the form is submitted to the Formspree service for processing.

## Instructions
### How to use the form:
1. **Choose Language:** Users can switch between Arabic and English using the links at the top of the page.
2. **Fill in the fields:** Users must enter request details such as name, material type, power, and other specifications.
3. **Upload identity image:** The user must upload the required identity image.
4. **Submit the request:** After filling in the form, the user can click the "Submit Request" button to submit the data.

### Language Switch Links:
- [العربية](?lang=ar)
- [English](?lang=en)

## Page Structure:
The page contains a simple design including:
- A header with the title of the form.
- A form with fields like name, material type, power, lighting, product size and shape, and identity image.
- A submit button to send the request.
- Links to switch between Arabic and English languages.

## How to Customize the Form:
- To change text or add new options to the form, you can modify the code in the HTML.
- To customize the page design, you can modify the styles in the `<style>` section.

## Requirements:
- **HTML** and **CSS** to create and design the form.
- **JavaScript** to toggle between Arabic and English text.
- **Formspree** to handle the form submissions.

### Note:
Make sure that the form submission is working correctly via Formspree. Use the URL provided by Formspree in the `action` attribute within the `<form>`.
