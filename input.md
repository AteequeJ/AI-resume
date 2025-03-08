**Project** **Setup** **Guide**

**1.** **Setting** **Up** **the** **Environment**

> 1.**Unzip** **the** **project** **folder**and open it in **VS**
> **Code**.
>
> 2.Open the terminal and run the following commands to set up a virtual
> environment:
>
> python -m venv env env\Scripts\activate \# Windows
>
> source env/bin/activate \# Mac/Linux

*Ensure* *that* *your* *terminal* *displays* *a* *prefix* *(env)*
*before* *the* *path.*

**2.** **Navigate** **to** **the** **Configuration** **Directory**

> cd ai_resume_matcher

**3.** **Run** **theServer**

Start the Django development server:

> python manage.py runserver

<img src="./jqvc1uz3.png"
style="width:6.26805in;height:1.14167in" />

**4.Run** **thestreamlit** **project** **Open** **another** **terminal**
**navigate** **to** **jobpoint_ui**

> streamlit run app.py

**if** **streamlit** **is** **not** **installed** **you** **encounter**
**error** **message**

**Then** **run** **the** **command:**

> pipinstall streamlit

**now** **run:**

> streamlit run app.py

<img src="./o21neajb.png"
style="width:6.26805in;height:3.52431in" /><img src="./np3sqa2b.png"
style="width:6.26805in;height:3.52431in" />

> **1.Home** **Screen**
>
> **2.Upload** **resume**
>
> **Uploaded** **successfully**

<img src="./nmr23rrl.png"
style="width:6.26805in;height:3.52431in" />

> <img src="./2cmah02c.png"
> style="width:6.26805in;height:3.52431in" />**3.Upload** **Jobs**
>
> <img src="./x4xs3ojz.png"
> style="width:6.26805in;height:3.52431in" /><img src="./y5trf2ow.png"
> style="width:6.26805in;height:3.525in" />**4.Match** **Jobs**

<img src="./bdvrocz3.png"
style="width:6.26805in;height:3.52431in" />

> **5.Generate** **cover** **letter**
>
> <img src="./ynpno1w4.png"
> style="width:6.26805in;height:3.525in" />Successful generation:
>
> **<u>Errors you might encounterand their solution</u>**
>
> **Ifany** **module** **is** **missing**
>
> pip install PyPDF2 pdfplumber python-docx
>
> **If** **virtual** **environment** **is** **not** **setup** **delete**
> **the** **venv** **folder** **and** **entercommand:**
>
> python -m venv venv
>
> **Requirements** **module** **not** **found:**
>
> pip install requirements
>
> **Streamlit** **not** **recognized:**
>
> pipinstall streamlit
