# Gallery

Real-world XML documents rendered with [`unxml`](https://github.com/vivainio/unxml-rs), syntax-highlighted with the same grammar `unxml` ships for `bat`.

The **basics** below are shown inline — original source on the left, `unxml` output on the right. The **gallery** further down links full-page renders of larger real-world documents, with original-vs-rendered size comparisons.

<style>
.unxml-demo .ansi2html-content { display: inline; white-space: pre-wrap; word-wrap: break-word; }
.unxml-demo .body_foreground { color: #AAAAAA; }
.unxml-demo .body_background { background-color: #000000; }
.unxml-demo .inv_foreground { color: #000000; }
.unxml-demo .inv_background { background-color: #AAAAAA; }
.unxml-demo .ansi1 { font-weight: bold; }
.unxml-demo .ansi2 { font-weight: lighter; }
.unxml-demo .ansi3 { font-style: italic; }
.unxml-demo .ansi4 { text-decoration: underline; }
.unxml-demo .ansi5 { text-decoration: blink; }
.unxml-demo .ansi6 { text-decoration: blink; }
.unxml-demo .ansi8 { visibility: hidden; }
.unxml-demo .ansi9 { text-decoration: line-through; }
.unxml-demo .ansi30 { color: #000000; }
.unxml-demo .inv30 { background-color: #000000; }
.unxml-demo .ansi31 { color: #cd0000; }
.unxml-demo .inv31 { background-color: #cd0000; }
.unxml-demo .ansi32 { color: #00cd00; }
.unxml-demo .inv32 { background-color: #00cd00; }
.unxml-demo .ansi33 { color: #cdcd00; }
.unxml-demo .inv33 { background-color: #cdcd00; }
.unxml-demo .ansi34 { color: #0000ee; }
.unxml-demo .inv34 { background-color: #0000ee; }
.unxml-demo .ansi35 { color: #cd00cd; }
.unxml-demo .inv35 { background-color: #cd00cd; }
.unxml-demo .ansi36 { color: #00cdcd; }
.unxml-demo .inv36 { background-color: #00cdcd; }
.unxml-demo .ansi37 { color: #e5e5e5; }
.unxml-demo .inv37 { background-color: #e5e5e5; }
.unxml-demo .ansi40 { background-color: #000000; }
.unxml-demo .inv40 { color: #000000; }
.unxml-demo .ansi41 { background-color: #cd0000; }
.unxml-demo .inv41 { color: #cd0000; }
.unxml-demo .ansi42 { background-color: #00cd00; }
.unxml-demo .inv42 { color: #00cd00; }
.unxml-demo .ansi43 { background-color: #cdcd00; }
.unxml-demo .inv43 { color: #cdcd00; }
.unxml-demo .ansi44 { background-color: #0000ee; }
.unxml-demo .inv44 { color: #0000ee; }
.unxml-demo .ansi45 { background-color: #cd00cd; }
.unxml-demo .inv45 { color: #cd00cd; }
.unxml-demo .ansi46 { background-color: #00cdcd; }
.unxml-demo .inv46 { color: #00cdcd; }
.unxml-demo .ansi47 { background-color: #e5e5e5; }
.unxml-demo .inv47 { color: #e5e5e5; }
.unxml-demo .ansi90 { color: #7f7f7f; }
.unxml-demo .inv90 { background-color: #7f7f7f; }
.unxml-demo .ansi91 { color: #ff0000; }
.unxml-demo .inv91 { background-color: #ff0000; }
.unxml-demo .ansi92 { color: #00ff00; }
.unxml-demo .inv92 { background-color: #00ff00; }
.unxml-demo .ansi93 { color: #ffff00; }
.unxml-demo .inv93 { background-color: #ffff00; }
.unxml-demo .ansi94 { color: #5c5cff; }
.unxml-demo .inv94 { background-color: #5c5cff; }
.unxml-demo .ansi95 { color: #ff00ff; }
.unxml-demo .inv95 { background-color: #ff00ff; }
.unxml-demo .ansi96 { color: #00ffff; }
.unxml-demo .inv96 { background-color: #00ffff; }
.unxml-demo .ansi97 { color: #ffffff; }
.unxml-demo .inv97 { background-color: #ffffff; }
.unxml-demo .ansi100 { background-color: #7f7f7f; }
.unxml-demo .inv100 { color: #7f7f7f; }
.unxml-demo .ansi101 { background-color: #ff0000; }
.unxml-demo .inv101 { color: #ff0000; }
.unxml-demo .ansi102 { background-color: #00ff00; }
.unxml-demo .inv102 { color: #00ff00; }
.unxml-demo .ansi103 { background-color: #ffff00; }
.unxml-demo .inv103 { color: #ffff00; }
.unxml-demo .ansi104 { background-color: #5c5cff; }
.unxml-demo .inv104 { color: #5c5cff; }
.unxml-demo .ansi105 { background-color: #ff00ff; }
.unxml-demo .inv105 { color: #ff00ff; }
.unxml-demo .ansi106 { background-color: #00ffff; }
.unxml-demo .inv106 { color: #00ffff; }
.unxml-demo .ansi107 { background-color: #ffffff; }
.unxml-demo .inv107 { color: #ffffff; }
.unxml-demo .ansi38-0 { color: #000000; }
.unxml-demo .inv38-0 { background-color: #000000; }
.unxml-demo .ansi38-1 { color: #cd0000; }
.unxml-demo .inv38-1 { background-color: #cd0000; }
.unxml-demo .ansi38-2 { color: #00cd00; }
.unxml-demo .inv38-2 { background-color: #00cd00; }
.unxml-demo .ansi38-3 { color: #cdcd00; }
.unxml-demo .inv38-3 { background-color: #cdcd00; }
.unxml-demo .ansi38-4 { color: #0000ee; }
.unxml-demo .inv38-4 { background-color: #0000ee; }
.unxml-demo .ansi38-5 { color: #cd00cd; }
.unxml-demo .inv38-5 { background-color: #cd00cd; }
.unxml-demo .ansi38-6 { color: #00cdcd; }
.unxml-demo .inv38-6 { background-color: #00cdcd; }
.unxml-demo .ansi38-7 { color: #e5e5e5; }
.unxml-demo .inv38-7 { background-color: #e5e5e5; }
.unxml-demo .ansi38-8 { color: #7f7f7f; }
.unxml-demo .inv38-8 { background-color: #7f7f7f; }
.unxml-demo .ansi38-9 { color: #ff0000; }
.unxml-demo .inv38-9 { background-color: #ff0000; }
.unxml-demo .ansi38-10 { color: #00ff00; }
.unxml-demo .inv38-10 { background-color: #00ff00; }
.unxml-demo .ansi38-11 { color: #ffff00; }
.unxml-demo .inv38-11 { background-color: #ffff00; }
.unxml-demo .ansi38-12 { color: #5c5cff; }
.unxml-demo .inv38-12 { background-color: #5c5cff; }
.unxml-demo .ansi38-13 { color: #ff00ff; }
.unxml-demo .inv38-13 { background-color: #ff00ff; }
.unxml-demo .ansi38-14 { color: #00ffff; }
.unxml-demo .inv38-14 { background-color: #00ffff; }
.unxml-demo .ansi38-15 { color: #ffffff; }
.unxml-demo .inv38-15 { background-color: #ffffff; }
.unxml-demo .ansi48-0 { background-color: #000000; }
.unxml-demo .inv48-0 { color: #000000; }
.unxml-demo .ansi48-1 { background-color: #cd0000; }
.unxml-demo .inv48-1 { color: #cd0000; }
.unxml-demo .ansi48-2 { background-color: #00cd00; }
.unxml-demo .inv48-2 { color: #00cd00; }
.unxml-demo .ansi48-3 { background-color: #cdcd00; }
.unxml-demo .inv48-3 { color: #cdcd00; }
.unxml-demo .ansi48-4 { background-color: #0000ee; }
.unxml-demo .inv48-4 { color: #0000ee; }
.unxml-demo .ansi48-5 { background-color: #cd00cd; }
.unxml-demo .inv48-5 { color: #cd00cd; }
.unxml-demo .ansi48-6 { background-color: #00cdcd; }
.unxml-demo .inv48-6 { color: #00cdcd; }
.unxml-demo .ansi48-7 { background-color: #e5e5e5; }
.unxml-demo .inv48-7 { color: #e5e5e5; }
.unxml-demo .ansi48-8 { background-color: #7f7f7f; }
.unxml-demo .inv48-8 { color: #7f7f7f; }
.unxml-demo .ansi48-9 { background-color: #ff0000; }
.unxml-demo .inv48-9 { color: #ff0000; }
.unxml-demo .ansi48-10 { background-color: #00ff00; }
.unxml-demo .inv48-10 { color: #00ff00; }
.unxml-demo .ansi48-11 { background-color: #ffff00; }
.unxml-demo .inv48-11 { color: #ffff00; }
.unxml-demo .ansi48-12 { background-color: #5c5cff; }
.unxml-demo .inv48-12 { color: #5c5cff; }
.unxml-demo .ansi48-13 { background-color: #ff00ff; }
.unxml-demo .inv48-13 { color: #ff00ff; }
.unxml-demo .ansi48-14 { background-color: #00ffff; }
.unxml-demo .inv48-14 { color: #00ffff; }
.unxml-demo .ansi48-15 { background-color: #ffffff; }
.unxml-demo .inv48-15 { color: #ffffff; }
.unxml-demo .ansi38-16 { color: #000000; }
.unxml-demo .inv38-16 { background: #000000; }
.unxml-demo .ansi48-16 { background: #000000; }
.unxml-demo .inv48-16 { color: #000000; }
.unxml-demo .ansi38-17 { color: #00005f; }
.unxml-demo .inv38-17 { background: #00005f; }
.unxml-demo .ansi48-17 { background: #00005f; }
.unxml-demo .inv48-17 { color: #00005f; }
.unxml-demo .ansi38-18 { color: #000087; }
.unxml-demo .inv38-18 { background: #000087; }
.unxml-demo .ansi48-18 { background: #000087; }
.unxml-demo .inv48-18 { color: #000087; }
.unxml-demo .ansi38-19 { color: #0000af; }
.unxml-demo .inv38-19 { background: #0000af; }
.unxml-demo .ansi48-19 { background: #0000af; }
.unxml-demo .inv48-19 { color: #0000af; }
.unxml-demo .ansi38-20 { color: #0000d7; }
.unxml-demo .inv38-20 { background: #0000d7; }
.unxml-demo .ansi48-20 { background: #0000d7; }
.unxml-demo .inv48-20 { color: #0000d7; }
.unxml-demo .ansi38-21 { color: #0000ff; }
.unxml-demo .inv38-21 { background: #0000ff; }
.unxml-demo .ansi48-21 { background: #0000ff; }
.unxml-demo .inv48-21 { color: #0000ff; }
.unxml-demo .ansi38-52 { color: #5f0000; }
.unxml-demo .inv38-52 { background: #5f0000; }
.unxml-demo .ansi48-52 { background: #5f0000; }
.unxml-demo .inv48-52 { color: #5f0000; }
.unxml-demo .ansi38-53 { color: #5f005f; }
.unxml-demo .inv38-53 { background: #5f005f; }
.unxml-demo .ansi48-53 { background: #5f005f; }
.unxml-demo .inv48-53 { color: #5f005f; }
.unxml-demo .ansi38-54 { color: #5f0087; }
.unxml-demo .inv38-54 { background: #5f0087; }
.unxml-demo .ansi48-54 { background: #5f0087; }
.unxml-demo .inv48-54 { color: #5f0087; }
.unxml-demo .ansi38-55 { color: #5f00af; }
.unxml-demo .inv38-55 { background: #5f00af; }
.unxml-demo .ansi48-55 { background: #5f00af; }
.unxml-demo .inv48-55 { color: #5f00af; }
.unxml-demo .ansi38-56 { color: #5f00d7; }
.unxml-demo .inv38-56 { background: #5f00d7; }
.unxml-demo .ansi48-56 { background: #5f00d7; }
.unxml-demo .inv48-56 { color: #5f00d7; }
.unxml-demo .ansi38-57 { color: #5f00ff; }
.unxml-demo .inv38-57 { background: #5f00ff; }
.unxml-demo .ansi48-57 { background: #5f00ff; }
.unxml-demo .inv48-57 { color: #5f00ff; }
.unxml-demo .ansi38-88 { color: #870000; }
.unxml-demo .inv38-88 { background: #870000; }
.unxml-demo .ansi48-88 { background: #870000; }
.unxml-demo .inv48-88 { color: #870000; }
.unxml-demo .ansi38-89 { color: #87005f; }
.unxml-demo .inv38-89 { background: #87005f; }
.unxml-demo .ansi48-89 { background: #87005f; }
.unxml-demo .inv48-89 { color: #87005f; }
.unxml-demo .ansi38-90 { color: #870087; }
.unxml-demo .inv38-90 { background: #870087; }
.unxml-demo .ansi48-90 { background: #870087; }
.unxml-demo .inv48-90 { color: #870087; }
.unxml-demo .ansi38-91 { color: #8700af; }
.unxml-demo .inv38-91 { background: #8700af; }
.unxml-demo .ansi48-91 { background: #8700af; }
.unxml-demo .inv48-91 { color: #8700af; }
.unxml-demo .ansi38-92 { color: #8700d7; }
.unxml-demo .inv38-92 { background: #8700d7; }
.unxml-demo .ansi48-92 { background: #8700d7; }
.unxml-demo .inv48-92 { color: #8700d7; }
.unxml-demo .ansi38-93 { color: #8700ff; }
.unxml-demo .inv38-93 { background: #8700ff; }
.unxml-demo .ansi48-93 { background: #8700ff; }
.unxml-demo .inv48-93 { color: #8700ff; }
.unxml-demo .ansi38-124 { color: #af0000; }
.unxml-demo .inv38-124 { background: #af0000; }
.unxml-demo .ansi48-124 { background: #af0000; }
.unxml-demo .inv48-124 { color: #af0000; }
.unxml-demo .ansi38-125 { color: #af005f; }
.unxml-demo .inv38-125 { background: #af005f; }
.unxml-demo .ansi48-125 { background: #af005f; }
.unxml-demo .inv48-125 { color: #af005f; }
.unxml-demo .ansi38-126 { color: #af0087; }
.unxml-demo .inv38-126 { background: #af0087; }
.unxml-demo .ansi48-126 { background: #af0087; }
.unxml-demo .inv48-126 { color: #af0087; }
.unxml-demo .ansi38-127 { color: #af00af; }
.unxml-demo .inv38-127 { background: #af00af; }
.unxml-demo .ansi48-127 { background: #af00af; }
.unxml-demo .inv48-127 { color: #af00af; }
.unxml-demo .ansi38-128 { color: #af00d7; }
.unxml-demo .inv38-128 { background: #af00d7; }
.unxml-demo .ansi48-128 { background: #af00d7; }
.unxml-demo .inv48-128 { color: #af00d7; }
.unxml-demo .ansi38-129 { color: #af00ff; }
.unxml-demo .inv38-129 { background: #af00ff; }
.unxml-demo .ansi48-129 { background: #af00ff; }
.unxml-demo .inv48-129 { color: #af00ff; }
.unxml-demo .ansi38-160 { color: #d70000; }
.unxml-demo .inv38-160 { background: #d70000; }
.unxml-demo .ansi48-160 { background: #d70000; }
.unxml-demo .inv48-160 { color: #d70000; }
.unxml-demo .ansi38-161 { color: #d7005f; }
.unxml-demo .inv38-161 { background: #d7005f; }
.unxml-demo .ansi48-161 { background: #d7005f; }
.unxml-demo .inv48-161 { color: #d7005f; }
.unxml-demo .ansi38-162 { color: #d70087; }
.unxml-demo .inv38-162 { background: #d70087; }
.unxml-demo .ansi48-162 { background: #d70087; }
.unxml-demo .inv48-162 { color: #d70087; }
.unxml-demo .ansi38-163 { color: #d700af; }
.unxml-demo .inv38-163 { background: #d700af; }
.unxml-demo .ansi48-163 { background: #d700af; }
.unxml-demo .inv48-163 { color: #d700af; }
.unxml-demo .ansi38-164 { color: #d700d7; }
.unxml-demo .inv38-164 { background: #d700d7; }
.unxml-demo .ansi48-164 { background: #d700d7; }
.unxml-demo .inv48-164 { color: #d700d7; }
.unxml-demo .ansi38-165 { color: #d700ff; }
.unxml-demo .inv38-165 { background: #d700ff; }
.unxml-demo .ansi48-165 { background: #d700ff; }
.unxml-demo .inv48-165 { color: #d700ff; }
.unxml-demo .ansi38-196 { color: #ff0000; }
.unxml-demo .inv38-196 { background: #ff0000; }
.unxml-demo .ansi48-196 { background: #ff0000; }
.unxml-demo .inv48-196 { color: #ff0000; }
.unxml-demo .ansi38-197 { color: #ff005f; }
.unxml-demo .inv38-197 { background: #ff005f; }
.unxml-demo .ansi48-197 { background: #ff005f; }
.unxml-demo .inv48-197 { color: #ff005f; }
.unxml-demo .ansi38-198 { color: #ff0087; }
.unxml-demo .inv38-198 { background: #ff0087; }
.unxml-demo .ansi48-198 { background: #ff0087; }
.unxml-demo .inv48-198 { color: #ff0087; }
.unxml-demo .ansi38-199 { color: #ff00af; }
.unxml-demo .inv38-199 { background: #ff00af; }
.unxml-demo .ansi48-199 { background: #ff00af; }
.unxml-demo .inv48-199 { color: #ff00af; }
.unxml-demo .ansi38-200 { color: #ff00d7; }
.unxml-demo .inv38-200 { background: #ff00d7; }
.unxml-demo .ansi48-200 { background: #ff00d7; }
.unxml-demo .inv48-200 { color: #ff00d7; }
.unxml-demo .ansi38-201 { color: #ff00ff; }
.unxml-demo .inv38-201 { background: #ff00ff; }
.unxml-demo .ansi48-201 { background: #ff00ff; }
.unxml-demo .inv48-201 { color: #ff00ff; }
.unxml-demo .ansi38-22 { color: #005f00; }
.unxml-demo .inv38-22 { background: #005f00; }
.unxml-demo .ansi48-22 { background: #005f00; }
.unxml-demo .inv48-22 { color: #005f00; }
.unxml-demo .ansi38-23 { color: #005f5f; }
.unxml-demo .inv38-23 { background: #005f5f; }
.unxml-demo .ansi48-23 { background: #005f5f; }
.unxml-demo .inv48-23 { color: #005f5f; }
.unxml-demo .ansi38-24 { color: #005f87; }
.unxml-demo .inv38-24 { background: #005f87; }
.unxml-demo .ansi48-24 { background: #005f87; }
.unxml-demo .inv48-24 { color: #005f87; }
.unxml-demo .ansi38-25 { color: #005faf; }
.unxml-demo .inv38-25 { background: #005faf; }
.unxml-demo .ansi48-25 { background: #005faf; }
.unxml-demo .inv48-25 { color: #005faf; }
.unxml-demo .ansi38-26 { color: #005fd7; }
.unxml-demo .inv38-26 { background: #005fd7; }
.unxml-demo .ansi48-26 { background: #005fd7; }
.unxml-demo .inv48-26 { color: #005fd7; }
.unxml-demo .ansi38-27 { color: #005fff; }
.unxml-demo .inv38-27 { background: #005fff; }
.unxml-demo .ansi48-27 { background: #005fff; }
.unxml-demo .inv48-27 { color: #005fff; }
.unxml-demo .ansi38-58 { color: #5f5f00; }
.unxml-demo .inv38-58 { background: #5f5f00; }
.unxml-demo .ansi48-58 { background: #5f5f00; }
.unxml-demo .inv48-58 { color: #5f5f00; }
.unxml-demo .ansi38-59 { color: #5f5f5f; }
.unxml-demo .inv38-59 { background: #5f5f5f; }
.unxml-demo .ansi48-59 { background: #5f5f5f; }
.unxml-demo .inv48-59 { color: #5f5f5f; }
.unxml-demo .ansi38-60 { color: #5f5f87; }
.unxml-demo .inv38-60 { background: #5f5f87; }
.unxml-demo .ansi48-60 { background: #5f5f87; }
.unxml-demo .inv48-60 { color: #5f5f87; }
.unxml-demo .ansi38-61 { color: #5f5faf; }
.unxml-demo .inv38-61 { background: #5f5faf; }
.unxml-demo .ansi48-61 { background: #5f5faf; }
.unxml-demo .inv48-61 { color: #5f5faf; }
.unxml-demo .ansi38-62 { color: #5f5fd7; }
.unxml-demo .inv38-62 { background: #5f5fd7; }
.unxml-demo .ansi48-62 { background: #5f5fd7; }
.unxml-demo .inv48-62 { color: #5f5fd7; }
.unxml-demo .ansi38-63 { color: #5f5fff; }
.unxml-demo .inv38-63 { background: #5f5fff; }
.unxml-demo .ansi48-63 { background: #5f5fff; }
.unxml-demo .inv48-63 { color: #5f5fff; }
.unxml-demo .ansi38-94 { color: #875f00; }
.unxml-demo .inv38-94 { background: #875f00; }
.unxml-demo .ansi48-94 { background: #875f00; }
.unxml-demo .inv48-94 { color: #875f00; }
.unxml-demo .ansi38-95 { color: #875f5f; }
.unxml-demo .inv38-95 { background: #875f5f; }
.unxml-demo .ansi48-95 { background: #875f5f; }
.unxml-demo .inv48-95 { color: #875f5f; }
.unxml-demo .ansi38-96 { color: #875f87; }
.unxml-demo .inv38-96 { background: #875f87; }
.unxml-demo .ansi48-96 { background: #875f87; }
.unxml-demo .inv48-96 { color: #875f87; }
.unxml-demo .ansi38-97 { color: #875faf; }
.unxml-demo .inv38-97 { background: #875faf; }
.unxml-demo .ansi48-97 { background: #875faf; }
.unxml-demo .inv48-97 { color: #875faf; }
.unxml-demo .ansi38-98 { color: #875fd7; }
.unxml-demo .inv38-98 { background: #875fd7; }
.unxml-demo .ansi48-98 { background: #875fd7; }
.unxml-demo .inv48-98 { color: #875fd7; }
.unxml-demo .ansi38-99 { color: #875fff; }
.unxml-demo .inv38-99 { background: #875fff; }
.unxml-demo .ansi48-99 { background: #875fff; }
.unxml-demo .inv48-99 { color: #875fff; }
.unxml-demo .ansi38-130 { color: #af5f00; }
.unxml-demo .inv38-130 { background: #af5f00; }
.unxml-demo .ansi48-130 { background: #af5f00; }
.unxml-demo .inv48-130 { color: #af5f00; }
.unxml-demo .ansi38-131 { color: #af5f5f; }
.unxml-demo .inv38-131 { background: #af5f5f; }
.unxml-demo .ansi48-131 { background: #af5f5f; }
.unxml-demo .inv48-131 { color: #af5f5f; }
.unxml-demo .ansi38-132 { color: #af5f87; }
.unxml-demo .inv38-132 { background: #af5f87; }
.unxml-demo .ansi48-132 { background: #af5f87; }
.unxml-demo .inv48-132 { color: #af5f87; }
.unxml-demo .ansi38-133 { color: #af5faf; }
.unxml-demo .inv38-133 { background: #af5faf; }
.unxml-demo .ansi48-133 { background: #af5faf; }
.unxml-demo .inv48-133 { color: #af5faf; }
.unxml-demo .ansi38-134 { color: #af5fd7; }
.unxml-demo .inv38-134 { background: #af5fd7; }
.unxml-demo .ansi48-134 { background: #af5fd7; }
.unxml-demo .inv48-134 { color: #af5fd7; }
.unxml-demo .ansi38-135 { color: #af5fff; }
.unxml-demo .inv38-135 { background: #af5fff; }
.unxml-demo .ansi48-135 { background: #af5fff; }
.unxml-demo .inv48-135 { color: #af5fff; }
.unxml-demo .ansi38-166 { color: #d75f00; }
.unxml-demo .inv38-166 { background: #d75f00; }
.unxml-demo .ansi48-166 { background: #d75f00; }
.unxml-demo .inv48-166 { color: #d75f00; }
.unxml-demo .ansi38-167 { color: #d75f5f; }
.unxml-demo .inv38-167 { background: #d75f5f; }
.unxml-demo .ansi48-167 { background: #d75f5f; }
.unxml-demo .inv48-167 { color: #d75f5f; }
.unxml-demo .ansi38-168 { color: #d75f87; }
.unxml-demo .inv38-168 { background: #d75f87; }
.unxml-demo .ansi48-168 { background: #d75f87; }
.unxml-demo .inv48-168 { color: #d75f87; }
.unxml-demo .ansi38-169 { color: #d75faf; }
.unxml-demo .inv38-169 { background: #d75faf; }
.unxml-demo .ansi48-169 { background: #d75faf; }
.unxml-demo .inv48-169 { color: #d75faf; }
.unxml-demo .ansi38-170 { color: #d75fd7; }
.unxml-demo .inv38-170 { background: #d75fd7; }
.unxml-demo .ansi48-170 { background: #d75fd7; }
.unxml-demo .inv48-170 { color: #d75fd7; }
.unxml-demo .ansi38-171 { color: #d75fff; }
.unxml-demo .inv38-171 { background: #d75fff; }
.unxml-demo .ansi48-171 { background: #d75fff; }
.unxml-demo .inv48-171 { color: #d75fff; }
.unxml-demo .ansi38-202 { color: #ff5f00; }
.unxml-demo .inv38-202 { background: #ff5f00; }
.unxml-demo .ansi48-202 { background: #ff5f00; }
.unxml-demo .inv48-202 { color: #ff5f00; }
.unxml-demo .ansi38-203 { color: #ff5f5f; }
.unxml-demo .inv38-203 { background: #ff5f5f; }
.unxml-demo .ansi48-203 { background: #ff5f5f; }
.unxml-demo .inv48-203 { color: #ff5f5f; }
.unxml-demo .ansi38-204 { color: #ff5f87; }
.unxml-demo .inv38-204 { background: #ff5f87; }
.unxml-demo .ansi48-204 { background: #ff5f87; }
.unxml-demo .inv48-204 { color: #ff5f87; }
.unxml-demo .ansi38-205 { color: #ff5faf; }
.unxml-demo .inv38-205 { background: #ff5faf; }
.unxml-demo .ansi48-205 { background: #ff5faf; }
.unxml-demo .inv48-205 { color: #ff5faf; }
.unxml-demo .ansi38-206 { color: #ff5fd7; }
.unxml-demo .inv38-206 { background: #ff5fd7; }
.unxml-demo .ansi48-206 { background: #ff5fd7; }
.unxml-demo .inv48-206 { color: #ff5fd7; }
.unxml-demo .ansi38-207 { color: #ff5fff; }
.unxml-demo .inv38-207 { background: #ff5fff; }
.unxml-demo .ansi48-207 { background: #ff5fff; }
.unxml-demo .inv48-207 { color: #ff5fff; }
.unxml-demo .ansi38-28 { color: #008700; }
.unxml-demo .inv38-28 { background: #008700; }
.unxml-demo .ansi48-28 { background: #008700; }
.unxml-demo .inv48-28 { color: #008700; }
.unxml-demo .ansi38-29 { color: #00875f; }
.unxml-demo .inv38-29 { background: #00875f; }
.unxml-demo .ansi48-29 { background: #00875f; }
.unxml-demo .inv48-29 { color: #00875f; }
.unxml-demo .ansi38-30 { color: #008787; }
.unxml-demo .inv38-30 { background: #008787; }
.unxml-demo .ansi48-30 { background: #008787; }
.unxml-demo .inv48-30 { color: #008787; }
.unxml-demo .ansi38-31 { color: #0087af; }
.unxml-demo .inv38-31 { background: #0087af; }
.unxml-demo .ansi48-31 { background: #0087af; }
.unxml-demo .inv48-31 { color: #0087af; }
.unxml-demo .ansi38-32 { color: #0087d7; }
.unxml-demo .inv38-32 { background: #0087d7; }
.unxml-demo .ansi48-32 { background: #0087d7; }
.unxml-demo .inv48-32 { color: #0087d7; }
.unxml-demo .ansi38-33 { color: #0087ff; }
.unxml-demo .inv38-33 { background: #0087ff; }
.unxml-demo .ansi48-33 { background: #0087ff; }
.unxml-demo .inv48-33 { color: #0087ff; }
.unxml-demo .ansi38-64 { color: #5f8700; }
.unxml-demo .inv38-64 { background: #5f8700; }
.unxml-demo .ansi48-64 { background: #5f8700; }
.unxml-demo .inv48-64 { color: #5f8700; }
.unxml-demo .ansi38-65 { color: #5f875f; }
.unxml-demo .inv38-65 { background: #5f875f; }
.unxml-demo .ansi48-65 { background: #5f875f; }
.unxml-demo .inv48-65 { color: #5f875f; }
.unxml-demo .ansi38-66 { color: #5f8787; }
.unxml-demo .inv38-66 { background: #5f8787; }
.unxml-demo .ansi48-66 { background: #5f8787; }
.unxml-demo .inv48-66 { color: #5f8787; }
.unxml-demo .ansi38-67 { color: #5f87af; }
.unxml-demo .inv38-67 { background: #5f87af; }
.unxml-demo .ansi48-67 { background: #5f87af; }
.unxml-demo .inv48-67 { color: #5f87af; }
.unxml-demo .ansi38-68 { color: #5f87d7; }
.unxml-demo .inv38-68 { background: #5f87d7; }
.unxml-demo .ansi48-68 { background: #5f87d7; }
.unxml-demo .inv48-68 { color: #5f87d7; }
.unxml-demo .ansi38-69 { color: #5f87ff; }
.unxml-demo .inv38-69 { background: #5f87ff; }
.unxml-demo .ansi48-69 { background: #5f87ff; }
.unxml-demo .inv48-69 { color: #5f87ff; }
.unxml-demo .ansi38-100 { color: #878700; }
.unxml-demo .inv38-100 { background: #878700; }
.unxml-demo .ansi48-100 { background: #878700; }
.unxml-demo .inv48-100 { color: #878700; }
.unxml-demo .ansi38-101 { color: #87875f; }
.unxml-demo .inv38-101 { background: #87875f; }
.unxml-demo .ansi48-101 { background: #87875f; }
.unxml-demo .inv48-101 { color: #87875f; }
.unxml-demo .ansi38-102 { color: #878787; }
.unxml-demo .inv38-102 { background: #878787; }
.unxml-demo .ansi48-102 { background: #878787; }
.unxml-demo .inv48-102 { color: #878787; }
.unxml-demo .ansi38-103 { color: #8787af; }
.unxml-demo .inv38-103 { background: #8787af; }
.unxml-demo .ansi48-103 { background: #8787af; }
.unxml-demo .inv48-103 { color: #8787af; }
.unxml-demo .ansi38-104 { color: #8787d7; }
.unxml-demo .inv38-104 { background: #8787d7; }
.unxml-demo .ansi48-104 { background: #8787d7; }
.unxml-demo .inv48-104 { color: #8787d7; }
.unxml-demo .ansi38-105 { color: #8787ff; }
.unxml-demo .inv38-105 { background: #8787ff; }
.unxml-demo .ansi48-105 { background: #8787ff; }
.unxml-demo .inv48-105 { color: #8787ff; }
.unxml-demo .ansi38-136 { color: #af8700; }
.unxml-demo .inv38-136 { background: #af8700; }
.unxml-demo .ansi48-136 { background: #af8700; }
.unxml-demo .inv48-136 { color: #af8700; }
.unxml-demo .ansi38-137 { color: #af875f; }
.unxml-demo .inv38-137 { background: #af875f; }
.unxml-demo .ansi48-137 { background: #af875f; }
.unxml-demo .inv48-137 { color: #af875f; }
.unxml-demo .ansi38-138 { color: #af8787; }
.unxml-demo .inv38-138 { background: #af8787; }
.unxml-demo .ansi48-138 { background: #af8787; }
.unxml-demo .inv48-138 { color: #af8787; }
.unxml-demo .ansi38-139 { color: #af87af; }
.unxml-demo .inv38-139 { background: #af87af; }
.unxml-demo .ansi48-139 { background: #af87af; }
.unxml-demo .inv48-139 { color: #af87af; }
.unxml-demo .ansi38-140 { color: #af87d7; }
.unxml-demo .inv38-140 { background: #af87d7; }
.unxml-demo .ansi48-140 { background: #af87d7; }
.unxml-demo .inv48-140 { color: #af87d7; }
.unxml-demo .ansi38-141 { color: #af87ff; }
.unxml-demo .inv38-141 { background: #af87ff; }
.unxml-demo .ansi48-141 { background: #af87ff; }
.unxml-demo .inv48-141 { color: #af87ff; }
.unxml-demo .ansi38-172 { color: #d78700; }
.unxml-demo .inv38-172 { background: #d78700; }
.unxml-demo .ansi48-172 { background: #d78700; }
.unxml-demo .inv48-172 { color: #d78700; }
.unxml-demo .ansi38-173 { color: #d7875f; }
.unxml-demo .inv38-173 { background: #d7875f; }
.unxml-demo .ansi48-173 { background: #d7875f; }
.unxml-demo .inv48-173 { color: #d7875f; }
.unxml-demo .ansi38-174 { color: #d78787; }
.unxml-demo .inv38-174 { background: #d78787; }
.unxml-demo .ansi48-174 { background: #d78787; }
.unxml-demo .inv48-174 { color: #d78787; }
.unxml-demo .ansi38-175 { color: #d787af; }
.unxml-demo .inv38-175 { background: #d787af; }
.unxml-demo .ansi48-175 { background: #d787af; }
.unxml-demo .inv48-175 { color: #d787af; }
.unxml-demo .ansi38-176 { color: #d787d7; }
.unxml-demo .inv38-176 { background: #d787d7; }
.unxml-demo .ansi48-176 { background: #d787d7; }
.unxml-demo .inv48-176 { color: #d787d7; }
.unxml-demo .ansi38-177 { color: #d787ff; }
.unxml-demo .inv38-177 { background: #d787ff; }
.unxml-demo .ansi48-177 { background: #d787ff; }
.unxml-demo .inv48-177 { color: #d787ff; }
.unxml-demo .ansi38-208 { color: #ff8700; }
.unxml-demo .inv38-208 { background: #ff8700; }
.unxml-demo .ansi48-208 { background: #ff8700; }
.unxml-demo .inv48-208 { color: #ff8700; }
.unxml-demo .ansi38-209 { color: #ff875f; }
.unxml-demo .inv38-209 { background: #ff875f; }
.unxml-demo .ansi48-209 { background: #ff875f; }
.unxml-demo .inv48-209 { color: #ff875f; }
.unxml-demo .ansi38-210 { color: #ff8787; }
.unxml-demo .inv38-210 { background: #ff8787; }
.unxml-demo .ansi48-210 { background: #ff8787; }
.unxml-demo .inv48-210 { color: #ff8787; }
.unxml-demo .ansi38-211 { color: #ff87af; }
.unxml-demo .inv38-211 { background: #ff87af; }
.unxml-demo .ansi48-211 { background: #ff87af; }
.unxml-demo .inv48-211 { color: #ff87af; }
.unxml-demo .ansi38-212 { color: #ff87d7; }
.unxml-demo .inv38-212 { background: #ff87d7; }
.unxml-demo .ansi48-212 { background: #ff87d7; }
.unxml-demo .inv48-212 { color: #ff87d7; }
.unxml-demo .ansi38-213 { color: #ff87ff; }
.unxml-demo .inv38-213 { background: #ff87ff; }
.unxml-demo .ansi48-213 { background: #ff87ff; }
.unxml-demo .inv48-213 { color: #ff87ff; }
.unxml-demo .ansi38-34 { color: #00af00; }
.unxml-demo .inv38-34 { background: #00af00; }
.unxml-demo .ansi48-34 { background: #00af00; }
.unxml-demo .inv48-34 { color: #00af00; }
.unxml-demo .ansi38-35 { color: #00af5f; }
.unxml-demo .inv38-35 { background: #00af5f; }
.unxml-demo .ansi48-35 { background: #00af5f; }
.unxml-demo .inv48-35 { color: #00af5f; }
.unxml-demo .ansi38-36 { color: #00af87; }
.unxml-demo .inv38-36 { background: #00af87; }
.unxml-demo .ansi48-36 { background: #00af87; }
.unxml-demo .inv48-36 { color: #00af87; }
.unxml-demo .ansi38-37 { color: #00afaf; }
.unxml-demo .inv38-37 { background: #00afaf; }
.unxml-demo .ansi48-37 { background: #00afaf; }
.unxml-demo .inv48-37 { color: #00afaf; }
.unxml-demo .ansi38-38 { color: #00afd7; }
.unxml-demo .inv38-38 { background: #00afd7; }
.unxml-demo .ansi48-38 { background: #00afd7; }
.unxml-demo .inv48-38 { color: #00afd7; }
.unxml-demo .ansi38-39 { color: #00afff; }
.unxml-demo .inv38-39 { background: #00afff; }
.unxml-demo .ansi48-39 { background: #00afff; }
.unxml-demo .inv48-39 { color: #00afff; }
.unxml-demo .ansi38-70 { color: #5faf00; }
.unxml-demo .inv38-70 { background: #5faf00; }
.unxml-demo .ansi48-70 { background: #5faf00; }
.unxml-demo .inv48-70 { color: #5faf00; }
.unxml-demo .ansi38-71 { color: #5faf5f; }
.unxml-demo .inv38-71 { background: #5faf5f; }
.unxml-demo .ansi48-71 { background: #5faf5f; }
.unxml-demo .inv48-71 { color: #5faf5f; }
.unxml-demo .ansi38-72 { color: #5faf87; }
.unxml-demo .inv38-72 { background: #5faf87; }
.unxml-demo .ansi48-72 { background: #5faf87; }
.unxml-demo .inv48-72 { color: #5faf87; }
.unxml-demo .ansi38-73 { color: #5fafaf; }
.unxml-demo .inv38-73 { background: #5fafaf; }
.unxml-demo .ansi48-73 { background: #5fafaf; }
.unxml-demo .inv48-73 { color: #5fafaf; }
.unxml-demo .ansi38-74 { color: #5fafd7; }
.unxml-demo .inv38-74 { background: #5fafd7; }
.unxml-demo .ansi48-74 { background: #5fafd7; }
.unxml-demo .inv48-74 { color: #5fafd7; }
.unxml-demo .ansi38-75 { color: #5fafff; }
.unxml-demo .inv38-75 { background: #5fafff; }
.unxml-demo .ansi48-75 { background: #5fafff; }
.unxml-demo .inv48-75 { color: #5fafff; }
.unxml-demo .ansi38-106 { color: #87af00; }
.unxml-demo .inv38-106 { background: #87af00; }
.unxml-demo .ansi48-106 { background: #87af00; }
.unxml-demo .inv48-106 { color: #87af00; }
.unxml-demo .ansi38-107 { color: #87af5f; }
.unxml-demo .inv38-107 { background: #87af5f; }
.unxml-demo .ansi48-107 { background: #87af5f; }
.unxml-demo .inv48-107 { color: #87af5f; }
.unxml-demo .ansi38-108 { color: #87af87; }
.unxml-demo .inv38-108 { background: #87af87; }
.unxml-demo .ansi48-108 { background: #87af87; }
.unxml-demo .inv48-108 { color: #87af87; }
.unxml-demo .ansi38-109 { color: #87afaf; }
.unxml-demo .inv38-109 { background: #87afaf; }
.unxml-demo .ansi48-109 { background: #87afaf; }
.unxml-demo .inv48-109 { color: #87afaf; }
.unxml-demo .ansi38-110 { color: #87afd7; }
.unxml-demo .inv38-110 { background: #87afd7; }
.unxml-demo .ansi48-110 { background: #87afd7; }
.unxml-demo .inv48-110 { color: #87afd7; }
.unxml-demo .ansi38-111 { color: #87afff; }
.unxml-demo .inv38-111 { background: #87afff; }
.unxml-demo .ansi48-111 { background: #87afff; }
.unxml-demo .inv48-111 { color: #87afff; }
.unxml-demo .ansi38-142 { color: #afaf00; }
.unxml-demo .inv38-142 { background: #afaf00; }
.unxml-demo .ansi48-142 { background: #afaf00; }
.unxml-demo .inv48-142 { color: #afaf00; }
.unxml-demo .ansi38-143 { color: #afaf5f; }
.unxml-demo .inv38-143 { background: #afaf5f; }
.unxml-demo .ansi48-143 { background: #afaf5f; }
.unxml-demo .inv48-143 { color: #afaf5f; }
.unxml-demo .ansi38-144 { color: #afaf87; }
.unxml-demo .inv38-144 { background: #afaf87; }
.unxml-demo .ansi48-144 { background: #afaf87; }
.unxml-demo .inv48-144 { color: #afaf87; }
.unxml-demo .ansi38-145 { color: #afafaf; }
.unxml-demo .inv38-145 { background: #afafaf; }
.unxml-demo .ansi48-145 { background: #afafaf; }
.unxml-demo .inv48-145 { color: #afafaf; }
.unxml-demo .ansi38-146 { color: #afafd7; }
.unxml-demo .inv38-146 { background: #afafd7; }
.unxml-demo .ansi48-146 { background: #afafd7; }
.unxml-demo .inv48-146 { color: #afafd7; }
.unxml-demo .ansi38-147 { color: #afafff; }
.unxml-demo .inv38-147 { background: #afafff; }
.unxml-demo .ansi48-147 { background: #afafff; }
.unxml-demo .inv48-147 { color: #afafff; }
.unxml-demo .ansi38-178 { color: #d7af00; }
.unxml-demo .inv38-178 { background: #d7af00; }
.unxml-demo .ansi48-178 { background: #d7af00; }
.unxml-demo .inv48-178 { color: #d7af00; }
.unxml-demo .ansi38-179 { color: #d7af5f; }
.unxml-demo .inv38-179 { background: #d7af5f; }
.unxml-demo .ansi48-179 { background: #d7af5f; }
.unxml-demo .inv48-179 { color: #d7af5f; }
.unxml-demo .ansi38-180 { color: #d7af87; }
.unxml-demo .inv38-180 { background: #d7af87; }
.unxml-demo .ansi48-180 { background: #d7af87; }
.unxml-demo .inv48-180 { color: #d7af87; }
.unxml-demo .ansi38-181 { color: #d7afaf; }
.unxml-demo .inv38-181 { background: #d7afaf; }
.unxml-demo .ansi48-181 { background: #d7afaf; }
.unxml-demo .inv48-181 { color: #d7afaf; }
.unxml-demo .ansi38-182 { color: #d7afd7; }
.unxml-demo .inv38-182 { background: #d7afd7; }
.unxml-demo .ansi48-182 { background: #d7afd7; }
.unxml-demo .inv48-182 { color: #d7afd7; }
.unxml-demo .ansi38-183 { color: #d7afff; }
.unxml-demo .inv38-183 { background: #d7afff; }
.unxml-demo .ansi48-183 { background: #d7afff; }
.unxml-demo .inv48-183 { color: #d7afff; }
.unxml-demo .ansi38-214 { color: #ffaf00; }
.unxml-demo .inv38-214 { background: #ffaf00; }
.unxml-demo .ansi48-214 { background: #ffaf00; }
.unxml-demo .inv48-214 { color: #ffaf00; }
.unxml-demo .ansi38-215 { color: #ffaf5f; }
.unxml-demo .inv38-215 { background: #ffaf5f; }
.unxml-demo .ansi48-215 { background: #ffaf5f; }
.unxml-demo .inv48-215 { color: #ffaf5f; }
.unxml-demo .ansi38-216 { color: #ffaf87; }
.unxml-demo .inv38-216 { background: #ffaf87; }
.unxml-demo .ansi48-216 { background: #ffaf87; }
.unxml-demo .inv48-216 { color: #ffaf87; }
.unxml-demo .ansi38-217 { color: #ffafaf; }
.unxml-demo .inv38-217 { background: #ffafaf; }
.unxml-demo .ansi48-217 { background: #ffafaf; }
.unxml-demo .inv48-217 { color: #ffafaf; }
.unxml-demo .ansi38-218 { color: #ffafd7; }
.unxml-demo .inv38-218 { background: #ffafd7; }
.unxml-demo .ansi48-218 { background: #ffafd7; }
.unxml-demo .inv48-218 { color: #ffafd7; }
.unxml-demo .ansi38-219 { color: #ffafff; }
.unxml-demo .inv38-219 { background: #ffafff; }
.unxml-demo .ansi48-219 { background: #ffafff; }
.unxml-demo .inv48-219 { color: #ffafff; }
.unxml-demo .ansi38-40 { color: #00d700; }
.unxml-demo .inv38-40 { background: #00d700; }
.unxml-demo .ansi48-40 { background: #00d700; }
.unxml-demo .inv48-40 { color: #00d700; }
.unxml-demo .ansi38-41 { color: #00d75f; }
.unxml-demo .inv38-41 { background: #00d75f; }
.unxml-demo .ansi48-41 { background: #00d75f; }
.unxml-demo .inv48-41 { color: #00d75f; }
.unxml-demo .ansi38-42 { color: #00d787; }
.unxml-demo .inv38-42 { background: #00d787; }
.unxml-demo .ansi48-42 { background: #00d787; }
.unxml-demo .inv48-42 { color: #00d787; }
.unxml-demo .ansi38-43 { color: #00d7af; }
.unxml-demo .inv38-43 { background: #00d7af; }
.unxml-demo .ansi48-43 { background: #00d7af; }
.unxml-demo .inv48-43 { color: #00d7af; }
.unxml-demo .ansi38-44 { color: #00d7d7; }
.unxml-demo .inv38-44 { background: #00d7d7; }
.unxml-demo .ansi48-44 { background: #00d7d7; }
.unxml-demo .inv48-44 { color: #00d7d7; }
.unxml-demo .ansi38-45 { color: #00d7ff; }
.unxml-demo .inv38-45 { background: #00d7ff; }
.unxml-demo .ansi48-45 { background: #00d7ff; }
.unxml-demo .inv48-45 { color: #00d7ff; }
.unxml-demo .ansi38-76 { color: #5fd700; }
.unxml-demo .inv38-76 { background: #5fd700; }
.unxml-demo .ansi48-76 { background: #5fd700; }
.unxml-demo .inv48-76 { color: #5fd700; }
.unxml-demo .ansi38-77 { color: #5fd75f; }
.unxml-demo .inv38-77 { background: #5fd75f; }
.unxml-demo .ansi48-77 { background: #5fd75f; }
.unxml-demo .inv48-77 { color: #5fd75f; }
.unxml-demo .ansi38-78 { color: #5fd787; }
.unxml-demo .inv38-78 { background: #5fd787; }
.unxml-demo .ansi48-78 { background: #5fd787; }
.unxml-demo .inv48-78 { color: #5fd787; }
.unxml-demo .ansi38-79 { color: #5fd7af; }
.unxml-demo .inv38-79 { background: #5fd7af; }
.unxml-demo .ansi48-79 { background: #5fd7af; }
.unxml-demo .inv48-79 { color: #5fd7af; }
.unxml-demo .ansi38-80 { color: #5fd7d7; }
.unxml-demo .inv38-80 { background: #5fd7d7; }
.unxml-demo .ansi48-80 { background: #5fd7d7; }
.unxml-demo .inv48-80 { color: #5fd7d7; }
.unxml-demo .ansi38-81 { color: #5fd7ff; }
.unxml-demo .inv38-81 { background: #5fd7ff; }
.unxml-demo .ansi48-81 { background: #5fd7ff; }
.unxml-demo .inv48-81 { color: #5fd7ff; }
.unxml-demo .ansi38-112 { color: #87d700; }
.unxml-demo .inv38-112 { background: #87d700; }
.unxml-demo .ansi48-112 { background: #87d700; }
.unxml-demo .inv48-112 { color: #87d700; }
.unxml-demo .ansi38-113 { color: #87d75f; }
.unxml-demo .inv38-113 { background: #87d75f; }
.unxml-demo .ansi48-113 { background: #87d75f; }
.unxml-demo .inv48-113 { color: #87d75f; }
.unxml-demo .ansi38-114 { color: #87d787; }
.unxml-demo .inv38-114 { background: #87d787; }
.unxml-demo .ansi48-114 { background: #87d787; }
.unxml-demo .inv48-114 { color: #87d787; }
.unxml-demo .ansi38-115 { color: #87d7af; }
.unxml-demo .inv38-115 { background: #87d7af; }
.unxml-demo .ansi48-115 { background: #87d7af; }
.unxml-demo .inv48-115 { color: #87d7af; }
.unxml-demo .ansi38-116 { color: #87d7d7; }
.unxml-demo .inv38-116 { background: #87d7d7; }
.unxml-demo .ansi48-116 { background: #87d7d7; }
.unxml-demo .inv48-116 { color: #87d7d7; }
.unxml-demo .ansi38-117 { color: #87d7ff; }
.unxml-demo .inv38-117 { background: #87d7ff; }
.unxml-demo .ansi48-117 { background: #87d7ff; }
.unxml-demo .inv48-117 { color: #87d7ff; }
.unxml-demo .ansi38-148 { color: #afd700; }
.unxml-demo .inv38-148 { background: #afd700; }
.unxml-demo .ansi48-148 { background: #afd700; }
.unxml-demo .inv48-148 { color: #afd700; }
.unxml-demo .ansi38-149 { color: #afd75f; }
.unxml-demo .inv38-149 { background: #afd75f; }
.unxml-demo .ansi48-149 { background: #afd75f; }
.unxml-demo .inv48-149 { color: #afd75f; }
.unxml-demo .ansi38-150 { color: #afd787; }
.unxml-demo .inv38-150 { background: #afd787; }
.unxml-demo .ansi48-150 { background: #afd787; }
.unxml-demo .inv48-150 { color: #afd787; }
.unxml-demo .ansi38-151 { color: #afd7af; }
.unxml-demo .inv38-151 { background: #afd7af; }
.unxml-demo .ansi48-151 { background: #afd7af; }
.unxml-demo .inv48-151 { color: #afd7af; }
.unxml-demo .ansi38-152 { color: #afd7d7; }
.unxml-demo .inv38-152 { background: #afd7d7; }
.unxml-demo .ansi48-152 { background: #afd7d7; }
.unxml-demo .inv48-152 { color: #afd7d7; }
.unxml-demo .ansi38-153 { color: #afd7ff; }
.unxml-demo .inv38-153 { background: #afd7ff; }
.unxml-demo .ansi48-153 { background: #afd7ff; }
.unxml-demo .inv48-153 { color: #afd7ff; }
.unxml-demo .ansi38-184 { color: #d7d700; }
.unxml-demo .inv38-184 { background: #d7d700; }
.unxml-demo .ansi48-184 { background: #d7d700; }
.unxml-demo .inv48-184 { color: #d7d700; }
.unxml-demo .ansi38-185 { color: #d7d75f; }
.unxml-demo .inv38-185 { background: #d7d75f; }
.unxml-demo .ansi48-185 { background: #d7d75f; }
.unxml-demo .inv48-185 { color: #d7d75f; }
.unxml-demo .ansi38-186 { color: #d7d787; }
.unxml-demo .inv38-186 { background: #d7d787; }
.unxml-demo .ansi48-186 { background: #d7d787; }
.unxml-demo .inv48-186 { color: #d7d787; }
.unxml-demo .ansi38-187 { color: #d7d7af; }
.unxml-demo .inv38-187 { background: #d7d7af; }
.unxml-demo .ansi48-187 { background: #d7d7af; }
.unxml-demo .inv48-187 { color: #d7d7af; }
.unxml-demo .ansi38-188 { color: #d7d7d7; }
.unxml-demo .inv38-188 { background: #d7d7d7; }
.unxml-demo .ansi48-188 { background: #d7d7d7; }
.unxml-demo .inv48-188 { color: #d7d7d7; }
.unxml-demo .ansi38-189 { color: #d7d7ff; }
.unxml-demo .inv38-189 { background: #d7d7ff; }
.unxml-demo .ansi48-189 { background: #d7d7ff; }
.unxml-demo .inv48-189 { color: #d7d7ff; }
.unxml-demo .ansi38-220 { color: #ffd700; }
.unxml-demo .inv38-220 { background: #ffd700; }
.unxml-demo .ansi48-220 { background: #ffd700; }
.unxml-demo .inv48-220 { color: #ffd700; }
.unxml-demo .ansi38-221 { color: #ffd75f; }
.unxml-demo .inv38-221 { background: #ffd75f; }
.unxml-demo .ansi48-221 { background: #ffd75f; }
.unxml-demo .inv48-221 { color: #ffd75f; }
.unxml-demo .ansi38-222 { color: #ffd787; }
.unxml-demo .inv38-222 { background: #ffd787; }
.unxml-demo .ansi48-222 { background: #ffd787; }
.unxml-demo .inv48-222 { color: #ffd787; }
.unxml-demo .ansi38-223 { color: #ffd7af; }
.unxml-demo .inv38-223 { background: #ffd7af; }
.unxml-demo .ansi48-223 { background: #ffd7af; }
.unxml-demo .inv48-223 { color: #ffd7af; }
.unxml-demo .ansi38-224 { color: #ffd7d7; }
.unxml-demo .inv38-224 { background: #ffd7d7; }
.unxml-demo .ansi48-224 { background: #ffd7d7; }
.unxml-demo .inv48-224 { color: #ffd7d7; }
.unxml-demo .ansi38-225 { color: #ffd7ff; }
.unxml-demo .inv38-225 { background: #ffd7ff; }
.unxml-demo .ansi48-225 { background: #ffd7ff; }
.unxml-demo .inv48-225 { color: #ffd7ff; }
.unxml-demo .ansi38-46 { color: #00ff00; }
.unxml-demo .inv38-46 { background: #00ff00; }
.unxml-demo .ansi48-46 { background: #00ff00; }
.unxml-demo .inv48-46 { color: #00ff00; }
.unxml-demo .ansi38-47 { color: #00ff5f; }
.unxml-demo .inv38-47 { background: #00ff5f; }
.unxml-demo .ansi48-47 { background: #00ff5f; }
.unxml-demo .inv48-47 { color: #00ff5f; }
.unxml-demo .ansi38-48 { color: #00ff87; }
.unxml-demo .inv38-48 { background: #00ff87; }
.unxml-demo .ansi48-48 { background: #00ff87; }
.unxml-demo .inv48-48 { color: #00ff87; }
.unxml-demo .ansi38-49 { color: #00ffaf; }
.unxml-demo .inv38-49 { background: #00ffaf; }
.unxml-demo .ansi48-49 { background: #00ffaf; }
.unxml-demo .inv48-49 { color: #00ffaf; }
.unxml-demo .ansi38-50 { color: #00ffd7; }
.unxml-demo .inv38-50 { background: #00ffd7; }
.unxml-demo .ansi48-50 { background: #00ffd7; }
.unxml-demo .inv48-50 { color: #00ffd7; }
.unxml-demo .ansi38-51 { color: #00ffff; }
.unxml-demo .inv38-51 { background: #00ffff; }
.unxml-demo .ansi48-51 { background: #00ffff; }
.unxml-demo .inv48-51 { color: #00ffff; }
.unxml-demo .ansi38-82 { color: #5fff00; }
.unxml-demo .inv38-82 { background: #5fff00; }
.unxml-demo .ansi48-82 { background: #5fff00; }
.unxml-demo .inv48-82 { color: #5fff00; }
.unxml-demo .ansi38-83 { color: #5fff5f; }
.unxml-demo .inv38-83 { background: #5fff5f; }
.unxml-demo .ansi48-83 { background: #5fff5f; }
.unxml-demo .inv48-83 { color: #5fff5f; }
.unxml-demo .ansi38-84 { color: #5fff87; }
.unxml-demo .inv38-84 { background: #5fff87; }
.unxml-demo .ansi48-84 { background: #5fff87; }
.unxml-demo .inv48-84 { color: #5fff87; }
.unxml-demo .ansi38-85 { color: #5fffaf; }
.unxml-demo .inv38-85 { background: #5fffaf; }
.unxml-demo .ansi48-85 { background: #5fffaf; }
.unxml-demo .inv48-85 { color: #5fffaf; }
.unxml-demo .ansi38-86 { color: #5fffd7; }
.unxml-demo .inv38-86 { background: #5fffd7; }
.unxml-demo .ansi48-86 { background: #5fffd7; }
.unxml-demo .inv48-86 { color: #5fffd7; }
.unxml-demo .ansi38-87 { color: #5fffff; }
.unxml-demo .inv38-87 { background: #5fffff; }
.unxml-demo .ansi48-87 { background: #5fffff; }
.unxml-demo .inv48-87 { color: #5fffff; }
.unxml-demo .ansi38-118 { color: #87ff00; }
.unxml-demo .inv38-118 { background: #87ff00; }
.unxml-demo .ansi48-118 { background: #87ff00; }
.unxml-demo .inv48-118 { color: #87ff00; }
.unxml-demo .ansi38-119 { color: #87ff5f; }
.unxml-demo .inv38-119 { background: #87ff5f; }
.unxml-demo .ansi48-119 { background: #87ff5f; }
.unxml-demo .inv48-119 { color: #87ff5f; }
.unxml-demo .ansi38-120 { color: #87ff87; }
.unxml-demo .inv38-120 { background: #87ff87; }
.unxml-demo .ansi48-120 { background: #87ff87; }
.unxml-demo .inv48-120 { color: #87ff87; }
.unxml-demo .ansi38-121 { color: #87ffaf; }
.unxml-demo .inv38-121 { background: #87ffaf; }
.unxml-demo .ansi48-121 { background: #87ffaf; }
.unxml-demo .inv48-121 { color: #87ffaf; }
.unxml-demo .ansi38-122 { color: #87ffd7; }
.unxml-demo .inv38-122 { background: #87ffd7; }
.unxml-demo .ansi48-122 { background: #87ffd7; }
.unxml-demo .inv48-122 { color: #87ffd7; }
.unxml-demo .ansi38-123 { color: #87ffff; }
.unxml-demo .inv38-123 { background: #87ffff; }
.unxml-demo .ansi48-123 { background: #87ffff; }
.unxml-demo .inv48-123 { color: #87ffff; }
.unxml-demo .ansi38-154 { color: #afff00; }
.unxml-demo .inv38-154 { background: #afff00; }
.unxml-demo .ansi48-154 { background: #afff00; }
.unxml-demo .inv48-154 { color: #afff00; }
.unxml-demo .ansi38-155 { color: #afff5f; }
.unxml-demo .inv38-155 { background: #afff5f; }
.unxml-demo .ansi48-155 { background: #afff5f; }
.unxml-demo .inv48-155 { color: #afff5f; }
.unxml-demo .ansi38-156 { color: #afff87; }
.unxml-demo .inv38-156 { background: #afff87; }
.unxml-demo .ansi48-156 { background: #afff87; }
.unxml-demo .inv48-156 { color: #afff87; }
.unxml-demo .ansi38-157 { color: #afffaf; }
.unxml-demo .inv38-157 { background: #afffaf; }
.unxml-demo .ansi48-157 { background: #afffaf; }
.unxml-demo .inv48-157 { color: #afffaf; }
.unxml-demo .ansi38-158 { color: #afffd7; }
.unxml-demo .inv38-158 { background: #afffd7; }
.unxml-demo .ansi48-158 { background: #afffd7; }
.unxml-demo .inv48-158 { color: #afffd7; }
.unxml-demo .ansi38-159 { color: #afffff; }
.unxml-demo .inv38-159 { background: #afffff; }
.unxml-demo .ansi48-159 { background: #afffff; }
.unxml-demo .inv48-159 { color: #afffff; }
.unxml-demo .ansi38-190 { color: #d7ff00; }
.unxml-demo .inv38-190 { background: #d7ff00; }
.unxml-demo .ansi48-190 { background: #d7ff00; }
.unxml-demo .inv48-190 { color: #d7ff00; }
.unxml-demo .ansi38-191 { color: #d7ff5f; }
.unxml-demo .inv38-191 { background: #d7ff5f; }
.unxml-demo .ansi48-191 { background: #d7ff5f; }
.unxml-demo .inv48-191 { color: #d7ff5f; }
.unxml-demo .ansi38-192 { color: #d7ff87; }
.unxml-demo .inv38-192 { background: #d7ff87; }
.unxml-demo .ansi48-192 { background: #d7ff87; }
.unxml-demo .inv48-192 { color: #d7ff87; }
.unxml-demo .ansi38-193 { color: #d7ffaf; }
.unxml-demo .inv38-193 { background: #d7ffaf; }
.unxml-demo .ansi48-193 { background: #d7ffaf; }
.unxml-demo .inv48-193 { color: #d7ffaf; }
.unxml-demo .ansi38-194 { color: #d7ffd7; }
.unxml-demo .inv38-194 { background: #d7ffd7; }
.unxml-demo .ansi48-194 { background: #d7ffd7; }
.unxml-demo .inv48-194 { color: #d7ffd7; }
.unxml-demo .ansi38-195 { color: #d7ffff; }
.unxml-demo .inv38-195 { background: #d7ffff; }
.unxml-demo .ansi48-195 { background: #d7ffff; }
.unxml-demo .inv48-195 { color: #d7ffff; }
.unxml-demo .ansi38-226 { color: #ffff00; }
.unxml-demo .inv38-226 { background: #ffff00; }
.unxml-demo .ansi48-226 { background: #ffff00; }
.unxml-demo .inv48-226 { color: #ffff00; }
.unxml-demo .ansi38-227 { color: #ffff5f; }
.unxml-demo .inv38-227 { background: #ffff5f; }
.unxml-demo .ansi48-227 { background: #ffff5f; }
.unxml-demo .inv48-227 { color: #ffff5f; }
.unxml-demo .ansi38-228 { color: #ffff87; }
.unxml-demo .inv38-228 { background: #ffff87; }
.unxml-demo .ansi48-228 { background: #ffff87; }
.unxml-demo .inv48-228 { color: #ffff87; }
.unxml-demo .ansi38-229 { color: #ffffaf; }
.unxml-demo .inv38-229 { background: #ffffaf; }
.unxml-demo .ansi48-229 { background: #ffffaf; }
.unxml-demo .inv48-229 { color: #ffffaf; }
.unxml-demo .ansi38-230 { color: #ffffd7; }
.unxml-demo .inv38-230 { background: #ffffd7; }
.unxml-demo .ansi48-230 { background: #ffffd7; }
.unxml-demo .inv48-230 { color: #ffffd7; }
.unxml-demo .ansi38-231 { color: #ffffff; }
.unxml-demo .inv38-231 { background: #ffffff; }
.unxml-demo .ansi48-231 { background: #ffffff; }
.unxml-demo .inv48-231 { color: #ffffff; }
.unxml-demo .ansi38-232 { color: #080808; }
.unxml-demo .inv38-232 { background: #080808; }
.unxml-demo .ansi48-232 { background: #080808; }
.unxml-demo .inv48-232 { color: #080808; }
.unxml-demo .ansi38-233 { color: #121212; }
.unxml-demo .inv38-233 { background: #121212; }
.unxml-demo .ansi48-233 { background: #121212; }
.unxml-demo .inv48-233 { color: #121212; }
.unxml-demo .ansi38-234 { color: #1c1c1c; }
.unxml-demo .inv38-234 { background: #1c1c1c; }
.unxml-demo .ansi48-234 { background: #1c1c1c; }
.unxml-demo .inv48-234 { color: #1c1c1c; }
.unxml-demo .ansi38-235 { color: #262626; }
.unxml-demo .inv38-235 { background: #262626; }
.unxml-demo .ansi48-235 { background: #262626; }
.unxml-demo .inv48-235 { color: #262626; }
.unxml-demo .ansi38-236 { color: #303030; }
.unxml-demo .inv38-236 { background: #303030; }
.unxml-demo .ansi48-236 { background: #303030; }
.unxml-demo .inv48-236 { color: #303030; }
.unxml-demo .ansi38-237 { color: #3a3a3a; }
.unxml-demo .inv38-237 { background: #3a3a3a; }
.unxml-demo .ansi48-237 { background: #3a3a3a; }
.unxml-demo .inv48-237 { color: #3a3a3a; }
.unxml-demo .ansi38-238 { color: #444444; }
.unxml-demo .inv38-238 { background: #444444; }
.unxml-demo .ansi48-238 { background: #444444; }
.unxml-demo .inv48-238 { color: #444444; }
.unxml-demo .ansi38-239 { color: #4e4e4e; }
.unxml-demo .inv38-239 { background: #4e4e4e; }
.unxml-demo .ansi48-239 { background: #4e4e4e; }
.unxml-demo .inv48-239 { color: #4e4e4e; }
.unxml-demo .ansi38-240 { color: #585858; }
.unxml-demo .inv38-240 { background: #585858; }
.unxml-demo .ansi48-240 { background: #585858; }
.unxml-demo .inv48-240 { color: #585858; }
.unxml-demo .ansi38-241 { color: #626262; }
.unxml-demo .inv38-241 { background: #626262; }
.unxml-demo .ansi48-241 { background: #626262; }
.unxml-demo .inv48-241 { color: #626262; }
.unxml-demo .ansi38-242 { color: #6c6c6c; }
.unxml-demo .inv38-242 { background: #6c6c6c; }
.unxml-demo .ansi48-242 { background: #6c6c6c; }
.unxml-demo .inv48-242 { color: #6c6c6c; }
.unxml-demo .ansi38-243 { color: #767676; }
.unxml-demo .inv38-243 { background: #767676; }
.unxml-demo .ansi48-243 { background: #767676; }
.unxml-demo .inv48-243 { color: #767676; }
.unxml-demo .ansi38-244 { color: #808080; }
.unxml-demo .inv38-244 { background: #808080; }
.unxml-demo .ansi48-244 { background: #808080; }
.unxml-demo .inv48-244 { color: #808080; }
.unxml-demo .ansi38-245 { color: #8a8a8a; }
.unxml-demo .inv38-245 { background: #8a8a8a; }
.unxml-demo .ansi48-245 { background: #8a8a8a; }
.unxml-demo .inv48-245 { color: #8a8a8a; }
.unxml-demo .ansi38-246 { color: #949494; }
.unxml-demo .inv38-246 { background: #949494; }
.unxml-demo .ansi48-246 { background: #949494; }
.unxml-demo .inv48-246 { color: #949494; }
.unxml-demo .ansi38-247 { color: #9e9e9e; }
.unxml-demo .inv38-247 { background: #9e9e9e; }
.unxml-demo .ansi48-247 { background: #9e9e9e; }
.unxml-demo .inv48-247 { color: #9e9e9e; }
.unxml-demo .ansi38-248 { color: #a8a8a8; }
.unxml-demo .inv38-248 { background: #a8a8a8; }
.unxml-demo .ansi48-248 { background: #a8a8a8; }
.unxml-demo .inv48-248 { color: #a8a8a8; }
.unxml-demo .ansi38-249 { color: #b2b2b2; }
.unxml-demo .inv38-249 { background: #b2b2b2; }
.unxml-demo .ansi48-249 { background: #b2b2b2; }
.unxml-demo .inv48-249 { color: #b2b2b2; }
.unxml-demo .ansi38-250 { color: #bcbcbc; }
.unxml-demo .inv38-250 { background: #bcbcbc; }
.unxml-demo .ansi48-250 { background: #bcbcbc; }
.unxml-demo .inv48-250 { color: #bcbcbc; }
.unxml-demo .ansi38-251 { color: #c6c6c6; }
.unxml-demo .inv38-251 { background: #c6c6c6; }
.unxml-demo .ansi48-251 { background: #c6c6c6; }
.unxml-demo .inv48-251 { color: #c6c6c6; }
.unxml-demo .ansi38-252 { color: #d0d0d0; }
.unxml-demo .inv38-252 { background: #d0d0d0; }
.unxml-demo .ansi48-252 { background: #d0d0d0; }
.unxml-demo .inv48-252 { color: #d0d0d0; }
.unxml-demo .ansi38-253 { color: #dadada; }
.unxml-demo .inv38-253 { background: #dadada; }
.unxml-demo .ansi48-253 { background: #dadada; }
.unxml-demo .inv48-253 { color: #dadada; }
.unxml-demo .ansi38-254 { color: #e4e4e4; }
.unxml-demo .inv38-254 { background: #e4e4e4; }
.unxml-demo .ansi48-254 { background: #e4e4e4; }
.unxml-demo .inv48-254 { color: #e4e4e4; }
.unxml-demo .ansi38-255 { color: #eeeeee; }
.unxml-demo .inv38-255 { background: #eeeeee; }
.unxml-demo .ansi48-255 { background: #eeeeee; }
.unxml-demo .inv48-255 { color: #eeeeee; }
.unxml-demo .ansi38-249038114 { color: #F92672; }
.unxml-demo .ansi38-248248242 { color: #F8F8F2; }
.unxml-demo .ansi38-166226046 { color: #A6E22E; }
.unxml-demo .ansi38-230219116 { color: #E6DB74; }
.unxml-demo .ansi38-102217239 { color: #66D9EF; }
.unxml-demo .ansi38-190132255 { color: #BE84FF; }
.unxml-demo .ansi38-253151031 { color: #FD971F; }
.unxml-demo .ansi38-117113094 { color: #75715E; }
.unxml-demo .ansi38-255255255 { color: #FFFFFF; }
.unxml-demo { margin: 1rem 0 0; }
.unxml-demo .unxml-sample { margin: 0 0 1.75rem; }
.unxml-demo h3 { margin: 0 0 .15rem; }
.unxml-demo .unxml-cap { margin: 0 0 .5rem; font-size: .8em; color: #8b949e; }
.unxml-demo .unxml-cap a { color: inherit; text-decoration: underline; }
.unxml-demo .unxml-cols {
  display: grid; grid-template-columns: 1fr 1fr; gap: .75rem; align-items: start;
}
.unxml-demo .unxml-col { min-width: 0; }
.unxml-demo .unxml-col-label {
  font: 12px/1.4 ui-monospace, monospace; color: #8b949e; margin: 0 0 .25rem;
}
.unxml-demo pre.unxml {
  margin: 0; padding: .9rem 1rem; border-radius: 6px;
  background: #0d1117; color: #c9d1d9;
  font: 12px/1.5 ui-monospace, "SF Mono", SFMono-Regular, Menlo, Consolas, monospace;
  white-space: pre; tab-size: 2; overflow-x: auto; max-width: 100%;
}
@media (max-width: 820px) {
  .unxml-demo .unxml-cols { grid-template-columns: 1fr; }
}
</style>

## Invoice basics

<div class="unxml-demo">
<div class="unxml-sample">
<h3>CII / Factur-X — minimal invoice</h3>
<p class="unxml-cap"><a href="https://github.com/vivainio/unxml-demos/blob/main/examples/cii/factur-x-basic.xml">factur-x-basic.xml</a> · 130 → 95 lines</p>
<div class="unxml-cols">
<div class="unxml-col"><div class="unxml-col-label">XML source</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-255255255">&lt;?</span><span class="ansi38-249038114">xml</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">encoding</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">UTF-8</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-255255255">?&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CrossIndustryInvoice</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">rsm</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">urn:un:unece:uncefact:data:standard:CrossIndustryInvoice:100</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">xsi</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/2001/XMLSchema-instance</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">ram</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">urn:un:unece:uncefact:data:standard:ReusableAggregateBusinessInformationEntity:100</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">udt</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">urn:un:unece:uncefact:data:standard:UnqualifiedDataType:100</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">qdt</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">urn:un:unece:uncefact:data:standard:QualifiedDataType:100</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-117113094">&lt;!--</span><span class="ansi38-117113094"> generated by: mustangproject.org vnull</span><span class="ansi38-117113094">--&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ExchangedDocumentContext</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GuidelineSpecifiedDocumentContextParameter</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">urn:cen.eu:en16931:2017#compliant#urn:factur-x.eu:1p0:basic</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GuidelineSpecifiedDocumentContextParameter</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ExchangedDocumentContext</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ExchangedDocument</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">471102</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">380</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IssueDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">format</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">20241115</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IssueDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Rechnung gemäß Bestellung vom 01.11.2024.</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Lieferant GmbH</span>
<span class="ansi38-248248242">                Lieferantenstraße 20</span>
<span class="ansi38-248248242">                80333 München</span>
<span class="ansi38-248248242">                Deutschland</span>
<span class="ansi38-248248242">                Geschäftsführer: Hans Muster</span>
<span class="ansi38-248248242">                Handelsregisternummer: H A 123</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Unsere GLN: 4000001123452</span>
<span class="ansi38-248248242">                Ihre GLN: 4000001987658</span>
<span class="ansi38-248248242">                Ihre Kundennummer: GE2020211</span>
<span class="ansi38-248248242">                Zahlbar innerhalb 30 Tagen netto bis 25.12.2024, 3% Skonto innerhalb 10 Tagen bis 25.11.2024.</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Content</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedNote</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ExchangedDocument</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SupplyChainTradeTransaction</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedSupplyChainTradeLineItem</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">AssociatedDocumentLineDocument</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineID</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">1</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">AssociatedDocumentLineDocument</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeProduct</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GlobalID</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">schemeID</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">0160</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">4012345001235</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GlobalID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">GTIN: 4012345001235</span>
<span class="ansi38-248248242">                    Unsere Art.-Nr.: TB100A4</span>
<span class="ansi38-248248242">                    Trennblätter A4</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeProduct</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeAgreement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">NetPriceProductTradePrice</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ChargeAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">9.9000</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ChargeAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BasisQuantity</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">unitCode</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">H87</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">1.0000</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BasisQuantity</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">NetPriceProductTradePrice</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeAgreement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeDelivery</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BilledQuantity</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">unitCode</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">H87</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">20.0000</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BilledQuantity</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeDelivery</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeSettlement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableTradeTax</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">VAT</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">S</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">19.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableTradeTax</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeSettlementLineMonetarySummation</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">198.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeSettlementLineMonetarySummation</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedLineTradeSettlement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">IncludedSupplyChainTradeLineItem</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeAgreement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SellerTradeParty</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Lieferant GmbH</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostalTradeAddress</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">80333</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineOne</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Lieferantenstraße 20</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineOne</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CityName</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">München</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CityName</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CountryID</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">DE</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CountryID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostalTradeAddress</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTaxRegistration</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">schemeID</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">VA</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">DE123456789</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTaxRegistration</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTaxRegistration</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">schemeID</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">FC</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">201/113/40209</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTaxRegistration</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SellerTradeParty</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BuyerTradeParty</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Kunden AG Mitte</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Name</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostalTradeAddress</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">69876</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineOne</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Hans Muster</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineOne</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTwo</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Kundenstraße 15</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTwo</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CityName</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Frankfurt</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CityName</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CountryID</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">DE</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CountryID</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">PostalTradeAddress</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BuyerTradeParty</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeAgreement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeDelivery</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ActualDeliverySupplyChainEvent</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">OccurrenceDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">format</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">20241114</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">OccurrenceDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ActualDeliverySupplyChainEvent</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeDelivery</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeSettlement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">InvoiceCurrencyCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">EUR</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">InvoiceCurrencyCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableTradeTax</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CalculatedAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">37.62</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CalculatedAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">VAT</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BasisAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">198.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">BasisAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">S</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">19.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableTradeTax</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradePaymentTerms</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Description</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Zahlbar innerhalb 30 Tagen netto bis 25.12.2024, 3% Skonto innerhalb 10 Tagen bis 25.11.2024.</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">Description</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DueDateDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">format</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">20241215</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">udt</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DueDateDateTime</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradePaymentTerms</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeSettlementHeaderMonetarySummation</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">198.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ChargeTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">0.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ChargeTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">AllowanceTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">0.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">AllowanceTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TaxBasisTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">198.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TaxBasisTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TaxTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">currencyID</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">EUR</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">37.62</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TaxTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GrandTotalAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">235.62</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">GrandTotalAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TotalPrepaidAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">0.00</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">TotalPrepaidAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">                </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DuePayableAmount</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">235.62</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">DuePayableAmount</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">            </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SpecifiedTradeSettlementHeaderMonetarySummation</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">ram</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">ApplicableHeaderTradeSettlement</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">SupplyChainTradeTransaction</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">rsm</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">CrossIndustryInvoice</span><span class="ansi38-255255255">&gt;</span></span></pre></div>
<div class="unxml-col"><div class="unxml-col-label">unxml --auto</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-249038114">CrossIndustryInvoice</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">xmlns:xsi</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/2001/XMLSchema-instance</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">ExchangedDocumentContext</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">GuidelineSpecifiedDocumentContextParameter</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> urn:cen.eu:en16931:2017#compliant#urn:factur-x.eu:1p0:basic</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">ExchangedDocument</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 471102</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 380</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">IssueDateTime</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">format</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 20241115</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">IncludedNote</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">Content</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Rechnung gemäß Bestellung vom 01.11.2024.</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">IncludedNote</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">Content</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242"> Lieferant GmbH</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Lieferantenstraße 20</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 80333 München</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Deutschland</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Geschäftsführer</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">Hans</span><span class="ansi38-248248242"> Muster</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Handelsregisternummer</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">H</span><span class="ansi38-248248242"> A 123</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">IncludedNote</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">Content</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242"> Unsere GLN</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">4000001123452</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Ihre GLN</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">4000001987658</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Ihre Kundennummer</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">GE2020211</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                 Zahlbar innerhalb 30 Tagen netto bis 25.12.2024, 3% Skonto innerhalb 10 Tagen bis 25.11.2024.</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">SupplyChainTradeTransaction</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">IncludedSupplyChainTradeLineItem</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">AssociatedDocumentLineDocument</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">LineID</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 1</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedTradeProduct</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">GlobalID</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">schemeID</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">0160</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 4012345001235</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">Name</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242"> GTIN</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">4012345001235</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                     Unsere Art.-Nr.</span><span class="ansi38-248248242">:</span><span class="ansi38-248248242"> </span><span class="ansi38-102217239">TB100A4</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">|</span><span class="ansi38-248248242">                     Trennblätter A4</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedLineTradeAgreement</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">NetPriceProductTradePrice</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">ChargeAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 9.9000</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">BasisQuantity</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">unitCode</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">H87</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 1.0000</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedLineTradeDelivery</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">BilledQuantity</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">unitCode</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">H87</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 20.0000</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedLineTradeSettlement</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">ApplicableTradeTax</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> VAT</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> S</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 19.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">SpecifiedTradeSettlementLineMonetarySummation</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 198.00</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">ApplicableHeaderTradeAgreement</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SellerTradeParty</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">Name</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Lieferant GmbH</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">PostalTradeAddress</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 80333</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">LineOne</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Lieferantenstraße 20</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">CityName</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> München</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">CountryID</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> DE</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">SpecifiedTaxRegistration</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">schemeID</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">VA</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> DE123456789</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">SpecifiedTaxRegistration</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">ID</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">schemeID</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">FC</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 201/113/40209</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">BuyerTradeParty</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">Name</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Kunden AG Mitte</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">PostalTradeAddress</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">PostcodeCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 69876</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">LineOne</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Hans Muster</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">LineTwo</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Kundenstraße 15</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">CityName</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Frankfurt</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">CountryID</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> DE</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">ApplicableHeaderTradeDelivery</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">ActualDeliverySupplyChainEvent</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">OccurrenceDateTime</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">format</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 20241114</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">ApplicableHeaderTradeSettlement</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">InvoiceCurrencyCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> EUR</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">ApplicableTradeTax</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">CalculatedAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 37.62</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">TypeCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> VAT</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">BasisAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 198.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">CategoryCode</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> S</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">RateApplicablePercent</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 19.00</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedTradePaymentTerms</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">Description</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Zahlbar innerhalb 30 Tagen netto bis 25.12.2024, 3% Skonto innerhalb 10 Tagen bis 25.11.2024.</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">DueDateDateTime</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">DateTimeString</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">format</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">102</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 20241215</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">SpecifiedTradeSettlementHeaderMonetarySummation</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">LineTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 198.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">ChargeTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 0.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">AllowanceTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 0.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">TaxBasisTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 198.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">TaxTotalAmount</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">currencyID</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">EUR</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 37.62</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">GrandTotalAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 235.62</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">TotalPrepaidAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 0.00</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">DuePayableAmount</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> 235.62</span></span></pre></div>
</div></div>
</div>

## XSLT basics

<div class="unxml-demo">
<div class="unxml-sample">
<h3>Build an HTML table with for-each</h3>
<p class="unxml-cap"><a href="https://github.com/vivainio/unxml-demos/blob/main/examples/xslt/cdcatalog.xsl">cdcatalog.xsl</a> · 22 → 15 lines</p>
<div class="unxml-cols">
<div class="unxml-col"><div class="unxml-col-label">XSLT source</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-255255255">&lt;?</span><span class="ansi38-249038114">xml</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">encoding</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">UTF-8</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">?&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">xsl</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">/</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">My CD Collection</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">table</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">border</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">tr</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#9acd32</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">th</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">text-align:left</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Title</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">th</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">text-align:left</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Artist</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">catalog/cd</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">title</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">artist</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">table</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-255255255">&gt;</span></span></pre></div>
<div class="unxml-col"><div class="unxml-col-label">unxml --xslt</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-117113094">xsl:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">version</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">,</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns:xsl</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> /</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">html</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">body</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">h2</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> My CD Collection</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">table</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">border</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">tr</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#9acd32</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">th</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">text-align:left</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Title</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">th</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">text-align:left</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Artist</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">foreach</span><span class="ansi38-248248242"> catalog/cd</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">tr</span>
<span class="ansi38-248248242">              </span><span class="ansi38-249038114">td</span>
<span class="ansi38-248248242">                </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">title</span>
<span class="ansi38-248248242">              </span><span class="ansi38-249038114">td</span>
<span class="ansi38-248248242">                </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">artist</span></span></pre></div>
</div></div>
<div class="unxml-sample">
<h3>Branch with choose / when / otherwise</h3>
<p class="unxml-cap"><a href="https://github.com/vivainio/unxml-demos/blob/main/examples/xslt/cdcatalog-choose.xsl">cdcatalog-choose.xsl</a> · 32 → 20 lines</p>
<div class="unxml-cols">
<div class="unxml-col"><div class="unxml-col-label">XSLT source</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-255255255">&lt;?</span><span class="ansi38-249038114">xml</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">encoding</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">UTF-8</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">?&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span>
<span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">xsl</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">/</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">My CD Collection</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">table</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">border</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">tr</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#9acd32</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Title</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">Artist</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">th</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">catalog/cd</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">title</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">choose</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">when</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">test</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">price </span><span class="ansi38-190132255">&amp;</span><span class="ansi38-190132255">gt</span><span class="ansi38-190132255">;</span><span class="ansi38-230219116"> 10</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">         </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">td</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#ff00ff</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">         </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">artist</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">         </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">when</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">otherwise</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">         </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">artist</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">td</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">otherwise</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">choose</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">tr</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">table</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-255255255">&gt;</span></span></pre></div>
<div class="unxml-col"><div class="unxml-col-label">unxml --xslt</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-117113094">xsl:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">version</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">,</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns:xsl</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> /</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">html</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">body</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">h2</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> My CD Collection</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">table</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">border</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">tr</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#9acd32</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">th</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Title</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">th</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> Artist</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">foreach</span><span class="ansi38-248248242"> catalog/cd</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">tr</span>
<span class="ansi38-248248242">              </span><span class="ansi38-249038114">td</span>
<span class="ansi38-248248242">                </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">title</span>
<span class="ansi38-248248242">              </span><span class="ansi38-249038114">choose</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">                </span><span class="ansi38-249038114">when</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">price</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">&gt;</span><span class="ansi38-248248242"> </span><span class="ansi38-190132255">10</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">                  </span><span class="ansi38-249038114">td</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">bgcolor</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">#ff00ff</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">artist</span>
<span class="ansi38-248248242">                </span><span class="ansi38-249038114">else</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">                  </span><span class="ansi38-249038114">td</span>
<span class="ansi38-248248242">                    </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">artist</span></span></pre></div>
</div></div>
<div class="unxml-sample">
<h3>Named templates + apply-templates</h3>
<p class="unxml-cap"><a href="https://github.com/vivainio/unxml-demos/blob/main/examples/xslt/cdcatalog-templates.xsl">cdcatalog-templates.xsl</a> · 33 → 20 lines</p>
<div class="unxml-cols">
<div class="unxml-col"><div class="unxml-col-label">XSLT source</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-255255255">&lt;?</span><span class="ansi38-249038114">xml</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">encoding</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">UTF-8</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">?&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span>
<span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">xsl</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">/</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242">My CD Collection</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">h2</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">apply-templates</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">cd</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">p</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">apply-templates</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">title</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">apply-templates</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">artist</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">p</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">title</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  Title: </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">span</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">color:#ff0000</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">.</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">span</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">br</span><span class="ansi38-248248242"> </span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">match</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">artist</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  Artist: </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">span</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">color:#00ff00</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">.</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">span</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">br</span><span class="ansi38-248248242"> </span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">template</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-255255255">&gt;</span></span></pre></div>
<div class="unxml-col"><div class="unxml-col-label">unxml --xslt</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-117113094">xsl:</span><span class="ansi38-249038114">stylesheet</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">version</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">,</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns:xsl</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> /</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">html</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">body</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">h2</span><span class="ansi38-248248242"> </span><span class="ansi38-249038114">=</span><span class="ansi38-248248242"> My CD Collection</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">apply</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> cd</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">p</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">apply</span><span class="ansi38-248248242"> title</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">apply</span><span class="ansi38-248248242"> artist</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> title</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">Title:</span><span class="ansi38-230219116">"</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">span</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">color:#ff0000</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> .</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">br</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">template</span><span class="ansi38-248248242"> artist</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">    </span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">Artist:</span><span class="ansi38-230219116">"</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">span</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">color:#00ff00</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> .</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">br</span></span></pre></div>
</div></div>
<div class="unxml-sample">
<h3>Literal-result-element stylesheet</h3>
<p class="unxml-cap"><a href="https://github.com/vivainio/unxml-demos/blob/main/examples/xslt/breakfast-menu.xsl">breakfast-menu.xsl</a> · 17 → 15 lines</p>
<div class="unxml-cols">
<div class="unxml-col"><div class="unxml-col-label">XSLT source</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-255255255">&lt;?</span><span class="ansi38-249038114">xml</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">encoding</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">UTF-8</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">?&gt;</span>
<span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">html</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xsl</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">version</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xmlns</span><span class="ansi38-166226046">:</span><span class="ansi38-166226046">xsl</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">body</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-family:Arial;font-size:12pt;background-color:#EEEEEE</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">breakfast_menu/food</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">div</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">background-color:teal;color:white;padding:4px</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">span</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-weight:bold</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">name</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-248248242"> - </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">span</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">price</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">div</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">div</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">margin-left:20px;margin-bottom:1em;font-size:10pt</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">p</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">description</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">span</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">style</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-style:italic</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">&gt;</span><span class="ansi38-248248242"> (</span><span class="ansi38-255255255">&lt;</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">value-of</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">select</span><span class="ansi38-248248242">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">calories</span><span class="ansi38-230219116">"</span><span class="ansi38-255255255">/&gt;</span><span class="ansi38-248248242"> calories per serving)</span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">span</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">        </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">p</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">      </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">div</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">    </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">xsl</span><span class="ansi38-249038114">:</span><span class="ansi38-249038114">for-each</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-248248242">  </span><span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">body</span><span class="ansi38-255255255">&gt;</span>
<span class="ansi38-255255255">&lt;/</span><span class="ansi38-249038114">html</span><span class="ansi38-255255255">&gt;</span></span></pre></div>
<div class="unxml-col"><div class="unxml-col-label">unxml --xslt</div><pre class="unxml"><span class="ansi2html-content"><span class="ansi38-249038114">html</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">xmlns:xsl</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">http://www.w3.org/1999/XSL/Transform</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">,</span><span class="ansi38-248248242"> </span><span class="ansi38-166226046">xsl:version</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">1.0</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">  </span><span class="ansi38-249038114">body</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-family:Arial;font-size:12pt;background-color:#EEEEEE</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">    </span><span class="ansi38-249038114">foreach</span><span class="ansi38-248248242"> breakfast_menu/food</span><span class="ansi38-248248242">:</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">div</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">background-color:teal;color:white;padding:4px</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">span</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-weight:bold</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">name</span>
<span class="ansi38-248248242">          </span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">-</span><span class="ansi38-230219116">"</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">price</span>
<span class="ansi38-248248242">      </span><span class="ansi38-249038114">div</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">margin-left:20px;margin-bottom:1em;font-size:10pt</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">        </span><span class="ansi38-249038114">p</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">description</span>
<span class="ansi38-248248242">          </span><span class="ansi38-249038114">span</span><span class="ansi38-248248242">(</span><span class="ansi38-166226046">style</span><span class="ansi38-249038114">=</span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">font-style:italic</span><span class="ansi38-230219116">"</span><span class="ansi38-248248242">)</span>
<span class="ansi38-248248242">            </span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">(</span><span class="ansi38-230219116">"</span>
<span class="ansi38-248248242">            </span><span class="ansi38-249038114">&lt;-</span><span class="ansi38-248248242"> </span><span class="ansi38-253151031">calories</span>
<span class="ansi38-248248242">            </span><span class="ansi38-230219116">"</span><span class="ansi38-230219116">calories per serving)</span><span class="ansi38-230219116">"</span></span></pre></div>
</div></div>
</div>

## XML documents
| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [UBL — Invoice (instance)](xml/ubl/invoice-example.html) | 493 lines · 19.2 KB | 353 lines · 12.1 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-Invoice-2.1-Example.xml) |
| [UBL — Order (instance)](xml/ubl/order-example.html) | 341 lines · 13.6 KB | 250 lines · 7.5 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-Order-2.1-Example.xml) |
| [UBL — Credit Note (instance)](xml/ubl/creditnote-example.html) | 431 lines · 17.0 KB | 308 lines · 10.8 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xml/UBL-CreditNote-2.1-Example.xml) |
| [CII — Invoice (instance)](xml/cii/invoice-example.html) | 656 lines · 34.7 KB | 430 lines · 14.3 KB | [source](https://raw.githubusercontent.com/phax/en16931-cii2ubl/master/en16931-cii2ubl-cli/src/test/resources/CII_example1.xml) |
| [Factur-X / ZUGFeRD — Extended (instance)](xml/cii/factur-x-extended.html) | 430 lines · 20.6 KB | 249 lines · 8.4 KB | [source](https://raw.githubusercontent.com/ZUGFeRD/mustangproject/master/library/src/test/resources/factur-x-extended.xml) |

## Schemas
| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [Finvoice 3.0](schemas/finvoice-3.0.html) | 1,690 lines · 95.1 KB | 1,123 lines · 45.3 KB | [source](https://file.finanssiala.fi/finvoice/Finvoice3.0.xsd) |
| [UBL — Core Component Types](schemas/ubl/cct.html) | 731 lines · 44.2 KB | 83 lines · 4.0 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/CCTS_CCT_SchemaModule-2.1.xsd) |
| [UBL — Unqualified Data Types](schemas/ubl/udt.html) | 553 lines · 26.7 KB | 38 lines · 1.9 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-UnqualifiedDataTypes-2.1.xsd) |
| [UBL — Qualified Data Types](schemas/ubl/qdt.html) | 69 lines · 3.5 KB | 5 lines · 424 B | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-QualifiedDataTypes-2.1.xsd) |
| [UBL — Common Basic Components](schemas/ubl/cbc.html) | 5,388 lines · 214.7 KB | 1,752 lines · 90.0 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonBasicComponents-2.1.xsd) |
| [UBL — Common Aggregate Components](schemas/ubl/cac.html) | 39,798 lines · 2.3 MB | 5,401 lines · 288.4 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonAggregateComponents-2.1.xsd) |
| [UBL — Common Extension Components](schemas/ubl/cec.html) | 222 lines · 9.3 KB | 50 lines · 2.5 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/common/UBL-CommonExtensionComponents-2.1.xsd) |
| [UBL — Invoice](schemas/ubl/invoice.html) | 1,001 lines · 58.8 KB | 120 lines · 6.1 KB | [source](https://docs.oasis-open.org/ubl/os-UBL-2.1/xsd/maindoc/UBL-Invoice-2.1.xsd) |

## XSLT
| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [DocBook XSL — HTML driver](xslt/docbook/html-driver.html) | 558 lines · 20.0 KB | 338 lines · 10.2 KB | [source](https://cdn.docbook.org/release/xsl/current/html/docbook.xsl) |
| [DocBook XSL — inline elements](xslt/docbook/inline.html) | 1,598 lines · 49.8 KB | 837 lines · 21.9 KB | [source](https://cdn.docbook.org/release/xsl/current/html/inline.xsl) |
| [ISO Schematron — SVRL skeleton](xslt/schematron/iso-svrl.html) | 614 lines · 21.1 KB | 266 lines · 6.6 KB | [source](https://raw.githubusercontent.com/Schematron/schematron/master/trunk/schematron/code/iso_svrl_for_xslt1.xsl) |

## Schematron
| Document | Original | Rendered | Source |
| --- | --- | --- | --- |
| [EN16931 — UBL validation (driver)](schematron/en16931/ubl-validation.html) | 34 lines · 1.8 KB | 19 lines · 948 B | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/EN16931-UBL-validation.sch) |
| [EN16931 — abstract model rules](schematron/en16931/model.html) | 341 lines · 51.3 KB | 469 lines · 45.9 KB | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/abstract/EN16931-model.sch) |
| [EN16931 — UBL bindings](schematron/en16931/ubl-model.html) | 277 lines · 71.1 KB | 574 lines · 72.3 KB | [source](https://raw.githubusercontent.com/ConnectingEurope/eInvoicing-EN16931/master/ubl/schematron/UBL/EN16931-UBL-model.sch) |
