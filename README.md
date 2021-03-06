# Design-Pattern-Cpp

---

# Creational patterns 創建型模式

## FactoryMethod 工廠方法
    建造一種工廠
    可建造 同一父類別 但 不同子類別 之屬性與方法
    使用同一接口

## AbstractFactory 抽象工廠
    建造不同工廠
    不同工廠具有同樣品項名稱但個體不同之屬性與方法

## Builder 生成器
    事件訂閱
    toolchain

## Prototype 原型
    Clone
    註冊表

## Singleton 單例模式
    一個類只有一個實例
    提供全域變數
    僅在第一次使用時初始化

---

# Structural patterns 結構型模式

## Adapter 适配器模式
    能使接口不兼容的對象能互相合作
    宣告 target (物件、方法)、adaptee (擴充方法)
    宣告 adapter，繼承 target、adaptee，利用 adaptee 擴充方法 override 原 target 方法

## Bridge 橋接模式
	形狀、顏色
    形狀包含顏色
	優先考慮 合成 / 聚合 原則

## Composite 組合模式
    層級結構管理
    樹狀結構
    Set parent / Get Parent

## Decorator 裝飾模式
    封裝器(通知器)
    擴展
    層次結構
	
## Facade 外觀模式
    最外層接口
    包裝底層

## Flyweight 享元模式
    減少記憶體使用
    多個物體間有共同的狀態

## Proxy 代理模式
    服務未準備好時，代理依樣可以運作
    服務可能延遲


---

# Behavioral patterns

---
# Reference:

- [Refactoring Guru]

[Refactoring Guru]: https://refactoring.guru/
