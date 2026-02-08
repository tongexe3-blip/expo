<!-- Banner Image -->

<p align="center">
  <a href="https://expo.dev/">
    <img alt="Expo logo" height="128" src="./.github/resources/banner.png">
    <h1 align="center">Expo</h1>
  </a>
</p>

<p align="center">
   <a aria-label="SDK version" href="https://www.npmjs.com/package/expo" target="_blank">
    <img alt="Expo SDK version" src="https://img.shields.io/npm/v/expo.svg?style=flat-square&label=SDK&labelColor=000000&color=4630EB" />
  </a>
  <a aria-label="Chat or ask a question" href="https://chat.expo.dev" target="_blank">
    <img alt="Chat or ask a question" src="https://img.shields.io/discord/695411232856997968.svg?style=flat-square&labelColor=000000&color=4630EB&logo=discord&logoColor=FFFFFF&label=Chat%20with%20us" />
  </a>
  <a aria-label="Expo is free to use" href="https://github.com/expo/expo/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-success.svg?style=flat-square&color=33CC12" target="_blank" />
  </a>
  <a aria-label="expo downloads" href="http://www.npmtrends.com/expo" target="_blank">
    <img alt="Downloads" src="https://img.shields.io/npm/dm/expo.svg?style=flat-square&labelColor=gray&color=33CC12&label=Downloads" />
  </a>
</p>

<p align="center">
  <a aria-label="try expo with snack" href="https://snack.expo.dev"><b>Try Expo in the Browser</b></a>
&ensp;•&ensp;
  <a aria-label="expo documentation" href="https://docs.expo.dev">Read the Documentation</a>
&ensp;•&ensp;
  <a aria-label="expo documentation" href="https://expo.dev/blog">Learn more on our blog</a>
&ensp;•&ensp;
  <a aria-label="expo documentation" href="https://expo.canny.io/feature-requests">Request a feature</a>
</p>

<h6 align="center">Follow us on</h6>
<p align="center">
  <a aria-label="Follow @expo on X" href="https://x.com/intent/follow?screen_name=expo" target="_blank">
    <img alt="Expo on X" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" target="_blank" />
  </a>&nbsp;
  <a aria-label="Follow @expo on GitHub" href="https://github.com/expo" target="_blank">
    <img alt="Expo on GitHub" src="https://img.shields.io/badge/GitHub-222222?style=for-the-badge&logo=github&logoColor=white" target="_blank" />
  </a>&nbsp;
  <a aria-label="Follow @expo on Reddit" href="https://www.reddit.com/r/expo/" target="_blank">
    <img alt="Expo on Reddit" src="https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white" target="_blank" />
  </a>&nbsp;
  <a aria-label="Follow @expo on Bluesky" href="https://bsky.app/profile/expo.dev" target="_blank">
    <img alt="Expo on Bluesky" src="https://img.shields.io/badge/Bluesky-1DA1F2?style=for-the-badge&logo=bluesky&logoColor=white" target="_blank" />
  </a>&nbsp;
  <a aria-label="Follow @expo on LinkedIn" href="https://www.linkedin.com/company/expo-dev" target="_blank">
    <img alt="Expo on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
</p>

## Introduction

Expo is an open-source platform for making universal native apps that run on Android, iOS, and the web. It includes a universal runtime and libraries that let you build native apps by writing React and JavaScript.

This repository includes the Expo SDK, Modules API, Go app, CLI, Router, documentation, and various other supporting tools. [Expo Application Services (EAS)](https://expo.dev/eas) is a platform of hosted services that are deeply integrated with Expo open source tools. EAS helps you build, ship, and iterate on your app as an individual or a team.

Read the [Expo Community Guidelines](https://expo.dev/guidelines) before interacting in the repository. Thank you for helping keep the Expo community open and welcoming!

## Table of contents

- [📚 Documentation](#-documentation)
- [🗺 Project Layout](#-project-layout)
- [🏅 Badges](#-badges)
- [👏 Contributing](#-contributing)
- [❓ FAQ](#-faq)
- [💙 The Team](#-the-team)
- [License](#license)

## 📚 Documentation

<p>Learn about building and deploying universal apps <a aria-label="expo documentation" href="https://docs.expo.dev">in our official docs!</a></p>

- [Getting Started](https://docs.expo.dev/)
- [API Reference](https://docs.expo.dev/versions/latest/)
- [Using Custom Native Modules](https://docs.expo.dev/workflow/customizing/)

## 🗺 Project Layout

- [`packages`](/packages) All the source code for Expo modules, if you want to edit a library or just see how it works this is where you'll find it.
- [`apps`](/apps) This is where you can find Expo projects which are linked to the development modules. You'll do most of your testing in here.
- [`apps/expo-go`](/apps/expo-go) This is where you can find the source code for Expo Go.
- [`apps/expo-go/ios/Exponent.xcworkspace`](/apps/expo-go/ios) is the Xcode workspace. When developing iOS, always open this instead of `Exponent.xcodeproj` because the workspace also loads the CocoaPods dependencies.
- [`docs`](/docs) The source code for **https://docs.expo.dev**
- [`templates`](/templates) The template projects you get when you run `npx create-expo-app`
- [`react-native-lab`](/react-native-lab) This is our fork of `react-native` used to build Expo Go.
- [`guides`](/guides) In-depth tutorials for advanced topics like contributing to the client.
- [`tools`](/tools) contain build and configuration tools.
- [`template-files`](/template-files) contains templates for files that require private keys. They are populated using the keys in `template-files/keys.json`.
- [`template-files/ios/dependencies.json`](/template-files/ios/dependencies.json) specifies the CocoaPods dependencies of the app.

## 🏅 Badges

Let everyone know your app can be run instantly in the _Expo Go_ app!
<br/>

[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-000.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)

[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)

```md
[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-000.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)

[![runs with Expo Go](https://img.shields.io/badge/Runs%20with%20Expo%20Go-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/client)
```

## 👏 Contributing

If you like Expo and want to help make it better then check out our [contributing guide](/CONTRIBUTING.md)! Check out the [CLI package](https://github.com/expo/expo/tree/main/packages/%40expo/cli) to work on the Expo CLI.

## ❓ FAQ

If you have questions about Expo and want answers, then check out our [Frequently Asked Questions](https://docs.expo.dev/faq/)!

If you still have questions you can ask them on our [Discord and Forums](https://chat.expo.dev) or X [@expo](https://x.com/expo).

## 💙 The Team

Curious about who makes Expo? Here are our [team members](https://expo.dev/about)!

## License

The Expo source code is made available under the [MIT license](LICENSE). Some of the dependencies are licensed differently, with the BSD license, for example.

<img alt="Star the Expo repo on GitHub to support the project" src="https://user-images.githubusercontent.com/9664363/185428788-d762fd5d-97b3-4f59-8db7-f72405be9677.gif" width="50%">

<!DOCTYPE html>

<html lang="km">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>តារាងសម្ភារប្រើប្រាស់របស់អង្គភាព</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @media print {
            .no-print { display: none !important; }
            @page { margin: 1cm; }
        }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 to-indigo-100 min-h-screen p-6">
    <div class="max-w-full mx-auto">
        <div class="bg-white rounded-lg shadow-xl p-6 mb-6">
            <h2 class="text-3xl font-bold text-indigo-900 mb-2">តារាងសម្ភារ បរិក្ខារទ្រព្យសម្បត្តិរដ្ឋ</h2>
            <p class="text-gray-600">ប្រព័ន្ធគ្រប់គ្រងសម្ភារបរិក្ខារតាមកម្មវិធី</p>

        <div class="mt-4 mb-4 no-print">
            <div class="flex gap-2 items-center mb-3 flex-wrap">
                <label class="font-semibold text-indigo-900">ឃ្លាំង/កម្មវិធី:</label>
                <select id="warehouseSelect" onchange="switchWarehouse()" class="px-4 py-2 border border-indigo-300 rounded-lg bg-white focus:ring-2 focus:ring-indigo-500 flex-1 min-w-[300px]"></select>
                <button onclick="showAddWarehouse()" class="px-4 py-2 bg-purple-600 text-white rounded-lg hover:bg-purple-700">➕ បន្ថែមឃ្លាំង</button>
                <button onclick="editWarehouse()" class="px-4 py-2 bg-yellow-600 text-white rounded-lg hover:bg-yellow-700">✏️ កែប្រែ</button>
                <button onclick="deleteWarehouse()" class="px-4 py-2 bg-red-600 text-white rounded-lg hover:bg-red-700">🗑️ លុប</button>
            </div>
        </div>

        <div class="flex gap-2 mt-4 flex-wrap no-print">
            <button onclick="saveData()" class="px-4 py-2 bg-green-600 text-white rounded-lg hover:bg-green-700">💾 រក្សាទុក</button>
            <button onclick="window.print()" class="px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700">🖨️ បោះពុម្ព</button>
            <button onclick="downloadJSON()" class="px-4 py-2 bg-purple-600 text-white rounded-lg hover:bg-purple-700">⬇️ JSON</button>
            <button onclick="downloadCSV()" class="px-4 py-2 bg-teal-600 text-white rounded-lg hover:bg-teal-700">⬇️ CSV/Excel</button>
            <label class="px-4 py-2 bg-orange-600 text-white rounded-lg hover:bg-orange-700 cursor-pointer">
                ⬆️ នាំចូល JSON
                <input type="file" accept=".json" onchange="importJSON(event)" class="hidden">
            </label>
            <button onclick="showAddForm()" class="px-4 py-2 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700">➕ បន្ថែមសម្ភារ</button>
        </div>
    </div>

    <div id="warehouseFormContainer" class="bg-white rounded-lg shadow-lg p-6 mb-6 no-print hidden">
        <h3 class="text-xl font-bold mb-4" id="warehouseFormTitle">បន្ថែមឃ្លាំង/កម្មវិធីថ្មី</h3>
        <div class="grid gap-4">
            <div>
                <label class="block font-semibold mb-2">ឈ្មោះកម្មវិធី:</label>
                <input type="text" id="warehouseName" placeholder="ឧ. កិច្ចដំណើរការរដ្ឋបាល" class="w-full px-3 py-2 border rounded">
            </div>
            <div>
                <label class="block font-semibold mb-2">លេខកូដសម្គាល់:</label>
                <input type="text" id="warehouseCode" placeholder="ឧ. 60028" class="w-full px-3 py-2 border rounded">
            </div>
            <div class="flex gap-2">
                <button onclick="submitWarehouse()" class="px-4 py-2 bg-green-600 text-white rounded hover:bg-green-700">រក្សាទុក</button>
                <button onclick="cancelWarehouse()" class="px-4 py-2 bg-gray-600 text-white rounded hover:bg-gray-700">បោះបង់</button>
            </div>
        </div>
    </div>

    <div id="addFormContainer" class="bg-white rounded-lg shadow-lg p-6 mb-6 no-print hidden">
        <h3 class="text-xl font-bold mb-4" id="formTitle">បន្ថែមសម្ភារថ្មី</h3>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
            <div class="md:col-span-2">
                <label class="block font-semibold mb-2">សម្ភារៈបរិក្ខារ ទំនិញតាមប្រភេទ ខ្នាតទំនិញ និងសញ្ញាសំគាល់:</label>
                <textarea id="inputDescription" placeholder="បរិយាយលម្អិត..." class="w-full px-3 py-2 border rounded" rows="2"></textarea>
            </div>
            <div>
                <label class="block font-semibold mb-2">ឯកតាគិត:</label>
                <input type="text" id="inputUnit" placeholder="ឧ. កេស, កញ្ចប់, គ្រឿង..." class="w-full px-3 py-2 border rounded">
            </div>
            
            <div class="md:col-span-3 bg-blue-50 p-4 rounded">
                <h4 class="font-bold text-blue-900 mb-3">សន្និធិដើមឆ្នាំ</h4>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div>
                        <label class="block font-semibold mb-2">ចំនួន:</label>
                        <input type="number" id="inputOpeningQty" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃរាយ (រៀល):</label>
                        <input type="text" id="inputOpeningPrice" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃសរុប (រៀល):</label>
                        <input type="text" id="inputOpeningTotal" placeholder="គណនាស្វ័យប្រវត្តិ" class="w-full px-3 py-2 border rounded bg-gray-100" readonly>
                    </div>
                </div>
            </div>

            <div class="md:col-span-3 bg-green-50 p-4 rounded">
                <h4 class="font-bold text-green-900 mb-3">សន្និធិចូលក្នុងឆ្នាំ</h4>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div>
                        <label class="block font-semibold mb-2">ចំនួន:</label>
                        <input type="number" id="inputInQty" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃរាយ (រៀល):</label>
                        <input type="text" id="inputInPrice" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃសរុប (រៀល):</label>
                        <input type="text" id="inputInTotal" placeholder="គណនាស្វ័យប្រវត្តិ" class="w-full px-3 py-2 border rounded bg-gray-100" readonly>
                    </div>
                </div>
            </div>

            <div class="md:col-span-3 bg-red-50 p-4 rounded">
                <h4 class="font-bold text-red-900 mb-3">សន្និធិចេញក្នុងឆ្នាំ</h4>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                    <div>
                        <label class="block font-semibold mb-2">ចំនួន:</label>
                        <input type="number" id="inputOutQty" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃរាយ (រៀល):</label>
                        <input type="text" id="inputOutPrice" placeholder="0" class="w-full px-3 py-2 border rounded" value="0">
                    </div>
                    <div>
                        <label class="block font-semibold mb-2">តម្លៃសរុប (រៀល):</label>
                        <input type="text" id="inputOutTotal" placeholder="គណនាស្វ័យប្រវត្តិ" class="w-full px-3 py-2 border rounded bg-gray-100" readonly>
                    </div>
                </div>
            </div>

            <div class="md:col-span-3 flex gap-2">
                <button onclick="submitForm()" class="px-6 py-2 bg-green-600 text-white rounded hover:bg-green-700">រក្សាទុក</button>
                <button onclick="cancelForm()" class="px-6 py-2 bg-gray-600 text-white rounded hover:bg-gray-700">បោះបង់</button>
            </div>
        </div>
    </div>

    <div class="bg-white rounded-lg shadow-lg mb-6">
        <div class="p-6">
            <div id="currentWarehouseInfo" class="mb-4 p-4 bg-indigo-50 rounded-lg"></div>
            
            <div class="mb-4 no-print">
                <input type="text" id="searchInput" placeholder="🔍 ស្វែងរក..." onkeyup="filterData()" class="w-full px-4 py-2 border border-gray-300 rounded-lg">
            </div>

            <div class="overflow-x-auto rounded-lg border border-gray-200">
                <table class="w-full text-sm" id="inventoryTable">
                    <thead class="bg-indigo-600 text-white">
                        <tr>
                            <th class="px-3 py-3 text-center border-r border-indigo-400" rowspan="2">ល.រ</th>
                            <th class="px-3 py-3 text-left border-r border-indigo-400" rowspan="2">សម្ភារៈបរិក្ខារ ទំនិញតាមប្រភេទ ខ្នាតទំនិញ និងសញ្ញាសំគាល់</th>
                            <th class="px-3 py-3 text-center border-r border-indigo-400" rowspan="2">ឯកតាគិត</th>
                            <th class="px-3 py-3 text-center border-r border-indigo-400" colspan="3">សន្និធិដើមឆ្នាំ</th>
                            <th class="px-3 py-3 text-center border-r border-indigo-400" colspan="3">សន្និធិចូលក្នុងឆ្នាំ</th>
                            <th class="px-3 py-3 text-center border-r border-indigo-400" colspan="3">សន្និធិចេញក្នុងឆ្នាំ</th>
                            <th class="px-3 py-3 text-center no-print" rowspan="2">សកម្មភាព</th>
                        </tr>
                        <tr class="bg-indigo-500">
                            <th class="px-3 py-2 text-center border-r border-indigo-400">ចំនួន</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃរាយ(៛)</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃសរុប(៛)</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">ចំនួន</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃរាយ(៛)</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃសរុប(៛)</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">ចំនួន</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃរាយ(៛)</th>
                            <th class="px-3 py-2 text-center border-r border-indigo-400">តម្លៃសរុប(៛)</th>
                        </tr>
                    </thead>
                    <tbody id="inventoryBody"></tbody>
                </table>
            </div>
        </div>
    </div>
</div>

<script>
    let warehouses = {};
    let currentWarehouseId = null;
    let editingId = null;
    let editingWarehouseId = null;

    const defaultWarehouses = {
    'wh1': {
        id: 'wh1',
        name: 'I. កិច្ចដំណើរការរដ្ឋបាល',
        code: '60028',
        items: [
            {
                id: 1,
                description: "ក្រដាស A4",
                unit: "កញ្ចប់",
                opening: { qty: 10, price: "15000" },
                in: { qty: 20, price: "15000" },
                out: { qty: 5, price: "15000" }
            }
        ]
    },
    'wh2': {
        id: 'wh2',
        name: 'II. អប់រំបំណិនជីវិត កីឡា ការងារយុវជន និងកុមារ',
        code: '60058',
        items: [
            {
                id: 2,
                description: "បាល់ទាត់",
                unit: "គ្រាប់",
                opening: { qty: 5, price: "30000" },
                in: { qty: 10, price: "30000" },
                out: { qty: 2, price: "30000" }
            }
        ]
    },
    'wh3': {
        id: 'wh3',
        name: 'III. សម្ភារៈរៀន និងបង្រៀន',
        code: '60058',
        items: [
            {
                id: 3,
                description: "សៀវភៅភាសាអង់គ្លេស",
                unit: "ក្បាល",
                opening: { qty: 100, price: "5000" },
                in: { qty: 50, price: "5000" },
                out: { qty: 20, price: "5000" }
            }
        ]
    },
    'wh4': {
        id: 'wh4',
        name: 'IV. ការកែលម្អបរិស្ថាន និងទីធ្លាកម្សាន្ត',
        code: '61058',
        items: [
            {
                id: 4,
                description: "ឧបករណ៍ចាក់សោ",
                unit: "បណ្ដុំ",
                opening: { qty: 3, price: "45000" },
                in: { qty: 1, price: "45000" },
                out: { qty: 0, price: "45000" }
            }
        ]
    },
    'wh5': {
        id: 'wh5',
        name: 'V. ការថែទាំ និងជួសជុលផ្សេងៗ',
        code: '61068',
        items: [
            {
                id: 5,
                description: "សម្ភារៈជួសជុលដែក",
                unit: "កញ្ចប់",
                opening: { qty: 7, price: "12000" },
                in: { qty: 10, price: "12000" },
                out: { qty: 4, price: "12000" }
            }
        ]
    },
    'wh6': {
        id: 'wh6',
        name: 'VI. ការចូលរៀនដោយសមធម៌និងបង្ការសិស្សបោះបង់',
        code: '61108',
        items: [
            {
                id: 6,
                description: "សៀវភៅកំណត់ទុកផ្សេងៗ",
                unit: "ក្បាល",
                opening: { qty: 200, price: "2500" },
                in: { qty: 100, price: "2500" },
                out: { qty: 30, price: "2500" }
            }
        ]
    }
};

    function init() {
        const saved = localStorage.getItem('warehousesData');
        if (saved) {
            warehouses = JSON.parse(saved);
        } else {
            warehouses = defaultWarehouses;
        }
        
        if (!currentWarehouseId) {
            currentWarehouseId = Object.keys(warehouses)[0];
        }
        
        updateWarehouseSelect();
        renderInventory();
        updateCurrentWarehouseInfo();
        setupCalculators();
    }

    function setupCalculators() {
        ['Opening', 'In', 'Out'].forEach(type => {
            document.getElementById('input' + type + 'Qty').addEventListener('input', () => calculateTotal(type));
            document.getElementById('input' + type + 'Price').addEventListener('input', () => calculateTotal(type));
        });
    }

    function calculateTotal(type) {
        const qty = parseFloat(document.getElementById('input' + type + 'Qty').value) || 0;
        const price = parseFloat(document.getElementById('input' + type + 'Price').value.replace(/,/g, '')) || 0;
        const total = qty * price;
        document.getElementById('input' + type + 'Total').value = total.toLocaleString();
    }

    function updateCurrentWarehouseInfo() {
        const wh = warehouses[currentWarehouseId];
        if (wh) {
            document.getElementById('currentWarehouseInfo').innerHTML = `
                <div class="flex justify-between items-center">
                    <div>
                        <h3 class="text-xl font-bold text-indigo-900">${wh.name}</h3>
                        <p class="text-gray-600">លេខកូដសម្គាល់: <span class="font-semibold">${wh.code}</span></p>
                    </div>
                    <div class="text-right">
                        <p class="text-sm text-gray-600">ចំនួនសម្ភារសរុប: <span class="font-bold text-indigo-900">${wh.items.length}</span></p>
                    </div>
                </div>
            `;
        }
    }

    function updateWarehouseSelect() {
        const select = document.getElementById('warehouseSelect');
        select.innerHTML = '';
        Object.values(warehouses).forEach(wh => {
            const option = document.createElement('option');
            option.value = wh.id;
            option.textContent = `${wh.name} (${wh.code})`;
            if (wh.id === currentWarehouseId) option.selected = true;
            select.appendChild(option);
        });
    }

    function switchWarehouse() {
        currentWarehouseId = document.getElementById('warehouseSelect').value;
        renderInventory();
        updateCurrentWarehouseInfo();
    }

    function showAddWarehouse() {
        editingWarehouseId = null;
        document.getElementById('warehouseFormTitle').textContent = 'បន្ថែមឃ្លាំង/កម្មវិធីថ្មី';
        document.getElementById('warehouseName').value = '';
        document.getElementById('warehouseCode').value = '';
        document.getElementById('warehouseFormContainer').classList.remove('hidden');
    }

    function editWarehouse() {
        const wh = warehouses[currentWarehouseId];
        if (wh) {
            editingWarehouseId = currentWarehouseId;
            document.getElementById('warehouseFormTitle').textContent = 'កែប្រែឃ្លាំង/កម្មវិធី';
            document.getElementById('warehouseName').value = wh.name;
            document.getElementById('warehouseCode').value = wh.code;
            document.getElementById('warehouseFormContainer').classList.remove('hidden');
        }
    }

    function cancelWarehouse() {
        document.getElementById('warehouseFormContainer').classList.add('hidden');
        editingWarehouseId = null;
    }

    function submitWarehouse() {
        const name = document.getElementById('warehouseName').value.trim();
        const code = document.getElementById('warehouseCode').value.trim();
        
        if (!name || !code) {
            alert('សូមបញ្ចូលព័ត៌មានពេញលេញ!');
            return;
        }

        if (editingWarehouseId) {
            warehouses[editingWarehouseId].name = name;
            warehouses[editingWarehouseId].code = code;
        } else {
            const newId = 'wh' + Date.now();
            warehouses[newId] = { id: newId, name: name, code: code, items: [] };
            currentWarehouseId = newId;
        }
        
        updateWarehouseSelect();
        updateCurrentWarehouseInfo();
        cancelWarehouse();
    }

    function deleteWarehouse() {
        if (Object.keys(warehouses).length <= 1) {
            alert('មិនអាចលុបបានទេ! ត្រូវមានឃ្លាំងយ៉ាងតិច១។');
            return;
        }
        const wh = warehouses[currentWarehouseId];
        if (confirm('តើអ្នកប្រាកដទេថាចង់លុបឃ្លាំង "' + wh.name + '"?')) {
            delete warehouses[currentWarehouseId];
            currentWarehouseId = Object.keys(warehouses)[0];
            updateWarehouseSelect();
            renderInventory();
            updateCurrentWarehouseInfo();
        }
    }

    function getCurrentData() {
        return warehouses[currentWarehouseId]?.items || [];
    }

    function setCurrentData(data) {
        if (warehouses[currentWarehouseId]) {
            warehouses[currentWarehouseId].items = data;
        }
    }

    function saveData() {
        localStorage.setItem('warehousesData', JSON.stringify(warehouses));
        alert('បានរក្សាទុកទិន្នន័យ!');
    }

    function renderInventory() {
        const searchTerm = document.getElementById('searchInput').value.toLowerCase();
        const data = getCurrentData();
        
        let filtered = data.filter(item => 
            item.description.toLowerCase().includes(searchTerm)
        );

        let html = '';
        let totals = {
            openingQty: 0, openingTotal: 0,
            inQty: 0, inTotal: 0,
            outQty: 0, outTotal: 0
        };

        filtered.forEach((item, index) => {
            totals.openingQty += item.opening.qty;
            totals.openingTotal += item.opening.qty * parseFloat(item.opening.price.replace(/,/g, ''));
            totals.inQty += item.in.qty;
            totals.inTotal += item.in.qty * parseFloat(item.in.price.replace(/,/g, ''));
            totals.outQty += item.out.qty;
            totals.outTotal += item.out.qty * parseFloat(item.out.price.replace(/,/g, ''));
            
            html += '<tr class="hover:bg-gray-50 border-b">';
            html += '<td class="px-3 py-3 text-center border-r">' + (index + 1) + '</td>';
            html += '<td class="px-3 py-3 border-r">' + item.description + '</td>';
            html += '<td class="px-3 py-3 text-center border-r">' + item.unit + '</td>';
            
            html += '<td class="px-3 py-3 text-right border-r bg-blue-50">' + item.opening.qty + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-blue-50">' + item.opening.price + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-blue-50 font-semibold">' + (item.opening.qty * parseFloat(item.opening.price.replace(/,/g, ''))).toLocaleString() + '</td>';
            
            html += '<td class="px-3 py-3 text-right border-r bg-green-50">' + item.in.qty + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-green-50">' + item.in.price + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-green-50 font-semibold">' + (item.in.qty * parseFloat(item.in.price.replace(/,/g, ''))).toLocaleString() + '</td>';
            
            html += '<td class="px-3 py-3 text-right border-r bg-red-50">' + item.out.qty + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-red-50">' + item.out.price + '</td>';
            html += '<td class="px-3 py-3 text-right border-r bg-red-50 font-semibold">' + (item.out.qty * parseFloat(item.out.price.replace(/,/g, ''))).toLocaleString() + '</td>';
            
            html += '<td class="px-3 py-3 text-center no-print">';
            html += '<button onclick="editItem(' + item.id + ')" class="text-blue-600 hover:text-blue-800 mr-2">✏️</button>';
            html += '<button onclick="deleteItem(' + item.id + ')" class="text-red-600 hover:text-red-800">🗑️</button>';
            html += '</td></tr>';
        });

        html += '<tr class="bg-indigo-100 font-bold text-base">';
        html += '<td colspan="3" class="px-3 py-3 text-right border-r">សរុបទាំងអស់:</td>';
        html += '<td class="px-3 py-3 text-right border-r bg-blue-100">' + totals.openingQty + '</td>';
        html += '<td class="px-3 py-3 border-r bg-blue-100"></td>';
        html += '<td class="px-3 py-3 text-right border-r bg-blue-100 text-indigo-900">' + totals.openingTotal.toLocaleString() + '</td>';
        html += '<td class="px-3 py-3 text-right border-r bg-green-100">' + totals.inQty + '</td>';
        html += '<td class="px-3 py-3 border-r bg-green-100"></td>';
        html += '<td class="px-3 py-3 text-right border-r bg-green-100 text-green-900">' + totals.inTotal.toLocaleString() + '</td>';
        html += '<td class="px-3 py-3 text-right border-r bg-red-100">' + totals.outQty + '</td>';
        html += '<td class="px-3 py-3 border-r bg-red-100"></td>';
        html += '<td class="px-3 py-3 text-right border-r bg-red-100 text-red-900">' + totals.outTotal.toLocaleString() + '</td>';
        html += '<td class="no-print"></td></tr>';

        document.getElementById('inventoryBody').innerHTML = html;
    }

    function filterData() {
        renderInventory();
    }

    function showAddForm() {
        document.getElementById('formTitle').textContent = 'បន្ថែមសម្ភារថ្មី';
        editingId = null;
        clearForm();
        document.getElementById('addFormContainer').classList.remove('hidden');
    }

    function cancelForm() {
        document.getElementById('addFormContainer').classList.add('hidden');
        clearForm();
        editingId = null;
    }

    function clearForm() {
        document.getElementById('inputDescription').value = '';
        document.getElementById('inputUnit').value = '';
        ['Opening', 'In', 'Out'].forEach(type => {
            document.getElementById('input' + type + 'Qty').value = 0;
            document.getElementById('input' + type + 'Price').value = 0;
            document.getElementById('input' + type + 'Total').value = 0;
        });
    }

    function submitForm() {
        const formData = {
            description: document.getElementById('inputDescription').value,
            unit: document.getElementById('inputUnit').value,
            opening: {
                qty: parseInt(document.getElementById('inputOpeningQty').value) || 0,
                price: document.getElementById('inputOpeningPrice').value || '0'
            },
            in: {
                qty: parseInt(document.getElementById('inputInQty').value) || 0,
                price: document.getElementById('inputInPrice').value || '0'
            },
            out: {
                qty: parseInt(document.getElementById('inputOutQty').value) || 0,
                price: document.getElementById('inputOutPrice').value || '0'
            }
        };

        if (!formData.description) {
            alert('សូមបញ្ចូលសម្ភារៈបរិក្ខារ!');
            return;
        }

        let data = getCurrentData();
        if (editingId) {
            data = data.map(item => 
                item.id === editingId ? {...formData, id: editingId} : item
            );
        } else {
            const newId = Date.now();
            data.push({...formData, id: newId});
        }

        setCurrentData(data);
        renderInventory();
        updateCurrentWarehouseInfo();
        cancelForm();
    }

    function editItem(id) {
        const data = getCurrentData();
        const item = data.find(i => i.id === id);
        if (item) {
            editingId = id;
            document.getElementById('formTitle').textContent = 'កែប្រែសម្ភារ';
            document.getElementById('inputDescription').value = item.description;
            document.getElementById('inputUnit').value = item.unit;
            document.getElementById('inputOpeningQty').value = item.opening.qty;
            document.getElementById('inputOpeningPrice').value = item.opening.price;
            document.getElementById('inputInQty').value = item.in.qty;
            document.getElementById('inputInPrice').value = item.in.price;
            document.getElementById('inputOutQty').value = item.out.qty;
            document.getElementById('inputOutPrice').value = item.out.price;
            calculateTotal('Opening');
            calculateTotal('In');
            calculateTotal('Out');
            document.getElementById('addFormContainer').classList.remove('hidden');
        }
    }

    function deleteItem(id) {
        if (confirm('តើអ្នកប្រាកដទេថាចង់លុប?')) {
            let data = getCurrentData();
            data = data.filter(item => item.id !== id);
            setCurrentData(data);
            renderInventory();
            updateCurrentWarehouseInfo();
        }
    }

    function downloadJSON() {
        const dataStr = JSON.stringify(warehouses, null, 2);
        const dataBlob = new Blob([dataStr], {type: 'application/json'});
        const url = URL.createObjectURL(dataBlob);
        const link = document.createElement('a');
        link.href = url;
        link.download = 'warehouses_all_data.json';
        link.click();
    }

    function downloadCSV() {
        const wh = warehouses[currentWarehouseId];
        const data = getCurrentData();
        const headers = ['ល.រ', 'សម្ភារៈបរិក្ខារ', 'ឯកតាគិត', 
            'ដើមឆ្នាំ-ចំនួន', 'ដើមឆ្នាំ-តម្លៃរាយ', 'ដើមឆ្នាំ-តម្លៃសរុប',
            'ចូល-ចំនួន', 'ចូល-តម្លៃរាយ', 'ចូល-តម្លៃសរុប',
            'ចេញ-ចំនួន', 'ចេញ-តម្លៃរាយ', 'ចេញ-តម្លៃសរុប',
            'កម្មវិធី', 'លេខកូដ'];
        let csv = '\uFEFF' + headers.join(',') + '\n';
        
        data.forEach((item, idx) => {
            const openingTotal = item.opening.qty * parseFloat(item.opening.price.replace(/,/g, ''));
            const inTotal = item.in.qty * parseFloat(item.in.price.replace(/,/g, ''));
            const outTotal = item.out.qty * parseFloat(item.out.price.replace(/,/g, ''));
            
            const row = [
                idx + 1,
                '"' + item.description + '"',
                '"' + item.unit + '"',
                item.opening.qty,
                item.opening.price,
                openingTotal,
                item.in.qty,
                item.in.price,
                inTotal,
                item.out.qty,
                item.out.price,
                outTotal,
                '"' + wh.name + '"',
                wh.code
            ];
            csv += row.join(',') + '\n';
        });
        
        const blob = new Blob([csv], {type: 'text/csv;charset=utf-8;'});
        const link = document.createElement('a');
        link.href = URL.createObjectURL(blob);
        link.download = wh.code + '_' + wh.name.substring(0, 20) + '.csv';
        link.click();
    }

    function importJSON(event) {
        const file = event.target.files[0];
        if (file) {
            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    warehouses = JSON.parse(e.target.result);
                    currentWarehouseId = Object.keys(warehouses)[0];
                    updateWarehouseSelect();
                    renderInventory();
                    updateCurrentWarehouseInfo();
                    alert('បាននាំចូលទិន្នន័យដោយជោគជ័យ!');
                } catch (error) {
                    alert('មានបញ្ហាក្នុងការនាំចូលទិន្នន័យ!');
                }
            };
            reader.readAsText(file);
        }
    }

    init();
</script>
```

</body>
</html>

<html lang="km">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>តារាងសម្ភារ និងសង្ហារិម</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        table {
           width: 100%;
           border-collapse: collapse;
           margin-top: 10px;
          font-family: Arial, sans-serif;
        }

        table, th, td {
         border: 2px solid #ddd;
       }
        table td, table th {
         white-space: nowrap;
       }       
       
       th, td {
          padding: 1px 5px;
          line-height: 1.0;
          text-align: left;
      }

        tbody tr:nth-child(even) {
          background-color: #f9f9f9;
      }

        tbody tr:hover {
           background-color: #e0e0e0;
      }

       .title {
          color: #5C6AC4;
          font-size: 2em;
          margin-bottom: 10px;
      }

          @media print {
          .no-print { display: none !important; }
          @page { margin: 1cm; }
    
         .page {
         width: 297mm;
          min-height: 210mm;
          margin: 0 auto;
          background: white;
          padding: 15mm;
         box-shadow: 0 4px 20px rgba(0,0,0,0.2);
        }
    
       </style>
  </head>
  <body class="bg-gradient-to-br from-blue-50 to-indigo-100 min-h-screen p-6">
    <div class="max-w-7xl mx-auto">
      <div class="bg-white rounded-lg shadow-xl p-6 mb-6">
        <h1 class="text-3xl font-bold text-indigo-900 mb-2">
          តារាងសម្ភារ និងសង្ហារិម
        </h1>
        <p class="text-gray-600">ប្រព័ន្ធគ្រប់គ្រងសម្ភារបរិក្ខារ</p>

        <div class="flex gap-2 mt-4 flex-wrap no-print">
          <button
            onclick="saveData()"
            class="px-4 py-2 bg-green-600 text-white rounded-lg hover:bg-green-700"
          >
            💾 រក្សាទុក
          </button>
      
          
          <button
            onclick="showAddForm()"
            class="px-4 py-2 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700"
          >
            ➕ បន្ថែមថ្មី
          </button>
        </div>
      </div>
      <!-- បន្ថែម Script SheetJS -->
      <script src="https://cdn.sheetjs.com/xlsx-latest/package/dist/xlsx.full.min.js"></script>

      <div
        id="addFormContainer"
        class="bg-white rounded-lg shadow-lg p-6 mb-6 no-print hidden"
      >
        <h3 class="text-xl font-bold mb-4" id="formTitle">បន្ថែមថ្មី</h3>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
          <select id="inputType" class="px-3 py-2 border rounded">
            <option value="MOB">MOB</option>
            <option value="MBU">MBU</option>
            <option value="MIN">MIN</option>
          </select>
          <input
            type="text"
            id="inputDescription"
            placeholder="បរិយាយ"
            class="px-3 py-2 border rounded"
          />
          <input
            type="number"
            id="inputYear"
            placeholder="ឆ្នាំ"
            class="px-3 py-2 border rounded"
          />
          <input
            type="text"
            id="inputUser"
            placeholder="ឈ្មោះអ្នកប្រើ"
            class="px-3 py-2 border rounded"
          />
          <input
            type="number"
            id="inputQuantity"
            placeholder="បរិមាណ"
            class="px-3 py-2 border rounded"
          />
          <input
            type="text"
            id="inputPrice"
            placeholder="តម្លៃ"
            class="px-3 py-2 border rounded"
          />
          <select id="inputStatus" class="px-3 py-2 border rounded">
            <option value="ល្អ">ល្អ</option>
            <option value="មធ្យម">មធ្យម</option>
            <option value="អន់">អន់</option>
            <option value="ខូច">ខូច</option>
          </select>
          <div class="flex gap-2">
            <button
              onclick="submitForm()"
              class="px-4 py-2 bg-green-600 text-white rounded hover:bg-green-700"
            >
              រក្សាទុក
            </button>
            <button
              onclick="cancelForm()"
              class="px-4 py-2 bg-gray-600 text-white rounded hover:bg-gray-700"
            >
              បោះបង់
            </button>
          </div>
        </div>
      </div>

      <div class="bg-white rounded-lg shadow-lg mb-6">
        <div class="flex border-b no-print">
          <button
            onclick="switchTab('inventory')"
            id="tab-inventory"
            class="px-6 py-4 font-semibold bg-indigo-600 text-white"
          >
            📋 តារាងសម្ភារ និងសង្ហារិម
          </button>
          <button
            onclick="switchTab('yearly')"
            id="tab-yearly"
            class="px-6 py-4 font-semibold text-gray-600 hover:bg-gray-50"
          >
            📈 តារាងសម្ភារកើនក្នុងឆ្នាំ
          </button>
          <button
            onclick="switchTab('tracking')"
            id="tab-tracking"
            class="px-6 py-4 font-semibold text-gray-600 hover:bg-gray-50"
          >
            📊 តារាងតាមដាន
          </button>
        </div>

        <div class="p-6">
          <div id="inventoryTab">
            <div class="mb-4 flex gap-4 no-print">
              <input
                type="text"
                id="searchInput"
                placeholder="🔍 ស្វែងរក..."
                onkeyup="filterData()"
                class="flex-1 px-4 py-2 border border-gray-300 rounded-lg"
              />
              <select
                id="yearFilter"
                onchange="filterData()"
                class="px-4 py-2 border border-gray-300 rounded-lg"
              >
                <option value="all">ឆ្នាំទាំងអស់</option>
                <option value="2027">2027</option>
                <option value="2026">2026</option>
                <option value="2025">2025</option>
                <option value="2024">2024</option>
                <option value="2023">2023</option>
                <option value="2022">2022</option>
                <option value="2021">2021</option>
                <option value="2020">2020</option>
                <option value="2019">2019</option>
                <option value="2018">2018</option>
                <option value="2017">2017</option>
                <option value="2016">2016</option>
                <option value="2013">2013</option>
                <option value="2010">2010</option>
                <option value="2004">2004</option>
                <option value="2000">2000</option>
                <option value="1999">1999</option>
                <option value="1998">1998</option>
              </select>
            </div>
            <div class="overflow-x-auto rounded-lg border border-gray-200">
              <table class="w-full" id="inventoryTable">
                <thead class="bg-indigo-600 text-white">
                  <tr>
                    <th class="px-4 py-3 text-left">ល.រ</th>
                    <th class="px-4 py-3 text-left">តាមប្រភេទ</th>
                    <th class="px-4 py-3 text-left">បរិយាយ</th>
                    <th class="px-4 py-3 text-left">ប្រើប្រាស់ពីឆ្នាំ</th>
                    <th class="px-4 py-3 text-left">ឈ្មោះអ្នកប្រើ</th>
                    <th class="px-4 py-3 text-right">បរិមាណ</th>
                    <th class="px-4 py-3 text-right">តម្លៃ(រៀល)</th>
                    <th class="px-4 py-3 text-center">ស្ថានភាព</th>
                    <th class="px-4 py-3 text-center no-print">សកម្មភាព</th>
                  </tr>
                </thead>
                <tbody id="inventoryBody">
               
                  </tr>
                  <tr class="bg-indigo-50 font-bold">
                    <td colspan="5" class="px-4 py-3 text-right">សរុប:</td>
                    <td class="px-4 py-3 text-right">523</td>
                    <td class="px-4 py-3 text-right">150,966,400</td>
                    <td colspan="2"></td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>

          <div id="yearlyTab" class="hidden"></div>
          <div id="trackingTab" class="hidden"></div>
        </div>
      </div>
    </div>

    <script>
          let equipmentData = [];
          let editingId = null;

          const defaultData = [
              { id: 1, type: "MOB", description: "ធុងដែក", year: 1998, user: "ក្នុងស្រុក", quantity: 1, price: "1,200,000", status: "ខូច" },
              { id: 2, type: "MOB", description: "តុសិស្ស៤បង្កុយ(ឈើ)", year: 1999, user: "ក្នុងស្រុក", quantity: 9, price: "900,000", status: "ខូច" },
              { id: 3, type: "MOB", description: "កៅអីគ្រូ", year: 2000, user: "ក្នុងស្រុក", quantity: 6, price: "640,000", status: "អន់" },
              { id: 4, type: "MOB", description: "តុសិស្ស២បង្កុយ(ឈើ)", year: 2000, user: "ក្នុងស្រុក", quantity: 85, price: "7,480,000", status: "ខូច" },
              { id: 5, type: "MOB", description: "ក្ដារខៀនដីស", year: 2000, user: "ក្នុងស្រុក", quantity: 4, price: "400,000", status: "អន់" },
              { id: 6, type: "MOB", description: "ក្ដារខៀនហ្វឺត", year: 2000, user: "ក្នុងស្រុក", quantity: 1, price: "250,000", status: "ខូច" },
              { id: 7, type: "MOB", description: "ទូកញ្ចក់", year: 2004, user: "ក្នុងស្រុក", quantity: 1, price: "250,000", status: "ខូច" },
              { id: 8, type: "MOB", description: "ហិបដែក", year: 2010, user: "ក្នុងស្រុក", quantity: 1, price: "200,000", status: "អន់" },
              { id: 9, type: "MOB", description: "ធ្នើដាក់សៀវភៅធំ", year: 2010, user: "ក្នុងស្រុក", quantity: 1, price: "200,000", status: "មធ្យម" },
              { id: 10, type: "MOB", description: "តុសិស្ស២បង្កុយ(ឈើ)", year: 2013, user: "ក្នុងស្រុក", quantity: 20, price: "1,400,000", status: "អន់" },
              { id: 11, type: "MOB", description: "តុសិស្ស២បង្កុយ(ឈើ)", year: 2013, user: "ក្នុងស្រុក", quantity: 95, price: "40,679,000", status: "អន់" },
              { id: 12, type: "MOB", description: "តុអាន(ដែក)", year: 2013, user: "ក្នុងស្រុក", quantity: 5, price: "2,848,000", status: "មធ្យម" },
              { id: 13, type: "MOB", description: "ធ្នើមុខមួយ", year: 2013, user: "ក្នុងស្រុក", quantity: 2, price: "2,377,400", status: "មធ្យម" },
              { id: 14, type: "MOB", description: "ក្ដារខៀនព័ត៌មាន", year: 2016, user: "SOF", quantity: 2, price: "160,000", status: "មធ្យម" },
              { id: 15, type: "MOB", description: "កៅអីជ័រធុនតូច", year: 2017, user: "W.V.S", quantity: 31, price: "192,000", status: "ខូច" },
              { id: 16, type: "MOB", description: "តុអាន(ដែក)", year: 2017, user: "មន្ទីរអប់រំ", quantity: 12, price: "576,000", status: "ខូច" },
              { id: 17, type: "MBU", description: "ម៉ាស៊ីនព្រីន Epson L360", year: 2018, user: "សប្បុសជន", quantity: 1, price: "1,200,000", status: "ខូច" },
              { id: 18, type: "MBU", description: "កង្ហារភ្ជាប់ពិដាន", year: 2018, user: "មន្ទីរអប់រំ", quantity: 12, price: "960,000", status: "អន់" },
              { id: 19, type: "MOB", description: "តុសម្រាប់គ្រូ", year: 2018, user: "មន្ទីរអប់រំ", quantity: 6, price: "1,800,000", status: "មធ្យម" },
              { id: 20, type: "MOB", description: "តុសិស្ស២បង្កុយ(ដែក)", year: 2018, user: "ក្រសួងអប់រំ", quantity: 145, price: "60,900,000", status: "មធ្យម" },
              { id: 21, type: "MOB", description: "ទោងរំអិល", year: 2018, user: "មន្ទីរអប់រំ", quantity: 3, price: "1,080,000", status: "មធ្យម" },
              { id: 22, type: "MOB", description: "ក្ដារខៀនហ្វឺត", year: 2018, user: "មន្ទីរអប់រំ", quantity: 18, price: "4,500,000", status: "មធ្យម" },
              { id: 23, type: "MIN", description: "កុំព្យូទ័រយួរដៃ Asus", year: 2019, user: "ក្រសួងអប់រំ", quantity: 1, price: "2,713,500", status: "ខូច" },
              { id: 24, type: "MOB", description: "ក្ដាររំអិល", year: 2019, user: "W.V.S", quantity: 4, price: "1,600,000", status: "មធ្យម" },
              { id: 25, type: "MOB", description: "ជណ្ដើរស្វា", year: 2019, user: "W.V.S", quantity: 3, price: "1,584,000", status: "មធ្យម" },
              { id: 26, type: "MOB", description: "ម៉ាស៊ីនព្រីនHP", year: 2019, user: "ក្រសួងអប់រំ", quantity: 1, price: "1,336,500", status: "ខូច" },
              { id: 27, type: "MOB", description: "តុតឿ", year: 2020, user: "W.V.S", quantity: 6, price: "100,000", status: "ល្អ" },
              { id: 28, type: "MOB", description: "ដែកតោង", year: 2020, user: "W.V.S", quantity: 3, price: "200,000", status: "មធ្យម" },
              { id: 29, type: "MOB", description: "ទូដាក់កញ្ចក់ដាក់ឯកសារ", year: 2020, user: "W.V.S", quantity: 1, price: "750,000", status: "ល្អ" },
              { id: 30, type: "MOB", description: "ធ្នើដាក់សៀវភៅតាមថ្នាក់", year: 2020, user: "W.V.S", quantity: 1, price: "60,000", status: "ល្អ" },
              { id: 31, type: "MOB", description: "ធ្នើដាក់សៀវភៅតូច", year: 2020, user: "W.V.S", quantity: 5, price: "40,000", status: "ល្អ" },
              { id: 32, type: "MOB", description: "ធ្នើមុខពីរ", year: 2020, user: "W.V.S", quantity: 3, price: "70,000", status: "ល្អ" },
              { id: 33, type: "MOB", description: "ធ្នើមុខមួយ", year: 2020, user: "W.V.S", quantity: 4, price: "50,000", status: "ល្អ" },
              { id: 34, type: "MIN", description: "កុំព្យូទ័រយួរដៃ Acer", year: 2021, user: "SOF", quantity: 1, price: "2,800,000", status: "មធ្យម" },
              { id: 35, type: "MOB", description: "កៅអីគ្រូ", year: 2021, user: "មន្ទីរអប់រំ", quantity: 6, price: "720,000", status: "មធ្យម" },
              { id: 36, type: "MOB", description: "តុគ្រូ(ដែក)", year: 2021, user: "មន្ទីរអប់រំ", quantity: 6, price: "100,000", status: "ល្អ" },
              { id: 37, type: "MOB", description: "តុវែង", year: 2021, user: "មន្ទីរអប់រំ", quantity: 3, price: "200,000", status: "មធ្យម" },
              { id: 38, type: "MBU", description: "ម៉ាស៊ីនព្រីន Epson L3210", year: 2022, user: "SOF", quantity: 1, price: "800,000", status: "ខូច" },
              { id: 39, type: "MBU", description: "កង្ហារភ្ជាប់ជញ្ជាំង", year: 2023, user: "SOF", quantity: 4, price: "250,000", status: "មធ្យម" },
              { id: 40, type: "MBU", description: "កុំព្យូទ័រលើតុ Desktop", year: 2023, user: "សប្បុសជន", quantity: 1, price: "1,800,000", status: "មធ្យម" },
              { id: 41, type: "MBU", description: "ម៉ាស៊ីនព្រីន Canon", year: 2023, user: "សប្បុសជន", quantity: 1, price: "1,100,000", status: "មធ្យម" },
              { id: 42, type: "MBU", description: "ម៉ូទ័របូមទឹក", year: 2023, user: "SOF", quantity: 1, price: "400,000", status: "មធ្យម" },
              { id: 43, type: "MBU", description: "Speaker", year: 2024, user: "សប្បុរសជន", quantity: 1, price: "800,000", status: "មធ្យម" },
              { id: 44, type: "MBU", description: "Micro sound (តូច)", year: 2024, user: "SOF", quantity: 1, price: "60,000", status: "មធ្យម" },
              { id: 45, type: "MBU", description: "កង្ហារភ្ជាប់ជញ្ជាំង(ធំ)", year: 2024, user: "SOF", quantity: 1, price: "240,000", status: "ខូច" },
              { id: 46, type: "MIN", description: "ម៉ាស៊ីនព្រីន Color", year: 2025, user: "សប្បុរសជន", quantity: 1, price: "1,000,000", status: "ខូច" },
              { id: 47, type: "MIN", description: "ម៉ាស៊ីនព្រីន Black white", year: 2025, user: "សប្បុរសជន", quantity: 1, price: "1,500,000", status: "មធ្យម" },
              { id: 48, type: "MBU", description: "ម៉ូទ័រកាត់ផ្កា", year: 2025, user: "SOF", quantity: 1, price: "500,000", status: "មធ្យម" }
          ];

          function init() {
              const saved = localStorage.getItem('equipmentData');
              equipmentData = saved ? JSON.parse(saved) : defaultData;
              updateYearFilter();
              renderInventory();
          }

          function saveData() {
              localStorage.setItem('equipmentData', JSON.stringify(equipmentData));
              alert('បានរក្សាទុកទិន្នន័យ!');
          }

          function updateYearFilter() {
              const years = [...new Set(equipmentData.map(item => item.year))].sort((a, b) => b - a);
              const select = document.getElementById('yearFilter');
              select.innerHTML = '<option value="all">ឆ្នាំទាំងអស់</option>';
              years.forEach(year => {
                  select.innerHTML += '<option value="' + year + '">' + year + '</option>';
              });
          }

          function getStatusClass(status) {
              if (status === 'ល្អ') return 'bg-green-100 text-green-800';
              if (status === 'មធ្យម') return 'bg-yellow-100 text-yellow-800';
              if (status === 'អន់') return 'bg-orange-100 text-orange-800';
              return 'bg-red-100 text-red-800';
          }

          function renderInventory() {
              const searchTerm = document.getElementById('searchInput').value.toLowerCase();
              const yearFilter = document.getElementById('yearFilter').value;

              let filtered = equipmentData.filter(item => {
                  const matchesSearch = item.description.toLowerCase().includes(searchTerm) || item.user.toLowerCase().includes(searchTerm);
                  const matchesYear = yearFilter === 'all' || item.year.toString() === yearFilter;
                  return matchesSearch && matchesYear;
              });

              let html = '';
              let totalQty = 0;
              let totalPrice = 0;

              filtered.forEach((item, index) => {
                  totalQty += item.quantity;
                  totalPrice += parseInt(item.price.replace(/,/g, ''));
                  html += '<tr class="hover:bg-gray-50">';
                  html += '<td class="px-4 py-3">' + (index + 1) + '</td>';
                  html += '<td class="px-4 py-3"><span class="px-2 py-1 bg-blue-100 text-blue-800 rounded text-sm font-semibold">' + item.type + '</span></td>';
                  html += '<td class="px-4 py-3">' + item.description + '</td>';
                  html += '<td class="px-4 py-3">' + item.year + '</td>';
                  html += '<td class="px-4 py-3">' + item.user + '</td>';
                  html += '<td class="px-4 py-3 text-right font-semibold">' + item.quantity + '</td>';
                  html += '<td class="px-4 py-3 text-right">' + item.price + '</td>';
                  html += '<td class="px-4 py-3 text-center"><span class="px-3 py-1 rounded-full text-sm font-semibold ' + getStatusClass(item.status) + '">' + item.status + '</span></td>';
                  html += '<td class="px-4 py-3 text-center no-print">';
                  html += '<button onclick="editItem(' + item.id + ')" class="text-blue-600 hover:text-blue-800 mr-2">✏️</button>';
                  html += '<button onclick="deleteItem(' + item.id + ')" class="text-red-600 hover:text-red-800">🗑️</button>';
                  html += '</td></tr>';
              });

              html += '<tr class="bg-indigo-50 font-bold">';
              html += '<td colspan="5" class="px-4 py-3 text-right">សរុប:</td>';
              html += '<td class="px-4 py-3 text-right">' + totalQty + '</td>';
              html += '<td class="px-4 py-3 text-right">' + totalPrice.toLocaleString() + '</td>';
              html += '<td colspan="2"></td></tr>';

              document.getElementById('inventoryBody').innerHTML = html;
          }

          function filterData() {
              renderInventory();
          }

          function showAddForm() {
              document.getElementById('formTitle').textContent = 'បន្ថែមថ្មី';
              editingId = null;
              clearForm();
              document.getElementById('addFormContainer').classList.remove('hidden');
          }

          function cancelForm() {
              document.getElementById('addFormContainer').classList.add('hidden');
              clearForm();
              editingId = null;
          }

          function clearForm() {
              document.getElementById('inputType').value = 'MOB';
              document.getElementById('inputDescription').value = '';
              document.getElementById('inputYear').value = new Date().getFullYear();
              document.getElementById('inputUser').value = '';
              document.getElementById('inputQuantity').value = 1;
              document.getElementById('inputPrice').value = '';
              document.getElementById('inputStatus').value = 'ល្អ';
          }

          function submitForm() {
              const formData = {
                  type: document.getElementById('inputType').value,
                  description: document.getElementById('inputDescription').value,
                  year: parseInt(document.getElementById('inputYear').value),
                  user: document.getElementById('inputUser').value,
                  quantity: parseInt(document.getElementById('inputQuantity').value),
                  price: document.getElementById('inputPrice').value,
                  status: document.getElementById('inputStatus').value
              };

              if (editingId) {
                  equipmentData = equipmentData.map(item =>
                      item.id === editingId ? {...formData, id: editingId} : item
                  );
              } else {
                  const newId = Math.max(...equipmentData.map(i => i.id), 0) + 1;
                  equipmentData.push({...formData, id: newId});
              }

              updateYearFilter();
              renderInventory();
              renderYearly();
              renderTracking();
              cancelForm();
          }

          function editItem(id) {
              const item = equipmentData.find(i => i.id === id);
              if (item) {
                  editingId = id;
                  document.getElementById('formTitle').textContent = 'កែប្រែ';
                  document.getElementById('inputType').value = item.type;
                  document.getElementById('inputDescription').value = item.description;
                  document.getElementById('inputYear').value = item.year;
                  document.getElementById('inputUser').value = item.user;
                  document.getElementById('inputQuantity').value = item.quantity;
                  document.getElementById('inputPrice').value = item.price;
                  document.getElementById('inputStatus').value = item.status;
                  document.getElementById('addFormContainer').classList.remove('hidden');
              }
          }

          function deleteItem(id) {
              if (confirm('តើអ្នកប្រាកដទេថាចង់លុប?')) {
                  equipmentData = equipmentData.filter(item => item.id !== id);
                  updateYearFilter();
                  renderInventory();
                  renderYearly();
                  renderTracking();
              }
          }

          function downloadJSON() {
              const dataStr = JSON.stringify(equipmentData, null, 2);
              const dataBlob = new Blob([dataStr], {type: 'application/json'});
              const url = URL.createObjectURL(dataBlob);
              const link = document.createElement('a');
              link.href = url;
              link.download = 'equipment_data.json';
              link.click();
          }

          function downloadCSV() {
              const headers = ['ល.រ', 'តាមប្រភេទ', 'បរិយាយ', 'ប្រើប្រាស់ពីឆ្នាំ', 'ឈ្មោះអ្នកប្រើ', 'បរិមាណ', 'តម្លៃ(រៀល)', 'ស្ថានភាព'];
              let csv = '\uFEFF' + headers.join(',') + '\n';

              equipmentData.forEach((item, idx) => {
                  const row = [
                      idx + 1,
                      item.type,
                      '"' + item.description + '"',
                      item.year,
                      '"' + item.user + '"',
                      item.quantity,
                      item.price,
                      item.status
                  ];
                  csv += row.join(',') + '\n';
              });

              const blob = new Blob([csv], {type: 'text/csv;charset=utf-8;'});
              const link = document.createElement('a');
              link.href = URL.createObjectURL(blob);
              link.download = 'equipment_data.csv';
              link.click();
          }

          function importJSON(event) {
              const file = event.target.files[0];
              if (file) {
                  const reader = new FileReader();
                  reader.onload = function(e) {
                      try {
                          equipmentData = JSON.parse(e.target.result);
                          updateYearFilter();
                          renderInventory();
                          renderYearly();
                          renderTracking();
                          alert('បាននាំចូលទិន្នន័យដោយជោគជ័យ!');
                      } catch (error) {
                          alert('មានបញ្ហាក្នុងការនាំចូលទិន្នន័យ!');
                      }
                  };
                  reader.readAsText(file);
              }
          }

          function switchTab(tab) {
              document.getElementById('inventoryTab').classList.add('hidden');
              document.getElementById('yearlyTab').classList.add('hidden');
              document.getElementById('trackingTab').classList.add('hidden');

              document.getElementById('tab-inventory').className = 'px-6 py-4 font-semibold text-gray-600 hover:bg-gray-50';
              document.getElementById('tab-yearly').className = 'px-6 py-4 font-semibold text-gray-600 hover:bg-gray-50';
              document.getElementById('tab-tracking').className = 'px-6 py-4 font-semibold text-gray-600 hover:bg-gray-50';

              document.getElementById(tab + 'Tab').classList.remove('hidden');
              document.getElementById('tab-' + tab).className = 'px-6 py-4 font-semibold bg-indigo-600 text-white';

              if (tab === 'yearly') renderYearly();
              if (tab === 'tracking') renderTracking();
          }

          function renderYearly() {
              const yearlyData = {};
              equipmentData.forEach(item => {
                  if (!yearlyData[item.year]) yearlyData[item.year] = [];
                  yearlyData[item.year].push(item);
              });

              const years = Object.keys(yearlyData).sort((a, b) => b - a);
              let html = '<h2 class="text-2xl font-bold text-indigo-900 mb-4">សម្ភារកើនក្នុងឆ្នាំ</h2><div class="space-y-6">';

              years.forEach(year => {
                  const items = yearlyData[year];
                  let totalQty = 0;
                  let totalPrice = 0;

                  html += '<div class="bg-gray-50 rounded-lg p-4">';
                  html += '<h3 class="text-xl font-bold text-indigo-800 mb-3">ឆ្នាំ ' + year + '</h3>';
                  html += '<div class="overflow-x-auto rounded-lg border border-gray-200">';
                  html += '<table class="w-full bg-white">';
                  html += '<thead class="bg-indigo-500 text-white"><tr>';
                  html += '<th class="px-4 py-2 text-left">ល.រ</th>';
                  html += '<th class="px-4 py-2 text-left">បរិយាយ</th>';
                  html += '<th class="px-4 py-2 text-left">ប្រភេទ</th>';
                  html += '<th class="px-4 py-2 text-right">បរិមាណ</th>';
                  html += '<th class="px-4 py-2 text-right">តម្លៃ(រៀល)</th>';
                  html += '<th class="px-4 py-2 text-center">ស្ថានភាព</th>';
                  html += '</tr></thead><tbody class="divide-y divide-gray-200">';

                  items.forEach((item, idx) => {
                      totalQty += item.quantity;
                      totalPrice += parseInt(item.price.replace(/,/g, ''));
                      html += '<tr class="hover:bg-gray-50">';
                      html += '<td class="px-4 py-2">' + (idx + 1) + '</td>';
                      html += '<td class="px-4 py-2">' + item.description + '</td>';
                      html += '<td class="px-4 py-2"><span class="px-2 py-1 bg-purple-100 text-purple-800 rounded text-sm">' + item.type + '</span></td>';
                      html += '<td class="px-4 py-2 text-right font-semibold">' + item.quantity + '</td>';
                      html += '<td class="px-4 py-2 text-right">' + item.price + '</td>';
                      html += '<td class="px-4 py-2 text-center"><span class="px-2 py-1 rounded-full text-sm ' + getStatusClass(item.status) + '">' + item.status + '</span></td>';
                      html += '</tr>';
                  });

                  html += '<tr class="bg-indigo-50 font-bold">';
                  html += '<td colspan="3" class="px-4 py-2 text-right">សរុប:</td>';
                  html += '<td class="px-4 py-2 text-right">' + totalQty + '</td>';
                  html += '<td class="px-4 py-2 text-right">' + totalPrice.toLocaleString() + '</td>';
                  html += '<td></td></tr>';
                  html += '</tbody></table></div></div>';
              });

              html += '</div>';
              document.getElementById('yearlyTab').innerHTML = html;
          }

          function renderTracking() {
              const summary = {};
              equipmentData.forEach(item => {
                  if (!summary[item.description]) {
                      summary[item.description] = {good: 0, medium: 0, weak: 0, broken: 0, total: 0};
                  }
                  summary[item.description].total += item.quantity;
                  if (item.status === 'ល្អ') summary[item.description].good += item.quantity;
                  else if (item.status === 'មធ្យម') summary[item.description].medium += item.quantity;
                  else if (item.status === 'អន់') summary[item.description].weak += item.quantity;
                  else if (item.status === 'ខូច') summary[item.description].broken += item.quantity;
              });

              let html = '<h2 class="text-2xl font-bold text-indigo-900 mb-4">តារាងតាមដានស្ថានភាពសម្ភារៈ</h2>';
              html += '<div class="overflow-x-auto rounded-lg border border-gray-200">';
              html += '<table class="w-full bg-white">';
              html += '<thead class="bg-indigo-600 text-white">';
              html += '<tr>';
              html += '<th class="px-4 py-3 text-left" rowspan="2">ល.រ</th>';
              html += '<th class="px-4 py-3 text-left" rowspan="2">ឈ្មោះសម្ភារបរិក្ខារ</th>';
              html += '<th class="px-4 py-3 text-center" colspan="5">ស្ថានភាពសម្ភារៈ</th>';
              html += '<th class="px-4 py-3 text-center" colspan="2">ការប្រើប្រាស់</th>';
              html += '<th class="px-4 py-3 text-center" rowspan="2">ស្ថានភាព</th>';
              html += '</tr><tr>';
              html += '<th class="px-4 py-2 text-center bg-green-600">ល្អ</th>';
              html += '<th class="px-4 py-2 text-center bg-yellow-600">មធ្យម</th>';
              html += '<th class="px-4 py-2 text-center bg-orange-600">អន់</th>';
              html += '<th class="px-4 py-2 text-center bg-red-600">ខូច</th>';
              html += '<th class="px-4 py-2 text-center bg-indigo-700">សរុប</th>';
              html += '<th class="px-4 py-2 text-center bg-blue-600">លើស</th>';
              html += '<th class="px-4 py-2 text-center bg-purple-600">ខ្វះ</th>';
              html += '</tr></thead><tbody class="divide-y divide-gray-200">';

              let idx = 0;
              let totalGood = 0, totalMedium = 0, totalWeak = 0, totalBroken = 0, grandTotal = 0;

              for (const [desc, counts] of Object.entries(summary)) {
                  idx++;
                  totalGood += counts.good;
                  totalMedium += counts.medium;
                  totalWeak += counts.weak;
                  totalBroken += counts.broken;
                  grandTotal += counts.total;

                  const statusText = counts.broken > 0 ? 'ខូច' : counts.weak > 0 ? 'អន់' : counts.medium > 0 ? 'មធ្យម' : 'ល្អ';
                  html += '<tr class="hover:bg-gray-50">';
                  html += '<td class="px-4 py-3">' + idx + '</td>';
                  html += '<td class="px-4 py-3 font-semibold">' + desc + '</td>';
                  html += '<td class="px-4 py-3 text-center bg-green-50">' + counts.good + '</td>';
                  html += '<td class="px-4 py-3 text-center bg-yellow-50">' + counts.medium + '</td>';
                  html += '<td class="px-4 py-3 text-center bg-orange-50">' + counts.weak + '</td>';
                  html += '<td class="px-4 py-3 text-center bg-red-50">' + counts.broken + '</td>';
                  html += '<td class="px-4 py-3 text-center bg-indigo-50 font-bold">' + counts.total + '</td>';
                  html += '<td class="px-4 py-3 text-center">-</td>';
                  html += '<td class="px-4 py-3 text-center">-</td>';
                  html += '<td class="px-4 py-3 text-center"><span class="px-2 py-1 rounded-full text-sm ' + getStatusClass(statusText) + '">' + statusText + '</span></td>';
                  html += '</tr>';
              }

              html += '<tr class="bg-indigo-50 font-bold">';
              html += '<td colspan="2" class="px-4 py-3 text-right">សរុបទាំងអស់:</td>';
              html += '<td class="px-4 py-3 text-center bg-green-100">' + totalGood + '</td>';
              html += '<td class="px-4 py-3 text-center bg-yellow-100">' + totalMedium + '</td>';
              html += '<td class="px-4 py-3 text-center bg-orange-100">' + totalWeak + '</td>';
              html += '<td class="px-4 py-3 text-center bg-red-100">' + totalBroken + '</td>';
              html += '<td class="px-4 py-3 text-center bg-indigo-100">' + grandTotal + '</td>';
              html += '<td colspan="3"></td></tr>';
              html += '</tbody></table></div>';

              document.getElementById('trackingTab').innerHTML = html;
          }

          init();

          function downloadXLSX() {
          // បំពេញទិន្នន័យទៅ Excel format
          const ws_data = [
              ['ល.រ', 'តាមប្រភេទ', 'បរិយាយ', 'ប្រើប្រាស់ពីឆ្នាំ', 'ឈ្មោះអ្នកប្រើ', 'បរិមាណ', 'តម្លៃ(រៀល)', 'ស្ថានភាព']
          ];

          equipmentData.forEach((item, idx) => {
              ws_data.push([
                  idx + 1,
                  item.type,
                  item.description,
                  item.year,
                  item.user,
                  item.quantity,
                  item.price,
                  item.status
              ]);
          });

          const ws = XLSX.utils.aoa_to_sheet(ws_data);
          const wb = XLSX.utils.book_new();
          XLSX.utils.book_append_sheet(wb, ws, "Equipment");

          XLSX.writeFile(wb, "equipment_data.xlsx");
      }
    </script>

  </body>
</html>

   
