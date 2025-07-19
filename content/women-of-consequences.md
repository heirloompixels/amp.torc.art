+++
+++



## A.M.P #4: Women of Consequence

<div id='product-component-1750820472438'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'intentionallyconfusing.myshopify.com',
      storefrontAccessToken: '26daf3c50a3c519acf8af64a65e58217',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '9214229020903',
        node: document.getElementById('product-component-1750820472438'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "calc(25% - 20px)",
          "margin-left": "20px",
          "margin-bottom": "50px"
        }
      },
      "button": {
        "font-family": "Gill Sans, sans-serif",
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        ":hover": {
          "background-color": "#6c6c6c"
        },
        "background-color": "#787878",
        ":focus": {
          "background-color": "#6c6c6c"
        },
        "border-radius": "0px"
      },
      "quantityInput": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px"
      }
    },
    "contents": {
      "img": false,
      "title": false,
      "price": false
    },
    "text": {
      "button": "pre-order"
    }
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "font-family": "Gill Sans, sans-serif",
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        ":hover": {
          "background-color": "#6c6c6c"
        },
        "background-color": "#787878",
        ":focus": {
          "background-color": "#6c6c6c"
        },
        "border-radius": "0px"
      },
      "quantityInput": {
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px"
      }
    },
    "text": {
      "button": "preorder"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        "font-family": "Gill Sans, sans-serif",
        "font-size": "17px",
        "padding-top": "16.5px",
        "padding-bottom": "16.5px",
        ":hover": {
          "background-color": "#6c6c6c"
        },
        "background-color": "#787878",
        ":focus": {
          "background-color": "#6c6c6c"
        },
        "border-radius": "0px"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    },
    "popup": false
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Gill Sans, sans-serif",
        "background-color": "#787878",
        ":hover": {
          "background-color": "#6c6c6c"
        },
        ":focus": {
          "background-color": "#6c6c6c"
        }
      },
      "count": {
        "font-size": "17px"
      }
    }
  }
},
      });
    });
  }
})();
/*]]>*/
</script>



