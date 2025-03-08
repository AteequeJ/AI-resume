**Project Setup Guide** 

**1. Setting Up the Environment** 

1. **Unzip the project folder** and open it in **VS Code**. 
1. Open the terminal and run the following commands to set up a virtual environment: 

   python -m venv env ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.001.png)env\Scripts\activate  # Windows 

source env/bin/activate  # Mac/Linux

*Ensure that your terminal displays a prefix (env) before the path.* 

2. **Navigate to the Configuration Directory** cd  ai\_resume\_matcher![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.002.png)
2. **Run the Server** 

Start the Django development server:**   python manage.py runserver ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.003.png)

**4.Run the streamlit project Open another terminal  navigate to jobpoint\_ui** 

streamlit run app.py  ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.004.png)

**if streamlit is not installed you encounter error message** 

![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.005.jpeg)

**Then run the command:**   pip install streamlit  ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.006.png)

**now run:** 

streamlit run app.py  ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.007.png)

1. **Home Screen** 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.008.jpeg)

2. **Upload resume** 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.009.jpeg)

   **Uploaded successfully**

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.010.jpeg)

3. **Upload Jobs** 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.011.jpeg)

4. **Match Jobs** 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.012.jpeg)

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.013.jpeg)

5. **Generate cover letter** 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.014.jpeg)

   Successful generation: 

   ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.015.jpeg)

   **Errors you might encounter and their solution If any module is missing** 

pip install PyPDF2 pdfplumber python-docx ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.016.png)

**If virtual environment is not setup delete the venv folder and enter command:** 

python -m venv venv ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.017.png)

**Requirements module not found:** 

pip install requirements ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.018.png)

**Streamlit not recognized:** 

pip install streamlit  ![](Aspose.Words.96cff609-97aa-46f6-9d01-3e5d1c088ad9.019.png)
