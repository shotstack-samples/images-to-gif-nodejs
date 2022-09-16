## Create gif from images using Node js and Shotstack API

This program creates gif from images using Nodejs, [Shotstack Node SDK](https://www.npmjs.com/package/shotstack-sdk), and Shotstack API.

### What is Shotstack API?

Shotstack API is a cloud based meida editing API that enables you to render multiple gif concurrently in the cloud using your favourite programming language. Sign up for a free developer account [here](https://dashboard.shotstack.io/register?utm_source=github&utm_campaign=sample_demos) to get your API key. 

### Why use Shotstack API?

Rendering media files is a resource consuming process. It may take several minutes to render one video depending on the complexity. Shotstack enables to concurrently render multiple media files in the powerful cloud infrastructure. This reduces rendering time and fastens production process without having to build your own infrastructure. Visit our [Docs](https://shotstack.io/docs/guide/getting-started/core-concepts/?utm_source=github&utm_campaign=sample_demos) to learn more.

Checkout other media manipulation demo examples using Nodejs in this [Github repo](https://github.com/shotstack/node-demos).


### Installation

Clone this repository with following command

```bash
git clone https://github.com/shotstack-samples/images-to-gif-nodejs.git
```

Go inside the project directory
```bash
cd images-to-gif-nodejs
```

Install the required dependencies including the [Shotstack Node SDK](https://www.npmjs.com/package/shotstack-sdk)

```bash
npm install
```


### Set your API key

The demos use the **staging** endpoint by default so use your provided **staging** key:

```bash
export SHOTSTACK_KEY=your_key_here
```

Windows users (Command Prompt):

```bash
set SHOTSTACK_KEY=your_key_here
```

You can [get an API key](https://dashboard.shotstack.io/register?utm_source=github&utm_campaign=sample_demos) by signing up for a free developer account via the Shotstack web site.


### Running the program

To run this program, run the `gif.js` inside the root folder:

```bash
node gif.js
```

### Final gif example

[Here](https://cdn.shotstack.io/au/stage/c9npc4w5c4/f0a7eb51-844f-4dc4-b8ff-34a4d843d8c2.gif) is what the final media file looks like.

### Accessing rendered media

To access your rendered media files, sign into your Shotstack account. Inside the dashboard, you can find all rendered gif under Renders tab.

![Alt Text](https://im5.ezgif.com/tmp/ezgif-5-9da1b35692.gif)


### Edit and automate media production using Nodejs

This is just a basic example. You can do way more with Shotstack Node SDK like: 
- Beautify video by adding effects, transitions, overlays, titles
- Automate video editing and production
- Personalize videos with code
- Convert media files i.e. gif, mp3, mp4, jpg, bmp, and png
- Generate, add SRT files to multiple videos concurrently
- Use AI to generate media assets to produce videos & more

See our other [tutorial articles](https://shotstack.io/learn/?utm_source=github&utm_campaign=sample_demos) to learn media manipulation using Node js. 