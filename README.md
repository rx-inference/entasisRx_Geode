<!-- PURPOSE: documentation for the entasisrx project. -->
<div align="center">

  <h1>entasisRx</h1>
  <p>
    <b>a portable, single-file, browser-based todo list application powered by sql.js.</b>
  </p>
  
  <p>
    <img src="https://img.shields.io/badge/Prototype / Work in Progress-crimson" alt="prototype">
    <img src="https://img.shields.io/badge/Tech-HTML_/_JS_/_sql.js-blueviolet" alt="tech stack">
    <a href="https://github.com/rx-inference/fragmentsFx/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="License"></a>
    <a href="#"><img src="https://img.shields.io/badge/Version-v0.3.1-brightgreen" alt="Version"></a>
  </p>


</div>

---

## PROTOTYPING / WORK IN PROGRESS (⚠️)

This software is a work in progress and currently in its prototyping phase. It is not intended for production use. Errors may occur, features may change, and documentation may be fragmented or incomplete. During the prototyping phase, all support inquiries about this software will be ignored.

## OVERVIEW

entasisRx is a self-contained, privacy-focused task manager that runs entirely in your web browser. it's a single html file that uses sql.js to create, manage, and store your todo lists in a local sqlite database file. no server, no installation, no cloud account needed—just open the file and start managing your tasks. your data stays with you.

## KEY FEATURES

- **🔧 serverless & portable:** runs entirely in the browser from a single `.html` file. no installation needed.
- **🗄️ local-first storage:** all data is stored in a local sqlite file that you own and control.
- **✨ intuitive ui:** a clean, table-based view with inline editing for quick and easy task updates.
- **🚦 dynamic priority:** features a visual priority slider (0-1000) with a dynamic color gradient to represent urgency.
- **🗂️ state management:** track tasks with states like 'open', 'in progress', 'passive', 'done', and 'cancelled'.
- **📥/📤 database handling:** create a new database from scratch, load an existing `.sqlite` file, or back up your current tasks at any time.

## USAGE

1. open `entasisRx.html` in a modern web browser.
2. click **database** > **new** to start a fresh todo list.
3. alternatively, click **database** > **load** to open a pre-existing `.sqlite` or `.db` file.
4. add new tasks using the input row at the top of the table.
5. click on any task field (like the task description, due date, or state) to edit it directly.
6. remember to save your database as this can not happen automatically.

## REQUIREMENTS

- a modern web browser (chrome, firefox, edge, etc.) with javascript enabled.

## COPYRIGHT, CONTEXT, LICENSE & LIMITATIONS

Copyright 2025 - Robin Winkelmann | robinRx | rx-inference

This repository, its software and all other associated material is licensed under Apache License, Version 2.0 (the "License").
You may not use this file except in compliance with the License.
See the [LICENSE](https://github.com/rx-inference/entasisRx_Geode/blob/main/LICENSE) in the root of this project for details.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.