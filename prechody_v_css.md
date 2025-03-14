# CSS Gradients - Základné poznámky

CSS gradienty umožňujú plynulý prechod medzi dvoma alebo viacerými farbami bez potreby obrázka. Existujú dva hlavné typy gradientov:

---

## **1. Lineárny gradient (`linear-gradient`)**

Definuje prechod farieb v priamom smere (zľava doprava, zhora nadol, diagonálne).

### **Syntax:**
```css
background: linear-gradient(smer, farba1, farba2, ...);
```
- `smer` – môže byť uhol (napr. `45deg`) alebo smer (`to right`, `to bottom`).
- `farba1, farba2, ...` – farby pre prechod.

### **Príklad: Prechod z modrej do fialovej zhora nadol**
```css
.box {
    width: 200px;
    height: 200px;
    background: linear-gradient(to bottom, blue, purple);
}
```

### **Príklad: Diagonálny prechod**
```css
.box {
    background: linear-gradient(45deg, red, yellow);
}
```

---

## **2. Radiálny gradient (`radial-gradient`)**

Prechod farieb sa šíri z jedného bodu smerom von v kruhovom alebo eliptickom tvare.

### **Syntax:**
```css
background: radial-gradient(tvar, farba1, farba2, ...);
```
- `tvar` – `circle` (kruh) alebo `ellipse` (elipsa, predvolené).
- `farba1, farba2, ...` – farby pre prechod.

### **Príklad: Kruhový gradient zo stredu**
```css
.box {
    background: radial-gradient(circle, red, yellow, blue);
}
```

---

## **3. Kužeľový gradient (`conic-gradient`)**

Farby sa otáčajú okolo stredu v kužeľovom tvare.

### **Syntax:**
```css
background: conic-gradient(farba1, farba2, ...);
```
- Farby sa postupne miešajú do kruhu.

### **Príklad: Viacfarebný gradient v kruhu**
```css
.box {
    background: conic-gradient(red, yellow, green, blue, red);
}
```

---

## **4. Použitie priehľadnosti (`rgba` alebo `transparent`)**

Možno použiť priehľadné farby na vytvorenie zaujímavých efektov.

### **Príklad: Postupná priehľadnosť**
```css
.box {
    background: linear-gradient(to right, rgba(255,0,0,1), rgba(255,0,0,0));
}
```

---

## **5. Užitočné nástroje**

- [CSS Gradient Generator](https://cssgradient.io/) – vizuálny generátor gradientov
- [Gradient CSS Generator](https://www.colorzilla.com/gradient-editor/) – pokročilý editor gradientov
