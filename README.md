# 935106_64_ProjectOOP
> * ความเป็นมาของโปรแกรม โปรเจ็ค 935106เนื่องเป็นคนที่ชื่นชอบซื้อของผ่านออนไลน์ Application ที่ได้รับความนิยมตลอดอย่าง Shopee จึงเลือกที่จะนำมาเป็นไอเดียทำโปรเจ็คในครั้งนี้
> * วัตถุประสงค์ของโปรแกรม เพื่อศึกษาการทำระบบการเลือกซื้อของ
> * โครงสร้างของโปรแกรม (Class diagram) 
```mermaid
flowchart LR
A[Clothing_Store] -->|Link| B(Main)
B --> C{Menu}
C -->|One| D[Upload 1]
C -->|two| E[Menu 2]
```

```mermaid
classDiagram
ClassMain_Form --|> ClassMain : Link1
ClassMain --|> ClassMenu_Form : Link2
ClassMenu_Form --|> ClassMenu : Link3
ClassMenu <|--|> ClassUpload_Form : Link4
ClassUpload_Form <|--|> ClassUpload : Link5
<<Interface>> ClassMain
Clothing_Store --|> ClassMain_Form
Clothing_Store : MainJF()
Clothing_Store : Visible()
ClassMain : size()
ClassMain : Title()
ClassMain : Bounds()
ClassMain : MaximizedBounds()
ClassMain : int chimp
ClassMain : int gorilla
<<Interface>> ClassMenu
ClassMenu : String cerrency
ClassMenu : String display
ClassMenu : String output
ClassMenu : String price
ClassMenu : String order
ClassMenu : DecimalFormat()
ClassMenu : double allprice
ClassMenu : int selected
ClassMenu : int row
ClassMenu : int x
ClassMenu : DefaultTableModel()
<<Interface>> ClassUpload
ClassUpload : Bounds()
ClassUpload : Size()
ClassUpload : Title()
```

> * ชื่อของผู้พัฒนาโปรแกรม นางสาว พิมพ์พรรณ์ ภูชาดา 633410128-9



