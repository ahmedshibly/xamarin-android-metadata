# Xamarin Android Metadata for DCS
The **Transforms/Metadata.xml** and  **Additions/OptionExt.cs** files can solve building issues caused by binding [Dynamsoft Android Camera SDK](https://www.dynamsoft.com/Products/mobile-imaging-sdk.aspx)(.aar) in Visual Studio.

## How to Use
1. Create an **Android library binding** project in **Visual Studio**.
2. Drag **dynamsoftcamerasdk1.0.0.aar** to **Jars** folder and change **build action** to **LibraryProjectZip**.
3. Copy **Transforms/Metadata.xml** and  **Additions/OptionExt.cs** to the project.
4. Build the project.