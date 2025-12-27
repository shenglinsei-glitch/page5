<!DOCTYPE html>
<html class="light" lang="ja"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>インポート</title>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Lexend:wght@300;400;500;700&amp;family=M+PLUS+Rounded+1c:wght@300;400;500;700&amp;family=Noto+Sans+JP:wght@400;500;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    colors: {
                        "primary": "#53BEE8",
                        "success": "#2AC69E",
                        "error": "#F7893F",
                        "background-light": "#f6f6f8",
                        "background-dark": "#101622",
                        "app-title": "#C6CBD4",
                        "app-text": "#5E5E5E",
                        "app-icon": "#53BEE8",
                        "app-icon-shadow": "#E5EBF2",
                        "example-bg": "#E5EBF2",
                        "example-text": "#53BEE8",
                    },
                    fontFamily: {
                        "display": ["M PLUS Rounded 1c", "Lexend", "Noto Sans JP", "sans-serif"],
                        "body": ["M PLUS Rounded 1c", "Noto Sans JP", "sans-serif"],
                    },
                    boxShadow: {
                        "icon": "0 2px 4px var(--tw-shadow-color)",
                    }
                },
            },
        }
    </script>
<style>
        ::-webkit-scrollbar {
            width: 6px;
            height: 6px;
        }
        ::-webkit-scrollbar-track {
            background: transparent;
        }
        ::-webkit-scrollbar-thumb {
            background-color: #e5e7eb;
            border-radius: 20px;
        }
        .icon-shadow {
            filter: drop-shadow(1px 2px 2px #E5EBF2);
        }
        details > summary {
            list-style: none;
        }
        details > summary::-webkit-details-marker {
            display: none;
        }
    </style>
<style>
        body {
            min-height: max(884px, 100dvh);
        }
    </style>
<style>
    body {
      min-height: max(884px, 100dvh);
    }
  </style>
  </head>
<body class="bg-white text-app-text font-display antialiased selection:bg-primary/20 selection:text-primary">
<div class="relative flex h-full min-h-screen w-full flex-col overflow-x-hidden max-w-md mx-auto border-x border-gray-50">
<header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-gray-100">
<div class="flex items-center justify-between p-4 h-14">
<button class="flex size-10 shrink-0 items-center justify-center rounded-full hover:bg-gray-50 transition-colors group">
<span class="material-symbols-outlined text-app-icon icon-shadow group-active:scale-95 transition-transform" style="font-size: 24px;">arrow_back_ios_new</span>
</button>
<h2 class="text-app-title text-xl font-bold leading-tight tracking-tight flex-1 text-center pr-10">インポート</h2>
</div>
</header>
<main class="flex-1 flex flex-col p-4 gap-6">
<section class="flex flex-col gap-3">
<button class="relative w-full overflow-hidden rounded-xl bg-primary h-14 px-5 flex items-center justify-center gap-3 text-white shadow-lg shadow-primary/30 active:scale-[0.98] transition-all hover:bg-primary/90 group z-10">
<span class="material-symbols-outlined group-hover:-translate-y-0.5 transition-transform duration-300" style="font-size: 24px;">upload_file</span>
<span class="text-base font-bold tracking-wide">ファイルを選択</span>
<div class="absolute inset-0 bg-gradient-to-tr from-white/0 via-white/10 to-white/0 opacity-0 group-hover:opacity-100 transition-opacity pointer-events-none"></div>
</button>
<div class="relative overflow-hidden rounded-xl border border-gray-100 bg-white shadow-sm p-4 flex items-center gap-4 animate-in fade-in slide-in-from-top-2 duration-500">
<div class="size-10 rounded-lg bg-primary/10 flex items-center justify-center shrink-0 text-app-icon">
<span class="material-symbols-outlined icon-shadow" style="font-size: 24px;">description</span>
</div>
<div class="flex-1 min-w-0">
<p class="text-sm font-bold text-app-text truncate">my_vocabulary_list.csv</p>
<div class="flex items-center gap-2 mt-1">
<span class="inline-flex items-center gap-1 rounded-full bg-orange-50 px-2 py-0.5 text-[10px] font-bold text-orange-600 border border-orange-100">
<span class="block size-1.5 rounded-full bg-orange-500 animate-pulse"></span>
                            検証完了 (エラーあり)
                        </span>
<span class="text-[10px] text-gray-400">12KB</span>
</div>
</div>
<button class="size-8 flex items-center justify-center rounded-full hover:bg-gray-50 text-gray-300 hover:text-error transition-colors">
<span class="material-symbols-outlined" style="font-size: 20px;">close</span>
</button>
</div>
</section>
<section>
<details class="group rounded-xl border border-gray-100 bg-gray-50/50 overflow-hidden open:bg-white open:shadow-sm transition-all duration-300">
<summary class="flex cursor-pointer items-center justify-between p-3 select-none hover:bg-gray-50 transition-colors">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-app-icon icon-shadow" style="font-size: 20px;">info</span>
<h3 class="text-app-text text-sm font-bold">インポート規則説明</h3>
</div>
<span class="material-symbols-outlined text-gray-400 transition-transform duration-300 group-open:rotate-180" style="font-size: 20px;">expand_more</span>
</summary>
<div class="px-4 pb-4 pt-1 border-t border-gray-100/50">
<div class="grid gap-4 pt-2">
<div class="flex gap-3 items-start">
<span class="material-symbols-outlined text-app-icon shrink-0 mt-0.5 icon-shadow" style="font-size: 16px;">format_quote</span>
<div class="flex flex-col w-full">
<p class="text-app-text text-xs font-bold mb-1">データ構成・形式</p>
<div class="bg-example-bg/50 rounded-lg p-2.5 border border-example-bg">
<div class="flex flex-wrap justify-start items-center gap-1 mb-2 text-[10px]">
<span class="text-example-text font-bold">日本語</span>
<span class="text-gray-400">␣</span>
<span class="text-example-text font-bold">カタカナ</span>
<span class="text-gray-400">␣</span>
<span class="text-example-text font-bold">中国語</span>
<span class="text-gray-400">␣</span>
<span class="text-example-text font-bold">英語</span>
</div>
<div class="bg-white/80 rounded p-2 border border-white/60 w-full">
<code class="block font-mono text-[10px] text-app-text whitespace-pre">食べる   たべる      吃    eat</code>
<code class="block font-mono text-[10px] text-app-text whitespace-pre">難しい   むつかしい  困難  -</code>
</div>
</div>
</div>
</div>
<div class="flex gap-3 items-start">
<span class="material-symbols-outlined text-app-icon shrink-0 mt-0.5 icon-shadow" style="font-size: 16px;">rule</span>
<div class="flex flex-col">
<p class="text-app-text text-xs font-bold">規則・ルール</p>
<p class="text-app-text/70 text-[11px] leading-relaxed">
                                    ・スペースまたはTab区切り<br/>
                                    ・「-」は空欄として扱います<br/>
                                    ・列数自動識別、空行はスキップ
                                </p>
</div>
</div>
<div class="flex gap-3 items-start">
<span class="material-symbols-outlined text-app-icon shrink-0 mt-0.5 icon-shadow" style="font-size: 16px;">folder_open</span>
<div class="flex flex-col">
<p class="text-app-text text-xs font-bold">対応ファイル</p>
<p class="text-app-text/70 text-[11px]">txt / csv / xlsx (iCloud / ローカル)</p>
</div>
</div>
</div>
</div>
</details>
</section>
<section class="flex flex-col gap-3 flex-1">
<div class="flex items-center justify-between pb-1 border-b border-gray-100">
<div class="flex items-center gap-2">
<span class="material-symbols-outlined text-app-icon icon-shadow" style="font-size: 20px;">analytics</span>
<h3 class="text-app-text text-base font-bold">インポート結果 / プレビュー</h3>
</div>
</div>
<div class="grid grid-cols-3 gap-3">
<div class="flex flex-col items-center justify-center p-3 rounded-xl border border-gray-100 bg-gray-50">
<span class="text-[10px] font-bold text-gray-400 mb-0.5">総データ</span>
<span class="text-lg font-bold text-app-text">50</span>
</div>
<div class="flex flex-col items-center justify-center p-3 rounded-xl border border-[#2AC69E]/20 bg-[#2AC69E]/5">
<span class="text-[10px] font-bold text-success/70 mb-0.5">成功</span>
<span class="text-lg font-bold text-success">48</span>
</div>
<div class="flex flex-col items-center justify-center p-3 rounded-xl border border-[#F7893F]/20 bg-[#F7893F]/5">
<span class="text-[10px] font-bold text-error/70 mb-0.5">エラー</span>
<span class="text-lg font-bold text-error">2</span>
</div>
</div>
<div class="flex flex-col gap-2 p-3 rounded-xl bg-[#F7893F]/5 border border-[#F7893F]/20">
<div class="flex items-center gap-2 text-error">
<span class="material-symbols-outlined" style="font-size: 18px;">error</span>
<span class="text-xs font-bold">修正が必要な行</span>
</div>
<div class="flex flex-col gap-1.5 max-h-32 overflow-y-auto pr-1 custom-scrollbar">
<div class="flex gap-2 text-[11px] bg-white/80 p-2 rounded border border-[#F7893F]/10 text-red-700/80">
<span class="font-bold shrink-0 bg-[#F7893F]/10 px-1.5 rounded text-error">行 12</span>
<span class="text-[#5E5E5E]">必須項目「日本語」が空欄です</span>
</div>
<div class="flex gap-2 text-[11px] bg-white/80 p-2 rounded border border-[#F7893F]/10 text-red-700/80">
<span class="font-bold shrink-0 bg-[#F7893F]/10 px-1.5 rounded text-error">行 34</span>
<span class="text-[#5E5E5E]">フォーマット不正: 列数が足りません</span>
</div>
</div>
</div>
<div class="flex-1 rounded-xl border border-gray-200 bg-white overflow-hidden flex flex-col min-h-[200px]">
<div class="px-3 py-2 bg-gray-50 border-b border-gray-100 flex items-center justify-between">
<span class="text-xs font-bold text-gray-500">データプレビュー (先頭5件)</span>
<span class="text-[10px] text-gray-400">※ - は空欄扱い</span>
</div>
<div class="overflow-x-auto">
<table class="w-full text-left text-xs whitespace-nowrap">
<thead class="bg-gray-50/50 text-gray-500 font-medium border-b border-gray-100">
<tr>
<th class="px-3 py-2 w-10">No.</th>
<th class="px-3 py-2 min-w-[80px]">日本語<span class="text-error">*</span></th>
<th class="px-3 py-2 min-w-[80px]">カタカナ</th>
<th class="px-3 py-2 min-w-[80px]">中国語</th>
<th class="px-3 py-2 min-w-[80px]">英語</th>
<th class="px-3 py-2 text-gray-400 font-normal">ステータス</th>
</tr>
</thead>
<tbody class="divide-y divide-gray-50 text-app-text">
<tr class="hover:bg-gray-50/50">
<td class="px-3 py-2 text-gray-400">1</td>
<td class="px-3 py-2 font-bold">りんご</td>
<td class="px-3 py-2 text-gray-500">リンゴ</td>
<td class="px-3 py-2">苹果</td>
<td class="px-3 py-2">Apple</td>
<td class="px-3 py-2"><span class="text-success text-[10px] border border-success/20 bg-success/5 px-1.5 py-0.5 rounded">OK</span></td>
</tr>
<tr class="hover:bg-gray-50/50">
<td class="px-3 py-2 text-gray-400">2</td>
<td class="px-3 py-2 font-bold">学校</td>
<td class="px-3 py-2 text-gray-500">ガッコウ</td>
<td class="px-3 py-2">学校</td>
<td class="px-3 py-2">School</td>
<td class="px-3 py-2"><span class="text-success text-[10px] border border-success/20 bg-success/5 px-1.5 py-0.5 rounded">OK</span></td>
</tr>
<tr class="hover:bg-gray-50/50">
<td class="px-3 py-2 text-gray-400">3</td>
<td class="px-3 py-2 font-bold">電車</td>
<td class="px-3 py-2 text-gray-500">デンシャ</td>
<td class="px-3 py-2">电车</td>
<td class="px-3 py-2">Train</td>
<td class="px-3 py-2"><span class="text-success text-[10px] border border-success/20 bg-success/5 px-1.5 py-0.5 rounded">OK</span></td>
</tr>
<tr class="hover:bg-gray-50/50 bg-[#F7893F]/5">
<td class="px-3 py-2 text-error font-bold">12</td>
<td class="px-3 py-2 text-gray-300">-</td>
<td class="px-3 py-2 text-gray-500">-</td>
<td class="px-3 py-2">书</td>
<td class="px-3 py-2">Book</td>
<td class="px-3 py-2"><span class="text-error text-[10px] font-bold">必須エラー</span></td>
</tr>
</tbody>
</table>
</div>
</div>
</section>
<section class="mt-2 mb-4">
<button class="w-full rounded-xl bg-primary h-12 flex items-center justify-center gap-2 text-white shadow-lg shadow-primary/20 active:scale-[0.98] transition-all hover:bg-primary/90 disabled:opacity-50 disabled:cursor-not-allowed disabled:shadow-none">
<span class="text-base font-bold">48件をインポート実行</span>
<span class="material-symbols-outlined" style="font-size: 20px;">arrow_forward</span>
</button>
<p class="text-[10px] text-center text-gray-400 mt-2">※ エラーのある行は自動的にスキップされます</p>
</section>
</main>
</div>

</body></html>
