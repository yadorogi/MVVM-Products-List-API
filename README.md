# MVVM (Model View ViewModel) + Data Binding + Singleton + Generic API Calls

MVVMパターンを使ったサンプルプロジェクト
Closure(Data Binding)メソッドを用いて、ViewとViewModelを結合する

## 特徴

- [x] UIKit （SwiftUIでは無い）
- [x] MVVM アーキテクチャ
- [x] Data Binding （RX - リアクティブプログラミング）
- [x] Singleton Design Pattern （生成するインスタンスの数を1つに制限するデザインパターン）
- [x] URLSession - Generic Api calls - Networking API　（RestFull API専用）
- [x] JSONDecoder によるデコード
- [x] 画像ダウンロード - Kingfisher Library　（Webから画像をダウンロードしてキャッシュするSwiftライブラリ）
- [x] Swift Package Manager - SPM （CocoaPodsでも良い）
- [x] Closure, Completion, Typealias, Enum
- [x] Detailed use of UIStackView, UITableView, UITableViewCell XIB　（StoryBoardを使わずカスタマイズされたリストUIを実装）
- [x] Inheritance - Final Keyword, Init()
- [x] Memory Management （ガベージコレクションなど）
- [x] Light and Dark Mode (iOS13がサポートするダークモードへの対応)

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
