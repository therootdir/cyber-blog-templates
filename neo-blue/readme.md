<<<<<<< HEAD
## About Video 1: Build your FIRST Website UI using AI (easy peasy!)

We built a sleek and reponsive blog temple [neo-blue](link) with the help of the [PureCode AI](link) and deployed it on GitHub pages

## Getting Started
> Simply 
Simply check 
### Prerequisites
- Basic HTML knowledge
- GitHub account
- Git installed on your local machine
- Internet connection

## how to customize

### Adding Images

The template uses Unsplash for placeholder images. To add your own:

1. Replace the Unsplash URLs in the HTML with your chosen image links
2. Example: 
   ```html
   <img src="https://source.unsplash.com/random/800x600" alt="Blog post image">
   ```


## Using Unsplash Images

This project uses Unsplash for placeholder images. To use Unsplash images in your project:

1. Visit [Unsplash](https://unsplash.com/) and search for an image you like.
2. Click on the image to open it.
3. Right-click on the image and select "Copy image address".
4. In your HTML file, replace the `src` attribute of the `<img>` tag with the copied URL:
```html
<img src="https://images.unsplash.com/photo-..." alt="Description of the image">
=======
# neo-blue-template

This single-file template creates a clean, elegant and responsive website for showcasing your brand, blog articles, and projects.
The template is developed using HTML and styled with [Tailwind CSS](https://tailwindcss.com/), with the assistance of [PureCode AI](https://purecode.ai/). The prompts used for development are available in the [prompts.txt](https://github.com/douglascybersec/cyber-blog-templates/blob/root/neo-blue/prompts.txt) file

> _It is "kiss'ed" (designed with simplicity in mind: KISS principle - Keep It Simple, Stupid)_

> This template is a suplement to the YouTube Video:
>
> ## 1. [Build your FIRST Website UI using AI (easy peasy!)](https://youtu.be/AHu4uMpmaNg)

## Getting Started

1. Clone this repository or download the files.
2. Open `index.html` in your preferred code editor.
3. Replace all placeholder content with your actual information.
4. Customize the headings, descriptions, and links to match your brand and content.

## Customizing Images

We used Unsplash for the high-quality images! Here's how to personalize the template with your own images while maintaining the structure and functionality:

### Method 1: Using Unsplash Images

- Visit [Unsplash](https://unsplash.com) and search for an image you want to use

- Click on the image to open it in full view

- Right-click on the image and select `Copy Image address` or `Open image in new tab`

- In the new tab, you'll see the full URL of the image, which looks like this:
  "https://images.unsplash.com/photo-[image-id]?ixlib=rb-[version]&q=[quality]&w=[width]&fit=[fit]"

- Copy everything before the _query string start_ or the question mark (?)
  "https://images.unsplash.com/photo-[image-id]"

- In the HTML file, locate the `<img>` tag you want to update and replace the `src` attribute with your new URL

- Adjust the width and quality parameters (where need be)

> Example:
> Replacing blog 1 with _[this white-robot-toy image example](https://unsplash.com/photos/a-white-toy-with-a-black-nose-6UDansS-rPI):_

#### Original:

HTML:

```html
<img
  src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80"
  alt="Blog 1"
  class="w-full h-48 object-cover"
/>
```

> Result:

<img
  src="https://images.unsplash.com/photo-1550751827-4bd374c3f58b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80"
  alt="Blog 1"
  class="w-full h-48 object-cover"
/>

#### Updated:

HTML:

```html
<img
  src="https://images.unsplash.com/photo-1666597107756-ef489e9f1f09?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80"
  alt="Blog 1"
  class="w-full h-48 object-cover"
/>
```

> Result:

<img src="https://images.unsplash.com/photo-1666597107756-ef489e9f1f09?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=800&q=80" alt="Blog 1" class="w-full h-48 object-cover">

## Method 2: Using Local Images

1. Save your images in a local folder within your project directory as in [anony-green template](https://github.com/douglascybersec/cyber-blog-templates/tree/root/anony-green)
2. Update the `src` attribute in the HTML to point to your local image file

   ### Example:

   ```html
   <img
     src="images/your-image-filename.jpg"
     alt="Blog 1"
     class="w-full h-48 object-cover"
   />
   ```

   > For more info: _Refer to the [Tailwind CSS Documentation](https://tailwindcss.com/docs/installation) for available classes and utilities.!!_

## Contributing

Please feel free to fork this project and send pull requests with updated versions, new functionality, or more templates. Happy coding, cyber-buddy!
>>>>>>> 1ae6188d3637280a624df83ba4bcb692bfd0f8c6
