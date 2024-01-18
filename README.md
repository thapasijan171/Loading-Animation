# Loading Animation

A minimalistic loading animation created using HTML and CSS. Perfect for indicating background processes or content loading in your web applications.

![Loading Animation](preview.gif)

## Table of Contents

- [Demo](#demo)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can view a live demo of the loading animation [here](#).

## Getting Started

Follow these simple steps to get started with the loading animation:

1. Clone the repository:

   ```bash
   git clone https://github.com/thapasijan171/loading-animation.git

## usage

Integrate the loading animation into your web project effortlessly. Use it to signify ongoing processes, data loading, or any other scenarios where you want to engage users during a wait.


```bash
   <section class="wrapper">
      <div class="loader">
        <div class="loading one"></div>
        <div class="loading two"></div>
        <div class="loading three"></div>
        <div class="loading four"></div>
      </div>
    </section>
```

##Customization

Feel free to customize the loading animation to match your project's design. Adjust the colors, size, or animation speed by modifying the styles in the styles.css file.

```bash

      .wrapper {
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
      }
      
      .wrapper .loader {
        display: flex;
        justify-content: space-evenly;
        padding: 0 20px;
      }
      
      .loader .loading {
        background: #fff;
        width: 30px;
        height: 30px;
        border-radius: 50px;
        margin: 0 10px;
        animation: load 0.8s ease infinite;
      }
      
      .loader .loading.one {
        animation-delay: 0.3s;
      }
      .loader .loading.two {
        animation-delay: 0.4s;
      }
      .loader .loading.three {
        animation-delay: 0.5s;
      }
      
      @keyframes load {
        0% {
          width: 30px;
          height: 30px;
        }
        50% {
          width: 20px;
          height: 20px;
        }
      }
```

##Contributing

Contributions are welcome! If you have any ideas, enhancements, or bug fixes, please open an issue or submit a pull request.

##License

```bash

Remember to replace `"thapasijan171"` with your actual GitHub username in the clone URL and provide a live demo link if available. This README includes more detailed sections, making it a comprehensive guide for users and potential contributors.


```

