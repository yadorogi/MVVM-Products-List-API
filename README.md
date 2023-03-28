# MVVM (Model View ViewModel) + Data Binding + Singleton + Generic API Calls

MVVMパターンを使ったサンプルプロジェクト
Closure(Data Binding)メソッドを用いて、ViewとViewModelを結合する

## 特徴

- [x] UIKit （SwiftUIでは無い）
- [x] MVVM アーキテクチャ
- [x] Data Binding
- [x] Singleton Design Pattern
- [x] URLSession - Generic Api calls - Networking API
- [x] Decodable Protocol with JSONDecoder
- [x] 画像ダウンロード - Kingfisher Library　（Webから画像をダウンロードしてキャッシュするSwiftライブラリ）
- [x] Swift Package Manager - SPM
- [x] Closure, Completion, Typealias, Enum
- [x] Detailed use of UIStackView, UITableView, UITableViewCell XIB
- [x] Inheritance - Final Keyword, Init()
- [x] Memory Management
- [x] Light and Dark Mode

##　動画サンプル

https://user-images.githubusercontent.com/5846718/228222696-016c8066-285a-4dab-bca9-07cff84d3da6.mov

## サンプルのダミーJSON

https://dummyjson.com/products

```json
{
    "products": [
        {
            "id": 1,
            "title": "iPhone 9",
            "description": "An apple mobile which is nothing like apple",
            "price": 549,
            "discountPercentage": 12.96,
            "rating": 4.69,
            "stock": 94,
            "brand": "Apple",
            "category": "smartphones",
            "thumbnail": "https://i.dummyjson.com/data/products/1/thumbnail.jpg",
            "images": [
                "https://i.dummyjson.com/data/products/1/1.jpg",
                "https://i.dummyjson.com/data/products/1/2.jpg",
                "https://i.dummyjson.com/data/products/1/3.jpg",
                "https://i.dummyjson.com/data/products/1/4.jpg",
                "https://i.dummyjson.com/data/products/1/thumbnail.jpg"
            ]
        }
    }
}
```
