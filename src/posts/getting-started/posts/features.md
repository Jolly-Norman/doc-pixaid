---
title: "Classes"
summary: "bdfk kdlfk lk "
eleventyNavigation:
  key: Classes
  parent: Esquisse
  order: 3
---

## PopupOnglet

BLA BLA EXPLICATION

```shell
    import PopupOnglet from "./Popups/PopupOnglet";



    const popupTest = new PopupOnglet({
      texteTitre: "Ajouter une insruction : ",
      callbackValider: async () => {
          const texteInstruction =
              document.getElementById(
                  "input-instruction"
              );
          alert(texteInstruction?.textContent);
          return true;
      },
      callbackAnnuler: async () => {
          const texteInstruction =
              document.getElementById(
                  "input-instruction"
              );
          alert(texteInstruction?.textContent);
          return true;
      },
    });
    popupTest.divPopup.innerHTML +=
    `
      <div">
        <input style="width: 100%;" type="text" name="" id='input-instruction' placeholder="Que souhaitez vous ajouter ? ">
      </div>
    `;
    popupTest.afficher();


```

- Info info info info
- Info info info info
- Info info info info

## AutreMethodes

BLA BLA EXPLICATION

- Info info info info
- Info info info info
- Info info info info
