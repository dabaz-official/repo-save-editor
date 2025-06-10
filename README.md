# R.E.P.O Save Editor

[<img src="https://flagcdn.com/w20/cn.png" alt="中国国旗"> 简体中文](./README.cn.md)

<div>
  <img src="src/app/icon.png" alt="R.E.P.O Save Editor Logo" width="200" height="200" />
</div>

## Overview

R.E.P.O Save Editor is a web application that allows you to modify R.E.P.O game save files. This tool helps players adjust various game parameters, including:

- Player stats and attributes
- Run stats and currencies
- Purchased items and upgrades
- Team settings and configurations

## Technologies

This project is built using modern web technologies:

- **Next.js 15** - React framework with App Router
- **React 19** - UI library
- **TypeScript** - Type-safe JavaScript
- **TailwindCSS 4** - Utility-first CSS framework
- **next-intl** - Internationalization support
- **shadcn/ui** - Accessible UI components built with Radix UI
- **Lucide React** - Beautiful & consistent icon set

## Getting Started

```bash
# Clone the repository
git clone https://github.com/luccasfr/repo-save-editor.git

# Navigate to the project directory
cd repo-save-editor

# Install dependencies
yarn install

# Start the development server
yarn run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to access the application.

## How to Use

1. Locate your R.E.P.O save file (typically in `%USERPROFILE%\AppData\LocalLow\semiwork\Repo\saves`)
2. Upload the save file to the editor
3. Make your desired changes
4. Download the modified save file
5. Replace your original save file with the modified one

## Acknowledgements

Special thanks to [N0edL's R.E.P.O Save Editor](https://github.com/N0edL/R.E.P.O-Save-Editor) for providing the encryption functions with the key in Python, which were extracted and implemented in Node.js for this project.

## Author

<table>
  <tbody>
    <tr>
      <td align="center">
        <a href="https://github.com/luccasfr">
          <img src="https://github.com/luccasfr.png?size=200" alt="Lucas Ferreira" />
          <p>Lucas Ferreira</p>
        </a>
      </td>
      <td align="center">
        <a href="https://github.com/dabaz-official">
          <img src="https://github.com/dabaz-official.png?size=200" alt="DabAZ" />
          <p>DabAZ</p>
        </a>
      </td>
    </tr>
  </tbody>
</table>
