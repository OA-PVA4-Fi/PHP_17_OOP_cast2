# PVA4 - Programování a vývoj aplikací
## Lekce 17: OOP

## Obsah


### 1
Vytvořte třídu Product, s vlastnostmi: produktové číslo, název, cena. Všechny vlastnosti vyjma ceny jsou povinné. Nebude-li vyplněna cena, nastavte hodnotu 0.

Pro každou vlastnost vytvořte settery a gettery.

Cena nesmí být menší než 0 Kč.

### 2
Vytvořte třídu Order. Třída bude obsahovat metody:
* addProduct - přidá produkt do objednávky
* getTotal - vypočítá cenu všech produktů 

### 3
V souboru mujTest.php sestavte objednávku 3 libovolných produktů a zobrazte celkovou cenu objednávky.


### 4
Rozhodli jste se prodávat počítače a potřebujete k nim evidovat další povinné údaje (sériové číslo a rok výroby). Sestavte podřízenou třídu, která bude dědit z třídy Product.

Vytvořte v souboru mujPc.php novou objednávku a přidejte do ní počítač. (Pro usnadnění můžete využít vytvořený kód z předchozího bodu.)
