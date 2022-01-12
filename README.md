<!-- ABOUT THE PROJECT -->
## StockBit - iOS Tech Challenge

## Getting Started

This app built using MVVM Design Pattern to reduce the complexity of the code by making view controller simpler by moving a lot of business logic into View Model. The minimum iOS to running this app is 12.1. I'm also provide an reusable HTTP Service for http request.

Here's some third party that i used:
- Alamofire: Is a HTTP networking library to do some request and gather response from min-api.cryptocompare.com
- RxSwift, RxCocoa, RxDataSources: Used for data binding & async task for reactive programming
- SVProgressHUD: Used for showing error message from request
- Starscream: User for open a connection to Websocket server, in this case Starscream Library user for showing live price updates from wss://streamer.cryptocompare.com

### Installation

1. Install Pod by running:
    ```sh
    pod install
    ```
2. Create Config.xcconfig file to put CRYPTO_COMPARE_API_KEY
    ```
    CRYPTO_COMPARE_API_KEY={YOUR_KEY}
    ```

## TODOs

If i have more time, here's the think i would do:
- Add some shimmer loading effect to the list
- Using Coordinator Pattern
- Create some resuable components
