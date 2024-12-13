# PureLine
### Weboldal elérhetősége: [https://pureline.infinityfreeapp.com](#https://pureline.infinityfreeapp.com)



### [Noszlopy Gáspár Közgazdasági Technikum](http://www.ngkszki.hu/)

### Csapattagok: Kiss Gábor, Kiss Máté Márk, Takács Zoltán

### Tartalomjegyzék

[TOC]






---

## 1. Bevezetés

### 1.1 Záródolgozat téma kiválasztása

A vizsgaremek elkészítése során háromfős fejlesztői csapatként dolgoztunk együtt egy komplex szoftveralkalmazáson, amely egy valós piaci problémára kínál megoldást. Olyan témát választottunk, amely lehetővé tette egy mindenki számára elérhető, webes alapú webshop létrehozását. A webshop reszponzív kialakításának köszönhetően minden eszközön, legyen az asztali számítógép, táblagép vagy mobiltelefon, zökkenőmentesen működik. 

Az ötletet és inspirációt egy ismerősünk ruhaboltja adta, aki saját üzlete számára keresett modern, felhasználóbarát megoldást. Az alkalmazás egyik fő előnye, hogy a vásárlóknak nem kell fizikailag felkeresniük az üzletet, hiszen az online felület lehetőséget biztosít a termékek kényelmes böngészésére és megrendelésére akár otthonról is. Ezzel időt és energiát takarítanak meg, miközben az eladó számára is egyszerűbbé válik az adminisztráció és az ügyfélkapcsolatok kezelése.

A fejlesztés során különös figyelmet fordítottunk arra, hogy az alkalmazás megfeleljen a korszerű technológiai követelményeknek, miközben a felhasználói élményt is kiemelten kezeltük, hogy a rendszer egyszerre legyen praktikus és könnyen használható.

### 1.2 Alkalmazás tervezése

A projekt kezdetén a szoftveralkalmazás tervezése során az elsődleges célunk egy könnyen navigálható, reszponzív, modern és felhasználóbarát webshop létrehozása volt, amely minden eszközön optimálisan működik. A tervezési fázisban fontos szerepet kapott a célcsoport igényeinek feltérképezése, valamint a felhasználói élmény (UX) és a vizuális dizájn (UI) összhangja.

Első lépésként meghatároztuk a webshop alapvető funkcióit, amelyek közé tartozott a termékek könnyű kereshetősége, szűrhetősége, biztonságos és gyors vásárlási folyamat, valamint az egyszerű navigáció. A felhasználóknak egy átlátható, gyors és élvezetes vásárlási élményt szerettünk volna biztosítani, ezért a dizájn során kiemelt figyelmet fordítottunk a reszponzív megjelenítésre, hogy mobiltelefonokon, tableteken és asztali számítógépeken egyaránt kifogástalanul működjön.

A weboldal struktúráját úgy terveztük meg, hogy az egyszerűen bővíthető és módosítható legyen, figyelembe véve a jövőbeli igényeket, mint például új termékkategóriák hozzáadása, promóciók, vagy bármilyen új funkciók integrálása. A dizájn egy letisztult, modern arculatot kapott, amely lehetővé teszi a gyors navigációt, ugyanakkor esztétikus és vonzó a felhasználók számára.

A tervezés során külön figyelmet fordítottunk a webshop adminisztrációs felületére is. Az adminisztrációs oldal egy könnyen kezelhető felületet biztosít a termékek kezelésére, az egyes rendelések nyomon követésére, valamint a felhasználói adatok, illetve termékek kezelésére. Az admin felület is reszponzív, hogy bárhonnan elérhető és kényelmesen használható legyen.

A felhasználói élmény mellett az alkalmazás technikai oldalát is megterveztük. Az adatbázis felépítése során figyelembe vettük a webshop működéséhez szükséges összes adatot, például a termékek, vásárlók, rendelési információk tárolását. Az adatbázis modell kapcsolódik a front-end és back-end rendszerekhez, biztosítva ezzel a megfelelő működést.

### 1.3 Programozási nyelv kiválasztása, előkészítés

**A PureLine webshop fejlesztése során**
Kiemelt figyelmet fordítottunk arra, hogy a frontend és backend technológiák optimális kombinációjával egy funkcionálisan stabil, gyors és felhasználóbarát rendszert hozzunk létre. A PureLine célja nemcsak egy esztétikus és modern megjelenésű felület biztosítása volt, hanem egy olyan webshopé, amely egyszerűen navigálható, gördülékenyen működik, és megfelelően kezeli mind az ügyféloldali, mind a háttérben zajló folyamatokat.

A fejlesztés során:

- **Frontend technológiákkal** letisztult dizájnt és reszponzív felhasználói felületet hoztunk létre, amely tökéletesen alkalmazkodik asztali és mobil eszközökhöz.
- **Backend technológiák** segítségével biztosítottuk az adatok biztonságos tárolását, gyors feldolgozását és a webshop alapvető funkcióinak, például a rendeléskezelés és a felhasználói bejelentkezés hitelesítés működését.

**A PureLine webshop esetében az alábbi technológiák együttes alkalmazásával érhető el a kívánt eredmény:**

1. **Frontend technológiák (HTML, CSS, JavaScript, Bootstrap):**
   Ezek felelősek a vizuális megjelenésért és a felhasználói interakciókért, például a termékek böngészéséért, a kosár kezeléséért és az űrlapok kitöltéséért.
2. **Backend technológiák (PHP):**
   A háttérben futó folyamatok felelősek az adatok biztonságos tárolásáért, feldolgozásáért és a logikák működéséért.
   - A PHP biztosítja a szerveroldali logikát, például a rendelések feldolgozását, a felhasználói fiókok kezelését és az adatbázisokkal való kommunikációt.
   - Az AJAX lehetővé teszi az aszinkron adatlekérést, amely gyors és dinamikus adatcserét tesz lehetővé a frontend és backend között a REST API-n keresztül, elkerülve az oldal teljes újratöltését.

Ez a kombináció hatékony működést biztosít a PureLine webshop számára, és lehetővé teszi a valós idejű, gördülékeny felhasználói élményt.

Az alábbiakban bemutatjuk a PureLine webshopnál felhasznált frontend és backend technológiákat. Ez a struktúra biztosítja a hatékony működést, skálázhatóságot és a kiváló felhasználói élményt.

------

### **Frontend technológiák**

A frontend az a réteg, amelyet a felhasználók közvetlenül látnak és használnak. Ez magában foglalja a vizuális elemeket, az interaktív funkciókat és a felhasználói élmény biztosítását.

#### **HTML (HyperText Markup Language)**

A HTML a weboldal alapvető vázát képezi, amely meghatározza az egyes elemek elhelyezkedését, tartalmát és szerkezetét.

- Jellemzők:
  - Statikus elemek felépítése (címek, képek, bekezdések, linkek).
  - Hipertext kapcsolatok és formázási struktúrák létrehozása.
  - Az összes böngésző támogatja.
  - Egyszerű és gyors integrálás más technológiákkal, például CSS-sel és JavaScript-tel.

------

#### **CSS (Cascading Style Sheets)**

A CSS biztosítja a weboldal megjelenését, az elrendezéstől kezdve a színek és animációk megadásáig.

- Jellemzők:
  - Elrendezési modellek, például rácsrendszer (grid) és rugalmas boxmodell (flexbox) támogatása.
  - Média lekérdezések segítségével reszponzív design kialakítása.
  - Könnyű testreszabhatóság.

------

#### **JavaScript (JS)**

A JavaScript az interaktív funkciókat és dinamikus működést biztosítja. Lehetővé teszi, hogy az oldal elemei valós időben változzanak, anélkül, hogy az oldalt újra kellene tölteni.

- Jellemzők:
  - Eseményvezérelt működés, például kattintások, görgetések, billentyűlenyomások kezelése.
  - DOM (Document Object Model) manipuláció a HTML tartalom módosításához.
  - Böngészőben futó kód, így nincs szükség telepítésre.
  - Számos keretrendszer támogatása (pl. React, Angular, Vue.js).

------

#### **Bootstrap**

A Bootstrap lehetővé teszi reszponzív weboldalak gyors létrehozását előre definiált stílusokkal és komponensekkel.

- Jellemzők:
  - Előre elkészített rácsrendszer (grid) a weboldalak elrendezéséhez.
  - Komponensek, például navigációs sávok, gombok, űrlapok gyors implementálása.
  - Mobilbarát kialakítás alapértelmezetten.
  - Könnyen tanulható és testreszabható.

------

### **Backend technológiák**

A backend az alkalmazás háttérben működő része, amely kezeli az adatbázisokat, a szerveroldali logikát és a kliensoldalról érkező kéréseket.

#### **PHP (Hypertext Preprocessor)**

A PHP egy szerveroldali szkriptnyelv, amely az adatok feldolgozását, dinamikus tartalom generálását és a REST API működtetését végzi.

- Jellemzők:
  - Adatbázisokkal való közvetlen integráció (pl. MySQL, PostgreSQL).
  - Szerveroldali logikák kezelése, például hitelesítés, felhasználói adatok kezelése.
  - Nyílt forráskódú és széles körű támogatással rendelkezik.
  - Könnyen integrálható más technológiákkal, például HTML-lel és AJAX-szal.

------

#### **AJAX (Asynchronous JavaScript and XML)**

Az AJAX aszinkron adatkommunikációt biztosít a kliens és a szerver között, amely lehetővé teszi az oldalak frissítés nélküli adatlekérdezését.

- Jellemzők:
  - Adatok kezelése JSON vagy XML formátumban.
  - HTTP metódusok (GET, POST, PUT, DELETE) használata a REST API-val való kommunikáció során.
  - Gyors és hatékony adatfrissítés.
  - Kiválóan alkalmas valós idejű alkalmazásokhoz, például chat rendszerekhez vagy keresési javaslatokhoz.

---
### 1.4 Köszönetnyilvánítás
 **Köszönet a Fejlesztői Csapatnak**

- **Projektvezető:**  
  Kiss Gábor, a folyamatok irányításáért és koordinálásáért.  

- **Fejlesztők:**  
  [Kiss Máté Márk, Kiss Gábor, Takács Zoltán], akik a kódolásért és technikai megoldásokért feleltek.  

- **UI/UX Tervezők:**  
  [Takács Zoltán, Kiss Gábor, Kiss Máté Márk], akik biztosították a felhasználóbarát és esztétikus megjelenést.  

### Oktató és Intézmény

Külön köszönetünket fejezzük ki **Bloch Tamás oktatónak**, aki szakmai iránymutatásával segítette a projektünket.

Hálásak vagyunk a **KIÁKK intézménynek**, amely megfelelő kereteket és erőforrásokat biztosított a projekt létrejöttéhez.

### Felhasználók

Hálásak vagyunk a felhasználóknak, akik visszajelzéseikkel és javaslataikkal segítették a projekt fejlesztését, valamint hozzájárultak ahhoz, hogy a végeredmény még jobb legyen.


---

## 2. Fejlesztői Dokumentáció

### 2.1 Adatbázis

Az alábbiakban bemutatjuk a shop adatbázis szerkezetét, tábláit, kapcsolatait és az adatbázis működéséhez szükséges fontos részleteket.

**PureLine adatbázis diagram:**

<img src="C:\Users\User\Desktop\kepek\AdatbazisDiagram.png" alt="AdatbazisDiagram" style="zoom:100%;" />

### Kapcsolatok, amelyek az ábrát vezérelték:

1. **"categories"."id" < "products"."category_id"**

 A termékek kategóriákhoz vannak rendelve, így ellenőrizni kell a kategóriákat termékek hozzáadásakor.

2. **"users"."id" < "orders"."customer_id"**

 A felhasználók (vásárlók) adatai kapcsolódnak a rendelésekhez.

3. **"users"."id" < "products"."user_id"**

 A termékekhez felhasználói azonosító (tulajdonos) tartozik.

**PureLine adatbázis folyamatábra:** 

![database_process_flow_vertical](C:\Users\User\Desktop\kepek\database_process_flow_vertical.png)

**Alakzatok jelentése a folyamatábrában:** 

Ovális: Folyamat kezdete vagy vége.

Téglalap: Adatok táblába mentése, műveletek végrehajtása.

Rombusz: Logikai döntés (pl. "Van-e ilyen kategória?").

Nyíl: Az adatok vagy műveletek sorrendje.

---

### 2.1.1 Általános információk

- **Adatbázis neve:** shop
- **Adatbázis-kezelő rendszer:** MariaDB 10.4.32
- **PHP verzió:** 8.2.12
- **Karakterkódolás:** utf8mb4_general_ci
- **Adatbázis-adminisztrációs eszköz:** phpMyAdmin 5.2.1

---

### 2.1.2 Tábla szerkezetek

#### 2.1.2.1 `"categories"` tábla  
Ez a tábla a kategóriák adatait tárolja.

- **Oszlopok:**
  - `id` (int): Egyedi azonosító, elsődleges kulcs, AUTO_INCREMENT.
  - `name` (text): A kategória neve.
  - `photo` (text): Kategória fotóinak JSON formátumú tárolása.
  - `parent_id` (int): Szülőkategória azonosítója (hierarchia támogatása).
  - `description` (text): Kategória leírása.

---

#### 2.1.2.2 `"orders"` tábla  
Az összes rendelés információját tárolja.

- **Oszlopok:**
  - `id` (int): Egyedi azonosító, elsődleges kulcs, AUTO_INCREMENT.
  - `customer_id` (int): A megrendelő azonosítója (users táblából).
  - `order_status` (int): Rendelés állapota.
    - **Ha 0:** Kiszállítva
    - **Ha 1:** Folyamatban
    - **Ha 2:** Késik
    - **Ha 3:** Törölve
  - `shipping` (text): Szállítási adatok JSON formátumban.
  - `cart` (text): Kosár tartalma JSON formátumban.
  - `user` (text): Felhasználói információk JSON formátumban.
  - `order_date` (varchar): Rendelés dátuma.
  - `total_price` (int): Rendelés összértéke.

---

#### 2.1.2.3 `"products"` tábla  
A termékek adatait tartalmazza.

- **Oszlopok:**
  - `id` (int): Egyedi azonosító, elsődleges kulcs, AUTO_INCREMENT.
  - `name` (text): Termék neve.
  - `gender` (text): Célcsoport (Man, Woman, Kid).
  - `buying_price` (int): Beszerzési ár.
  - `price` (int): Eladási ár.
  - `description` (text): Termék leírása.
  - `photos` (text): Termék képei JSON formátumban.
  - `category_id` (int): Hivatkozás a `categories` táblára.
  - `user_id` (int): Hivatkozás a létrehozó felhasználóra (`users` tábla).

---

#### 2.1.2.4 `"users"` tábla  
A felhasználói információkat tárolja.

- **Oszlopok:**
  - `id` (int): Egyedi azonosító, elsődleges kulcs, AUTO_INCREMENT.
  - `first_name` (varchar): Keresztnév.
  - `last_name` (varchar): Vezetéknév.
  - `username` (varchar): Felhasználónév.
  - `password` (text): Hash-elt jelszó.
  - `phone_number` (varchar): Telefonszám.
  - `email` (varchar): E-mail cím.
  - `address` (varchar): Cím.
  - `user_type` (varchar): Felhasználói típus (pl. customer, admin).
  - `created` (varchar): Fiók létrehozási dátuma.



### 2.2 Mappa struktúra és fájlok

Itt látható a PureLine Divat Webshop fájlrendszerének felépítése, amely különböző komponenseket tartalmaz az alkalmazás működtetéséhez. Íme a struktúra részletes leírása a főbb elemekkel:

<img src="C:\Users\User\Desktop\kepek\mappa1.png" alt="mappa1" style="zoom:80%;" />

<img src="C:\Users\User\Desktop\kepek\mappa2.png" alt="mappa2" style="zoom:95%;" />

### 2.2.1 Fájlrendszer leírás

#### 1. **CSS**
- Az alkalmazás stíluslapja található itt (CSS fájl), amely a weboldal megjelenését határozza meg.

#### 2. **Database**
- A weboldal adatbázis fájlait tartalmazza.

#### 3. **Favicon**
- Az itt lévő fájlok a weboldal faviconjait tartalmazzák különböző méretekben.

#### 4. **Files**
A következő fájlokat tartalmazza:
- **`account-sidebar.php`**: Felhasználói oldalmenü megjelenítéséhez szükséges fájl.
- **`admin-account-sidebar.php`**: Admin oldalmenüjének sablonja.
- **`footer.php`**: Az oldal alsó részének (lábléc) megjelenítését kezelő fájl.
- **`functions.php`**: A webshop funkcióit tartalmazza.
- **`header.php`**: Az oldal felső részét (fejléc) tartalmazó sablonfájl.
- **`Zebra_Image.php`**: Egy képkezelő PHP fájl, amely képméretezési és optimalizálási funkciókat biztosít.

#### 5. **Fonts**
- A webshop által használt betűtípusokat tartalmazza:
  - **`cartzilla-icons435b.svg/ttf/woff`**: Az alkalmazás harmadik féltől származó ikonfontjai SVG, TTF és WOFF formátumban.

#### 6. **Img**
- Képfájlok mappája, például termékképek, logók, egyéb médiaelemek.

#### 7. **JS**
- Az alkalmazás Createx Studio által készített JavaScript fájlja található itt.

#### 8. **Uploads**
- Felhasználók által feltöltött képeket tartalmazza.

#### 9. **Vendor**
Harmadik féltől származó könyvtárak, pluginok és csomagok, amelyek az alkalmazás működéséhez szükségesek. Ezek a következőket tartalmazzák:
- **`bootstrap`**: A Bootstrap framework fájljai, amelyek a front-end fejlesztést segítik.
- **`card`**: Kártya-alapú UI komponensek megvalósításához szükséges eszközök.
- **`chartist`**: Diagramok és grafikonok megjelenítéséhez használt könyvtár.
- **`drift-zoom`**: Kép nagyításhoz kapcsolódó funkciókat biztosít.
- **`flatpickr`**: Egy dátumválasztó (date-picker) JavaScript plugin.
- **`imagesloaded`**: Képek betöltésének figyelésére szolgáló eszköz.
- **`lightgallery`**: Galéria megjelenítéséhez használt plugin.
- **`nouislider`**: Felhasználóbarát csúszkák készítéséhez használható plugin.
- **`prismjs`**: Szintaxiskiemelő, amely a kódblokkok stílusozására használható.
- **`shufflejs`**: Elemek keverésére és szűrésére használt könyvtár.
- **`simplebar`**: Egyedi görgetősávok megvalósítását segítő plugin.
- **`smooth-scroll`**: Egy JavaScript könyvtár, amely a sima görgetés (smooth scrolling) funkciót biztosítja.
- **`tiny-slider`**: Egy könnyű és gyors csúszka (slider) plugin, amely képek és egyéb tartalmak lapozására szolgál.

---

### 2.2.3 PHP fájlok funkciói

1. **`account-orders.php`**  
   - Felhasználói rendelések megtekintésére szolgáló oldal.
2. **`admin-account-orders.php`**  
   - Adminisztrátor által kezelt rendeléseket listázza.
3. **`admin-categories-add.php`**  
   - Kategóriák hozzáadására szolgáló adminisztrátori felület.
4. **`admin-categories.php`**  
   - Kategóriák kezelése és listázása adminisztrátori oldalról.
5. **`admin-products-add.php`**  
   - Új termékek hozzáadása az admin felületen keresztül.
6. **`admin-products.php`**  
   - Az adminisztrátor által kezelt termékek listája.
7. **`cart-process-add.php`**  
   - Kosárhoz adási folyamatot végző logikai fájl.
8. **`cart-process-remove.php`**  
   - Termék eltávolítása a kosárból.
9. **`cart.php`**  
   - A vásárlói kosár megjelenítése.
10. **`checkout-complete.php`**  
    - Rendelési folyamat befejezéséhez tartozó oldal.
11. **`checkout.php`**  
    - Pénztár oldal a vásárlás véglegesítéséhez.
12. **`delete_category.php`**  
    - Kategóriák törlését kezelő fájl.
13. **`delete_product.php`**  
    - Termékek törlésére szolgáló logikai fájl.
14. **`edit_category.php`**  
    - Kategóriák szerkesztése.
15. **`edit_product.php`**  
    - Termékek szerkesztése.
16. **`index.php`**  
    - A webshop kezdőlapja.
17. **`login-logic.php`**  
    - Bejelentkezési folyamatot kezelő háttérfájl.
18. **`login.php`**  
    - Bejelentkezési oldal.
19. **`logout.php`**  
    - Kijelentkezési folyamatot végző fájl.
20. **`product.php`**  
    - Egyedi termék megjelenítésére szolgáló oldal.
21. **`register-logic.php`**  
    - Regisztrációs folyamatot kezelő háttérfájl.
22. **`review.php`**  
    - Termékértékelések megjelenítésére és kezelésére szolgáló fájl.
23. **`search-results.php`**  
    - A keresési eredményeket jeleníti meg az oldalon.
24. **`shop.php`**  
    - A termékek listája található.
25. **`submit-order.php`**  
    - A rendelési folyamat véglegesítését kezelő fájl.
26. **`whishlist-process-add.php`**  
    - Hozzáadja a kiválasztott terméket a kívánságlistához.
27. **`whishlist-process-remove.php`**  
    - Eltávolítja a kívánságlistáról a már korábban hozzáadott terméket.
28. **`wishlist.php`**  
    - A kívánságlista oldalt jeleníti meg.

---

## 2.3 [Forráskód](#forraskod)

Fontosabb tiszta kódnak megfelelő kódsorok, amelyek fontos funkciót látnak el a webshopunk működésében:

### 2.3.1 [protected_area()](#protected_area)

```php
function protected_area(){
    if(!isset($_SESSION['user'])){
        alert('warning','Jogosulatlan hozzáférés, a folytatás előtt jelentkezzen be.');
        header('Location: login.php');
        die();
    }
}
protected_area();
```

Ez a funkció biztosítja, hogy csak bejelentkezett felhasználók férhessenek hozzá egy adott oldalhoz. Amennyiben a felhasználó nincs bejelentkezve, figyelmeztető üzenetet kap, majd átirányításra kerül a bejelentkezési oldalra.

#### Működés:
1. Ellenőrzi, hogy az `$_SESSION['user']` létezik-e.
2. Ha nem létezik:
   - Figyelmeztető üzenetet küld az `alert()` funkcióval.
   - Átirányítja a felhasználót a `login.php` oldalra.
   - A script végrehajtása megszakad a `die()` hívással.

### 2.3.2 [logout()](#logout())
```php
function logout(){
    if(isset($_SESSION["user"])){
        unset($_SESSION['user']);
    }
    alert('success','Sikeres kijelentkezés');
    header('Location: login.php');
    die();
}
logout();
```

Ez a funkció a felhasználó kijelentkeztetését végzi el. Ha a felhasználó be van jelentkezve, törli a kapcsolódó munkamenet-adatokat, majd értesíti a sikeres kijelentkezésről, és átirányítja a bejelentkezési oldalra.

#### Működés:
1. Ellenőrzi, hogy az `$_SESSION['user']` létezik-e.
2. Ha létezik:
   - Törli a munkamenetben tárolt felhasználói adatokat.
3. Értesítést küld az `alert()` funkcióval.
4. Átirányítja a felhasználót a `login.php` oldalra.

### 2.3.3 [is_logged_in()](#is_logged_in())
```php
function is_logged_in(){
    if(isset($_SESSION["user"])){
        return true;
    } else{
        return false;
    }
}
is_logged_in();
```

Ez a funkció ellenőrzi, hogy a felhasználó be van-e jelentkezve, és ennek megfelelően ad vissza egy logikai értéket.

#### Működés:
1. Ellenőrzi, hogy az `$_SESSION['user']` létezik-e.
2. Ha létezik, `true`-t ad vissza.
3. Ha nem létezik, `false`-t ad vissza.

### 2.3.4 [alert($type,$message)](#alert($type,$message))
```php
function alert($type,$message){
    $_SESSION['alert']['type'] = $type;
    $_SESSION['alert']['message'] = $message;
}
alert($type, $message);
```

Ez a funkció egy egyszerű figyelmeztetési rendszer, amely értesítéseket tárol az aktuális munkamenetben. Ezek az értesítések lehetnek figyelmeztetések, hibák vagy sikeres műveletek visszajelzései.

#### Működés:
1. Beállítja az `$_SESSION['alert']` tömb elemeit:
   - `type`: Az értesítés típusa (pl. warning, success, error).
   - `message`: Az értesítés szövege.
2. Ezek az adatok felhasználhatók a weboldalon értesítési üzenetek megjelenítésére.

### 2.3.5 [login_user($email,$password)](#login_user($email,$password))
```php
function login_user($email,$password){
    global $conn;
    $sql = "SELECT * FROM users WHERE email = '{$email}'";
    $res = $conn->query($sql);

    if ($res->num_rows < 1){
        return false;
    }
    $row = $res->fetch_assoc();
    
    if (!password_verify($password,$row['password'])) {
        return false;
    }
    
    $_SESSION["user"] = $row;
    return true;}
```

#### Leírás:
A `login_user` funkció felelős a felhasználók bejelentkeztetéséért. Ellenőrzi az e-mail-cím és a jelszó helyességét, majd ha az adatok érvényesek, elmenti a felhasználói adatokat a munkamenetbe.

#### Paraméterek:
- `$email` (string): A felhasználó által megadott e-mail-cím.
- `$password` (string): A felhasználó által megadott jelszó.

#### Működés:
1. A funkció lekérdezi az adatbázisból az adott e-mailhez tartozó felhasználói adatokat.
2. Ha az e-mail-cím nem található az adatbázisban, a funkció `false` értéket ad vissza.
3. Ha az e-mail létezik, a `password_verify` funkcióval ellenőrzi, hogy a megadott jelszó egyezik-e az adatbázisban tárolt (hash-elt) jelszóval.
4. Ha a jelszó helyes, a felhasználói adatokat elmenti a munkamenetbe (`$_SESSION['user']`), és `true` értéket ad vissza.
5. Ha a jelszó nem egyezik, a funkció `false` értéket ad vissza.

### 2.3.6 [text_input($data)](#text_input($data))

```php
function text_input($data)
{
    $name = (isset($data['name'])) ? $data['name'] : "";
    $attributes = (isset($data['attributes'])) ? $data['attributes'] : "";

    $value = "";
    $error = "";
    $error_text = "";
    if (isset($_SESSION['form'])){
        if(isset($_SESSION['form'] ['value'])){
            if(isset($_SESSION['form'] ['value'] [$name])){
                $value = $_SESSION['form'] ['value'] [$name];
            }
        }
    }

    if (isset($_SESSION['form'])){
        if(isset($_SESSION['form'] ['error'])){
            if(isset($_SESSION['form'] ['error'] [$name])){
                $error = $_SESSION['form'] ['error'] [$name];
                $error_text ='<div class="form-text text-danger">'.$error.'</div>';
            }
        }
    }
    
    $label = (isset($data['label'])) ? $data['label'] : $name;
    $value = (isset($data['value'])) ? $data['value'] : $value;
    $error = (isset($data['error'])) ? $data['error'] : $error;
    return 
    '<label class="form-label text-capitalize" for="'.$name.'">'. $label .'</label>
    <input name="'.$name.'" value="'.$value.'" class="form-control" type="text" id="'.$name.'" placeholder="'.$label.'" '.$attributes.'>' 
    . $error_text;
}

```

#### Leírás:
A `text_input` funkció egy dinamikus űrlapelem-generátor, amely a bemeneti mező HTML kódját készíti el, figyelembe véve a munkamenetben tárolt értékeket és hibaüzeneteket.

#### Paraméterek:
- `$data` (array): Egy tömb, amely tartalmazza az űrlapelem attribútumait és megjelenítési információit:
  - `name` (string): Az input mező neve (kötelező).
  - `attributes` (string): Az input mező további attribútumai (pl. required).
  - `label` (string): A mező címkéje.
  - `value` (string): Az input mező alapértelmezett értéke.
  - `error` (string): Az adott mezőhöz tartozó hibaüzenet (opcionális).

#### Működés:
1. Ellenőrzi, hogy van-e korábbi érték (`$_SESSION['form']['value']`) a munkamenetben az adott mezőhöz. Ha van, az lesz az alapértelmezett érték.
2. Ha hibaüzenet van társítva a mezőhöz (`$_SESSION['form']['error']`), azt megjeleníti a mező alatt.
3. Létrehozza az input mező HTML kódját a megadott és a munkamenetből származó információk alapján.

### 2.3.7 [select_input($data, $options)](#select_input($data, $options))
```php
function select_input($data, $options)
{
    $name = (isset($data['name'])) ? $data['name'] : "";
    $attributes = (isset($data['attributes'])) ? $data['attributes'] : "";

    $value = "";
    $error = "";
    $error_text = "";
    if (isset($_SESSION['form'])){
        if(isset($_SESSION['form']['value'])){
            if(isset($_SESSION['form']['value'][$name])){
                $value = $_SESSION['form']['value'][$name];
            }
        }
    }
    
    if (isset($_SESSION['form'])){
        if(isset($_SESSION['form']['error'])){
            if(isset($_SESSION['form']['error'][$name])){
                $error = $_SESSION['form']['error'][$name];
                $error_text = '<div class="form-text text-danger">'.$error.'</div>';
            }
        }
    }
    
    $label = (isset($data['label'])) ? $data['label'] : $name;
    $value = (isset($data['value'])) ? $data['value'] : $value;
    
    $select_options = "";
    $selected = "";
    foreach ($options as $key => $val) {
        $selected = "";
        if ($key == $value) {
            $selected = "selected";
        }
        $select_options .= '<option value="' .$key.'"'.$selected.'>'.$val.'</option>';
    }
    
    $select_tag = '<select name="'.$name.'" class="form-select" id="'.$name.'" '.$attributes.'>'.$select_options.'</select>';
    
    return 
    '<label class="form-label text-capitalize" for="'.$name.'">'. $label .'</label>'
    .$select_tag
    . $error_text;
}
```

A `select_input` funkció egy HTML `<select>` legördülő menü generálására szolgál. Figyelembe veszi az aktuális űrlapadatokat, hibaüzeneteket, valamint az előre definiált opciókat, és dinamikusan hozza létre a menüelemeket.

#### Paraméterek:
- **$data (array)**: Az űrlapelem attribútumait és megjelenítési információit tartalmazza:
  - `name (string)`: A legördülő menü neve.
  - `attributes (string)`: További HTML attribútumok (pl. required).
  - `label (string)`: A mező címkéje.
  - `value (string)`: Az alapértelmezett érték.
  
- **$options (array)**: A legördülő menü opcióit tartalmazó tömb, ahol a kulcs az opció értéke, az érték pedig a megjelenített szöveg.

#### Működés:
1. Ellenőrzi, hogy van-e korábban kiválasztott érték a munkamenetben (`$_SESSION['form']['value']`).
2. Ellenőrzi, hogy van-e a mezőhöz társított hibaüzenet (`$_SESSION['form']['error']`).
3. Létrehozza az opciók listáját, és az aktuális értékhez beállítja a `selected` attribútumot.
4. Generálja a `<label>` címkét és a `<select>` menüt, valamint megjeleníti a hibaüzenetet, ha van.

### 2.3.8 [get_category_name($category_id)](#get_category_name($category_id))

```php
function get_category_name($category_id) {
    global $conn; // Az adatbázis kapcsolathoz

    $stmt = $conn->prepare("SELECT name FROM categories WHERE id = ?");
    $stmt->bind_param("i", $category_id);
    $stmt->execute();
    $result = $stmt->get_result();

    return $result->fetch_column(); // Visszaadja a kategória nevét
}
```

#### Leírás:
A `get_category_name` funkció egy adott kategória nevét adja vissza az adatbázisból, az adott kategóriaazonosító alapján.

#### Paraméterek:
- **$category_id (int)**: A kategória egyedi azonosítója az adatbázisban.

#### Működés:
1. Használja az adatbáziskapcsolatot (`$conn`), hogy előkészített SQL lekérdezést futtasson.
2. Paraméterként átadja a kategóriaazonosítót a lekérdezésnek (`bind_param`).
3. Lefuttatja a lekérdezést, és visszaadja az eredményül kapott kategórianév oszlopot.

#### Visszatérési érték:
- A kategória neve (string), vagy null, ha az adott azonosító nem található.

---

### 2.3.9 [product_item_ui_1($pro)](#product_item_ui_1($pro))

```php
function product_item_ui_1($pro)
{
    $thumb = get_product_thumb($pro["photos"]);
    // Kategória neve lekérdezése
    $category_name = get_category_name($pro["category_id"]);
    $format_price = number_format($pro["price"]);

    $str = <<<EOF

<div class="col-md-4 col-sm-6 px-2 mb-4">
    <div class="card product-card">
        <form style="display: flex; justify-content: flex-end;" action="whislist-process-add.php" method="post">
            <input type="hidden" name="id" value="{$pro['id']}">
            <button class="btn-wishlist btn-sm" type="submit" data-bs-toggle="tooltip" data-bs-placement="left" title="Hozzáadás a kívánságlistához">
                <i class="ci-heart"></i>
            </button>
        </form>
        <a class="card-img-top d-block overflow-hidden text-center" href="product.php?id={$pro["id"]}">
            <img src="{$thumb}" alt="Termék" class="product-image" style="height: 200px; width: auto; object-fit: contain;">
        </a>
        <div class="card-body py-2">
            <a class="product-meta d-block fs-xs pb-1" href="javascript:;">{$category_name}</a>
            <h3 class="product-title fs-sm"><a href="product.php?id={$pro["id"]}">{$pro["name"]}</a></h3>
            <div class="d-flex justify-content-between">
                <div class="product-price"><span class="text-accent">{$format_price} Ft</span></div>
                <div class="star-rating">
                    <i class="star-rating-icon ci-star-filled active"></i>
                    <i class="star-rating-icon ci-star-filled active"></i>
                    <i class="star-rating-icon ci-star-filled active"></i>
                    <i class="star-rating-icon ci-star-filled active"></i>
                    <i class="star-rating-icon ci-star"></i>
                </div>
            </div>
        </div>
        <div class="card-body card-body-hidden">
            <div class="text-center pb-2">
                <div class="form-check form-option form-check-inline mb-2">
                    <input class="form-check-input" type="radio" name="size_{$pro['id']}" id="s_{$pro['id']}_s">
                    <label class="form-option-label" for="s_{$pro['id']}_s">S</label>
                </div>
                <div class="form-check form-option form-check-inline mb-2">
                    <input class="form-check-input" type="radio" name="size_{$pro['id']}" id="m_{$pro['id']}_m">
                    <label class="form-option-label" for="m_{$pro['id']}_m">M</label>
                </div>
                <div class="form-check form-option form-check-inline mb-2">
                    <input class="form-check-input" type="radio" name="size_{$pro['id']}" id="l_{$pro['id']}_l">
                    <label class="form-option-label" for="l_{$pro['id']}_l">L</label>
                </div>
                <div class="form-check form-option form-check-inline mb-2">
                    <input class="form-check-input" type="radio" name="size_{$pro['id']}" id="xl_{$pro['id']}_xl">
                    <label class="form-option-label" for="xl_{$pro['id']}_xl">XL</label>
                </div>
            </div>
            <form action="cart-process-add.php" method="post">
                <input type="hidden" name="id" value="{$pro['id']}">
                <button class="btn btn-primary btn-sm d-block w-100 mb-2" type="submit">
                    <i class="ci-cart fs-sm me-1"></i>Hozzáadás a kosárhoz
                </button>
            </form>
        </div>
    </div>
    <hr class="d-sm-none">
</div>
EOF;

    return $str;
}
```
A `product_item_ui_1` funkció a termék kártya felületének HTML kódját generálja. A kártya tartalmazza a termék képét, nevét, árát, kategóriáját, méretválasztó opcióit, valamint gombokat a kívánságlistára és kosárhoz való hozzáadáshoz.

---

#### Bemeneti Paraméterek
- **$pro (array)**:
  Egy tömb, amely a termék adatait tartalmazza. A fontos kulcsok:
  - `id`: A termék egyedi azonosítója.
  - `name`: A termék neve.
  - `photos`: A termék képeinek elérhetősége.
  - `category_id`: A termékhez tartozó kategória azonosítója.
  - `price`: A termék ára.

---

#### Működés
1. **Termékkép lekérése**:
   A `get_product_thumb` funkció segítségével lekéri a termék fő képének elérési útját.
2. **Kategória neve**:
   A `get_category_name` funkció segítségével lekérdezi a termék kategóriájának nevét az adatbázisból az `category_id` alapján.
3. **Ár formázása**:
   A termék árát a `number_format` funkcióval forintban formázza, hogy olvashatóbb legyen.
4. **HTML kód generálása**:
   Egy Bootstrap-alapú kártyát hoz létre a következő elemekkel:
   - **Kép**: A termék képe középre igazítva.
   - **Kategória neve**: Link nélkül megjelenítve.
   - **Termék neve**: Hivatkozásként megjelenítve, ami a termék részletes adatlapjára vezet.
   - **Ár**: A termék ára forintban.
   - **Értékelés**: Statikus csillagokkal megjelenítve.
   - **Méretválasztás**: Négy méret opció (S, M, L, XL) rádiógombokkal.
   - **Gombok**:
     - **Kívánságlista gomb**: A terméket hozzáadja a kívánságlistához.
     - **Kosár gomb**: A terméket hozzáadja a kosárhoz.

---

#### Visszatérési Érték
- **HTML kód**:  
  Egy Bootstrap-alapú HTML kód, amely a termék kártyáját jeleníti meg a webáruházban.

---

## 2.4 [PHP funkciók](#php-funkciok)

A `functions.php` a webshopunk funkcióinak alapját képezi. Több segédfüggvényt, adatbáziskapcsolatot és képkezelési lehetőséget definiál. Az alábbiakban röviden bemutatjuk a fontosabb részeit:

---

### 2.4.1 Alapértelmezett beállítások és kapcsolatok
- **Zebra_Image osztály betöltése**: A `require_once 'Zebra_Image.php';` sor a Zebra Image PHP könyvtárat tölti be, amelyet a képek átméretezéséhez és feldolgozásához használnak.
- **Session indítása**: Ellenőrzi, hogy fut-e már PHP session, és ha nem, elindítja.
- **Adatbáziskapcsolat**:
  - Az `mysqli` osztállyal létrehozza az adatbáziskapcsolatot a következő hitelesítő adatokkal:
    - Host: `sql213.infinityfree.com`
    - Felhasználónév: `if0_37627594`
    - Jelszó: `S4ZftgwvR8pKh`
    - Adatbázis: `if0_37627594_shop`

---

### 2.4.2 Fake termékek generálása
- **`fake_products_generator()`**:
  - Véletlenszerű termékeket generál nevek, árak, leírások és kategóriák alapján.
  - A generált termékeket a `db_insert()` függvénnyel menti az adatbázisba.

---

### 2.4.3 Termékmenedzsment
- **`get_product($id)`**:
  - Egy adott termék adatait lekéri az adatbázisból azonosító (ID) alapján.
  - Kiegészíti a termék adatait a kategória adataival is.
- **`get_product_photos($json)`**:
  - A termékhez tartozó képek adatait dolgozza fel JSON formátumból. Ha nincs kép, egy alapértelmezett képet ad vissza.
- **`get_product_thumb($json)`**:
  - A termék elsődleges képének bélyegképét adja vissza.

---

### 2.4.4 Adatbázis-kezelő függvények
- **`db_select($table, $condition = null)`**:
  - Az adott táblából lekérdezi az adatokat opcionális feltétellel.
  - Tömbben adja vissza a találatokat.
- **`db_insert($table_name, $data)`**:
  - Adatok beszúrására szolgál az adatbázis egy adott táblájába.
  - Dinamikusan generálja az SQL beszúró lekérdezést.

---

### 2.4.5 Képkezelés
- **`create_thumb($source, $target)`**:
  - A Zebra Image osztállyal átméretez egy képet, megőrizve az arányokat.
  - A célméret alapértelmezetten 1000x1000 pixel.
  - Visszaadja az új kép elérési útját.
- **`get_jpeg_quality($_size)`**:
  - Meghatározza a JPEG képminőséget a fájlméret alapján:
    - Nagyobb méret → alacsonyabb minőség
    - Kisebb méret → magasabb minőség

---

### 2.4.6 Fájlfeltöltés
- **`upload_images($files)`**:
  - Több fájl feltöltésére alkalmas.
  - Feldolgozza a fájlokat, ellenőrzi az alapvető attribútumokat (`name`, `type`, `tmp_name`, `error`, `size`).
  - Létrehozza a cél elérési útvonalat a fájlokhoz, és bélyegképet generál a `create_thumb()` függvénnyel.
  - Visszaad egy tömböt, amely tartalmazza a feltöltött fájlok elérési útvonalait és bélyegképeit.

---

### 2.4.7 URL és hozzáférés kezelés
- **`url($path)`**:
  - A megadott relatív útvonalból teljes URL-t készít a `BASE_URL` alapján.
- **`protected_area()`**:
  - Ellenőrzi, hogy a felhasználó be van-e jelentkezve. Ha nem, átirányítja a bejelentkezési oldalra és figyelmeztetést küld.
- **`logout()`**:
  - Kijelentkezteti a felhasználót, és átirányítja a bejelentkezési oldalra egy sikeres kijelentkezési üzenettel.
- **`is_logged_in()`**:
  - Ellenőrzi, hogy a felhasználó be van-e jelentkezve. Igaz/hamis értéket ad vissza.

---

### 2.4.8 Felhasználói kezelés
- **`login_user($email, $password)`**:
  - Ellenőrzi a felhasználó hitelesítő adatait az adatbázisban.
  - Ha az e-mail cím és a jelszó helyes, a felhasználót bejelentkezteti (session-t hoz létre).
  - Visszatérési érték:
    - `true`: Sikeres bejelentkezés.
    - `false`: Sikertelen bejelentkezés.
- **`alert($type, $message)`**:
  - Figyelmeztető üzenetet ad hozzá a session adatokhoz (`type`: üzenet típusa, pl. siker, hiba; `message`: megjelenítendő üzenet).

---

### 2.4.9 Űrlapkezelés
- **`text_input($data)`**:
  - Szövegbeviteli mező generálása.
  - Dinamikusan beállítható attribútumok, alapértelmezett értékek és hibakezelés.
- **`select_input($data, $options)`**:
  - Legördülő menü generálása.
  - Beállítja az alapértelmezetten megjelenő értékeket és hibakezelést.
- **Űrlaphibák kezelése**:
  - Az űrlapokhoz társított hibák (`error`) és előre kitöltött értékek (`value`) megjelennek a session adatain keresztül.

---

### 2.4.10 Adatbáziskezelés
- **`get_category_name($category_id)`**:
  - Egy kategória nevét adja vissza az azonosítója alapján.
  - Előkészített lekérdezést (prepare) használ, hogy biztonságos legyen a lekérdezés.

---

### 2.4.11 Termékek megjelenítése
#### 1. **`product_item_ui_1($pro)`**
- **Funkció**: Dinamikusan létrehoz egy termékkártyát, amely a termék részleteit, kategóriáját, képét, árát és különböző interakciós lehetőségeket tartalmaz.
- **Főbb elemek**:
  1. **Kívánságlista hozzáadás**:
     - A terméket a kívánságlistához adhatja a felhasználó egy POST kéréssel.
  2. **Termékkép és kategória**:
     - A kártya tartalmazza a termékképet (a `get_product_thumb()` használatával generálva) és a kategória nevét (a `get_category_name()` használatával lekérdezve).
  3. **Termék neve és ára**:
     - A terméknév és az ár formázott formában jelenik meg.
  4. **Méretválasztási opciók**:
     - A felhasználó kiválaszthatja a kívánt méretet rádiógombok segítségével (S, M, L, XL).
  5. **Kosárba helyezés**:
     - A termék kosárhoz adható egy POST kérésen keresztül.

#### 2. **`product_item_ui_static($pro)`**
- **Funkció**: Statikus termékkártyát hoz létre, amely elsősorban egyedi megjelenítést biztosít a kisebb képernyőkre korlátozás nélkül.

- **Főbb elemek**:
  1. **Termékkép és kategória**:
     - Ugyanúgy megjeleníti a termékképet és a kategória nevét, mint az első függvény.
     
  2. **Termék neve és ára**:
     - A terméknév és ár reszponzívan jelenik meg, a szokásos módon formázva.
     
  3. **Csillagos értékelés**:
     
     - A termék értékelését vizuálisan jelzi a csillagos rendszerrel (Bootstrap ikonok használatával).
     
  4. **Interakció korlátozása**:
     - Statikus megjelenítés, nem tartalmaz méretválasztási lehetőséget vagy kosárba helyezési gombot.
     
     ---
     
     ## 2.5 [Adminisztrátorként való regisztráció/bejelentkezés](#Adminisztrátorkent_valo regisztracio/bejelentkezes)
     
     #### Alapértelmezett Adminisztrátorként való bejelentkezés
     A rendszerben egy alapértelmezett adminisztrátori fiók áll rendelkezésre, amely az alábbi hitelesítési adatokkal érhető el:
     - **E-mail**: `admin@gmail.com`
     - **Jelszó**: `1234`
  
     Ez az adminisztrátori fiók kezdeti tesztelésre és karbantartásra használható.
  
     #### Adminisztrátorként való regisztráció
     Adminisztrátorként kizárólag akkor lehet regisztrálni, ha az e-mail cím tartalmazza az "admin" szót. Például az alábbi e-mail címek elfogadhatók:
     - `admin45@gmail.com`
  
     Amennyiben az e-mail cím nem tartalmazza az "admin" szót, a regisztráció nem lesz érvényes adminisztrátori státuszra, hanem egyszerű felhasználói fiókként kerül rögzítésre.
  
     #### Funkcionalitás részletei
  
     1. **Regisztráció ellenőrzése**
        - A rendszer a regisztráció során ellenőrzi az e-mail címben az "admin" szó meglétét.
        - Amennyiben az "admin" szó hiányzik, a regisztráció sikeresen lezajlik, de az új felhasználó nem adminisztrátori jogosultságot kap.
     
     2. **Bejelentkezés folyamata**
        - Az adminisztrátorok és a normál felhasználók bejelentkezési felülete azonos.
        - A rendszer a bejelentkezési adatok (e-mail) alapján különbözteti meg az adminokat a normál felhasználóktól.

---
## 2.6 [Admin Panel](#admin-panel)  

#### PureLine Divat Webshop Admin Panel

A **PureLine Divat Webshop** tartalmaz egy admin panelt, amely az adminisztrátorok számára biztosítja a webshop kezeléséhez szükséges funkciókat. Az admin panel kialakítása és átláthatósága lehetővé teszi az adminisztrátor számára a termékek, rendelési adatok és kategóriák hatékony kezelését. Az adminisztrátorok itt kezelhetik a webshop működéséhez kapcsolódó alapvető feladatokat.

#### Admin panel elérése
Adminisztrátorként kell bejelentkeznünk, majd felül a navigációs részen, jobb oldalt a „**Fiókom**” szövegre kattintva érhetjük el az Admin panelt.

#### Funkciók:
**Irányítópult (Bal oldalon található az oldalsávon):**
- Itt találhatóak az admin funkciók, amit csak az adminok látnak.

<img src="C:\Users\User\Desktop\kepek\AdminPanel1.png" style="zoom:80%;" />

#### Rendelések kezelése az Admin Panelen

Ha belépünk az Admin panelre, vagy rákattintunk a bal oldali oldalsávon található „**Rendelések**” menüpontra, a középső részen megjelenik az összes beérkező rendelés. Ezek állapotát négyféleképpen módosíthatjuk:

1. **Kiszállítva**
2. **Folyamatban**
3. **Késik**
4. **Törölve**

Ezen kívül a rendeléseket véglegesen törölhetjük az adatbázisból a „**Törlés**” gomb segítségével.

#### Rendelések szűrése:
A „**Rendelések szűrése:**” lehetőségnél ki tudjuk választani, hogy melyik rendelési állapotot jelenítse meg. Ha nem található rendelés, akkor a következő üzenet jelenik meg: 

<img src="C:\Users\User\Desktop\kepek\AdminPanelNincs.png" alt="AdminPanelNincs" style="zoom:67%;" />

**1. Termékek kezelése:**

- **Termék létrehozása:** Új termékek tudunk hozzáadni      a webshopunkhoz a következők kitöltésével:

<img src="C:\Users\User\Desktop\kepek\TermekHozzaad1.png" alt="TermekHozzaad1" style="zoom:67%;" />

**Termékek**: Az összes meglévő termék megtekintése, módosítása vagy törlése, illetve statisztikai adatokat is ezen a felületen láthatjuk:

- A termék árát,
- Az adott termékből értékesített     mennyiséget,
- Az adott termékből származó     bevételt:

![Termekek1](C:\Users\User\Desktop\kepek\Termekek1.png)

Így néz ki, ha módosítani szeretnénk egy terméket (terméknél a kék ikonra kattintva tudjuk ezt megtenni):

![TermekModositas](C:\Users\User\Desktop\kepek\TermekModositas.png)

**2. Termékkategóriák kezelése:**

- **Termékkategória létrehozása:** Új kategóriák hozzáadása a termékek rendszerezéséhez:

<img src="C:\Users\User\Desktop\kepek\TermekKategoria.png" alt="TermekKategoria" style="zoom:67%;" />

**Termékkategóriák:** Az összes meglévő kategória megtekintése, módosítása vagy törlése, illetve statisztikai adatokat is ezen a felületen láthatjuk:

- A kategóriák eladások számát,
- Az adott kategóriából származó bevételt.

<img src="C:\Users\User\Desktop\kepek\TermekKategoria2.png" alt="TermekKategoria2" style="zoom:60%;" />

**3. Saját fiók:**

Itt tudjuk megnézni „Rendelések” lehetőséget, illetve itt tudunk kijelentkezni a „Kijelentkezés” lehetőséggel.

Rendelések:

 <img src="C:\Users\User\Desktop\kepek\Rendelesek.png" alt="Rendelesek" style="zoom:60%;" />

---

## 2.7 [Jövőbeli Fejlesztési Lehetőségek](#jovobeli-fejlesztesi-lehetosegek)   

A PureLine webshop fejlesztése közben számos ötlet jutott eszünkbe, amelyekkel a jövőben továbbfejleszthetjük az oldalt, hogy még élvezetesebb és felhasználóbarátabb legyen:

1. **Továbbfejlesztett keresőmotor**: Kategóriák és szűrők bevezetése, például szín, méret alapján.
2. **Hűségprogram**: Pontgyűjtő rendszerek és exkluzív kedvezmények a visszatérő vásárlók számára.
3. **E-mail funkciók bevezetése**: Az alapvető e-mail támogatás megvalósítása, például jelszó-visszaállítási lehetőség és rendelés-visszaigazolások küldése, amely később kiterjeszthető kosárelhagyási értesítésekre és szezonális ajánlatokra is.
4. **Dinamikus termékértékelés és vélemények**: Lehetőség a vásárlók számára, hogy véleményüket közvetlenül a termékoldalon hagyják, és ezek valós időben megjelenjenek az oldalon.
5. **Többnyelvű támogatás**: A webshop különböző nyelveken való elérhetősége a nemzetközi piacok elérése érdekében.
6. **Többféle fizetési opció támogatása**: Bankkártyás fizetés, utánvét, digitális pénztárcák (pl. PayPal, Revolut).
7. **Szállítási opciók bővítése**: Gyorsított kézbesítés, személyes átvétel, csomagautomata szolgáltatások.
8. **Csomag nyomon követése**: Integráció futárszolgálatokkal, hogy a vásárlók valós időben láthassák rendelésük állapotát.
9. **Egyszerű regisztráció és belépés**: E-mail, Facebook vagy Google-fiókkal.
10. **Kategóriák és alkategóriák bővítése**: Könnyebb navigáció érdekében.
11. **Raktárkészlet valós idejű megjelenítése**: Termékek elérhetőségének pontos állapota.
12. **Méretválasztási lehetőség**: Olyan funkció bevezetése, amely lehetővé teszi a vásárlók számára, hogy a termékekhez elérhető méretek közül könnyen kiválasszák a számukra megfelelőt a termékoldalon.

## 2.8 [Felmerült Kihívások](#felmerult-kihivások)  

A PureLine webshop fejlesztése során rengeteg kihívással kellett szembenéznünk, amelyek rengeteg időt emésztettek fel. A kihívások megoldása nagyon fontos volt a projekt előrehaladása szempontjából. Az alábbiakban részletezzük a legjelentősebb problémákat:

1. **Felhasználói élmény optimalizálása**
   - **Probléma**: Az oldal mobilbarát kialakítása és reszponzív megjelenése kezdetben nem volt tökéletes, ami negatívan befolyásolta a mobilos böngészést.
   - **Megoldás**: A Bootstrap keretrendszer használatával sikerült reszponzívvá alakítanunk a design-t.

2. **Bejelentkezés és regisztráció**
   - **Probléma**: Kezdetben a felhasználói bejelentkezési és regisztrációs folyamat nem volt kellően biztonságos és felhasználóbarát, ami a vásárlók számára kényelmetlenséget okozott.
   - **Megoldás**: A bejelentkezési és regisztrációs rendszert biztonságosabbá tettük titkosított jelszókezeléssel és egyszerűsítettük a felhasználói élményt.

3. **Adatbázis kezelése**
   - **Probléma**: Az adatbázis kezdetben nem volt optimálisan felépítve, ami lassította az oldal betöltési idejét és a keresési funkciókat.
   - **Megoldás**: Az adatbázis struktúráját optimalizáltuk, így gyorsabb adatlekérést és jobb teljesítményt érhettünk el.

4. **Kosár és vásárlási folyamat**
   - **Probléma**: A vásárlási folyamat nem volt kellően gördülékeny, és a kosár nem frissült automatikusan.
   - **Megoldás**: A kosár funkció dinamikus frissítésével és a vásárlási folyamat egyszerűsítésével sikerült megoldani. A vásárlók most már könnyedén módosíthatják kosarukat, és gyorsan átválthatnak a pénztárhoz.

## 2.9 [Teszt Dokumentáció](#teszt-dokumentacio)

### 2.9.1 Tesztelés célja

A bejelentkezési és regisztrációs funkciók helyes működésének ellenőrzése, különös tekintettel a hibás adatok kezelésére. A teszt célja biztosítani, hogy a rendszer megfelelő hibakezelést nyújtson, és ne engedje a hibás vagy hiányos adatokkal történő bejelentkezést vagy regisztrációt a weboldalra, hiszen bejelentkezés nélkül a felhasználók nem tudnak vásárolni, ez a weboldal helyes működése szempontjából kulcsfontosságú pont. Emellett a sikeres bejelentkezés és regisztráció működését is teszteljük.

### 2.9.2 Tesztelési módszer

A rendszer működésének ellenőrzésére funkcionális tesztelést alkalmaztunk. A cél annak biztosítása, hogy az alkalmazás minden funkciója a tervezett módon működjön, és a felhasználói interakciók a megfelelő választ eredményezzék. A tesztelés során az alábbiakat vizsgáltuk:

- A bejelentkezési és regisztrációs folyamatokat érvényes és érvénytelen bemeneti adatokkal.
- Hibás adatok kezelését, és a rendszer által visszaadott hibaüzeneteket.
- A sikeres műveletek, például sikeres bejelentkezés és regisztráció működését.

## 2.9.3 [Funkcionális tesztelés alkalmazása](#Funkcionalis-teszteles alkalmazasa)

A funkcionális tesztelés során a rendszer funkcióit az elvárt viselkedés alapján teszteltük, és biztosítottuk, hogy a következő szempontok mindegyike megfeleljen a követelményeknek:

- **Pozitív tesztelés**: A rendszer helyes működését teszteltük érvényes adatok bevitele esetén (pl. helyes email és jelszó).
- **Negatív tesztelés**: A rendszer reagálását teszteltük hibás vagy érvénytelen adatok esetén (pl. helytelen email vagy jelszó, hiányzó mezők).

## 2.9.4 [Tesztelési lépések](#Tesztelesi-lepesek)

#### 1. Bejelentkezés funkció tesztelése

##### Tesztelési forgatókönyvek:

- **TC1.1**: Helytelen email-cím és jelszó.
- **TC1.2**: Létező email-cím helytelen jelszóval.
- **TC1.3**: Hiányzó email-cím vagy jelszó.
- **TC1.4**: Sikeres bejelentkezés helyes email-cím és jelszó esetén.

### Elvárt eredmény:

- A rendszer hibát jelez hibás adatok esetén, és nem lép tovább a főoldalra.
- Sikeres bejelentkezés esetén a felhasználót átirányítja a felhasználói fiók oldalára.

### Tesztpéldák:

 #### Teszt 1 - Bejelentkezés helytelen email-cím és jelszóval

- **Teszt azonosító**: TC1.1
- **Bemeneti adatok**:
  - Email: admi@gmail.com
  - Jelszó: 123
- **Tesztelt funkció**: Bejelentkezés
- **Eredmény**:
  - Hibaüzenet jelenik meg: „Hibás email cím vagy jelszó.”
  - A felhasználó nem tud bejelentkezni.
- **Státusz**: Sikeres (a rendszer helyesen reagál a hibás adatokra).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\LoginTest1.png" alt="LoginTest1" style="zoom:80%;" />

#### Teszt 2 - Bejelentkezés létező email-cím helytelen jelszóval

- **Teszt azonosító**: TC1.2
- **Bemeneti adatok**:
  - Email: admin@gmail.com
  - Jelszó: helytelenjelszo
- **Tesztelt funkció**: Bejelentkezés
- **Eredmény**:
  - Hibaüzenet jelenik meg: „Hibás email cím vagy jelszó.”
  - A felhasználó nem tud bejelentkezni.
- **Státusz**: Sikeres (a rendszer helyesen reagál a helytelen jelszóra).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\LoginTest2.png" alt="LoginTest2" style="zoom:80%;" />

---

#### Teszt 3 - Bejelentkezés hiányzó email-cím vagy jelszó esetén

- **Teszt azonosító**: TC1.3
- **Bemeneti adatok**:
  - Email: hiányzik vagy üres
  - Jelszó: üres
- **Tesztelt funkció**: Bejelentkezés
- **Eredmény**:
  - Hibaüzenet jelenik meg: „A mezők kitöltése kötelező.”
  - A felhasználó nem tud bejelentkezni.
- **Státusz**: Sikeres (a rendszer helyesen reagál az üres mezőkre).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\LoginTest3.png" alt="LoginTest3" style="zoom:80%;" />

#### Teszt 4 - Bejelentkezés érvényes email-címmel és jelszóval

- **Teszt azonosító**: TC1.4
- **Bemeneti adatok**:
  - Email: admin@gmail.com
  - Jelszó: 1234
- **Tesztelt funkció**: Bejelentkezés
- **Eredmény**:
  - A rendszer sikeresen bejelentkezik, és a felhasználó átirányításra kerül a **Rendeléseim** oldalra.
  - Nincs hibaüzenet.
- **Státusz**: Sikeres (a bejelentkezés a várt módon történt).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\testsiker.png" alt="testsiker" style="zoom:80%;" />

#### 2. Regisztráció funkció tesztelése

**Tesztelési forgatókönyvek:**

- **TC2.1:** Érvénytelen     email-cím.
- **TC2.2:** Már létező     email-cím.
- **TC2.3:** Hiányos adatok (pl.     üres mezők).
- **TC2.4** Sikeres regisztráció     érvényes adatokkal.

**Elvárt eredmény:**

- A rendszer hibát jelez érvénytelen adatok esetén és nem hoz létre új felhasználót.
- Sikeres regisztráció esetén a felhasználót regisztrálja, és átirányítja a Rendeléseim     oldalra.

**Tesztpéldák:**

**Teszt 1 - Regisztráció érvénytelen email-címmel**

- **Teszt azonosító:** TC2.1
- **Bemeneti adatok:**
  - Email: érvénytelen-email
  - Jelszó: 123456
  - Jelszó megerősítése: 123456
- **Tesztelt funkció:** Regisztráció
- **Eredmény:**
  - Hibaüzenet jelenik meg: „Érvénytelen email cím.”
  - A regisztráció nem történik meg.
- **Státusz:** Sikeres (a rendszer helyesen kezeli az érvénytelen email-címet).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\RegiTest1.png" alt="RegiTest1" style="zoom:80%;" />

#### Teszt 2 - Regisztráció már létező email-címmel

- **Teszt azonosító**: TC2.2
- **Bemeneti adatok**:
  - Email: admin@gmail.com
  - Jelszó: 123456
  - Jelszó megerősítése: 123456
- **Tesztelt funkció**: Regisztráció
- **Eredmény**:
  - Hibaüzenet jelenik meg: „Ez az email cím már használatban van.”
  - A regisztráció nem történik meg.
- **Státusz**: Sikeres (a rendszer helyesen azonosítja a duplikált email-címet).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\RegiTest2.png" alt="RegiTest2" style="zoom:80%;" />

#### Teszt 3 - Regisztráció hiányos adatokkal (pl. üres mezők)

- **Teszt azonosító**: TC2.3
- **Bemeneti adatok**:
  - Email: üres
  - Jelszó: 123456
  - Jelszó megerősítése: üres
- **Tesztelt funkció**: Regisztráció
- **Eredmény**:
  - Hibaüzenet jelenik meg: „A mezők kitöltése kötelező.”
  - A regisztráció nem történik meg.
- **Státusz**: Sikeres (a rendszer helyesen kezeli az üres mezőket).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\RegiTest3.png" alt="RegiTest3" style="zoom:80%;" />

#### Teszt 4 - Regisztráció sikeres érvényes adatokkal

- **Teszt azonosító**: TC2.4
- **Bemeneti adatok**:
  - Email: ujfelhasznalo@gmail.com
  - Jelszó: ErősJelszó123
  - Jelszó megerősítése: ErősJelszó123
- **Tesztelt funkció**: Regisztráció
- **Eredmény**:
  - A felhasználó sikeresen regisztrál, és átirányításra kerül a **Rendelési oldalra**.
  - Nincs hibaüzenet.
- **Státusz**: Sikeres (a regisztráció a várt módon történt).

### Így jelenik meg az oldalon:

<img src="C:\Users\User\Desktop\kepek\RegiTest4.png" alt="RegiTest4" style="zoom:80%;" />

## 2.9.5 [Teszt forráskódja](#Teszt-forraskodja)

```php
<?php
require_once('files/functions.php'); // Az autentikálásért felelős függvények betöltése

class LoginTests {

    public function runTests() {
        echo "Tesztelés indítása...<br>"; // Tesztelés indítása

        // TC1.1: Helytelen email-cím és jelszó
        $this->testInvalidEmailAndPassword();

        // TC1.2: Létező email-cím helytelen jelszóval
        $this->testExistingEmailWithWrongPassword();

        // TC1.3: Hiányzó email-cím vagy jelszó
        $this->testMissingEmailOrPassword();

        // TC1.4: Sikeres bejelentkezés helyes email-cím és jelszó esetén
        $this->testValidEmailAndPassword();
    }
    // TC1.1: Helytelen email-cím és jelszó
    private function testInvalidEmailAndPassword() {
        $_POST['email'] = 'invalid@example.com'; // Hibás e-mail cím
        $_POST['password'] = 'wrongpassword'; // Hibás jelszó
        if (!$this->loginUser('invalid@example.com', 'wrongpassword')) {
            echo "✔ TC1.1: Helytelen email-cím és jelszó esetén a bejelentkezés nem sikerült.<br>";
        } else {
            echo "✘ TC1.1: Helytelen email-cím és jelszó esetén a bejelentkezés sikerült.<br>";
        }
    }

    // TC1.2: Létező email-cím helytelen jelszóval
    private function testExistingEmailWithWrongPassword() {
        $_POST['email'] = 'user@example.com'; // Létező e-mail cím
        $_POST['password'] = 'wrongpassword'; // Hibás jelszó
        if (!$this->loginUser('user@example.com', 'wrongpassword')) {
            echo "✔ TC1.2: Létező email-cím helytelen jelszóval a bejelentkezés nem sikerült.<br>";
        } else {
            echo "✘ TC1.2: Létező email-cím helytelen jelszóval a bejelentkezés sikerült.<br>";
        }
    }

    // TC1.3: Hiányzó email-cím vagy jelszó
    private function testMissingEmailOrPassword() {
        $_POST['email'] = ''; // Hiányzó email
        $_POST['password'] = ''; // Hiányzó jelszó
        if (!$this->loginUser('', '')) {
            echo "✔ TC1.3: Hiányzó email-cím vagy jelszó esetén a bejelentkezés nem sikerült.<br>";
        } else {
            echo "✘ TC1.3: Hiányzó email-cím vagy jelszó esetén a bejelentkezés sikerült.<br>";
        }
    }

    // TC1.4: Sikeres bejelentkezés helyes email-cím és jelszó esetén
    private function testValidEmailAndPassword() {
        $_POST['email'] = 'admin@gmail.com'; // Helyes e-mail cím
        $_POST['password'] = '1234'; // Helyes jelszó
        if ($this->loginUser('admin@gmail.com', '1234')) {
            echo "✔ TC1.4: Sikeres bejelentkezés helyes email-cím és jelszó esetén.<br>";
        } else {
            echo "✘ TC1.4: Sikeres bejelentkezés helyes email-cím és jelszó esetén nem sikerült.<br>";
        }
    }

    // Segédfüggvény a bejelentkezés szimulálásához
    private function loginUser($email, $password) {
        return login_user($email, $password);
    }
    
}

// Tesztek futtatása
$loginTests = new LoginTests();
$loginTests->runTests();
?>


```
## 2.9.6 [Tesztek eredményeinek megjelenítése a weboldalon](#Tesztek eredmenyeinek-megjelenitese-a-weboldalon)

![Visualteszt1](C:\Users\User\Desktop\kepek\Visualteszt1.png)

## 3. [Felhasználói Dokumentáció](#felhasznaloi-dokumentacio)  

### PureLine Divat Webshop

A PureLine Divat Webshopot az **InfinityFree** ingyenes webtárhely szolgáltatásán futtatjuk. A webshop zökkenőmentesen használható különböző eszközökön és böngészőkben.

## 3.1 [Rendszerkövetelmények](#rendszerkovetelmenyek)

A PureLine Divat Webshop használatához az alábbi rendszer- és felhasználói követelmények szükségesek:

1. **Hardver**:
   - **Asztali számítógép/laptop**:
     - Legalább 2 GB RAM és 2 GHz-es processzor a böngészők zavartalan futtatásához.
   - **Táblagép/okostelefon**:
     - Modern érintőképernyős eszköz.

2. **Operációs rendszer**:
   - **Asztali eszközök**: Windows 10/11, macOS 11+ vagy Linux disztribúciók.
   - **Mobil eszközök**: iOS 12+ vagy Android 8.0+ operációs rendszer ajánlott.

3. **Böngészők**:
   - Ajánlott böngészők:
     - Google Chrome: 92-es vagy újabb verzió.
     - Mozilla Firefox: 90-es vagy újabb verzió.
     - Microsoft Edge: Chromium alapú verziók.
     - Apple Safari: iOS/macOS legfrissebb verziói.

4. **Internetkapcsolat**:
   - Ajánlott sebesség: Legalább 5 Mbps betöltési sebesség a gyors termékmegjelenítéshez és vásárlási folyamatokhoz.

5. **Képernyőfelbontás**:
   - **Asztali gép**: Minimum 1280x720 pixel (ajánlott 1920x1080 pixel vagy magasabb).
   - **Táblagép**: Minimum 768x1024 pixel.
   - **Mobiltelefon**: Minimum 360x640 pixel, ajánlott 720x1280 pixel vagy magasabb.

---

## 3.2 [Hozzáférés és használat](#Hozzaferes-es-hasznalat)

A PureLine Divat Webshop egy teljesen online elérhető platform, amely nem igényel telepítést vagy külön konfigurációt a felhasználók részéről.

### Hozzáférés az áruházhoz:
1. **Weboldal URL**:
   - A webshop a következő linken érhető el: [https://pureline.infinityfreeapp.com](https://pureline.infinityfreeapp.com)
2. **Felhasználói felület**:
   - Nyisson meg bármilyen modern böngészőt (pl. Google Chrome, Firefox, Edge).
   - Adja meg a fenti URL-t a címsorban, majd nyomja meg az Enter billentyűt.

---

## [3.3 Lehetőségek ismertetése a weboldalon (Asztali / Mobil nézet)](#Lehetosegek-ismertetese)

#### Az oldalon **bejelentkezés nélkül** használható funkciók:
1. **Termékkatalógus böngészése**:
  - A látogatók szabadon böngészhetik az elérhető termékeket, kategóriák és szűrők alapján válogatva.
  - A termékoldalakon elérhetők a részletes információk, például a leírás, ár és képek.
2. **Kereső funkció**:
  - A keresősáv segítségével könnyedén találhatók meg a konkrét termékek vagy terméktípusok.
3. **Kosár használata**:
  - Bejelentkezés nélkül is hozzáadhatók termékek a kosárhoz, azonban a kosár tartalma nem mentődik el a későbbi látogatásokhoz.
4. **Kapcsolatfelvételi információk**:
  - A látogatók elérhetik az ügyfélszolgálat elérhetőségi adatait (telefon, e-mail, közösségi média).
5. **Termékértékelések olvasása**:
  - A termékekhez kapcsolódó vélemények, amelyeket regisztrált felhasználók írtak, minden látogató számára elérhetők.
6. **Kívánságlista**:
  - A látogatók hozzáadhatnak termékeket a kívánságlistájukhoz, így könnyen megjegyezhetik a számukra érdekes vagy később megvásárolni kívánt termékeket.

#### Az oldalon **csak bejelentkezéssel** elérhető funkciók:
1. **Vásárlási előzmények megtekintése**:
  - A regisztrált felhasználók hozzáférhetnek korábbi rendeléseik listájához, beleértve a vásárlás részleteit, például a termékeket, árakat és a szállítás állapotát.
2. **Rendelések követése**:
  - A bejelentkezett felhasználók nyomon követhetik aktuális rendeléseik státuszát (pl. „Folyamatban”, „Késik”, „Kiszállítva”).
3. **Vásárlás**:
  - A vásárlási folyamat befejezése kizárólag regisztrált felhasználók számára elérhető.
  - Ez magában foglalja a termékek kosárból történő megrendelését, a szállítási és számlázási adatok megadását, valamint a fizetési opciók kiválasztását.

## [3.3.1 Regisztráció és Bejelentkezés](#Regisztracio-es-Bejelentkezes)

#### Itt tudunk regisztrálni és bejelentkezni:



<img src="C:\Users\User\Desktop\kepek\Fooldal1.png" alt="Fooldal1" style="zoom:80%;" />

#### Mobil nézet: 

<img src="C:\Users\User\Desktop\kepek\Mobbere.png" alt="Mobbere" style="zoom:67%;" />

#### Pirosan bekeretezett részre kattintva a következő jelenik meg:

<img src="C:\Users\User\Desktop\kepek\MobBe.png" alt="MobBe" style="zoom:67%;" />

<img src="C:\Users\User\Desktop\kepek\MobReg.png" alt="MobReg" style="zoom:67%;" />

#### Mobil nézet: 

<img src="C:\Users\User\Desktop\kepek\MobBe.png" alt="MobBe" style="zoom:67%;" />

<img src="C:\Users\User\Desktop\kepek\MobReg.png" alt="MobReg" style="zoom:67%;" />

Ezeknek a mezők kötelező és helyes kitöltésével tudunk bejelentkezni és regisztrálni.

### 3.3.2 [Főoldal](#Fooldal)

A **PureLine Webshop** letisztult és reszponzív kialakításával biztosítja, hogy a felhasználók könnyedén eligazodjanak az oldalon mind asztali, mind mobil nézetben. Az alábbiakban bemutatjuk a főoldalon található főbb elemeket és funkciókat:

### Főbb szekciók és funkciók

#### 1. Felső menüsor:
- Tartalmazza az alábbi gyorselérési lehetőségeket:
  - Kapcsolatfelvétel (Ügyfélszolgálat elérhetősége)
  - Ingyenes szállítás információja
  - Rendeléskövetés és valuta beállítások (pl. HUF/FT).

#### 2. Logó és Navigációs menü:
- A PureLine logó mellett található a fő kategóriák menüje:
  - Főoldal, Férfi, Női, Gyerekek termékkategóriák.
- Jobb oldalon gyors hozzáférés biztosított:
  - Keresőmező: Termékkeresés egyszerűen.
  - Kívánságlista, Fiókbeállítások és Kosár ikonok.

##### 3. Fő banner:
- Dinamikus, teljes szélességű hirdetés, amely az aktuális kollekciót és promóciókat mutatja be (pl. "Óriási Nyári Kollekció").

#### 4. Népszerű termékek szekció:
- A legkeresettebb termékek rácsos elrendezésben jelennek meg.
- A termékkártyák tartalmazzák:
  - Terméknév, ár, értékelés, és a kívánságlistára helyezés lehetőségét.

#### 5. Promóciós banner:
- Egyedi ajánlatok, például korlátozott idejű akciók kiemelése (pl. „Converse All Star akcióban”).

#### 6. Hangsúlyos termékkategória:
- Például a „Hoodie nap” szekció, amely külön tematikus termékcsoportot mutat be.

#### 7. Blog és Instagram integráció:
- Felhívás a blog olvasására (divathírek és trendek).
- Instagram-fiók elérése a közösségi jelenlét növelése érdekében.

#### 8. Lábléc szekció:
- Hasznos információk a vásárlók számára:
  - Gyors szállítás, Pénzvisszafizetési garancia, és 24/7 Ügyfélszolgálat.



<img src="C:\Users\User\Desktop\kepek\FooldalTeljes.png" alt="FooldalTeljes" style="zoom:80%;" />

**Mobil nézet:** 

<img src="C:\Users\User\Desktop\kepek\MobFo.png" alt="MobFo" style="zoom:80%;" />

### 3.3.3 [Bolt](#Bolt)

### Főbb elemek és funkciók

#### 1. Navigációs menü:
- Az oldal tetején található, amely lehetővé teszi a gyors hozzáférést a Főoldalhoz, a Bolt oldalhoz, valamint a különböző kategóriákhoz (Férfi, Női, Gyerekek).

#### 2. Szűrő panel (bal oldalon):
- **Nem szerinti szűrés**:
  - Férfi, női, gyerekek, vagy mindegyik termékkategória.
- **Árkategóriák szerinti szűrés**:
  - 5000 Ft alatti, 5000-10 000 Ft közötti, és 10 000 Ft feletti termékek.

#### 3. Termékkatalógus:
- A termékek rácsos elrendezésben jelennek meg.
- Minden termékkártyán megtalálható:
  - Terméknév
  - Ár
  - Értékelés
  - Kívánságlistára helyezés ikon.

#### 4. Rendezési lehetőség:
- A felhasználók az oldalon megjelenő termékeket ár (alacsony vagy magas ár), népszerűség vagy értékelés szerint rendezhetik.

#### 5. Lapozás funkció:
- Az oldal alján található lapozó segítségével a látogatók könnyedén navigálhatnak a különböző termékoldalak között.

#### 6. Promóciós banner:
- Az oldal közepén található, amely az aktuális promóciókat és különleges ajánlatokat hirdeti. (Pl. „Converse All Star – Tedd kényelmessé a napodat.”)

<img src="C:\Users\User\Desktop\kepek\Bolt.png" alt="Bolt" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\MobilBolt.png" alt="MobilBolt" style="zoom:67%;" />

### 3.3.4 [**Termékinformáció**](#**Termekinformacio**)

<img src="C:\Users\User\Desktop\kepek\Termek.png" alt="Termek" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\MoTer.png" alt="MoTer" style="zoom:67%;" />

### 3.3.5 [Kivánságlista/Kosár](#Kivánságlista/Kosár)

**Kosár:**

<img src="C:\Users\User\Desktop\kepek\Kosar.png" alt="Kosar" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\KosarMobil.png" alt="KosarMobil" style="zoom:8	%;" />

**Kívánságlista:**

<img src="C:\Users\User\Desktop\kepek\Kivansaglista.png" alt="Kivansaglista" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\KivansagListaMobil.png" alt="KivansagListaMobil" style="zoom:67%;" />

### 3.3.6 [Rendeléseim](#Rendeléseim)

<img src="C:\Users\User\Desktop\kepek\Rendeleseim.png" alt="Rendeleseim" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\RendeleseimMobil.png" alt="RendeleseimMobil" style="zoom:80%;" />

### 3.3.7 [Pénztár](#Penztar)

<img src="C:\Users\User\Desktop\kepek\Penztar.png" alt="Penztar" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\PenztarMob.png" alt="PenztarMob" style="zoom:80%;" />

### 3.3.8 [Rendelés befejezés](#Rendeles-befejezes)

<img src="C:\Users\User\Desktop\kepek\RenBef.png" alt="RenBef" style="zoom:67%;" />

**Mobil nézet:**

<img src="C:\Users\User\Desktop\kepek\RendBefMob.png" alt="RendBefMob" style="zoom:67%;" />

### 3.4 [Gyakran Ismételt Kérdések](#Gyakran-Ismételt-Kérdések)

Az alábbiakban összegyűjtöttük a leggyakoribb kérdéseket és válaszokat a PureLine Divat Webshop használatával kapcsolatban.

### 3.4.1 [Hogyan tudok bejelentkezni/regisztrálni?](#Hogyan-tudok-bejelentkezni/regisztralni?)

A PureLine Divat Webshop bejelentkezési és regisztrációs folyamata egyszerű, és a weboldal minden eszközön könnyen használható.

#### Bejelentkezés folyamata:
1. Nyissa meg a webshop főoldalát: [https://pureline.infinityfreeapp.com](https://pureline.infinityfreeapp.com).
2. A navigációs sáv jobb felső sarkában kattintson a "Fiókom" gombra.
3. Válassza a "Bejelentkezés" opciót.
4. Adja meg a regisztrált email címét és jelszavát.
5. Kattintson a "Bejelentkezés" gombra, és már hozzáférhet fiókjához.

#### Regisztráció folyamata:
1. Nyissa meg a webshop főoldalát: [https://pureline.infinityfreeapp.com](https://pureline.infinityfreeapp.com).
2. A navigációs sáv jobb felső sarkában kattintson a "Fiókom" gombra.
3. Válassza a "Regisztráció" opciót.
4. Töltse ki a regisztrációs űrlapot.
5. Kattintson a "Regisztráció" gombra, és már létre is hozta az oldal a fiókját.

### 3.4.2 [Mi a teendőm, ha elfelejtettem a jelszavamat?](#mi-a-teendom-ha-elfelejtettem-a-jelszavamat)
Jelenleg a PureLine Divat Webshop nem támogatja az automatikus jelszó-helyreállítást az oldalon. Ha elfelejtette jelszavát, az alábbi lépéseket követve kérhet segítséget:

#### Teendők:
1. A főoldalon, a képernyő alján, a jobb oldalon található Live Chat ikonra kattintva azonnal kapcsolatba léphet ügyfélszolgálatunkkal.
2. Miután rákattintott a Live Chat ikonra, válassza ki, hogy AI-bot segítségével vagy valódi ügyfélszolgálattal szeretne beszélni. Ezt követően kérdezze meg, hogyan tudják megoldani a problémát, és biztos lehet abban, hogy segítséget nyújtanak a jelszó visszaállításában.

### 3.4.3 [Kapok-e értesítést a rendelés állapotáról?](#kapok-e-ertesitest-a-rendeles-allapotarol)
Jelenleg nincs automatikus értesítés a rendelés állapotáról, de a weboldalon könnyedén nyomon követheti, hogy a rendelése éppen milyen fázisban van.

#### A rendelés állapotának megtekintésének lépései:
1. Nyissa meg a webshop főoldalát: [https://pureline.infinityfreeapp.com](https://pureline.infinityfreeapp.com).
2. A navigációs sáv jobb felső sarkában kattintson a "Fiókom" gombra.
3. A bal oldalon található profilképe alatt kattintson a "Saját rendeléseim" menüpontra.
4. Ekkor megjelennek a korábbi rendelései, és láthatja azok aktuális állapotát.

### 3.4.4 [Hogyan tudok rendelést törölni vagy módosítani?](#hogyan-tudok-rendelest-torolni-vagy-modositani)
1. A rendelés törléséhez vagy módosításához lépjen kapcsolatba ügyfélszolgálatunkkal a Live Chat funkció segítségével. Ezt a főoldal alján, a jobb oldalon található Live Chat ikonra kattintva érheti el.
2. A Live Chat elindítása után válassza ki, hogy AI-bottal vagy valódi ügyfélszolgálati munkatárssal szeretne beszélni. Ezt követően jelezze, hogy módosítani vagy törölni szeretné rendelését, és csapatunk készséggel segít Önnek a probléma megoldásában.

### 3.4.5 [Vásárolhatok regisztráció nélkül?](#vasarolhatok-regisztracio-nelkul)
Nem, regisztráció szükséges a rendelés leadásához, mivel csak így biztosítható a rendelés státuszának nyomon követése és a vásárlói fiók funkciók elérése.

## 3.5 [Fejlesztői Kapcsolati Információk](#fejlesztoi-kapcsolati-informaciok)
- **E-mail cím**: [kissgabor5622@gmail.com](mailto:kissgabor5622@gmail.com)
- **Telefon**: +36 30 455 9752
- **Weboldal**: [https://pureline.infinityfreeapp.com](https://pureline.infinityfreeapp.com)

