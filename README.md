<div align="center">
<a href="https://curencee.netlify.app"><img src="https://user-images.githubusercontent.com/62628408/175771392-c4d43488-04ac-4253-85ac-4c58a87315bc.svg" alt="logo" width="80px"></a>  
</div>

<div align="center">
<h1>CurrencyXchange</h1>
</div>

<div align="center">
<img src="./assets/images/sample.png" width="600px">
</div> <br>

## Get Started

Currencee is a simple app built using HTML and JavaScript. Styling is done using SASS.
To run the project locally, simply fork and clone the project to your machine, then run the index.html file using liver server.

The converter is powered by the <a href="https://www.exchangerate-api.com/">Exchange Rate API</a>, which supports over 161 commonly circulating world currencies listed <a href="https://www.exchangerate-api.com/docs/supported-currencies">here</a>. These cover 99% of all UN recognized states and territories. The API offers 1500 requests per month for free.

Countries are stored in a JavaScript object. These are the available countries. To add more, use the currency code as the element name and country intial for the object element value.

```js
let country_code = {
  INR: "in",
  USD: "us",
  GBP: "gb",
  EUR: "eu",
  NGN: "ng",
  JPY: "jp",
  CNY: "cn",
  GHS: "gh",
  AUD: "au",
};
```

The flags used are embedded using <a href="https://flagpedia.net">Flagpedia</a> which offers countries images based on their code.

```js
https://flagcdn.com/h20/in.png
```

- [Google Analytics](https://analytics.google.com) to measure metrics and usage.
- [Google font](https://fonts.google.com/)
- [Fontawesome](https://fontawesome.com) for icons
- [GSAP](https://greensock.com/gsap/) for animation

## 🔐 License

This project is protected by <a href="https://github.com/Theternos/currencyXchange/blob/main/LICENSE">MIT License</a>.
If you like this project, kindly star ⭐ and share this project.

# Color Code

| Color           | Hex                                                                                                               | Code      |
| --------------- | ----------------------------------------------------------------------------------------------------------------- | --------- |
| Primary color   | ![#8896CE](https://user-images.githubusercontent.com/62628408/176185657-5ae625c0-c7d3-4f85-815d-769c7a69045c.png) | `#8896CE` |
| Secondary color | ![#191136](https://user-images.githubusercontent.com/62628408/176185659-787210c1-fac9-4e87-8e6a-96b36ef53e0f.png) | `#191136` |
| Accent color    | ![#E5E9FE](https://user-images.githubusercontent.com/62628408/176185662-c471c6e7-97fc-4c60-afea-1574ab64216f.png) | `#E5E9FE` |
| Bg Dark         | ![#000000](https://user-images.githubusercontent.com/62628408/176185645-615c74cd-a2af-4ee3-bda8-f5982fe06011.png) | `#000000` |
| Bg Light        | ![#FFFFFF](https://user-images.githubusercontent.com/62628408/176185668-57712bfb-3d6f-4a5e-81e6-140de0004395.png) | `#FFFFFF` |
