# Changelog

## v2.5.0 (2026-09-20)

### Fix

- Support toml parsing on python 3.10 ([`0ce026b`](https://github.com/NawrotLab/larvaworld-move/commit/0ce026b9eb3497bee8385fcfe4e3d038b721bb1a))
- Install egl and correct regression test assertions ([`12e2dd2`](https://github.com/NawrotLab/larvaworld-move/commit/12e2dd23effc5c2844bc3827348adc71af4d5fff))
- Remove deb822 chrome apt source ([`64837b7`](https://github.com/NawrotLab/larvaworld-move/commit/64837b7cd7ef86f48ae6875cc16ebabd25321b5e))
- Exclude chrome repository from apt update ([`dec1f13`](https://github.com/NawrotLab/larvaworld-move/commit/dec1f130e30c3497a94ea0e06167c5e90837494f))
- Allow legacy portal commit headers ([`a35d556`](https://github.com/NawrotLab/larvaworld-move/commit/a35d556333af5bd2715400d8e63616170fe321ac))
- Scale ingested_body_area_ratio by v^(2/3) ([`3f89786`](https://github.com/NawrotLab/larvaworld-move/commit/3f897869d5f668529e22fd9a9059fefe39f99161))
- Repair geolarvadataset construction and unit properties ([`5b9cb64`](https://github.com/NawrotLab/larvaworld-move/commit/5b9cb642f5200333fb609a68b3260909f1ac4e10))
- Store manifest reference paths with posix separators ([`3a1e394`](https://github.com/NawrotLab/larvaworld-move/commit/3a1e3944eb8fc25b503a0666492af9a6c061a190))
- Centre trajectories on the bounding-box midpoint ([`9aafa06`](https://github.com/NawrotLab/larvaworld-move/commit/9aafa068534fff984bd4d2136ffb757e5edac092))
- Keep per-agent temporal order when sorting imported tracks ([`54a91c2`](https://github.com/NawrotLab/larvaworld-move/commit/54a91c23e2dfeaba416ef3bdb53410482e2398ac))
- Refactor test_predictions to use symbol-mapping dict ([`c0e50e8`](https://github.com/NawrotLab/larvaworld-move/commit/c0e50e84a732a41409be557ce5eb3d93e8e8b217))
- Sort the epoch ticks into a new list ([`ce1e774`](https://github.com/NawrotLab/larvaworld-move/commit/ce1e77496f9d2b00d18c7c7dc7048674774caae2))
- Stop handing out live registry objects and shared defaults ([`23ece1e`](https://github.com/NawrotLab/larvaworld-move/commit/23ece1e80bc4c48d57d7639d2e3e402d5bff854e))
- Copy the module defaults instead of updating them in place ([`c71d1ec`](https://github.com/NawrotLab/larvaworld-move/commit/c71d1ec1650383531c928002a5a1d48d5de87362))
- Make the odor-patch analyses runnable end to end ([`2d1149c`](https://github.com/NawrotLab/larvaworld-move/commit/2d1149ceca35d7f81b4d6bda8a54c9eba9e3e062))
- Stop the olfactor wiring leaking between stored models ([`47e524d`](https://github.com/NawrotLab/larvaworld-move/commit/47e524d589a1fea9f413051726ca02d2c8830caf))
- Draw the food grid and repair the food-intake plots ([`123f860`](https://github.com/NawrotLab/larvaworld-move/commit/123f860821a7060d5991bb2beb1e8dd6ec60958e))
- Follow the tutorial notebooks to their renumbered sections ([`f4f571e`](https://github.com/NawrotLab/larvaworld-move/commit/f4f571ea133309b3f421bb63876aa46b28e8a03a))
- Repair the annotated track plots and complete the experiment analyses ([`f04ec2e`](https://github.com/NawrotLab/larvaworld-move/commit/f04ec2e6a9b49c749d501e116d91ed727287ef56))
- Follow the tutorial notebooks to their new section paths ([`36b014d`](https://github.com/NawrotLab/larvaworld-move/commit/36b014d07b8143fd32dda99965f3ade237190bad))
- Scale explore preview plots responsively ([`cc15240`](https://github.com/NawrotLab/larvaworld-move/commit/cc1524095a739b0b16634583912a10dc5bab01ae))
- Keep the pooled index usable when agent ids repeat ([`bb2fa50`](https://github.com/NawrotLab/larvaworld-move/commit/bb2fa50c2b1037c88daf1565426eac5074ee61bf))
- Derive the trajectory from the midline when no point is tracked ([`e0768f8`](https://github.com/NawrotLab/larvaworld-move/commit/e0768f852aeccb8da37dfd32ef956f21da94e8ed))
- Keep quick-start tabs below header ([`8da19f3`](https://github.com/NawrotLab/larvaworld-move/commit/8da19f3fbd0e95805047b870eafb73012340898c))
- Render optional pixel scale safely ([`62ca719`](https://github.com/NawrotLab/larvaworld-move/commit/62ca7196ad86f1816364f09560c1764a8c9972ae))
- Remove the dataset manager&#39;s notebook tutorial link ([`beedc7f`](https://github.com/NawrotLab/larvaworld-move/commit/beedc7f99326a89e62a80513af0e5817322f65a0))
- Accept list values for numerictuple and range parameters ([`8ffe1a7`](https://github.com/NawrotLab/larvaworld-move/commit/8ffe1a7afda1886579900442cef54147514e5306))
- Remove inner scrollbar from parameter database table ([`b408b9f`](https://github.com/NawrotLab/larvaworld-move/commit/b408b9f595f7eac93616df24a3f294e04817bff4))
- Default model inspector&#39;s preset dropdown to explorer ([`c0ffdbc`](https://github.com/NawrotLab/larvaworld-move/commit/c0ffdbc9801dae8b141b24d958c710a992de740c))
- Move landing page banner below quick start ([`0a71ba9`](https://github.com/NawrotLab/larvaworld-move/commit/0a71ba95c92a9b3a7727a655329e54329234b447))
- Polish model inspector&#39;s new stored configurations panel and comparison ([`2803fbc`](https://github.com/NawrotLab/larvaworld-move/commit/2803fbc1ee66202d071245ceefea93843749759b))
- Rebuild wrapped text render cache when max_text_width changes ([`f39aff9`](https://github.com/NawrotLab/larvaworld-move/commit/f39aff97bab16213f314f99909b34447b1c830c3))
- Apply save/load/delete color convention to environment builder&#39;s preset buttons ([`8592dfe`](https://github.com/NawrotLab/larvaworld-move/commit/8592dfe1c171d102d6eeb2f4ea31e7a3f5a1687d))
- Match evalrun&#39;s live simulation arena to the target dataset ([`c7038b2`](https://github.com/NawrotLab/larvaworld-move/commit/c7038b2aafbbcafa872af192c65aa871d98f6d91))
- Exclude body tips from reconstruct_at_nsegs vectors ([`6978c6f`](https://github.com/NawrotLab/larvaworld-move/commit/6978c6ff69aba5dc38bea00f78716dc72426e409))
- Rewrite simulation intro-text overlay to scale and wrap ([`ad12434`](https://github.com/NawrotLab/larvaworld-move/commit/ad124348f4276de3bf245b69b42cdbb8663fd549))
- Coordinate larvadatasetcollection color fallback batch ([`b9ea162`](https://github.com/NawrotLab/larvaworld-move/commit/b9ea1629c9b2b8dcd6c2359ef5a1bf2e367d572c))
- Resolve two spurious blanks in ga best-vs-base model diff ([`c01c43f`](https://github.com/NawrotLab/larvaworld-move/commit/c01c43fdf696b1330cf5553485ee4a9d5d7b4a4e))
- Model config table was silently dropping every module but intermitter ([`9cd96e5`](https://github.com/NawrotLab/larvaworld-move/commit/9cd96e57b5b49f40876f448dc6ce7665fe7241ad))
- Fix legend overflow in dispersal summary, x-label overlap in model summary ([`10f8dc3`](https://github.com/NawrotLab/larvaworld-move/commit/10f8dc3be12247ac7e82b28d2b16d362f28277e2))
- Crop saved plots to their actual content, not the nominal figsize ([`b17f457`](https://github.com/NawrotLab/larvaworld-move/commit/b17f4576620078196613a136194a7917d7d4b09a))
- Fix three bugs blocking expconf.imitation_exp end-to-end ([`36edd55`](https://github.com/NawrotLab/larvaworld-move/commit/36edd5563192a4c8b6d204cebbcd45c6ee1d8cf5))
- Fix two real bugs in larvadatasetcollection hit by multi-dataset plots ([`0f7ef00`](https://github.com/NawrotLab/larvaworld-move/commit/0f7ef00a9adfed93880d1a1a563c55eabb3781f3))
- Let fixate_larva focus/tether simulated (non-reference) datasets ([`7cac288`](https://github.com/NawrotLab/larvaworld-move/commit/7cac288d69e0608c377785e465aee6ef7b598675))
- Fix three real bugs in mdiff_table/diff_df ([`a9d7ea1`](https://github.com/NawrotLab/larvaworld-move/commit/a9d7ea19c8b5de1498c6a04c8a9c56254f3edd05))
- Fix operator-precedence bug in comp_orientations&#39; angle wrap ([`83b3ba2`](https://github.com/NawrotLab/larvaworld-move/commit/83b3ba2820b7f38a0ca5f6a653e4082a0baedfef))
- Fix broken tutorial notebooks, fix bare raise in odorscape ([`c6687f0`](https://github.com/NawrotLab/larvaworld-move/commit/c6687f05aa83a24be03e552e805c89fc0c82f16c))
- Fix analysis app plotting pipeline, add missing test coverage ([`26904cb`](https://github.com/NawrotLab/larvaworld-move/commit/26904cbcca1f2773eeea7ca5e0a80f0f46ce83ba))
- Make combine_videos independent of system ffmpeg/ffprobe ([`435a16f`](https://github.com/NawrotLab/larvaworld-move/commit/435a16f7144453560b0cd17dfd66f2bf8e2f22c5))
- Allow editing bundled datasets, fix dish01/dish02 bootstrap gap ([`be91d13`](https://github.com/NawrotLab/larvaworld-move/commit/be91d13f3fd8f415521258286c68ac9eb51a5812))
- Fix test-isolation registry leak, discovery gap, and model-inspector primary tracking; add data_dir dataset detection ([`6ba5cda`](https://github.com/NawrotLab/larvaworld-move/commit/6ba5cdabc58e0da6176a1430936175b871352d44))
- Give branchintermitter.beta a real default instead of none ([`757d628`](https://github.com/NawrotLab/larvaworld-move/commit/757d6281a3288ea2234220de7dd5cc7cf0f7687c))
- Resolve panel spacing parameter and test record type issues ([`9bf704a`](https://github.com/NawrotLab/larvaworld-move/commit/9bf704a6ccf6da07e0ca919438e5c48e278ae19d))
- Make analysis app robust to missing plot functions ([`95ac45d`](https://github.com/NawrotLab/larvaworld-move/commit/95ac45db1ce54330513372afb682b118fd306ba6))
- Implement disabled property on comparison selector proxy ([`dd2cc7a`](https://github.com/NawrotLab/larvaworld-move/commit/dd2cc7a05d6b21620c56e5515ed1252c1ce3860d))
- Robust trajectory and error handling ([`0f55b14`](https://github.com/NawrotLab/larvaworld-move/commit/0f55b1495c3c324f83297433d9decfccc0f348e7))
- Improve schleyer format detection and import app documentation ([`82dde4a`](https://github.com/NawrotLab/larvaworld-move/commit/82dde4a43429363025f926ecb2d0f91e816cecb2))
- Resolve all essay construction crashes ([`305c8cb`](https://github.com/NawrotLab/larvaworld-move/commit/305c8cbd23a90cd3af33217abb78e7458eba94cd))

### Refactor

- Remove legacy desktop gui ([`059f111`](https://github.com/NawrotLab/larvaworld-move/commit/059f1117aa1815726846fc372f7e15c0ea27f37b))
- Build buttons through the semantic factories ([`68a437c`](https://github.com/NawrotLab/larvaworld-move/commit/68a437c3b896ac6cb60fa258207e2fc4774b8e40))
- Model inspector adopts shared stored configurations panel, relocates comparison ([`58a58a6`](https://github.com/NawrotLab/larvaworld-move/commit/58a58a61f13496b9a1ce3ce0b45d7313887e3567))
- Adopt shared stored configurations panel in environment builder ([`a77deb2`](https://github.com/NawrotLab/larvaworld-move/commit/a77deb2451a48850f925b7f52efe4fb2500ccf3d))
- Remove single experiment&#39;s larva-group placement canvas, adopt shared preset panel ([`8d00e63`](https://github.com/NawrotLab/larvaworld-move/commit/8d00e63d3dd8fbfebc1a8a67d8a511c57dc7ff4d))
- Migrate environment builder presets onto presetcontrolscontroller ([`b03a104`](https://github.com/NawrotLab/larvaworld-move/commit/b03a104bd0d86b6926ec16d1dc674ead2fb89ab4))
- Migrate environment builder onto shared placement helpers ([`bda8d27`](https://github.com/NawrotLab/larvaworld-move/commit/bda8d27ea7a2cceed3e00f1282a02356c1cadc31))
- Rewrite mdiff_table layout with spanning model header ([`8f5703e`](https://github.com/NawrotLab/larvaworld-move/commit/8f5703e27989d3ab5fe04bc33859b79d28c277b8))
- Generalize resolve_param_class via introspection, split naming/value concerns ([`e6f8408`](https://github.com/NawrotLab/larvaworld-move/commit/e6f84085648565a6edcb55b6a89c48dacc305890))
- Extract header dropdown builders, add shared controls panel ([`6e3a897`](https://github.com/NawrotLab/larvaworld-move/commit/6e3a8971eebf52e882830e702a0a97485478c308))
- Reorganize media files and update portal components ([`9e29278`](https://github.com/NawrotLab/larvaworld-move/commit/9e29278d254a7c3fd7f414df42cf62342a6acd3a))
- Drop the redundant drosophila species option ([`b7608b3`](https://github.com/NawrotLab/larvaworld-move/commit/b7608b3c3fad97d7e8246ccadc1fab7787cb941a))
- Drive the deb model from the ground-truth equations ([`0843b68`](https://github.com/NawrotLab/larvaworld-move/commit/0843b686d9586b7612a1b72c716bb8843038d02b))
- Minor tweaks to widgets and components ([`6d2c40b`](https://github.com/NawrotLab/larvaworld-move/commit/6d2c40bdaf6af59b2cfc6f094ed039a68a57c928))
- Register analysis app and update landing registry ([`9c6fa6c`](https://github.com/NawrotLab/larvaworld-move/commit/9c6fa6c6e21d3726ccb5f429c7e5645092a865ed))
- Expand manager helpers for unified dataset discovery ([`f6086dc`](https://github.com/NawrotLab/larvaworld-move/commit/f6086dc5c12d565fcb4ccda55889e67f28eca2c8))
- Improve backward-compatible select proxies ([`000471b`](https://github.com/NawrotLab/larvaworld-move/commit/000471b8327bb5867d6dc17871f0593d1e483f04))
- Task 2.6 - add json export feature to model inspector ([`e0e6cd8`](https://github.com/NawrotLab/larvaworld-move/commit/e0e6cd86decd8cabd93383d1d786ac4593eaa563))
- Task 1.4 - add parameter reference table to module inspector ([`995e721`](https://github.com/NawrotLab/larvaworld-move/commit/995e721e2970a101ad760d583cbd233294162960))
- Task 1.1 - add collapsible configuration panel to module inspector ([`785f5f1`](https://github.com/NawrotLab/larvaworld-move/commit/785f5f1e67d6652c3f546c2b4413cf0ef8cf6206))
- Split environment builder into qt modules and shared helpers ([`4a2cb2f`](https://github.com/NawrotLab/larvaworld-move/commit/4a2cb2fd988d7e8e83bebc60413f164087c19b5e))

### Documentation

- Complete the docstring pass over the package ([`db2d2ca`](https://github.com/NawrotLab/larvaworld-move/commit/db2d2ca5187d7103ace8402f84b98c6f11e08b3e))
- Document the single experiment app ([`99343ad`](https://github.com/NawrotLab/larvaworld-move/commit/99343ad430dbb1b29e7a00ff72374532a4fc1927))
- Document the environment builder app ([`7106236`](https://github.com/NawrotLab/larvaworld-move/commit/7106236729913e4d6f27efb6826cc5ae1f6cb688))
- Document the model inspector app ([`d0ab4d9`](https://github.com/NawrotLab/larvaworld-move/commit/d0ab4d9f64a6fc7012ffa93d8d0e08a864e70068))
- Document the import, manager, analysis and replay apps ([`b6b4011`](https://github.com/NawrotLab/larvaworld-move/commit/b6b4011987f79a4eba8e5aa2a801b26b4927d83e))
- Document the preset stores, the canvas and the model draft ([`3b76b2b`](https://github.com/NawrotLab/larvaworld-move/commit/3b76b2b066af7777f163e42ffda3333c7469fce7))
- Document the replay data layer and the conftype editor ([`308add9`](https://github.com/NawrotLab/larvaworld-move/commit/308add9a9f40b4a7b94438bab1769564c2a39999))
- Document the builder payload and preview data layers ([`2ff192a`](https://github.com/NawrotLab/larvaworld-move/commit/2ff192a75bf7e2c83c79bc06ef65e21475411603))
- Document the config widget base and the shortcut dialog ([`dbed549`](https://github.com/NawrotLab/larvaworld-move/commit/dbed5493c5a62a1e1838c5ecbb37da53671a4854))
- Document the workspace, discovery and startup helpers ([`fcdcf89`](https://github.com/NawrotLab/larvaworld-move/commit/fcdcf89cb84a51daaae4710f2442a6f2958c15ac))
- Document the portal modules and classes ([`caa2821`](https://github.com/NawrotLab/larvaworld-move/commit/caa2821b4414934fa5f3b46fab0f6fccb1d72028))
- Document the parameter database and the generators ([`0497dba`](https://github.com/NawrotLab/larvaworld-move/commit/0497dba7e4b796a5818856dbcfbb6a22b6b848ed))
- Document the run manifest, the screen layer and the sim modules ([`37fc27a`](https://github.com/NawrotLab/larvaworld-move/commit/37fc27a3cbb892c0d842cc9d79be57796c063b38))
- Complete the docstring pass over lib/param ([`1526125`](https://github.com/NawrotLab/larvaworld-move/commit/15261258b5e834aeb9696de17eae6342c5f41080))
- Document the parameter types and configuration groups ([`333e652`](https://github.com/NawrotLab/larvaworld-move/commit/333e652a7b90d956bc2730fc7816a076cb50f3e7))
- Complete the docstring pass over lib/model ([`04baa57`](https://github.com/NawrotLab/larvaworld-move/commit/04baa57d62a919e0ff2781c42e7548d011b8401c))
- Document the module registry, memory and agent primitives ([`84ce8b5`](https://github.com/NawrotLab/larvaworld-move/commit/84ce8b5a9c37bfecdee912eb6281118a22815a74))
- Document the locomotion and brain modules ([`d3ef0c2`](https://github.com/NawrotLab/larvaworld-move/commit/d3ef0c22141eb189791b6cd203d9b8feed8e761d))
- Document the environment value grids and the sensors ([`cf7a070`](https://github.com/NawrotLab/larvaworld-move/commit/cf7a07046974fe27870c261fa09034d9bbfa391d))
- Document the gut digestion and absorption chain ([`7fa48a1`](https://github.com/NawrotLab/larvaworld-move/commit/7fa48a1bb59f94711efda54764d1f043a98ac773))
- Document the deb model accessors and hunger coupling ([`edc5222`](https://github.com/NawrotLab/larvaworld-move/commit/edc522213acf8ae4354d85968d4a7bcd31ea7b53))
- Add module and class docstrings to lib/model ([`2f926c0`](https://github.com/NawrotLab/larvaworld-move/commit/2f926c0af0febcefa64cdf2c80fa277558ddce2d))
- Document the dataset computation and collection apis ([`758c222`](https://github.com/NawrotLab/larvaworld-move/commit/758c222593a2834e5eac445bac60211a4647d125))
- Document lib/process and annotate its signatures ([`52ea659`](https://github.com/NawrotLab/larvaworld-move/commit/52ea659bf72c26366e2fe0e84b91ac835cb60071))
- Add missing docstrings and type hints to lib/util and cli ([`9ce0443`](https://github.com/NawrotLab/larvaworld-move/commit/9ce04434635162d07692d6d10e159735bd2f7a13))
- Add educational pipeline for testing deb predictions ([`8e411b2`](https://github.com/NawrotLab/larvaworld-move/commit/8e411b2e694769f55ead324ec338e7f0e5260ce1))
- Add the four-model comparison on one odor patch ([`7f3e2fb`](https://github.com/NawrotLab/larvaworld-move/commit/7f3e2fb002cbebcfc35d6054bc5d3ddbccc2b0d4))
- Add the feeding assay to the simulated experiments ([`e1145a8`](https://github.com/NawrotLab/larvaworld-move/commit/e1145a8f535260190aad5bbd197252cfa10564dc))
- Add simulated experiments and apply the course review ([`fcce4a3`](https://github.com/NawrotLab/larvaworld-move/commit/fcce4a3db180a6a64f420500dfb1a9e743bbc1bd))
- Restructure and rewrite the tutorial course ([`b0acffb`](https://github.com/NawrotLab/larvaworld-move/commit/b0acffbefaf3eccac33e71b803c072c81ee2986c))
- Add two public-dataset tutorials and fetch the data automatically ([`1caaef5`](https://github.com/NawrotLab/larvaworld-move/commit/1caaef5909aba82f1c5f06532410ee77b6ba6fe2))
- Add a template for importing public datasets ([`b9b9947`](https://github.com/NawrotLab/larvaworld-move/commit/b9b9947cbce26da24618a84753b1560ec7b9fc59))
- Restructure the feeding-state import tutorial ([`aa39daf`](https://github.com/NawrotLab/larvaworld-move/commit/aa39dafc5ddf71db11d31fd568ae7d491512a140))
- Add feeding-state locomotion import tutorial ([`d486efb`](https://github.com/NawrotLab/larvaworld-move/commit/d486efb6d62e6984560ac6f809dc89b111ec63b1))
- Thread per-run output folder through ga turner-noise notebook ([`cdf015b`](https://github.com/NawrotLab/larvaworld-move/commit/cdf015b70d3e6510b6fe41552574e187dd785bc5))
- Rewrite ga turner-noise notebook on top of fixed codebase ([`aabedd0`](https://github.com/NawrotLab/larvaworld-move/commit/aabedd07ddbbc4b4286c0a04c1c77b8599db8d61))
- Add ga turner input/output noise optimization notebook ([`b1c5b0e`](https://github.com/NawrotLab/larvaworld-move/commit/b1c5b0eb8e63479ff93c4d1df3ba526eb945dc55))

### Build

- Update dependencies to clear known vulnerabilities ([`377e66a`](https://github.com/NawrotLab/larvaworld-move/commit/377e66a97290ecc922f71493e1796bacaca762c3))
- Add sphinx-design and sphinx-copybutton to the docs group ([`103eb57`](https://github.com/NawrotLab/larvaworld-move/commit/103eb57fb635da7987b592e8872e5b89b41caa15))

### Feature

- Add arena occupancy and midline-endpoint spatial parameters ([`8e09c0f`](https://github.com/NawrotLab/larvaworld-move/commit/8e09c0fcdbfec4baac10619694be94ab6842f56e))
- Complete univariate tww_f plot generation (phase 1) ([`410f84f`](https://github.com/NawrotLab/larvaworld-move/commit/410f84f3d1d09732d1abe1ed3e94aa1bb651a3cb))
- Add univariate data reproduction framework with roadmap ([`5d4efa3`](https://github.com/NawrotLab/larvaworld-move/commit/5d4efa3d6b422190a63dbd3f16dd066c4f38ff9e))
- Integrate generalized_animal parameter analysis and amp pipeline ([`19f0585`](https://github.com/NawrotLab/larvaworld-move/commit/19f05851d4679e780b8081d145e521757539e3ec))
- Add error statistics and summary metrics ([`0e4c707`](https://github.com/NawrotLab/larvaworld-move/commit/0e4c707eb77c050f54efb7939c2c6bd9b7147679))
- Port debtool ode solvers for instars, emergence, and lifespan ([`0245414`](https://github.com/NawrotLab/larvaworld-move/commit/024541497dde179b9b5f1e4e27086d0dc8b835b4))
- Give the food-grid experiment its intake analysis ([`e120315`](https://github.com/NawrotLab/larvaworld-move/commit/e120315e7bcc9b0209d48fc36076fed31f20ce32))
- Enhance explore previews and dataset inspection ([`914ee03`](https://github.com/NawrotLab/larvaworld-move/commit/914ee031fb397e386f653de09c3e8f4b5ffa389e))
- Add explore preview analysis tables ([`b60e940`](https://github.com/NawrotLab/larvaworld-move/commit/b60e940209d24d513038e95a24a61b38da29a3f9))
- Configure explore canvas playback ([`d1e47c3`](https://github.com/NawrotLab/larvaworld-move/commit/d1e47c3b8598c6fa57af258d40f160fd8c7a7ee2))
- Derive tracker metadata from the data being imported ([`f81ca5b`](https://github.com/NawrotLab/larvaworld-move/commit/f81ca5bb8d775e4dca498b482f32b0c8b5dc4297))
- Add deeplabcut importer ([`f147f23`](https://github.com/NawrotLab/larvaworld-move/commit/f147f23aca4bd86b951cbd59f904cb7ee4a8804e))
- Add spine-to-per-parameter raw file converter ([`593e089`](https://github.com/NawrotLab/larvaworld-move/commit/593e08922755854cdccb00105aa39d63cd0831db))
- Add template import/export and preset parity to single experiment ([`bb712f0`](https://github.com/NawrotLab/larvaworld-move/commit/bb712f0074bb43b6909c1f9f9c9ac43d4791b916))
- Add dropdown-only preset selector and visible save target ([`e91470c`](https://github.com/NawrotLab/larvaworld-move/commit/e91470c316ccff913e2ac426a42fecdddc7080a5))
- Add zero-configuration explore entry point ([`0c42794`](https://github.com/NawrotLab/larvaworld-move/commit/0c4279447e1841d29f864916f24a3d4306bc0032))
- Add semantic button factories ([`157414a`](https://github.com/NawrotLab/larvaworld-move/commit/157414a69e7e6044508cb8eedb1a3913c21c6315))
- Add reproducible run manifests ([`ced6742`](https://github.com/NawrotLab/larvaworld-move/commit/ced6742308452b289c58e9a75539f0547181b849))
- Rework analysis app&#39;s about panel, dataset table, and plot picker ([`0f59504`](https://github.com/NawrotLab/larvaworld-move/commit/0f59504d560244c2172450f6c0cb526623626e5f))
- Add dual_write mode to presetcontrolscontroller ([`ac4776f`](https://github.com/NawrotLab/larvaworld-move/commit/ac4776f7195fe29369e3255de2d39c946f032843))
- Click-to-place larva groups on single experiment&#39;s canvas ([`67b3571`](https://github.com/NawrotLab/larvaworld-move/commit/67b3571ea426d5963820b09b405dab3bdb1524bb))
- Expose classdict_editor&#39;s select widget via on_select_widget ([`97701b6`](https://github.com/NawrotLab/larvaworld-move/commit/97701b6a82d74a7d7455ea3b9ee8c1b8110870e5))
- Add generic canvas placement helpers ([`1e6a7e4`](https://github.com/NawrotLab/larvaworld-move/commit/1e6a7e498752b653f0228e6a72d137ea2a9230cd))
- Rewrite ga progress plot with db-sourced labels and clearer layout ([`1d7df09`](https://github.com/NawrotLab/larvaworld-move/commit/1d7df0913d3c196b0d8df0e7d02f46cff1c87058))
- Add clone-by-key, multi-select required keys, color convention ([`0c2b084`](https://github.com/NawrotLab/larvaworld-move/commit/0c2b08401db44f61e8f915e94fb1995aa2104b02))
- Add larvadataset.reconstruct_at_nsegs for angular-kinematics comparison ([`9a6dac0`](https://github.com/NawrotLab/larvaworld-move/commit/9a6dac08ad434bda35139e0606c113f60aea3135))
- Add ga per-generation optimization-progress plot ([`528be57`](https://github.com/NawrotLab/larvaworld-move/commit/528be57edae9fa13e1e4c3309a13d8b05d14687e))
- Make spacedict&#39;s effector-param exclusion optional, debug ga storage ([`1daae63`](https://github.com/NawrotLab/larvaworld-move/commit/1daae638e868df6849dd5441e7b9684d500d30db))
- Add about and parameter database popups, drop inert info icon ([`6372ccf`](https://github.com/NawrotLab/larvaworld-move/commit/6372ccf877adda86955f7bf785e4c27328b66c9a))
- Add per-stage deb simulation, full tempcorr and the amp importer ([`12c4e82`](https://github.com/NawrotLab/larvaworld-move/commit/12c4e8292f6461f02216204f0466039b5c05feda))
- Add ground-truth deb equations and rover/sitter phenotypes ([`ef08dcf`](https://github.com/NawrotLab/larvaworld-move/commit/ef08dcf42fd95bc8dafd8a20a73f98a95452a254))
- Add analysis app with plot discovery and visualization ([`f765e71`](https://github.com/NawrotLab/larvaworld-move/commit/f765e710c56cd1aa6121dfc804a476aabafadebd))
- Add performance metrics and sensitivity analysis ([`9daea35`](https://github.com/NawrotLab/larvaworld-move/commit/9daea356c1b6a1529a9f339320bd6d04311af125))
- Add simulation canvas visualization ([`db2277a`](https://github.com/NawrotLab/larvaworld-move/commit/db2277a83882853ab1b309fba8ad372d5645fab7))
- Build comparison mode for model inspector ([`c6a578d`](https://github.com/NawrotLab/larvaworld-move/commit/c6a578d3a4fb8ab2b3bb1990c3562d2cef0ab82d))
- Multi-select model picker for model inspector ([`b045afe`](https://github.com/NawrotLab/larvaworld-move/commit/b045afe773c9de75ee65a5ce777621cc12235ec4))
- Enhance status circle, improve lab format feedback, add timing widget ([`56ce094`](https://github.com/NawrotLab/larvaworld-move/commit/56ce0948e7712ac8ca1461ead34136264e9838c9))
- Replace workspace led indicator with emoji icons ([`ee46812`](https://github.com/NawrotLab/larvaworld-move/commit/ee46812dccce097a4a60986fe8692e548e643b55))
- Add collapsible &#34;ℹ️ about&#34; info panels to major apps ([`1d8e7f4`](https://github.com/NawrotLab/larvaworld-move/commit/1d8e7f494d673bf43b90da8bb52a990058a5d8a9))
- Add workspace path access buttons (open &amp; copy) ([`2ddf9f2`](https://github.com/NawrotLab/larvaworld-move/commit/2ddf9f24fc90d71fcb1a5c6865f7da6a13c4075c))
- Harden import datasets ux with status, native browse, deferred import ([`ad5e435`](https://github.com/NawrotLab/larvaworld-move/commit/ad5e435b79a975d2bde10cbc8383bdcdf35c165c))

### Test

- Verify behavioral simulation rover/sitter integration ([`88c39fe`](https://github.com/NawrotLab/larvaworld-move/commit/88c39fe18cfb08e1f8f0ab5af9a09bb0ef212770))
- Drop branch-intermitter beta validation tests ([`936203e`](https://github.com/NawrotLab/larvaworld-move/commit/936203e741198084cc128aeeba312c2bd15cf2e6))
- Fix draft/registry synchronization test ([`7a36b72`](https://github.com/NawrotLab/larvaworld-move/commit/7a36b723699d2a6e708bc887b2ec5426e28bfb41))
- Pin the deb integration contract before the core swap ([`0fa35f1`](https://github.com/NawrotLab/larvaworld-move/commit/0fa35f1bd5f129d7c28b0648b85ae00a4b81823d))
- Make rl memory learning deterministic ([`27551a6`](https://github.com/NawrotLab/larvaworld-move/commit/27551a6a3ce5d577fce06e48ce657b6b190e4ec6))

### Performance

- Make test runs fast by default, opt into parallelism ([`f0d2f22`](https://github.com/NawrotLab/larvaworld-move/commit/f0d2f220a31b219e64baef1b42e2be3edf2cf77a))

## v2.4.0 (2026-06-05)

### Fix

- Coerce nested classdict payloads ([`27e9017`](https://github.com/NawrotLab/larvaworld-move/commit/27e9017828675f9cb759568d35a6dbd0744a53a5))
- Return copied defaults from module inspector default_module_config ([`770a6a0`](https://github.com/NawrotLab/larvaworld-move/commit/770a6a0ff20253a79491281d7bc8b05cdfd4daa2))
- Keep module inspector sensor stimulus on active gain keys ([`5596365`](https://github.com/NawrotLab/larvaworld-move/commit/5596365b0f52de237531ca5388c7915fbc5616e5))

### Performance

- Reduce landing banner gif sizes ([`8ad8d3c`](https://github.com/NawrotLab/larvaworld-move/commit/8ad8d3c24b05dd54c15d8ddcff117ab7145edf7a))

### Documentation

- Keep module inspector copy user-facing ([`f2bfd7e`](https://github.com/NawrotLab/larvaworld-move/commit/f2bfd7e3d9ad94c51ac44613933ddfbf7e606289))

### Feature

- Extend module inspector with kind-aware feeder and sensor probes ([`51dc86b`](https://github.com/NawrotLab/larvaworld-move/commit/51dc86bd4f35b7085c76cf008eab022279a9b927))
- Add portal module inspector for crawler and turner ([`21f9e64`](https://github.com/NawrotLab/larvaworld-move/commit/21f9e64de6db5b01c1607e9a8735db11b62a8807))
- Refine model inspector preview reporters and mode widgets ([`3f9abb2`](https://github.com/NawrotLab/larvaworld-move/commit/3f9abb26a296854b206509ac9b6bc3d644889c97))
- Extend model inspector layout and live preview ([`19112ab`](https://github.com/NawrotLab/larvaworld-move/commit/19112ab56f81f669167186ae61e7756f2353e20c))

## v2.3.0 (2026-06-01)

### Fix

- Preserve dataset coordinate origins ([`97c7d7e`](https://github.com/NawrotLab/larvaworld-move/commit/97c7d7eba5f191dd29a8b6313a442304d3201b5d))
- Include replay arena metadata helpers ([`2413044`](https://github.com/NawrotLab/larvaworld-move/commit/24130444d1b0e8fdd2d61edf555bbd6911a9a188))
- Merge optional modules into model inspector summary ([`6720ac0`](https://github.com/NawrotLab/larvaworld-move/commit/6720ac06642f6221d11dd22d8dc88520c932364d))
- Make dataset replay sections boxes ([`41c189e`](https://github.com/NawrotLab/larvaworld-move/commit/41c189e3959865e1bbb45e117e7fbc82b792967c))
- Make dataset replay time range pygame-only ([`21486f8`](https://github.com/NawrotLab/larvaworld-move/commit/21486f8b3f6fc84b5d8a4f2c1e7508791da129f8))
- Disable unsupported native replay members ([`1858f79`](https://github.com/NawrotLab/larvaworld-move/commit/1858f794fe302319a1d4c8cdc1572c0c346f0e4f))
- Restore replay segment selection ([`ccdbe59`](https://github.com/NawrotLab/larvaworld-move/commit/ccdbe595b66c7fcd900d48f41c640e5d46570958))
- Restore larva-group dirty-state tracking ([`171c63b`](https://github.com/NawrotLab/larvaworld-move/commit/171c63b20e00868125f54b28a0e3353b20d18ba6))
- Stabilize replay and experiment summaries ([`6f5463c`](https://github.com/NawrotLab/larvaworld-move/commit/6f5463ce268012524b47da2d11d0a611a78fb873))
- Preserve dynamic template items on reload ([`8ee3941`](https://github.com/NawrotLab/larvaworld-move/commit/8ee39412de82734c9797b826b40614167f341cbd))
- Improve display shortcuts capture and popup styling ([`ef9c895`](https://github.com/NawrotLab/larvaworld-move/commit/ef9c895a93ce472c3bf6f4a16461ea973de87cf2))
- Improve single experiment status dialog formatting ([`7be5e10`](https://github.com/NawrotLab/larvaworld-move/commit/7be5e10175b5ec91a4dbb848bb4fbc3f686df076))
- Align circle envelope and allow legacy registry warnings ([`18298d9`](https://github.com/NawrotLab/larvaworld-move/commit/18298d901073158250c235b537798cb285b523c7))
- Stabilize workspace experiment template load/edit flow ([`e6adb61`](https://github.com/NawrotLab/larvaworld-move/commit/e6adb615f7780b456134324004811bd82225e17a))
- Disable head snapping by default in canvas preview ([`d1d2115`](https://github.com/NawrotLab/larvaworld-move/commit/d1d2115e4a30eb0f99c601c984757b941cfb8bbd))
- Stabilize experiment preset selection and runtime defaults ([`0e434b8`](https://github.com/NawrotLab/larvaworld-move/commit/0e434b880a140b78e69404311489a95e22844bce))
- Wire source group legend renderer ([`008a526`](https://github.com/NawrotLab/larvaworld-move/commit/008a5264102cdb6d0e14777ca37a8d41556e91fb))
- Harden intermitter state helpers ([`865293b`](https://github.com/NawrotLab/larvaworld-move/commit/865293b73b629b7838c9bdbf80a020fce5304c50))

### Refactor

- Arrange import environment controls ([`fb36f35`](https://github.com/NawrotLab/larvaworld-move/commit/fb36f354c9b09dd06a3d28b8a7fd63419533e936))
- Reuse replay param metadata ([`348d152`](https://github.com/NawrotLab/larvaworld-move/commit/348d1529ee08413792873489f2b9c6b15692463d))
- Share display shortcuts runtime helper ([`573ad0e`](https://github.com/NawrotLab/larvaworld-move/commit/573ad0ed1975789b2b40a82543582469415afc70))
- Remove legacy single experiment preview ([`2498a6e`](https://github.com/NawrotLab/larvaworld-move/commit/2498a6ef7cda735b9c0e81a110c5d9c75862f8c8))
- Improve single experiment parameters layout ([`aba7852`](https://github.com/NawrotLab/larvaworld-move/commit/aba7852a3b1bbefdf0cdacb9f71120dc74998877))

### Feature

- Refine import layout and replay support ([`fd6d66c`](https://github.com/NawrotLab/larvaworld-move/commit/fd6d66cd76c4490194410c5370327acbfcf3affa))
- Refine model inspector layout and validation ([`501edaa`](https://github.com/NawrotLab/larvaworld-move/commit/501edaa8223fbdc9f2091bed10571ed1301d5526))
- Finish model inspector persistence ([`6814144`](https://github.com/NawrotLab/larvaworld-move/commit/681414434b6a6245ad730822159ec06972f3f35f))
- Add native replay close inspection controls ([`e7a49e6`](https://github.com/NawrotLab/larvaworld-move/commit/e7a49e6ca60d25177523e5528c427e80b20803ae))
- Render larva contours and split canvas legends ([`13862c1`](https://github.com/NawrotLab/larvaworld-move/commit/13862c1d53f93c1a8570285aa0bff44fc8d8a0df))
- Draw larva body segments in simulation preview ([`78f8290`](https://github.com/NawrotLab/larvaworld-move/commit/78f8290ef42cf7a82b009219d4774e3d966c1057))
- Add agent index filtering and strict track-point selection ([`0410419`](https://github.com/NawrotLab/larvaworld-move/commit/041041908782b66e78e5f57262aa8c0310f0120b))
- Extend dataset replay for simulation runs ([`387eca0`](https://github.com/NawrotLab/larvaworld-move/commit/387eca042c864fc75f684de4ba1b4454ab45adf4))
- Make model inspector live-editable ([`752e014`](https://github.com/NawrotLab/larvaworld-move/commit/752e01453dddbc76ffe5c751aade87129b19ddd8))
- Migrate larva_models to parity-first model inspector ([`682ccee`](https://github.com/NawrotLab/larvaworld-move/commit/682cceec138ddff566556de357d9f95ee6d8a27c))
- Add dataset replay app and migrate track_viewer route ([`8386a85`](https://github.com/NawrotLab/larvaworld-move/commit/8386a85f1e309293c5a52f9b5b24b99527c3a8ae))
- Add workspace editable display shortcuts ([`9f4a28d`](https://github.com/NawrotLab/larvaworld-move/commit/9f4a28d23582083ebc1593e892cafab9fce66d51))
- Validate food source compatibility in single experiment ([`acc150e`](https://github.com/NawrotLab/larvaworld-move/commit/acc150eb38f6f00c7cdfad2b75056f17210224a9))
- Validate single experiment environment compatibility ([`1dea9e3`](https://github.com/NawrotLab/larvaworld-move/commit/1dea9e30fd081ea7ddacde76664742c3ee5584c2))
- Integrate experiment template preset controls ([`c6a0634`](https://github.com/NawrotLab/larvaworld-move/commit/c6a063418c761d727ce1beac4a83c5b4f5ad498a))
- Integrate env preset controls into single experiment ([`0e8107b`](https://github.com/NawrotLab/larvaworld-move/commit/0e8107b2512219a3ff76266aff9574f268fd0c19))
- Add generic registry/workspace preset controls ([`eb04124`](https://github.com/NawrotLab/larvaworld-move/commit/eb041241856ddf85fa08dbd350af4cf646161a1f))
- Remap workspace folders and refine single experiment ux ([`3f6d5c7`](https://github.com/NawrotLab/larvaworld-move/commit/3f6d5c765c3c5ca5f126c0bcf322cfa14f249704))
- Wire typed trials editor ([`7120876`](https://github.com/NawrotLab/larvaworld-move/commit/7120876f3554e51d7b1eedb44029f9763b060cbc))
- Wire typed collections editor ([`02bc538`](https://github.com/NawrotLab/larvaworld-move/commit/02bc538c3a6f8020ed4a5bbcee9305b529268bad))
- Wire typed simulation settings editor ([`a2a3e01`](https://github.com/NawrotLab/larvaworld-move/commit/a2a3e01ad6d9b3ca90d1fb6e51ae660ba8149884))
- Wire typed env params editor in single experiment ([`f464af7`](https://github.com/NawrotLab/larvaworld-move/commit/f464af700c26f3cd485b693c52030c83de1d993b))
- Wire typed enrichment editor in single experiment ([`8f78cd5`](https://github.com/NawrotLab/larvaworld-move/commit/8f78cd5a33121857020dc09bf1f619e76a9890ba))
- Wire typed larva_groups editor in single experiment ([`966ca36`](https://github.com/NawrotLab/larvaworld-move/commit/966ca36090d6d7bc0da47338441160bb45bbda7a))
- Add param-driven larva group helpers ([`dc08371`](https://github.com/NawrotLab/larvaworld-move/commit/dc0837102337e46a2dfdca7ba874f117b7ff1311))
- Refine single experiment preview visuals ([`e91afe8`](https://github.com/NawrotLab/larvaworld-move/commit/e91afe8121cbada386ced7b50ff3e393c69ee833))
- Polish single experiment preview controls ([`e5428d2`](https://github.com/NawrotLab/larvaworld-move/commit/e5428d253a8342dc88dec12ab33bef1b37c2e533))
- Add frame-based single experiment preview ([`7cc339c`](https://github.com/NawrotLab/larvaworld-move/commit/7cc339c0eaf779a418b55f5347b18b256f3138fa))
- Add larva preview frame capture helper ([`99feb21`](https://github.com/NawrotLab/larvaworld-move/commit/99feb21d877de9032d76d1c44151dd8777094359))
- Add simulated larvae canvas playback layer ([`c9e21dc`](https://github.com/NawrotLab/larvaworld-move/commit/c9e21dc8343099690e0665c95a4f9e538ad51c5b))
- Refine single experiment canvas preview layers ([`d67b48a`](https://github.com/NawrotLab/larvaworld-move/commit/d67b48a3a95091dda8d84db2f3a41908704324e8))
- Add shared environment canvas preview ([`d8f5622`](https://github.com/NawrotLab/larvaworld-move/commit/d8f5622490c5bfaca6d27b1b6c0019e2ea22740f))
- Refine import and simulation previews ([`bf3a8a9`](https://github.com/NawrotLab/larvaworld-move/commit/bf3a8a9a981ae64cd3250db2f6b75d44d34be8ac))

### Performance

- Make dataset replay geometry tick-local ([`d1afa8d`](https://github.com/NawrotLab/larvaworld-move/commit/d1afa8d32d0a8010162165c4a939d66fb5f5c46a))
- Optimize live display rendering ([`2a74b19`](https://github.com/NawrotLab/larvaworld-move/commit/2a74b19fd1d6be3521f7d34dce040b738dee0c06))

### Test

- Update preset integration assertions for tokenized flow ([`41e179a`](https://github.com/NawrotLab/larvaworld-move/commit/41e179a28f397f4a907ed7ed5f5d2b943a2748d1))
- Add env params typed roundtrip contracts ([`c112e1c`](https://github.com/NawrotLab/larvaworld-move/commit/c112e1c7554d9e09e0df4c062c352b69046c186f))
- Align environment preset labels with reverted behavior ([`a0ef347`](https://github.com/NawrotLab/larvaworld-move/commit/a0ef34732b5e9990668418ced3fb4a19fbc4fada))

### Style

- Apply ruff formatting to single experiment updates ([`19258f1`](https://github.com/NawrotLab/larvaworld-move/commit/19258f181ee5195d42dbae270e1949f999ed2781))

## v2.2.0 (2026-04-28)

### Test

- Remove unsupported ga conftype widget case ([`0b34ed7`](https://github.com/NawrotLab/larvaworld-move/commit/0b34ed71fd62020d8ea2be4a343d947999f114ee))
- Normalize import adapter path assertions ([`16ee822`](https://github.com/NawrotLab/larvaworld-move/commit/16ee82217a8deaf492d539aca88adec1cc7e424a))

### Documentation

- Update web applications guide ([`6600ef3`](https://github.com/NawrotLab/larvaworld-move/commit/6600ef3a874253a0f9a14fdfceac4f6ad80e686b))
- Update installation and optional deps ([`b286045`](https://github.com/NawrotLab/larvaworld-move/commit/b286045a815c4347962779ee686cc2902f6e52bd))

### Feature

- Integrate milestone m2 apps ([`be5a517`](https://github.com/NawrotLab/larvaworld-move/commit/be5a517fd282fc7280e555a4d2e24aa7e64c76d3))
- Add import config widget families ([`13bdb17`](https://github.com/NawrotLab/larvaworld-move/commit/13bdb17d74de7c2328523b8598e9e584de4e4c34))
- Add config widget helpers and demo app ([`b08ff7e`](https://github.com/NawrotLab/larvaworld-move/commit/b08ff7e61c2e04dcfc2180f7093da5586ad74eca))
- Add dataset manager and lane housing ([`2b2405f`](https://github.com/NawrotLab/larvaworld-move/commit/2b2405f51175b34e18513c7a71837f5389d4c4db))
- Refine dataset import app workflow ui ([`a78cf77`](https://github.com/NawrotLab/larvaworld-move/commit/a78cf7777ed3b97c842c6d395e06cfa4d4c65fa9))
- Share source directory picker ([`c1413e2`](https://github.com/NawrotLab/larvaworld-move/commit/c1413e211431f3c294bb26e0411ad8b55d103a76))
- Add experimental dataset import app ([`f99ff2e`](https://github.com/NawrotLab/larvaworld-move/commit/f99ff2e703687c5b724dd1dcf89b372a52a6bca4))
- Add workspace-first dataset adapters ([`8084330`](https://github.com/NawrotLab/larvaworld-move/commit/8084330884f3164e52cc4ac11a1944bda0bed4d1))
- Refine environment builder editor workflows ([`b8acd79`](https://github.com/NawrotLab/larvaworld-move/commit/b8acd79adacbad2247992f06c0a09351b50e500d))
- Harden environment builder presets and validation ([`b8aa71e`](https://github.com/NawrotLab/larvaworld-move/commit/b8aa71e878e231df80e0542ab52d7a364ac965fe))
- Refine environment builder and experiment ui ([`5351752`](https://github.com/NawrotLab/larvaworld-move/commit/5351752cdb68f8aa95f64d00f6f4ba9939557da7))
- Refine previews and environment editing ([`d1cd111`](https://github.com/NawrotLab/larvaworld-move/commit/d1cd111903c9e650d677f29edd5cec00b8d6461a))
- Add single experiment workflow ([`617ed36`](https://github.com/NawrotLab/larvaworld-move/commit/617ed3645468d3a2c730bc26b3430d5c7849828f))
- Expand environment builder workflow ([`cc96631`](https://github.com/NawrotLab/larvaworld-move/commit/cc96631b88eed10d7ea9c81cef255d7658ff7e33))
- Enforce workspace-first startup flow ([`9b5ffad`](https://github.com/NawrotLab/larvaworld-move/commit/9b5ffad9158e864a667e856913f2f8e006978e64))
- Add shared workspace management ([`b848c8e`](https://github.com/NawrotLab/larvaworld-move/commit/b848c8e683a66103c1041dd70d18b88654f4e719))
- Add gui_v2 desktop shell scaffold ([`82fc291`](https://github.com/NawrotLab/larvaworld-move/commit/82fc291c2ece855af532878fbf4a304bb92a9a03))
- Add rotating gif showcase banner on landing ([`e2ac5a1`](https://github.com/NawrotLab/larvaworld-move/commit/e2ac5a13af7618c4cf099a36bf18a983682cd0e0))
- Add quick-start modes and bootstrap loading flow ([`62ae008`](https://github.com/NawrotLab/larvaworld-move/commit/62ae008b08c63255bd14cd4af4627eddd78c41e3))
- Add environment builder app and startup loader ([`d38ea23`](https://github.com/NawrotLab/larvaworld-move/commit/d38ea23f20e36fd95a814c3ddbacc9053a9bbcc1))
- Remove demos lane and add persistent footer ([`b7f0eb3`](https://github.com/NawrotLab/larvaworld-move/commit/b7f0eb3327fa3b2db40ec1f532e20d77fd0bbbf9))
- Harden notebook launch flow and lane-styled notebook actions ([`db96de4`](https://github.com/NawrotLab/larvaworld-move/commit/db96de4d19a5876428f4ddd5a4456ff78fb655bf))
- Add tutorial notebook actions with workspace copies ([`0d28070`](https://github.com/NawrotLab/larvaworld-move/commit/0d28070ebecefaac7e9de0f412017355acdf4028))
- Add lane accents and stronger hover tint ([`f79ad47`](https://github.com/NawrotLab/larvaworld-move/commit/f79ad47c70e2f464965560fc76b727a1d7107d54))
- Add demo entrypoint and serve wiring ([`1cb02a7`](https://github.com/NawrotLab/larvaworld-move/commit/1cb02a7e3e152f6b996cd5bcd42a3dad33342a9e))
- Add landing and preview apps ([`b4c2a77`](https://github.com/NawrotLab/larvaworld-move/commit/b4c2a778f598e6cae24ab1b72b478b44e0f8a5c2))
- Add registry core and smoke tests ([`57b1ad8`](https://github.com/NawrotLab/larvaworld-move/commit/57b1ad828215db6cebc0fee2aae391c8481bf6af))

### Fix

- Reset lab format registry from import app ([`1206931`](https://github.com/NawrotLab/larvaworld-move/commit/1206931894fbfa9e35d1e41660cca3dee419e931))
- Stabilize import environment and tracker config ([`72d1b4a`](https://github.com/NawrotLab/larvaworld-move/commit/72d1b4ad6250a79756acd07d6a32e91e750c9be8))
- Stabilize portal regressions and arena edge cases ([`c86cdaf`](https://github.com/NawrotLab/larvaworld-move/commit/c86cdafd4745d8d98b63bf00707761e46fbf3b9f))
- Refine environment builder interactions ([`5faab32`](https://github.com/NawrotLab/larvaworld-move/commit/5faab32f833a40d68c51fee68a810820cf89b585))
- Correct quick-start tab layering and active styling ([`611305b`](https://github.com/NawrotLab/larvaworld-move/commit/611305bf374d20b40d45d3b4f0d377f1ea7e1d89))
- Restore full-tile click overlay navigation ([`dedc2ba`](https://github.com/NawrotLab/larvaworld-move/commit/dedc2ba7c279dab9115466b3336d12aa9f0150d7))
- Enforce unique lane membership ([`062be56`](https://github.com/NawrotLab/larvaworld-move/commit/062be564a01080190e31cf7a872ef20ceecacdec))

### Refactor

- Refine environment builder and portal cleanup ([`1e22ccd`](https://github.com/NawrotLab/larvaworld-move/commit/1e22ccd217325949a219c9e2c26417f9030ba04d))
- Remove demo mode and preview route ([`c7aa023`](https://github.com/NawrotLab/larvaworld-move/commit/c7aa023962637bd559ea8695515441a3438fce3d))

### Build

- Refresh poetry lockfile ([`ecd1546`](https://github.com/NawrotLab/larvaworld-move/commit/ecd1546d9979152a2b758a91c3918c920a39640c))

### Style

- Polish header layout and settings dropdown ([`abd3573`](https://github.com/NawrotLab/larvaworld-move/commit/abd35730f5f7d976fc5992c92ee9603ead8e06fa))
- Keep grid layout panel-controlled ([`adf01de`](https://github.com/NawrotLab/larvaworld-move/commit/adf01de6c8e6c47ee25e31859769769a41f372e1))

## v2.1.1 (2026-01-13)

### Documentation

- Update tutorials and visualization guides ([`89af527`](https://github.com/NawrotLab/larvaworld-move/commit/89af527dae6c6824200f36f1647e0d2b78bf63a8))
- Align docs examples with v2.1.0 api ([`8030d2c`](https://github.com/NawrotLab/larvaworld-move/commit/8030d2caeaf50d43cf80a21384d0f4ddf0ff7e98))

### Fix

- Sync examples with code and harden eval plots ([`c6b8cc5`](https://github.com/NawrotLab/larvaworld-move/commit/c6b8cc5adb89985d842e3ead23863de078a43e56))

## v2.1.0 (2025-12-21)

### Documentation

- Add summary of all pr-4c changes to unreleased section ([`c47fcdc`](https://github.com/NawrotLab/larvaworld-move/commit/c47fcdc7e5eb2b2811f74ac897009b46c366ad7d))
- Add type examples and improve commit message documentation ([`bda3604`](https://github.com/NawrotLab/larvaworld-move/commit/bda3604831fc411b6a639a25459cbead3cced4ea))
- Remove codecov, poetry, and ruff badges from readme ([`7576a79`](https://github.com/NawrotLab/larvaworld-move/commit/7576a79e7e3b6f0ade06bdfb5d4ff3d4a16c73ae))
- Fix module-level constant docstrings for autoapi ([`8911126`](https://github.com/NawrotLab/larvaworld-move/commit/8911126ba30ffb89da0af07d73b33bb5860432f5))
- Update first publication link in publications page ([`6972912`](https://github.com/NawrotLab/larvaworld-move/commit/6972912dc787e25791a2ace39cce4992bea1438a))
- Add publications page and clarify cli argument order ([`d7cf5c2`](https://github.com/NawrotLab/larvaworld-move/commit/d7cf5c2a08765d03201ac8bf07f0c3cb8efc8f7b))

### Feature

- Python 3.12 &amp; 3.13 support, collision handling fixes, and code cleanup ([`0842aaf`](https://github.com/NawrotLab/larvaworld-move/commit/0842aafab994111d3db825243e9704ddfe8acb8d))
- Add storage directory feedback and update python 3.10-3.13 docs ([`e5e975b`](https://github.com/NawrotLab/larvaworld-move/commit/e5e975bbec53cfa08865f59637543242de9f31f2))

### Build

- Add imageio[ffmpeg] extra and use reg.default_refid ([`45897f1`](https://github.com/NawrotLab/larvaworld-move/commit/45897f1485bff45b0ee02114f7e71248cc5500d7))

### Fix

- Panel compatibility and add python 3.13 support ([`68cc0d0`](https://github.com/NawrotLab/larvaworld-move/commit/68cc0d0660d58f4a9b0766c97c0a7b34e9ee1658))
- Python 3.12 support and collision handling fixes ([`e1da5fc`](https://github.com/NawrotLab/larvaworld-move/commit/e1da5fc9da4dc0cd40e838c1522a4acab636d39a))
- Align timer baseline across time components ([`299eb59`](https://github.com/NawrotLab/larvaworld-move/commit/299eb59ecd5cf0b2090321ebbe4ca1ca3c0ef3db))

### Refactor

- Remove deprecation warnings and strict import checks ([`2e80eaf`](https://github.com/NawrotLab/larvaworld-move/commit/2e80eafe9d62a431d947997f4ec1e712c64acc6b))

## v2.0.1 (2025-11-25)

### Fix

- Improve installation docs, ci workflow, and simulation handling ([`670f66b`](https://github.com/NawrotLab/larvaworld-move/commit/670f66b74c37cfd5a20d3e29534b7aef88302592))
- Improve simulation window handling and pause feedback ([`304ce80`](https://github.com/NawrotLab/larvaworld-move/commit/304ce807e3ae5f202653b3ce24ce9568e9f15286))
- Properly detect linting errors vs formatting changes ([`679821c`](https://github.com/NawrotLab/larvaworld-move/commit/679821cfd268c9732a276d05cce04661750ee53f))
- Correct has_changes variable check in lint job ([`484bb00`](https://github.com/NawrotLab/larvaworld-move/commit/484bb0041fcb941fbaaaf800854c4ef1fefb8b0f))
- Broken documentation references to tutorials/index ([`6b3a41c`](https://github.com/NawrotLab/larvaworld-move/commit/6b3a41c6f815f7d46c9f5eb1b647771256ae1c9e))
- Simulation termination and visualization documentation ([`6b56f91`](https://github.com/NawrotLab/larvaworld-move/commit/6b56f91a3f316739e828ad5bb91f0eae6c75db38))

### Documentation

- Expand video examples ([`f13ee97`](https://github.com/NawrotLab/larvaworld-move/commit/f13ee97575a02f93dd4bf4ad2a7c6ca7fe18ba04))
- Hide tutorials toctree from main page, keep in sidebar ([`c9537ec`](https://github.com/NawrotLab/larvaworld-move/commit/c9537ec6cd622c694243b0aac925e1a3f569ac73))
- Remove :hidden: from tutorials toctree to show in sidebar ([`a473fdd`](https://github.com/NawrotLab/larvaworld-move/commit/a473fddb298aae15fcbdd827173e8bf4a28e98df))
- Restore tutorial subsections structure with .rst files ([`8aad1a5`](https://github.com/NawrotLab/larvaworld-move/commit/8aad1a5bb3b532b50d66ce8709fb51bcf564f9c3))
- Create tutorial subsections with index files (configuration, simulation, data, development) ([`a27d098`](https://github.com/NawrotLab/larvaworld-move/commit/a27d098dde933ec959e0ccabb945d4f2bdfade10))
- Organize tutorials into subsections (configuration, simulation, data, development) ([`6f60d95`](https://github.com/NawrotLab/larvaworld-move/commit/6f60d958b302c50ffdbae3dbae361cfba0819338))
- Remove duplicate myst_parser extension (included in myst_nb) ([`c2e63d1`](https://github.com/NawrotLab/larvaworld-move/commit/c2e63d1c1380d15a74e5e31c5c6278f2952b3de5))
- Switch from nbsphinx to myst_nb and add pygments style ([`76ffea2`](https://github.com/NawrotLab/larvaworld-move/commit/76ffea2de6bfd9046f14b21592986d2797bc0f40))
- Switch to sphinx_rtd_theme and rename autoapi entry ([`e92eac0`](https://github.com/NawrotLab/larvaworld-move/commit/e92eac0062d325426c5daf141e570a6f7e1caf3c))
- Fix sidebar navigation and use default furo theme ([`6597030`](https://github.com/NawrotLab/larvaworld-move/commit/659703028960614eb45c47d6c06401c97bc38767))
- Reorganize concepts and index ([`4d6a563`](https://github.com/NawrotLab/larvaworld-move/commit/4d6a56347080b4afed96ec63d64b87491f4ce016))

### Refactor

- Documentation improvements, ci enhancements, and test marker refactoring ([`838b554`](https://github.com/NawrotLab/larvaworld-move/commit/838b55431584b9aa9c0ba18ce89a87fe79c09b0d))
- Rename pytest marker from &#39;slow&#39; to &#39;heavy&#39; ([`333de3c`](https://github.com/NawrotLab/larvaworld-move/commit/333de3cfd726c6edfb05c67f494e53baacc673e9))

### Build

- Refresh poetry.lock ([`f7c491b`](https://github.com/NawrotLab/larvaworld-move/commit/f7c491b92806c75b132726d2170970f14e0e7e1e))
- Refresh poetry.lock ([`37e167f`](https://github.com/NawrotLab/larvaworld-move/commit/37e167fa2ce68f7605a5a525ea14387541daddce))

## v2.0.0 (2025-11-22)

### Style

- Apply pre-commit formatting fixes ([`b2b9071`](https://github.com/NawrotLab/larvaworld-move/commit/b2b9071e674536b9b08c540733edaf5febd28400))

### Fix

- Update poetry.lock to include sphinxcontrib-mermaid ([`ac9eb33`](https://github.com/NawrotLab/larvaworld-move/commit/ac9eb33869d3814105e467fbfabdc5d860cd940a))

### Documentation

- Major documentation overhaul with sphinx/readthedocs setup ([`e453018`](https://github.com/NawrotLab/larvaworld-move/commit/e453018e6576c1806ba7294ea044d5ac1baccb59))
- Update license to mit and fix python version constraints ([`8f136f8`](https://github.com/NawrotLab/larvaworld-move/commit/8f136f8efb889a4bed72ef6816a3c9f797373851))

### Breaking

- Complete package modernization (phases 1-4) (#3) ([`188bfb7`](https://github.com/NawrotLab/larvaworld-move/commit/188bfb7643c3c33fb62d8af52ba033473c5984a5))

## v1.0.0 (2025-05-08)

### Feature

- Start semver at 1.0.0 (#35) ([`f532b66`](https://github.com/NawrotLab/larvaworld-move/commit/f532b6653ad0a5bba8111194c99ec87f2e7e3efe))

## v0.1.0 (2025-05-08)

### Fix

- Semantic versioning ([`a224d62`](https://github.com/NawrotLab/larvaworld-move/commit/a224d62c2792ec195a8c95885b0f82f10d9f0c4e))
- Semantic versioning ([`a6c3929`](https://github.com/NawrotLab/larvaworld-move/commit/a6c3929f2a588fdee0e8ba90f8ff0537f0ba37b4))

## v0.1.0-rc.1 (2025-04-22)

### Fix

- Run venv test only on linux ([`cb2bcee`](https://github.com/NawrotLab/larvaworld-move/commit/cb2bcee20be0205db39d88bb0b8750d3c9e2fed8))
- Remove importlib dependency ([`a065475`](https://github.com/NawrotLab/larvaworld-move/commit/a06547572c2fac881e16172519c1b6ac2339e1a2))
- Add missing docopts dependency ([`248611c`](https://github.com/NawrotLab/larvaworld-move/commit/248611cc3fc478cabd93d0059c474ef96741645b))

### Feature

- Add venv install test to github action ([`edd69f5`](https://github.com/NawrotLab/larvaworld-move/commit/edd69f503754dda864236356cda3cc7c4cc06b49))
- Add venv install test to github action ([`09f218f`](https://github.com/NawrotLab/larvaworld-move/commit/09f218f14b4b9fc65e1fe152604facc7a81099bf))
- Add example code for remote brian interface and tutorial notebook ([`00e0b0c`](https://github.com/NawrotLab/larvaworld-move/commit/00e0b0ca88c0a21f099e048c30dd0a3feeec15bc))
- Add tutorial notebooks on library interface and custom modules ([`ec1dbd5`](https://github.com/NawrotLab/larvaworld-move/commit/ec1dbd5cd2c41af9f9fea01dac2ca76dd9dfccca))

## v0.0.1-rc.1 (2024-11-24)

### Fix

- Use master instead of main branch ([`a1d054b`](https://github.com/NawrotLab/larvaworld-move/commit/a1d054ba24ea5c1c8dab525a6b45be3678cbde47))
