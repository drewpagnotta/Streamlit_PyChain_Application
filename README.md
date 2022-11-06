# *Streamlit PyChain Application*
### Denver University FinTech Bootcamp Challenge 18

### Objective
To build a functioning blockchain using Streamlit library

---

### Imports:

<img width="251" alt="Screen Shot 2022-11-05 at 10 12 46 PM" src="https://user-images.githubusercontent.com/108194033/200153870-9b62a1b1-df03-40ba-bfe7-e9f5491611c7.png">

The data is collected through a `@dataclass` decorator through a class called `Record`.

<img width="141" alt="Screen Shot 2022-11-05 at 10 19 00 PM" src="https://user-images.githubusercontent.com/108194033/200153974-0d2f6921-aab3-47d5-a8f4-b82645432997.png">

The `sender`, `receiver`, and `amount` data is submitted by entering text input through 3 `streamlit` functions.

**Example using `sender` data:**
```python
input_value_sender = st.text_input("Enter Address of Sender")
if st.button("Submit Sender Address"):
    st.write(input_value_sender)
```

---

## The following are various screenshots of the *PyChain Application*:

### Overview

<img width="1667" alt="Screen Shot 2022-11-05 at 10 02 34 PM" src="https://user-images.githubusercontent.com/108194033/200154331-26859ca4-f3b4-4cad-b4c3-d9b5e186c3c7.png">

### DataFrame of Validated Blocks

<img width="1320" alt="Screen Shot 2022-11-05 at 10 06 52 PM" src="https://user-images.githubusercontent.com/108194033/200154349-b1f1c991-b991-4275-9654-553862f1791e.png"> <img width="1325" alt="Screen Shot 2022-11-05 at 10 07 08 PM" src="https://user-images.githubusercontent.com/108194033/200154353-5bcc4379-c801-463c-8ed1-c4c64fa69ca9.png">

### Dropdown Menu to Select & View Specific Block Data

<img width="329" alt="Screen Shot 2022-11-05 at 10 05 56 PM" src="https://user-images.githubusercontent.com/108194033/200154508-79920d96-3587-47e7-9743-0f5e6ac2c993.png"> <img width="328" alt="Screen Shot 2022-11-05 at 10 06 30 PM" src="https://user-images.githubusercontent.com/108194033/200154509-d5ac6580-aa88-48c1-9372-1270bda30f3a.png">
