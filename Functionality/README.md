## Functionality 

| No. | Title 
| --  | -- 
| 1.  | [Unsaved Changes alert](#unsaved-changes-alert)

---

1. ### Unsaved Changes Alert

    ```js
    window.addEventListener("beforeunload", (e) => {
    e.preventDefault();
    e.returnValue = "";
    });
    ```
