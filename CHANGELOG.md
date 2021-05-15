# Changelog

## v2.9.5 (2020-08-06)

 * [5759a0e1](https://github.com/argoproj/argo-workflows/commit/5759a0e198d333fa8c3e0aeee433d93808c0dc72) Update manifests to v2.9.5
 * [53d20462](https://github.com/argoproj/argo-workflows/commit/53d20462fe506955306cafccb86e969dfd4dd040) codegen
 * [c0382fd9](https://github.com/argoproj/argo-workflows/commit/c0382fd97d58c66b55eacbe2d05d473ecc93a5d9) remove line
 * [18cf4ea6](https://github.com/argoproj/argo-workflows/commit/18cf4ea6c15264f4db053a5d4d7ae1b478216fc0) fix: Enforce metric Help must be the same for each metric Name (#3613)
 * [7b4e98a8](https://github.com/argoproj/argo-workflows/commit/7b4e98a8d9e50d829feff75ad593ca3ac231ab5a) fix: Fix 'malformed request: field selector' error (#3636)
 * [0fceb627](https://github.com/argoproj/argo-workflows/commit/0fceb6274ac26b01d30d806978b532a7f675ea5b) fix: Fix panic and provide better error message on watch endpoint (#3605)
 * [8a7e9d3d](https://github.com/argoproj/argo-workflows/commit/8a7e9d3dc23749bbe7ed415c5e45abcd2fc40a92) fix(controller): Fix bug in util/RecoverWorkflowNameFromSelectorString. Add error handling (#3596)
 * [2ba24334](https://github.com/argoproj/argo-workflows/commit/2ba2433405643e845c521b9351fbfe14f9042195) fix: Re-introduce 1 second sleep to reconcile informer (#3684)
 * [dca3b6ce](https://github.com/argoproj/argo-workflows/commit/dca3b6ce275e2cc880ba92e58045e462cdf84671) fix(controller): Adds ALL_POD_CHANGES_SIGNIFICANT (#3689)
 * [819bfdb6](https://github.com/argoproj/argo-workflows/commit/819bfdb63c3abc398998af727f4e3fa8923a9497) fix: Avoid overriding the Workflow parameter when it is merging with WorkflowTemplate parameter (#3651)
 * [89e05bdb](https://github.com/argoproj/argo-workflows/commit/89e05bdb884029e7ad681089b11e1c8e9a38a3a7) fix: Don't panic on invalid template creation (#3643)
 * [0b8d78e1](https://github.com/argoproj/argo-workflows/commit/0b8d78e160800f23da9f793aee7fa57f601cd591) fix: Simplify the WorkflowTemplateRef field validation to support all fields in WorkflowSpec except `Templates` (#3632)

### Contributors

 * Alex Collins
 * Remington Breeze
 * Saravanan Balasubramanian
 * Simon Behar

## v2.9.4 (2020-07-24)

 * [20d2ace3](https://github.com/argoproj/argo-workflows/commit/20d2ace3d5344db68ce1bc2a250bbb1ba9862613) Update manifests to v2.9.4
 * [41db5525](https://github.com/argoproj/argo-workflows/commit/41db552549490caa9de2f9fa66521eb20a3263f3) Fix build
 * [58778559](https://github.com/argoproj/argo-workflows/commit/5877855904b23b5c139778c0ea6ffec1a337dc0b) Fix build
 * [f047ddf3](https://github.com/argoproj/argo-workflows/commit/f047ddf3b69f283ce72204377119d1724ea1059d) fix: Fix flakey TestRetryOmitted (#3552)
 * [b6ad88e2](https://github.com/argoproj/argo-workflows/commit/b6ad88e2cf8fdd4c457958131cd2aa236b8b3e03) fix: Fix when retrying Workflows with Omitted nodes (#3528)
 * [79599820](https://github.com/argoproj/argo-workflows/commit/7959982012f8dbe18f8ed7e38cf6f88f466da00d) fix: Panic on CLI Watch command (#3532)
 * [eaa815f1](https://github.com/argoproj/argo-workflows/commit/eaa815f1f353c7e192b81119fa2b12da8481658b) Fixed Packer and Hydrator test
 * [71c7f64e](https://github.com/argoproj/argo-workflows/commit/71c7f64e15fb347e33accdca0afd853e791f6d37) Fixed test failure
 * [f0e8a332](https://github.com/argoproj/argo-workflows/commit/f0e8a3326ddd025aedf6d740a994c028445321d3) fix: Merge WorkflowTemplateRef with defaults workflow spec (#3480)
 * [b03498be](https://github.com/argoproj/argo-workflows/commit/b03498be6c6b78fa467b1b6f5456d3668923d1b5) chore: Fix GitHub Actions Docker Image build  (#3442)
 * [bf138662](https://github.com/argoproj/argo-workflows/commit/bf138662ce6621d6692cca4a6bbb6b475dda7c57) chore: Use GitHub Actions to build Docker Images to allow publishing Windows Images (#3291)

### Contributors

 * Markus Lippert
 * Saravanan Balasubramanian
 * Simon Behar

## v2.9.3 (2020-07-14)

 * [9407e19b](https://github.com/argoproj/argo-workflows/commit/9407e19b3a1c61ad4043e382484fd0b6b15574f2) Merge branch 'release-2.9' of github.com:argoproj/argo into release-2.9
 * [d597af5c](https://github.com/argoproj/argo-workflows/commit/d597af5c13caf3b1d150da9cd27b0917db5b1644) Update manifests to v2.9.3
 * [d1a2ffd9](https://github.com/argoproj/argo-workflows/commit/d1a2ffd9b77e41657692ee2e70818dd51c1bd4e8) fix: Pass resolved arguments to onExit handler (#3482)
 * [a52c371c](https://github.com/argoproj/argo-workflows/commit/a52c371cbc375d91c3a56127da1c4875924cfe83) test: Removed flakey image tag check
 * [06a695e9](https://github.com/argoproj/argo-workflows/commit/06a695e9726aebdeb4752786d0ed64031dc76333) ci: v2.9.2
 * [1818b0a9](https://github.com/argoproj/argo-workflows/commit/1818b0a912a5f435ecbdfd24d3e0c8540238bd18) ci: make codegen fetch tags
 * [7d49f6a4](https://github.com/argoproj/argo-workflows/commit/7d49f6a4d8957fcdfa164f17590d81ffc82cc095) ci: Fix
 * [2376707c](https://github.com/argoproj/argo-workflows/commit/2376707c5330225b988e0aff1466cdcfd7cf410a) ci: Checkout tags
 * [54b24ff7](https://github.com/argoproj/argo-workflows/commit/54b24ff7d3e7d775fb71d26a96e8c4d729ca8fda) ci: Checkout tags
 * [2b706247](https://github.com/argoproj/argo-workflows/commit/2b706247fd81215e49edb539bd7d26ea62b69fd0) Revert "fix: Pass resolved arguments to onExit handler (#3477)"
 * [a431f93c](https://github.com/argoproj/argo-workflows/commit/a431f93cdabb01f4acf29a6a190737e259611ef2) fix: Pass resolved arguments to onExit handler (#3477)
 * [f394d571](https://github.com/argoproj/argo-workflows/commit/f394d5710239e43257ae31c09b7ce3530d71b10f) ci: Fix
 * [052efb47](https://github.com/argoproj/argo-workflows/commit/052efb479ab25c78ff4e8d6d71031bbb7ddfd3a8) ci: Fix
 * [52bb1471](https://github.com/argoproj/argo-workflows/commit/52bb1471e22ed25f5a8a4819d622556155e3de36) fix: Metric emission with retryStrategy (#3470)
 * [1766a019](https://github.com/argoproj/argo-workflows/commit/1766a019ae54543836f3b19be099ad2de587fc4d) build: Better VERSION logic
 * [7c6d8aa6](https://github.com/argoproj/argo-workflows/commit/7c6d8aa68e17f31712d2cf6f7ff38fc9468e76bb) build: Fix
 * [cf811286](https://github.com/argoproj/argo-workflows/commit/cf8112868cac213e21c2924c332b5564997e8b6e) ci: Attempt to fix
 * [e10a5bd7](https://github.com/argoproj/argo-workflows/commit/e10a5bd714c039555a2f7a8ed6cea58a54ea8471) ci: Capture logs
 * [07292ebe](https://github.com/argoproj/argo-workflows/commit/07292ebea9c20041673469a9e48c0bc13e9da9f9) build: mkdir -p dist
 * [505a6478](https://github.com/argoproj/argo-workflows/commit/505a64789329b46abc0990378cc764ffeda35c1d) build: Sync Github Action from master
 * [675ce293](https://github.com/argoproj/argo-workflows/commit/675ce293f41200bad96d4a66a31923a2cbe3b46c) fix(controller): Correct fail workflow when pod is deleted with --force. Fixes #3097 (#3469)
 * [194a2139](https://github.com/argoproj/argo-workflows/commit/194a21392e656af46952deedf39b276fc0ba774c) fix(controller): Respect the volumes of a workflowTemplateRef. Fixes … (#3451)
 * [584cb402](https://github.com/argoproj/argo-workflows/commit/584cb402c4057de79198dcb0e82de6337e6ea138) fix(controller): Port master fix for #3214
 * [065d9b65](https://github.com/argoproj/argo-workflows/commit/065d9b65109bb37c6147c4f87c7468434cbc70ed) test(controller): Add memoization tests. See #3214 (#3455) (#3466)
 * [b252b408](https://github.com/argoproj/argo-workflows/commit/b252b4085f58d3210cbe81ec986097398e48257b) test(controller): Add memoization tests. See #3214 (#3455)
 * [e3a8319b](https://github.com/argoproj/argo-workflows/commit/e3a8319be1b081e07252a241cd807486c27eddfa) fix(controller): Prevent panic on nil node. Fixes #3436 (#3437)

### Contributors

 * Alex Collins
 * Simon Behar

## v2.9.2 (2020-07-08)

 * [65c2bd44](https://github.com/argoproj/argo-workflows/commit/65c2bd44e45c11e0a0b03adeef8d6800b72cd551) merge Dockerfile from master
 * [14942f2f](https://github.com/argoproj/argo-workflows/commit/14942f2f940e1ee6f182a269a29691d4169d3160) Update manifests to v2.9.2
 * [823f9c54](https://github.com/argoproj/argo-workflows/commit/823f9c5499bd60dc5b9df6ce0c12f7295f72d294) Fix botched conflict resolution
 * [2b3ccd3a](https://github.com/argoproj/argo-workflows/commit/2b3ccd3a0ad8810e861696a7b97e84489ae4ed2a) fix: Add struct-wide RWMutext to metrics (#3421)
 * [8e9ba494](https://github.com/argoproj/argo-workflows/commit/8e9ba49401851603a1c154992cb22a87ff8430a3) fix: Use a unique queue to visit nodes (#3418)
 * [28f76572](https://github.com/argoproj/argo-workflows/commit/28f76572bc80b8582210549b1a67987ec812e7c5) conflict resolved
 * [dcc09c98](https://github.com/argoproj/argo-workflows/commit/dcc09c983414671ae303c0111e39cf544d787ed8) fix: No panic on watch. Fixes #3411 (#3426)
 * [4a48e25f](https://github.com/argoproj/argo-workflows/commit/4a48e25fcdb110ef788a1d63f20163ec88a330c2) fix(sso): Remove unused `groups` claim. Fixes #3411 (#3427)
 * [1e736b23](https://github.com/argoproj/argo-workflows/commit/1e736b23c92c9cb45b23ff44b144271d19ffe728) fix: panic on wait command if event is null (#3424)
 * [c10da5ec](https://github.com/argoproj/argo-workflows/commit/c10da5ecf7d0bb490b0ee4edaf985eeab7f42a2e) fix: Ensure non-leaf DAG tasks have their onExit handler's run (#3403)
 * [25b150aa](https://github.com/argoproj/argo-workflows/commit/25b150aa86a3539121fd72e4a942f250d4d263dc) fix(ui): Render DAG with exit node (#3408)
 * [6378a587](https://github.com/argoproj/argo-workflows/commit/6378a587bc6900b2074f35205039eec453fd8051) fix: Fix concurrency issues with metrics (#3401)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.9.1 (2020-07-03)

 * [6b967d08](https://github.com/argoproj/argo-workflows/commit/6b967d08c0a142aaa278538f2407c28de467262e) Update manifests to v2.9.1
 * [6bf5fb3c](https://github.com/argoproj/argo-workflows/commit/6bf5fb3c9de77de1629f059459bdce4f304e8d55) fix: Running pods are garaged in PodGC onSuccess
 * [d67d3b1d](https://github.com/argoproj/argo-workflows/commit/d67d3b1dbc61ebc5789806794ccd7e2debd71ffc) Update manifests to v2.9.0
 * [9c52c1be](https://github.com/argoproj/argo-workflows/commit/9c52c1be2aaa317720b6e2c1bae20d7489f45f14) fix: Don't double-count metric events (#3350)
 * [813122f7](https://github.com/argoproj/argo-workflows/commit/813122f765d47529cfe4e7eb25499ee98051abd6) fix: Fix UI bug in DAGs (#3368)
 * [248643d3](https://github.com/argoproj/argo-workflows/commit/248643d3b5ad4a93adef081afd73ee931ee76dae) fix: Ensure child pods respect maxDuration (#3280)
 * [71d29584](https://github.com/argoproj/argo-workflows/commit/71d295849ba4ffa3a2e7e843c952f3330fb4160a) fix(controller): Allow events to be sent to non-argo namespace. Fixes #3342 (#3345)
 * [52be71bc](https://github.com/argoproj/argo-workflows/commit/52be71bc7ab5ddf56aab65570ee78a2c40b852b6) fix: Remove broken SSO from quick-starts (#3327)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.9.0-rc4 (2020-06-26)

 * [5b109bcb](https://github.com/argoproj/argo-workflows/commit/5b109bcb9257653ecbae46e6315c8d65842de58a) Update manifests to v2.9.0-rc4
 * [36cbcfb6](https://github.com/argoproj/argo-workflows/commit/36cbcfb65ae33e58ef9b56c71f360c7dbc52326e) docs: Document access token creation and usage (#3316)
 * [00ad29bd](https://github.com/argoproj/argo-workflows/commit/00ad29bd0c9d59f99f786cd921e4b371fe116009) docs: Rename Ant Financial to Ant Group (#3304)
 * [011f1368](https://github.com/argoproj/argo-workflows/commit/011f1368d11abadc1f3bad323067007eea71b9bc) fix(controller): Fix panic logging. (#3315)
 * [9f934496](https://github.com/argoproj/argo-workflows/commit/9f9344960e74e15bf20138d2875bea3a1019a54f) build: Pin `goimports` to working version (#3311)
 * [888c9b8a](https://github.com/argoproj/argo-workflows/commit/888c9b8ac0d1a19af2b789f062a12dc26ade0a82) ci: Remove CircleCI (#3302)
 * [f7e13a3d](https://github.com/argoproj/argo-workflows/commit/f7e13a3dafc4800d02a90ac232fcfeb192173f68) build: Remove generated Swagger files. (#3297)
 * [5395ad3f](https://github.com/argoproj/argo-workflows/commit/5395ad3f9ad938e334f29dc27e4aa105c17f1c58) Clean up unused constants (#3298)
 * [2bb2cdf0](https://github.com/argoproj/argo-workflows/commit/2bb2cdf02402b9978ff87b01695ebef2127db4c1) build: Upload E2E diagnostics after failure (#3294)
 * [a2a1fba8](https://github.com/argoproj/argo-workflows/commit/a2a1fba8bf981aff0a9467368fd87cc0c5325de6) fix: Reapply Update if CronWorkflow resource changed (#3272)
 * [9af98a5b](https://github.com/argoproj/argo-workflows/commit/9af98a5bc141872d2fd55db8182674fb950c9ce1) Fixes validation of overridden ref template parameters. (#3286)
 * [dc65faa9](https://github.com/argoproj/argo-workflows/commit/dc65faa91ebe9fe845e637cb5616d16f90ce5e17) docs: Updated WorkflowTemplateRef  on WFT and CWFT (#3137)
 * [86401ba4](https://github.com/argoproj/argo-workflows/commit/86401ba468677b93f937e5480f02acecb39d109e) docs: ArchiveLabelSelector document (#3284)
 * [cce666b7](https://github.com/argoproj/argo-workflows/commit/cce666b77962045323c91184d3bb2043086a63fa) docs: Add example for handling large output resutls (#3276)
 * [a91cea5f](https://github.com/argoproj/argo-workflows/commit/a91cea5f087153553760f2d1f63413c7e78ab4ba) fix: Fix delete --complete (#3278)
 * [d5a4807a](https://github.com/argoproj/argo-workflows/commit/d5a4807aefed6d1df0296aabd2e4e6a7a7de32f1) Update releasing.md (#3283)

### Contributors

 * Alex Collins
 * Michael Crenshaw
 * Saravanan Balasubramanian
 * Simon Behar
 * Vlad Losev
 * Yuan Tang

## v2.9.0-rc3 (2020-06-23)

 * [2e95ff48](https://github.com/argoproj/argo-workflows/commit/2e95ff4843080e7fd673cf0a551a862e3e39d326) Update manifests to v2.9.0-rc3
 * [61ca07e2](https://github.com/argoproj/argo-workflows/commit/61ca07e21a774387e87865a1f7d3d73040a9fb5e) Merge branch 'master' into release-2.9
 * [acee573b](https://github.com/argoproj/argo-workflows/commit/acee573b88bf96160b69d18bcc8031caf119c647) docs: Update CI Badges (#3282)
 * [9eb182c0](https://github.com/argoproj/argo-workflows/commit/9eb182c04957f2ca587ff1de84b79fc274f91788) build: Allow to change k8s namespace for installation (#3281)
 * [2bcfafb5](https://github.com/argoproj/argo-workflows/commit/2bcfafb56230194fd2d23adcfa5a1294066ec91e) fix: Add {{workflow.status}} to workflow-metrics (#3271)
 * [e6aab605](https://github.com/argoproj/argo-workflows/commit/e6aab605122356a10cb21df3a08e1ddeac6d2593) fix(jqFilter)!: remove extra quotes around output parameter value (#3251)
 * [f4580163](https://github.com/argoproj/argo-workflows/commit/f4580163f4187f798f93b8d778415e8bec001dda) fix(ui): Allow render of templates without entrypoint. Fixes #2891 (#3274)
 * [f30c05c7](https://github.com/argoproj/argo-workflows/commit/f30c05c74f598b6400b66bb20a752d78eca05e45) build: Add warning to ensure 'v' is present on release versions (#3273)
 * [d1cb1992](https://github.com/argoproj/argo-workflows/commit/d1cb1992cd22e9f69894532f214fa0e00312ff36) fixed archiveLabelSelector nil (#3270)
 * [c7e4c180](https://github.com/argoproj/argo-workflows/commit/c7e4c1808cf097857b8ee89d326ef9f32384fc1b) fix(ui): Update workflow drawer with new duration format (#3256)
 * [f2381a54](https://github.com/argoproj/argo-workflows/commit/f2381a5448e9d49a7b6ed0c9583ac8cf9b257938) fix(controller): More structured logging. Fixes #3260 (#3262)
 * [acba084a](https://github.com/argoproj/argo-workflows/commit/acba084abb01b967c239952d49e8e3d7775cbf2c) fix: Avoid unnecessary nil check for annotations of resubmitted workflow (#3268)
 * [55e13705](https://github.com/argoproj/argo-workflows/commit/55e13705ae57f86ca6c5846eb5de3e80370bc1d4) feat: Append previous workflow name as label to resubmitted workflow (#3261)
 * [2dae7244](https://github.com/argoproj/argo-workflows/commit/2dae724496a96ce2e0993daea0a3b6a473f784da) feat: Add mode to require Workflows to use workflowTemplateRef (#3149)
 * [56694abe](https://github.com/argoproj/argo-workflows/commit/56694abe27267c1cb855064b44bc7c32d61ca66c) Fixed onexit on workflowtempalteRef (#3263)
 * [54dd72c2](https://github.com/argoproj/argo-workflows/commit/54dd72c2439b5a6ef389eab4cb39bd412db9fd42) update mysql yaml port (#3258)
 * [fb502632](https://github.com/argoproj/argo-workflows/commit/fb502632419409e528e23f1ef70e7f610812d175) feat: Configure ArchiveLabelSelector for Workflow Archive (#3249)
 * [5467c899](https://github.com/argoproj/argo-workflows/commit/5467c8995e07e5501d685384e44585fc1b02c6b8) fix(controller): set pod finish timestamp when it is deleted (#3230)
 * [04bc5492](https://github.com/argoproj/argo-workflows/commit/04bc5492d582d45633a4a18ec691a10d913a73a3) build: Disable Circle CI and Sonar (#3253)
 * [23ca07a7](https://github.com/argoproj/argo-workflows/commit/23ca07a790714ad8c97ecab71ffa439843a7ad6c) chore: Covered steps.<STEPNAME>.outputs.parameters in variables document (#3245)
 * [4bd33c6c](https://github.com/argoproj/argo-workflows/commit/4bd33c6c6ce6dcb9f0c85dab40f162608d5f67a6) chore(cli): Add examples of @latest alias for relevant commands. Fixes #3225 (#3242)
 * [17108df1](https://github.com/argoproj/argo-workflows/commit/17108df1cea937f49f099ec26b7a25bd376b16a5) fix: Ensure subscription is closed in log viewer (#3247)
 * [495dc89b](https://github.com/argoproj/argo-workflows/commit/495dc89b5cfb2419b0438c4a53cfb3b13cb5785a) docs: Correct available fields in {{workflow.failures}} (#3238)

### Contributors

 * Alex Collins
 * Ben Ye
 * Jie Zhang
 * Pierre Houssin
 * Remington Breeze
 * Saravanan Balasubramanian
 * Simon Behar
 * Yuan Tang
 * mark9white

## v2.9.0-rc2 (2020-06-16)

 * [abf02c3b](https://github.com/argoproj/argo-workflows/commit/abf02c3ba143cbd9f2d42f286b86fa80ed0ecb5b) Update manifests to v2.9.0-rc2
 * [8fdbfe58](https://github.com/argoproj/argo-workflows/commit/8fdbfe58d10c4c97c8949e89d7011b3bb175c961) Merge branch 'master' into release-2.9
 * [4db1c4c8](https://github.com/argoproj/argo-workflows/commit/4db1c4c8495d0b8e13c718207175273fe98555a2) fix: Support the TTLStrategy for WorkflowTemplateRef (#3239)
 * [47f50693](https://github.com/argoproj/argo-workflows/commit/47f5069376f3c61b09ff02ff5729e5c3e6e58e45) feat(logging): Made more controller err/warn logging structured (#3240)
 * [c25e2880](https://github.com/argoproj/argo-workflows/commit/c25e28809863435d718d7e5ab303591d8039c724) build: Migrate to Github Actions (#3233)
 * [ef159f9a](https://github.com/argoproj/argo-workflows/commit/ef159f9ad6be552de1abf58c3dc4dc6911c49733) feat: Tick CLI Workflow watch even if there are no new events (#3219)
 * [ff1627b7](https://github.com/argoproj/argo-workflows/commit/ff1627b71789c42f604c0f83a9a3328d7e6b8248) fix(events): Adds config flag. Reduce number of dupe events emitted. (#3205)
 * [eae8f681](https://github.com/argoproj/argo-workflows/commit/eae8f68144acaf5c2ec0145ef0d136097cca7fcc) feat: Validate CronWorkflows before execution (#3223)
 * [4470a8a2](https://github.com/argoproj/argo-workflows/commit/4470a8a29bca9e16ac7e5d7d8c8a2310d0200efa) fix(ui/server): Fix broken label filter functionality on UI due to bug on server. Fix #3226 (#3228)
 * [e5e6456b](https://github.com/argoproj/argo-workflows/commit/e5e6456be37b52856205c4f7600a05ffef6daab1) feat(cli): Add --latest flag for argo get command as per #3128 (#3179)
 * [34608594](https://github.com/argoproj/argo-workflows/commit/34608594b98257c4ae47a280831d462bab7c53b4) fix(ui): Correctly update workflow list when workflow are modified/deleted (#3220)
 * [a7d8546c](https://github.com/argoproj/argo-workflows/commit/a7d8546cf9515ea70d686b8c669bf0a1d9b7538d) feat(controller): Improve throughput of many workflows. Fixes #2908 (#2921)
 * [a37d0a72](https://github.com/argoproj/argo-workflows/commit/a37d0a729c206040463d41e88e09814c1bf622dd) build: Change "DB=..." to "PROFILE=..." (#3216)
 * [15885d3e](https://github.com/argoproj/argo-workflows/commit/15885d3edc6d4754bc66f950251450eea8f29170) feat(sso): Allow reading SSO clientID from a secret. (#3207)
 * [723e9d5f](https://github.com/argoproj/argo-workflows/commit/723e9d5f40448ae425631fac8af2863a1f1ff1f5) fix: Ensrue image name is present in containers (#3215)

### Contributors

 * Alex Collins
 * Remington Breeze
 * Saravanan Balasubramanian
 * Simon Behar
 * Vlad Losev

## v2.9.0-rc1 (2020-06-10)


### Contributors


## v2.9.0 (2020-07-01)

 * [d67d3b1d](https://github.com/argoproj/argo-workflows/commit/d67d3b1dbc61ebc5789806794ccd7e2debd71ffc) Update manifests to v2.9.0
 * [9c52c1be](https://github.com/argoproj/argo-workflows/commit/9c52c1be2aaa317720b6e2c1bae20d7489f45f14) fix: Don't double-count metric events (#3350)
 * [813122f7](https://github.com/argoproj/argo-workflows/commit/813122f765d47529cfe4e7eb25499ee98051abd6) fix: Fix UI bug in DAGs (#3368)
 * [248643d3](https://github.com/argoproj/argo-workflows/commit/248643d3b5ad4a93adef081afd73ee931ee76dae) fix: Ensure child pods respect maxDuration (#3280)
 * [71d29584](https://github.com/argoproj/argo-workflows/commit/71d295849ba4ffa3a2e7e843c952f3330fb4160a) fix(controller): Allow events to be sent to non-argo namespace. Fixes #3342 (#3345)
 * [52be71bc](https://github.com/argoproj/argo-workflows/commit/52be71bc7ab5ddf56aab65570ee78a2c40b852b6) fix: Remove broken SSO from quick-starts (#3327)
 * [5b109bcb](https://github.com/argoproj/argo-workflows/commit/5b109bcb9257653ecbae46e6315c8d65842de58a) Update manifests to v2.9.0-rc4
 * [36cbcfb6](https://github.com/argoproj/argo-workflows/commit/36cbcfb65ae33e58ef9b56c71f360c7dbc52326e) docs: Document access token creation and usage (#3316)
 * [00ad29bd](https://github.com/argoproj/argo-workflows/commit/00ad29bd0c9d59f99f786cd921e4b371fe116009) docs: Rename Ant Financial to Ant Group (#3304)
 * [011f1368](https://github.com/argoproj/argo-workflows/commit/011f1368d11abadc1f3bad323067007eea71b9bc) fix(controller): Fix panic logging. (#3315)
 * [9f934496](https://github.com/argoproj/argo-workflows/commit/9f9344960e74e15bf20138d2875bea3a1019a54f) build: Pin `goimports` to working version (#3311)
 * [888c9b8a](https://github.com/argoproj/argo-workflows/commit/888c9b8ac0d1a19af2b789f062a12dc26ade0a82) ci: Remove CircleCI (#3302)
 * [f7e13a3d](https://github.com/argoproj/argo-workflows/commit/f7e13a3dafc4800d02a90ac232fcfeb192173f68) build: Remove generated Swagger files. (#3297)
 * [5395ad3f](https://github.com/argoproj/argo-workflows/commit/5395ad3f9ad938e334f29dc27e4aa105c17f1c58) Clean up unused constants (#3298)
 * [2bb2cdf0](https://github.com/argoproj/argo-workflows/commit/2bb2cdf02402b9978ff87b01695ebef2127db4c1) build: Upload E2E diagnostics after failure (#3294)
 * [a2a1fba8](https://github.com/argoproj/argo-workflows/commit/a2a1fba8bf981aff0a9467368fd87cc0c5325de6) fix: Reapply Update if CronWorkflow resource changed (#3272)
 * [9af98a5b](https://github.com/argoproj/argo-workflows/commit/9af98a5bc141872d2fd55db8182674fb950c9ce1) Fixes validation of overridden ref template parameters. (#3286)
 * [dc65faa9](https://github.com/argoproj/argo-workflows/commit/dc65faa91ebe9fe845e637cb5616d16f90ce5e17) docs: Updated WorkflowTemplateRef  on WFT and CWFT (#3137)
 * [86401ba4](https://github.com/argoproj/argo-workflows/commit/86401ba468677b93f937e5480f02acecb39d109e) docs: ArchiveLabelSelector document (#3284)
 * [cce666b7](https://github.com/argoproj/argo-workflows/commit/cce666b77962045323c91184d3bb2043086a63fa) docs: Add example for handling large output resutls (#3276)
 * [a91cea5f](https://github.com/argoproj/argo-workflows/commit/a91cea5f087153553760f2d1f63413c7e78ab4ba) fix: Fix delete --complete (#3278)
 * [d5a4807a](https://github.com/argoproj/argo-workflows/commit/d5a4807aefed6d1df0296aabd2e4e6a7a7de32f1) Update releasing.md (#3283)
 * [2e95ff48](https://github.com/argoproj/argo-workflows/commit/2e95ff4843080e7fd673cf0a551a862e3e39d326) Update manifests to v2.9.0-rc3
 * [61ca07e2](https://github.com/argoproj/argo-workflows/commit/61ca07e21a774387e87865a1f7d3d73040a9fb5e) Merge branch 'master' into release-2.9
 * [acee573b](https://github.com/argoproj/argo-workflows/commit/acee573b88bf96160b69d18bcc8031caf119c647) docs: Update CI Badges (#3282)
 * [9eb182c0](https://github.com/argoproj/argo-workflows/commit/9eb182c04957f2ca587ff1de84b79fc274f91788) build: Allow to change k8s namespace for installation (#3281)
 * [2bcfafb5](https://github.com/argoproj/argo-workflows/commit/2bcfafb56230194fd2d23adcfa5a1294066ec91e) fix: Add {{workflow.status}} to workflow-metrics (#3271)
 * [e6aab605](https://github.com/argoproj/argo-workflows/commit/e6aab605122356a10cb21df3a08e1ddeac6d2593) fix(jqFilter)!: remove extra quotes around output parameter value (#3251)
 * [f4580163](https://github.com/argoproj/argo-workflows/commit/f4580163f4187f798f93b8d778415e8bec001dda) fix(ui): Allow render of templates without entrypoint. Fixes #2891 (#3274)
 * [f30c05c7](https://github.com/argoproj/argo-workflows/commit/f30c05c74f598b6400b66bb20a752d78eca05e45) build: Add warning to ensure 'v' is present on release versions (#3273)
 * [d1cb1992](https://github.com/argoproj/argo-workflows/commit/d1cb1992cd22e9f69894532f214fa0e00312ff36) fixed archiveLabelSelector nil (#3270)
 * [c7e4c180](https://github.com/argoproj/argo-workflows/commit/c7e4c1808cf097857b8ee89d326ef9f32384fc1b) fix(ui): Update workflow drawer with new duration format (#3256)
 * [f2381a54](https://github.com/argoproj/argo-workflows/commit/f2381a5448e9d49a7b6ed0c9583ac8cf9b257938) fix(controller): More structured logging. Fixes #3260 (#3262)
 * [acba084a](https://github.com/argoproj/argo-workflows/commit/acba084abb01b967c239952d49e8e3d7775cbf2c) fix: Avoid unnecessary nil check for annotations of resubmitted workflow (#3268)
 * [55e13705](https://github.com/argoproj/argo-workflows/commit/55e13705ae57f86ca6c5846eb5de3e80370bc1d4) feat: Append previous workflow name as label to resubmitted workflow (#3261)
 * [2dae7244](https://github.com/argoproj/argo-workflows/commit/2dae724496a96ce2e0993daea0a3b6a473f784da) feat: Add mode to require Workflows to use workflowTemplateRef (#3149)
 * [56694abe](https://github.com/argoproj/argo-workflows/commit/56694abe27267c1cb855064b44bc7c32d61ca66c) Fixed onexit on workflowtempalteRef (#3263)
 * [54dd72c2](https://github.com/argoproj/argo-workflows/commit/54dd72c2439b5a6ef389eab4cb39bd412db9fd42) update mysql yaml port (#3258)
 * [fb502632](https://github.com/argoproj/argo-workflows/commit/fb502632419409e528e23f1ef70e7f610812d175) feat: Configure ArchiveLabelSelector for Workflow Archive (#3249)
 * [5467c899](https://github.com/argoproj/argo-workflows/commit/5467c8995e07e5501d685384e44585fc1b02c6b8) fix(controller): set pod finish timestamp when it is deleted (#3230)
 * [04bc5492](https://github.com/argoproj/argo-workflows/commit/04bc5492d582d45633a4a18ec691a10d913a73a3) build: Disable Circle CI and Sonar (#3253)
 * [23ca07a7](https://github.com/argoproj/argo-workflows/commit/23ca07a790714ad8c97ecab71ffa439843a7ad6c) chore: Covered steps.<STEPNAME>.outputs.parameters in variables document (#3245)
 * [4bd33c6c](https://github.com/argoproj/argo-workflows/commit/4bd33c6c6ce6dcb9f0c85dab40f162608d5f67a6) chore(cli): Add examples of @latest alias for relevant commands. Fixes #3225 (#3242)
 * [17108df1](https://github.com/argoproj/argo-workflows/commit/17108df1cea937f49f099ec26b7a25bd376b16a5) fix: Ensure subscription is closed in log viewer (#3247)
 * [495dc89b](https://github.com/argoproj/argo-workflows/commit/495dc89b5cfb2419b0438c4a53cfb3b13cb5785a) docs: Correct available fields in {{workflow.failures}} (#3238)
 * [abf02c3b](https://github.com/argoproj/argo-workflows/commit/abf02c3ba143cbd9f2d42f286b86fa80ed0ecb5b) Update manifests to v2.9.0-rc2
 * [8fdbfe58](https://github.com/argoproj/argo-workflows/commit/8fdbfe58d10c4c97c8949e89d7011b3bb175c961) Merge branch 'master' into release-2.9
 * [4db1c4c8](https://github.com/argoproj/argo-workflows/commit/4db1c4c8495d0b8e13c718207175273fe98555a2) fix: Support the TTLStrategy for WorkflowTemplateRef (#3239)
 * [47f50693](https://github.com/argoproj/argo-workflows/commit/47f5069376f3c61b09ff02ff5729e5c3e6e58e45) feat(logging): Made more controller err/warn logging structured (#3240)
 * [c25e2880](https://github.com/argoproj/argo-workflows/commit/c25e28809863435d718d7e5ab303591d8039c724) build: Migrate to Github Actions (#3233)
 * [ef159f9a](https://github.com/argoproj/argo-workflows/commit/ef159f9ad6be552de1abf58c3dc4dc6911c49733) feat: Tick CLI Workflow watch even if there are no new events (#3219)
 * [ff1627b7](https://github.com/argoproj/argo-workflows/commit/ff1627b71789c42f604c0f83a9a3328d7e6b8248) fix(events): Adds config flag. Reduce number of dupe events emitted. (#3205)
 * [eae8f681](https://github.com/argoproj/argo-workflows/commit/eae8f68144acaf5c2ec0145ef0d136097cca7fcc) feat: Validate CronWorkflows before execution (#3223)
 * [4470a8a2](https://github.com/argoproj/argo-workflows/commit/4470a8a29bca9e16ac7e5d7d8c8a2310d0200efa) fix(ui/server): Fix broken label filter functionality on UI due to bug on server. Fix #3226 (#3228)
 * [e5e6456b](https://github.com/argoproj/argo-workflows/commit/e5e6456be37b52856205c4f7600a05ffef6daab1) feat(cli): Add --latest flag for argo get command as per #3128 (#3179)
 * [34608594](https://github.com/argoproj/argo-workflows/commit/34608594b98257c4ae47a280831d462bab7c53b4) fix(ui): Correctly update workflow list when workflow are modified/deleted (#3220)
 * [a7d8546c](https://github.com/argoproj/argo-workflows/commit/a7d8546cf9515ea70d686b8c669bf0a1d9b7538d) feat(controller): Improve throughput of many workflows. Fixes #2908 (#2921)
 * [a37d0a72](https://github.com/argoproj/argo-workflows/commit/a37d0a729c206040463d41e88e09814c1bf622dd) build: Change "DB=..." to "PROFILE=..." (#3216)
 * [15885d3e](https://github.com/argoproj/argo-workflows/commit/15885d3edc6d4754bc66f950251450eea8f29170) feat(sso): Allow reading SSO clientID from a secret. (#3207)
 * [723e9d5f](https://github.com/argoproj/argo-workflows/commit/723e9d5f40448ae425631fac8af2863a1f1ff1f5) fix: Ensrue image name is present in containers (#3215)
 * [c930d2ec](https://github.com/argoproj/argo-workflows/commit/c930d2ec6a5ab2a2473951c4500272181bc759be) Update manifests to v2.9.0-rc1
 * [0ee5e112](https://github.com/argoproj/argo-workflows/commit/0ee5e11253282eb5c36a5163086c20306cc09019) feat: Only process significant pod changes (#3181)
 * [c89a81f3](https://github.com/argoproj/argo-workflows/commit/c89a81f3ad3a76e22b98570a6045fd8eb358dbdb) feat: Add '--schedule' flag to 'argo cron create' (#3199)
 * [591f649a](https://github.com/argoproj/argo-workflows/commit/591f649a306edf826b667d0069ee04cb345dcd26) refactor: Refactor assesDAGPhase logic (#3035)
 * [285eda6b](https://github.com/argoproj/argo-workflows/commit/285eda6bbe9008ffa394edbc4b510e88119a1fd0) chore: Remove unused pod in addArchiveLocation() (#3200)
 * [8e1d56cb](https://github.com/argoproj/argo-workflows/commit/8e1d56cb78f8e039f4dbeea991bdaa1935738130) feat(controller): Add default name for artifact repository ref. (#3060)
 * [f1cdba18](https://github.com/argoproj/argo-workflows/commit/f1cdba18b3ef476e11f02e50a69fc33924158be7) feat(controller): Add `--qps` and `--burst` flags to controller (#3180)
 * [b86949f0](https://github.com/argoproj/argo-workflows/commit/b86949f0e9523e10c69e0f6b10b0f35413a20520) fix: Ensure stable desc/hash for metrics (#3196)
 * [e26d2f08](https://github.com/argoproj/argo-workflows/commit/e26d2f08c2d08dd83413b91a35e38ea6ed0d3839) docs: Update Getting Started (#3099)
 * [47bfea5d](https://github.com/argoproj/argo-workflows/commit/47bfea5d4e23d506c616fa8726c6bc751104bc94) docs: Add Graviti as official Argo user (#3187)
 * [04c77f49](https://github.com/argoproj/argo-workflows/commit/04c77f490b00ffc05f74a941f1c9ccf76a5bf789) fix(server): Allow field selection for workflow-event endpoint (fixes #3163) (#3165)
 * [0c38e66e](https://github.com/argoproj/argo-workflows/commit/0c38e66e619e243a5344f0f11a5e01194c7c5cb6) chore: Update Community Meeting link and specify Go@v1.13 (#3178)
 * [81846d41](https://github.com/argoproj/argo-workflows/commit/81846d416ecc84241ae8423d91280d6a39d9b4c2) build: Only check Dex in hosts file when SSO is enabled (#3177)
 * [a130d488](https://github.com/argoproj/argo-workflows/commit/a130d488ab69cf4d4d543c7348a45e4cd34f972e) feat(ui): Add drawer with more details for each workflow in Workflow List (#3151)
 * [fa84e203](https://github.com/argoproj/argo-workflows/commit/fa84e203239b35976210a441387d6480d951f034) fix: Do not use alphabetical order if index exists (#3174)
 * [138af597](https://github.com/argoproj/argo-workflows/commit/138af5977b81e619681eb2cfa20fd3891c752510) fix(cli): Sort expanded nodes by index. Closes #3145 (#3146)
 * [a9ec4d08](https://github.com/argoproj/argo-workflows/commit/a9ec4d08bf1e3a4b4ae55055011d5c64a1197bc0) docs: Fix api swagger file path in docs (#3167)
 * [c42e4d3a](https://github.com/argoproj/argo-workflows/commit/c42e4d3aeaf4093581d0a5d92b4d7750be205225) feat(metrics): Add node-level resources duration as Argo variable for metrics. Closes #3110 (#3161)
 * [e36fe66e](https://github.com/argoproj/argo-workflows/commit/e36fe66ee795fcde237360e593c34879873f0e36) docs: Add instructions on using Minikube as an alternative to K3D (#3162)
 * [edfa5b93](https://github.com/argoproj/argo-workflows/commit/edfa5b93fb58c0b243e1f019b92f02e846f7b83d) feat(metrics): Report controller error counters via metrics. Closes #3034 (#3144)
 * [8831e4ea](https://github.com/argoproj/argo-workflows/commit/8831e4ead39acfe3d49801271a95907a3b737d49) feat(argo-server): Add support for SSO. See #1813 (#2745)
 * [b62184c2](https://github.com/argoproj/argo-workflows/commit/b62184c2e3715fd7ddd9077e11513db25a512c93) feat(cli): More `argo list` and `argo delete` options (#3117)
 * [c6565d7c](https://github.com/argoproj/argo-workflows/commit/c6565d7c3c8c4b40c6725a1f682186e04e0a8f36) fix(controller): Maybe bug with nil woc.wfSpec. Fixes #3121 (#3160)
 * [06ca71d7](https://github.com/argoproj/argo-workflows/commit/06ca71d7a8b5f9ecc448006d3fae73baf88f9d18) build: Fix path to staticfiles and goreman binaries (#3159)
 * [cad84cab](https://github.com/argoproj/argo-workflows/commit/cad84cab7817141d259785f7565f82fd3c3dc540) chore: Remove unused nodeType in initializeNodeOrMarkError() (#3153)
 * [be425513](https://github.com/argoproj/argo-workflows/commit/be42551364ec9a792171588a662489ff32347ec1) chore: Master needs lint (#3152)
 * [70b56f25](https://github.com/argoproj/argo-workflows/commit/70b56f25baf78d67253a2f29bd4057279b0e9558) enhancement(ui): Add workflow labels column to workflow list. Fixes #2782 (#3143)
 * [3318c115](https://github.com/argoproj/argo-workflows/commit/3318c1152ac0654816e36c0b4eb8679c45b6250b) chore: Move default metrics server port/path to consts (#3135)
 * [a0062adf](https://github.com/argoproj/argo-workflows/commit/a0062adfe895ee39572db3aa6f259913279c6db3) feat(ui): Add Alibaba Cloud OSS related models in UI (#3140)
 * [1469991c](https://github.com/argoproj/argo-workflows/commit/1469991ce34333697df07ca750adb247b21cc3a9) fix: Update container delete grace period to match Kubernetes default (#3064)
 * [df725bbd](https://github.com/argoproj/argo-workflows/commit/df725bbddac2f3a216010b069363f0344a2f5a80) fix(ui): Input artifacts labelled in UI. Fixes #3098 (#3131)
 * [c0d59cc2](https://github.com/argoproj/argo-workflows/commit/c0d59cc283a62f111123728f70c24df5954d98e4) feat: Persist DAG rendering options in local storage (#3126)
 * [8715050b](https://github.com/argoproj/argo-workflows/commit/8715050b441f0fb5c84ae0a0a19695c89bf2e7b9) fix(ui): Fix label error (#3130)
 * [1814ea2e](https://github.com/argoproj/argo-workflows/commit/1814ea2e4a6702eacd567aefd1194bd6aec212ed) fix(item): Support ItemValue.Type == List. Fixes #2660 (#3129)
 * [12b72546](https://github.com/argoproj/argo-workflows/commit/12b72546eb49b8af5b4374577107f30484a6e975) fix: Panic on invalid WorkflowTemplateRef (#3127)
 * [09092147](https://github.com/argoproj/argo-workflows/commit/09092147cf26939e775848d75f687d5c8fc15aa9) fix(ui): Display error message instead of DAG when DAG cannot be rendered. Fixes #3091 (#3125)
 * [2d9a74de](https://github.com/argoproj/argo-workflows/commit/2d9a74de9b2ad28318dfb6bfdbc1db6f4db716db) docs: Document cost optimizations. Fixes #1139 (#2972)
 * [69c9e5f0](https://github.com/argoproj/argo-workflows/commit/69c9e5f053195e46871176c6a31d646144532c3a) fix: Remove unnecessary panic (#3123)
 * [2f3aca89](https://github.com/argoproj/argo-workflows/commit/2f3aca8988cee483f5fac116a8e99cdec7fd89cc) add AppDirect to the list of users (#3124)
 * [257355e4](https://github.com/argoproj/argo-workflows/commit/257355e4c54b8ca37e056e73718a112441faddb4) feat: Add 'submit --from' to CronWorkflow and WorkflowTemplate in UI. Closes #3112 (#3116)
 * [6e5dd2e1](https://github.com/argoproj/argo-workflows/commit/6e5dd2e19a3094f88e6f927f786f866eccc5f500) Add Alibaba OSS to the list of supported artifacts (#3108)
 * [1967b45b](https://github.com/argoproj/argo-workflows/commit/1967b45b1465693b71e3a0ccac9563886641694c) support sso (#3079)
 * [9229165f](https://github.com/argoproj/argo-workflows/commit/9229165f83011b3d5b867ac511793f8934bdcfab) feat(ui): Add cost optimisation nudges. (#3089)
 * [e88124db](https://github.com/argoproj/argo-workflows/commit/e88124dbf64128388cf0e6fa6d30b2f756e57d23) fix(controller): Do not panic of woc.orig in not hydrated. Fixes #3118 (#3119)
 * [132b947a](https://github.com/argoproj/argo-workflows/commit/132b947ad6ba5a5b81e281c469f08cb97748e42d) fix: Differentiate between Fulfilled and Completed (#3083)
 * [a93968ff](https://github.com/argoproj/argo-workflows/commit/a93968ff36a1472402ec9655458e6ad7b04401a8) docs: Document how to backfill a cron workflow (#3094)
 * [4de99746](https://github.com/argoproj/argo-workflows/commit/4de9974681034d7bb7223d2131eba1cd0e5d254d) feat: Added Label selector and Field selector in Argo list  (#3088)
 * [6229353b](https://github.com/argoproj/argo-workflows/commit/6229353b2355c9425f42509e3504e64ee7c7ae92) chore: goimports (#3107)
 * [8491e00f](https://github.com/argoproj/argo-workflows/commit/8491e00f31f1f744ee1af729e5598a7e8894ff5f) docs: Add link to USERS.md in PR template (#3086)
 * [bb2ce9f7](https://github.com/argoproj/argo-workflows/commit/bb2ce9f77894982f5bcae4e772795d0e679bf405) fix: Graceful error handling of malformatted log lines in watch (#3071)
 * [4fd27c31](https://github.com/argoproj/argo-workflows/commit/4fd27c314810ae43b39a5c2d36cef2dbbf5691af) build(swagger): Fix Swagger build problems (#3084)
 * [e4e0dfb6](https://github.com/argoproj/argo-workflows/commit/e4e0dfb6c66fd2c0dbbba240b1cfe8c12dcb93c2) test: fix TestContinueOnFailDag (#3101)
 * [fa69c1bb](https://github.com/argoproj/argo-workflows/commit/fa69c1bb7157e19755eea669bf44434e2bedd157) feat: Add CronWorkflowConditions to report errors (#3055)
 * [50ad3cec](https://github.com/argoproj/argo-workflows/commit/50ad3cec2b002b81e30a5d6975e7dc044a83b301) adds millisecond-level timestamps to argoexec (#2950)
 * [6464bd19](https://github.com/argoproj/argo-workflows/commit/6464bd199eff845da66d59d263f2d04479663020) fix(controller): Implement offloading for workflow updates that are re-applied. Fixes #2856 (#2941)
 * [6c369e61](https://github.com/argoproj/argo-workflows/commit/6c369e614281df0342d5cc46871551282da71ea9) chore: Rename files that include 'top-level' terminology (#3076)
 * [bd40b80b](https://github.com/argoproj/argo-workflows/commit/bd40b80bc0c6b81a824da04cbb892a5e93deeebb) docs: Document work avoidance. (#3066)
 * [6df0b2d3](https://github.com/argoproj/argo-workflows/commit/6df0b2d3538cd1525223c8d85581662ece172cf9) feat: Support Top level workflow template reference  (#2912)
 * [0709ad28](https://github.com/argoproj/argo-workflows/commit/0709ad28c3dbd4696404aa942478a7505e9e9a67) feat: Enhanced filters for argo {watch,get,submit} (#2450)
 * [784c1385](https://github.com/argoproj/argo-workflows/commit/784c1385f3bec1bacdc1ef80e223a33476696ed0) build: Use goreman for starting locally. (#3074)
 * [5b5bae9a](https://github.com/argoproj/argo-workflows/commit/5b5bae9a6e46a82f5830f68f87598ee0c7dc2ff7) docs: Add Isbank to users.md (#3068)
 * [2b038ed2](https://github.com/argoproj/argo-workflows/commit/2b038ed2e61781e5c4b8a796aba4c4afe4850305) feat: Enhanced depends logic (#2673)
 * [4c3387b2](https://github.com/argoproj/argo-workflows/commit/4c3387b273d802419a1552345dfb95dd05b8555b) fix: Linters should error if nothing was validated (#3011)
 * [51dd05b5](https://github.com/argoproj/argo-workflows/commit/51dd05b5f16e0554bdd33511f8332f3198604690) fix(artifacts): Explicit archive strategy. Fixes #2140 (#3052)
 * [ada2209e](https://github.com/argoproj/argo-workflows/commit/ada2209ef94e2380c4415cf19a8e321324650405) Revert "fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)" (#3047)
 * [b7ff9f09](https://github.com/argoproj/argo-workflows/commit/b7ff9f09c46c8f313378f7f6091260be4f6363e5) chore: Add ability to configure maximum DB connection lifetime (#3032)
 * [38a995b7](https://github.com/argoproj/argo-workflows/commit/38a995b749b83a76b5f1f2542df959898489210b) fix(executor): Properly handle empty resource results, like for a missing get (#3037)
 * [a1ac8bcf](https://github.com/argoproj/argo-workflows/commit/a1ac8bcf548c4f8fcff6b7df25aa61ad9e4c15ed) fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)
 * [f12d79ca](https://github.com/argoproj/argo-workflows/commit/f12d79cad9d4a9b2169f634183b6c7837c9e4615) fix(controller)!: Correctly format workflow.creationTimepstamp as RFC3339. Fixes #2974 (#3023)
 * [d10e949a](https://github.com/argoproj/argo-workflows/commit/d10e949a061de541f5312645dfa19c5732a302ff) fix: Consider metric nodes that were created and completed in the same operation (#3033)
 * [202d4ab3](https://github.com/argoproj/argo-workflows/commit/202d4ab31a2883d4f2448c309c30404f67761727) fix(executor): Optional input artifacts. Fixes #2990 (#3019)
 * [f17e946c](https://github.com/argoproj/argo-workflows/commit/f17e946c4d006cda4e161380fb5a0ba52dcebfd1) fix(executor): Save script results before artifacts in case of error. Fixes #1472 (#3025)
 * [3d216ae6](https://github.com/argoproj/argo-workflows/commit/3d216ae6d5ad96b996ce40c42793a2031a392bb1) fix: Consider missing optional input/output artifacts with same name (#3029)
 * [3717dd63](https://github.com/argoproj/argo-workflows/commit/3717dd636949e4a78e8a6ddee4320e6a98cc3c81) fix: Improve robustness of releases. Fixes #3004 (#3009)
 * [9f86a4e9](https://github.com/argoproj/argo-workflows/commit/9f86a4e941ecca4399267f7780fbb2e7ddcd2199) feat(ui): Enable CSP, HSTS, X-Frame-Options. Fixes #2760, #1376, #2761 (#2971)
 * [cb71d585](https://github.com/argoproj/argo-workflows/commit/cb71d585c73c72513aead057d570c279ba46e74b) refactor(metrics)!: Refactor Metric interface (#2979)
 * [c0ee1eb2](https://github.com/argoproj/argo-workflows/commit/c0ee1eb2293f268f6c56f343e77ff64480562f4a) docs: Add Ravelin as a user of Argo (#3020)
 * [052e6c51](https://github.com/argoproj/argo-workflows/commit/052e6c5197a6e8b4dfb14d18c2b923ca93fcb84c) Fix isTarball to handle the small gzipped file (#3014)
 * [cdcba3c4](https://github.com/argoproj/argo-workflows/commit/cdcba3c4d6849668238180903e59f37affdff01d) fix(ui): Displays command args correctl pre-formatted. (#3018)
 * [b5160988](https://github.com/argoproj/argo-workflows/commit/b516098804443b6741e9253cc211ddbf208898ab) build: Mockery v1.1.1 (#3015)
 * [a04d8f28](https://github.com/argoproj/argo-workflows/commit/a04d8f28b3028ebb3c9dacd525c563c448b19215) docs: Add StatefulSet and Service doc (#3008)
 * [8412526c](https://github.com/argoproj/argo-workflows/commit/8412526cb2d3675b4e9df5c0d4abb369eaf16380) docs: Fix Deprecated formatting (#3010)
 * [cc0fe433](https://github.com/argoproj/argo-workflows/commit/cc0fe433aebc0397c648ff4ddc8c1f99df042568) fix(events): Correct event API Version. Fixes #2994 (#2999)
 * [d5d6f750](https://github.com/argoproj/argo-workflows/commit/d5d6f750bf9324e8277fc0f05d8214b5dee255cd) feat(controller)!: Updates the resource duration calculation. Fixes #2934 (#2937)
 * [fa3801a5](https://github.com/argoproj/argo-workflows/commit/fa3801a5d89d58208f07977b73a8686e3aa2c3c9) feat(ui): Render 2000+ nodes DAG acceptably. (#2959)
 * [f952df51](https://github.com/argoproj/argo-workflows/commit/f952df517bae1f423063d61e7542c4f0c4c667e1) fix(executor/pns): remove sleep before sigkill (#2995)
 * [2a9ee21f](https://github.com/argoproj/argo-workflows/commit/2a9ee21f47dbd36ba1d2020d0939c73fc198b333) feat(ui): Add Suspend and Resume to CronWorkflows in UI (#2982)
 * [eefe120f](https://github.com/argoproj/argo-workflows/commit/eefe120f9f1e0fe5eb4876a24b00b1eb5147cebb) test: Upgrade to argosay:v2 (#3001)
 * [47472f73](https://github.com/argoproj/argo-workflows/commit/47472f73d9cec8ac601814a41388064185d2eae7) chore: Update Mockery (#3000)
 * [46b11e1e](https://github.com/argoproj/argo-workflows/commit/46b11e1eca9d25ab3dc936e959316ec587a86f52) docs: Use keyFormat instead of keyPrefix in docs (#2997)
 * [60d5fdc7](https://github.com/argoproj/argo-workflows/commit/60d5fdc7f91b675055ab0b1c7f450fa6feb0fac5) fix: Begin counting maxDuration from first child start (#2976)
 * [76aca493](https://github.com/argoproj/argo-workflows/commit/76aca4936290823c5fd0da0be8429e6d4d92efee) build: Fix Docker build. Fixes #2983 (#2984)
 * [d8cb66e7](https://github.com/argoproj/argo-workflows/commit/d8cb66e785c170030bd503ca4626ab4e6e4f8c6c) feat: Add Argo variable {{retries}} to track retry attempt (#2911)
 * [14b7a459](https://github.com/argoproj/argo-workflows/commit/14b7a459ec4ad58a3ae77c74c293a283cafdc33b) docs: Fix typo with WorkflowTemplates link (#2977)
 * [3c442232](https://github.com/argoproj/argo-workflows/commit/3c4422326dceea456df94a71270df80e9cbf7177) fix: Remove duplicate node event. Fixes #2961 (#2964)
 * [d8ab13f2](https://github.com/argoproj/argo-workflows/commit/d8ab13f24031eae58354b9ac1c59bad69968cbe6) fix: Consider Shutdown when assesing DAG Phase for incomplete Retry node (#2966)
 * [8a511e10](https://github.com/argoproj/argo-workflows/commit/8a511e109dc55d9f9c7b69614f110290c2536858) fix: Nodes with pods deleted out-of-band should be Errored, not Failed (#2855)
 * [ca4e08f7](https://github.com/argoproj/argo-workflows/commit/ca4e08f7ed861cf4e1d0a17617d210287ed83730) build: Build dev images from cache (#2968)
 * [5f01c4a5](https://github.com/argoproj/argo-workflows/commit/5f01c4a5945a9d89d5194efbbaaf1d4d2c40532d) Upgraded to Node 14.0.0 (#2816)
 * [849d876c](https://github.com/argoproj/argo-workflows/commit/849d876c835982bbfa814714e713b4d19b35148d) Fixes error with unknown flag: --show-all (#2960)
 * [93bf6609](https://github.com/argoproj/argo-workflows/commit/93bf6609cf407d6cd374a6dd3bc137b1c82e88df) fix: Don't update backoff message to save operations (#2951)
 * [3413a5df](https://github.com/argoproj/argo-workflows/commit/3413a5dfa7c29711d9bf0d227437a10bf0de9d3b) fix(cli): Remove info logging from watches. Fixes #2955 (#2958)
 * [fe9f9019](https://github.com/argoproj/argo-workflows/commit/fe9f90191fac2fb7909c8e0b31c5f3b5a31236c4) fix: Display Workflow finish time in UI (#2896)
 * [f281199a](https://github.com/argoproj/argo-workflows/commit/f281199a1df65a6716d29a8e29ba756aa31f36dc) docs: Update README with new features (#2807)
 * [c8bd0bb8](https://github.com/argoproj/argo-workflows/commit/c8bd0bb82e174cca8d733e7b75748273172efa37) fix(ui): Change default pagination to all and sort workflows (#2943)
 * [e3ed686e](https://github.com/argoproj/argo-workflows/commit/e3ed686e13eacf0174b3e1088fe3cf2eb7706b39) fix(cli): Re-establish watch on EOF (#2944)
 * [67355372](https://github.com/argoproj/argo-workflows/commit/673553729e12d4ad83387eba68b3cbfb0aea8fe4) fix(swagger)!: Fixes invalid K8S definitions in `swagger.json`. Fixes #2888 (#2907)
 * [023f2338](https://github.com/argoproj/argo-workflows/commit/023f233896ac90fdf1529f747c56ab19028b6a9c) fix(argo-server)!: Implement missing instanceID code. Fixes #2780 (#2786)
 * [7b0739e0](https://github.com/argoproj/argo-workflows/commit/7b0739e0b846cff7d2bc3340e88859ab655d25ff) Fix typo (#2939)
 * [20d69c75](https://github.com/argoproj/argo-workflows/commit/20d69c75662653523dc6276e7e57084ec1c7334f) Detect ctrl key when a link is clicked (#2935)
 * [f32cec31](https://github.com/argoproj/argo-workflows/commit/f32cec31027b7112a9a51069c2ad7b1cfbedd960) fix default null value for timestamp column - MySQL 5.7 (#2933)
 * [9773cfeb](https://github.com/argoproj/argo-workflows/commit/9773cfebcdcba9a6ab199c7001711c500f6f69a3) docs: Add docs/scaling.md (#2918)
 * [99858ea5](https://github.com/argoproj/argo-workflows/commit/99858ea53d79e964530f4a3840936d5da79585d9) feat(controller): Remove the excessive logging of node data (#2925)
 * [03ad694c](https://github.com/argoproj/argo-workflows/commit/03ad694c42a782dc9f45f7ff0ba94b32cbbfa2f1) feat(cli): Refactor `argo list --chunk-size` and add `argo archive list --chunk-size`. Fixes #2820 (#2854)
 * [1c45d5ea](https://github.com/argoproj/argo-workflows/commit/1c45d5eafe1c44b6dc53aba80ab3ef978db04afa) test: Use argoproj/argosay:v1 (#2917)
 * [f311a5a7](https://github.com/argoproj/argo-workflows/commit/f311a5a70a8f299f05363175e27afffc6772457b) build: Fix Darwin build (#2920)
 * [a06cb5e0](https://github.com/argoproj/argo-workflows/commit/a06cb5e0e02d7b480d20713e9c67f83d09fa2b24) fix: remove doubled entry in server cluster role deployment (#2904)
 * [c71116dd](https://github.com/argoproj/argo-workflows/commit/c71116ddedafde0f2931fbd489b9b17b8bd81e65) feat: Windows Container Support. Fixes #1507 and #1383 (#2747)
 * [3afa7b2f](https://github.com/argoproj/argo-workflows/commit/3afa7b2f1b4ecb9e64b2c9dee1e91dcf548f82c3) fix(ui): Use LogsViewer for container logs (#2825)
 * [9ecd5226](https://github.com/argoproj/argo-workflows/commit/9ecd522618b390b27c784092c3dc83e84785dcbb) docs: Document node field selector. Closes #2860 (#2882)
 * [7d8818ca](https://github.com/argoproj/argo-workflows/commit/7d8818ca2a335f5cb200d9b088305d032cacd020) fix(controller): Workflow stop and resume by node didn't properly support offloaded nodes. Fixes #2543 (#2548)
 * [e013f29d](https://github.com/argoproj/argo-workflows/commit/e013f29dd224a91023b5fc4cc9fed2879994ddb1) ci: Remove context to stop unauthozied errors on test jobs (#2910)
 * [db52e7ba](https://github.com/argoproj/argo-workflows/commit/db52e7bac649a7b101f846e7f7354d10a45c9e62) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)
 * [9a33aa2d](https://github.com/argoproj/argo-workflows/commit/9a33aa2d3c0ffedf33625bd3339c2006937c0953) docs(users): Adding Habx to the users list (#2781)
 * [9e4ac9b3](https://github.com/argoproj/argo-workflows/commit/9e4ac9b3c8c7028c9759278931a76c5f26481e53) feat(cli): Tolerate deleted workflow when running `argo delete`. Fixes #2821 (#2877)
 * [a0035dd5](https://github.com/argoproj/argo-workflows/commit/a0035dd58609d744a6fa304e51d61474f25c817d) fix: ConfigMap syntax (#2889)
 * [c05c3859](https://github.com/argoproj/argo-workflows/commit/c05c3859cf911502597456f5ed374c8604af85f0) ci: Build less and therefore faster (#2839)
 * [56143eb1](https://github.com/argoproj/argo-workflows/commit/56143eb1e1e80275da2742135ef147e563cae737) feat(ui): Add pagination to workflow list. Fixes #1080 and #976 (#2863)
 * [e0ad7de9](https://github.com/argoproj/argo-workflows/commit/e0ad7de97a82b2e509bb4bc8bb5fcf5b9c26dea3) test: Fixes various tests (#2874)
 * [e378ca47](https://github.com/argoproj/argo-workflows/commit/e378ca470f1a97d624d3aceb3c53b55155fd02a9) fix: Cannot create WorkflowTemplate with un-supplied inputs (#2869)
 * [c3e30c50](https://github.com/argoproj/argo-workflows/commit/c3e30c5052b9544d363c4c73315be5136b593f9a) fix(swagger): Generate correct Swagger for inline objects. Fixes #2835 (#2837)
 * [c0143d34](https://github.com/argoproj/argo-workflows/commit/c0143d3478c6ff2ec5138f7c6b272fc8e36c6734) feat: Add metric retention policy (#2836)
 * [f03cda61](https://github.com/argoproj/argo-workflows/commit/f03cda61a73243eea225fe4d0a49f2ada0523d0d) Update getting-started.md (#2872)

### Contributors

 * Adam Gilat
 * Alex Collins
 * Alex Stein
 * Ben Ye
 * Caden
 * Caglar Gulseni
 * Daisuke Taniwaki
 * Daniel Sutton
 * Florent Clairambault
 * Grant Stephens
 * Huan-Cheng Chang
 * Jie Zhang
 * Kannappan Sirchabesan
 * Leonardo Luz
 * Markus Lippert
 * Matt Brant
 * Michael Crenshaw
 * Mike Seddon
 * Pierre Houssin
 * Pradip Caulagi
 * Remington Breeze
 * Romain GUICHARD
 * Saravanan Balasubramanian
 * Sascha Grunert
 * Simon Behar
 * Stephen Steiner
 * Tomas Valasek
 * Vardan Manucharyan
 * Vlad Losev
 * William
 * Youngjoon Lee
 * Yuan Tang
 * Yunhai Luo
 * dmayle
 * maguowei
 * mark9white
 * shibataka000

## v2.8.2 (2020-06-22)

 * [c15e817b](https://github.com/argoproj/argo-workflows/commit/c15e817b2fa61456ae6612800017df6f094ff5a0) Update manifests to v2.8.2
 * [8a151aec](https://github.com/argoproj/argo-workflows/commit/8a151aec6538c9442cf2380c2544ba3efb60ff60) Update manifests to 2.8.2
 * [123e94ac](https://github.com/argoproj/argo-workflows/commit/123e94ac4827a4aa48d67045ed4e7fb6a9c15b4c) fix(controller): set pod finish timestamp when it is deleted (#3230)
 * [68a60661](https://github.com/argoproj/argo-workflows/commit/68a6066152ac5299fc689f4277b36799df9ca38a) fix: Begin counting maxDuration from first child start (#2976)

### Contributors

 * Jie Zhang
 * Simon Behar

## v2.8.1 (2020-05-28)

 * [0fff4b21](https://github.com/argoproj/argo-workflows/commit/0fff4b21c21c5ff5adbb5ff62c68e67edd95d6b8) Update manifests to v2.8.1
 * [05dd7862](https://github.com/argoproj/argo-workflows/commit/05dd786231a713690349826079bd2fcb1cdb7c1b) fix(item): Support ItemValue.Type == List. Fixes #2660 (#3129)
 * [def3b97a](https://github.com/argoproj/argo-workflows/commit/def3b97aec2c4c52315c5794ec8ad8d531fa79a8) test: Re-generate mocks
 * [888b2154](https://github.com/argoproj/argo-workflows/commit/888b215479c24e6e3bd5aa804371d73c85a9f20e) test: Add argoproj/argosay:v2 to whitelisted test images
 * [baf30725](https://github.com/argoproj/argo-workflows/commit/baf30725eb7d3474d776902f3317f18b6b95aa7a) build: Fix version
 * [ac02aa2c](https://github.com/argoproj/argo-workflows/commit/ac02aa2c67b2bd74e148d3c686e7d9b391edf9b8) build: Fix Makefile `git git tag` typo
 * [3b840201](https://github.com/argoproj/argo-workflows/commit/3b840201b2be6402d247ee12b9993061317653b7) Fix test
 * [41689c55](https://github.com/argoproj/argo-workflows/commit/41689c55ac388c6634cf46ee1154f31df556e59e) fix: Graceful error handling of malformatted log lines in watch (#3071)
 * [79aeca1f](https://github.com/argoproj/argo-workflows/commit/79aeca1f3faa62678115e92c0ecb0b0e7670392a) fix: Linters should error if nothing was validated (#3011)
 * [c977d8bb](https://github.com/argoproj/argo-workflows/commit/c977d8bbab61b282375dcac598eabc558751b386) fix(executor): Properly handle empty resource results, like for a missing get (#3037)
 * [1a01c804](https://github.com/argoproj/argo-workflows/commit/1a01c804212a069e3b82bf0e1fceb12141e101f6) fix: Consider metric nodes that were created and completed in the same operation (#3033)
 * [6065b7ed](https://github.com/argoproj/argo-workflows/commit/6065b7ed7688b3fc4fb9c46b449a8dab50da0a21) fix: Consider missing optional input/output artifacts with same name (#3029)
 * [acb0f1c1](https://github.com/argoproj/argo-workflows/commit/acb0f1c1679ee6ec686bb5ff266bc20c4344f3e2) fix: Cannot create WorkflowTemplate with un-supplied inputs (#2869)
 * [5b04ccce](https://github.com/argoproj/argo-workflows/commit/5b04ccce7199e02f6054c47c9d17f071af9d6c1d) fix(controller)!: Correctly format workflow.creationTimepstamp as RFC3339. Fixes #2974 (#3023)
 * [319ee46d](https://github.com/argoproj/argo-workflows/commit/319ee46d3927b2cfe1c7e2aec38e01e24ebd3b4f) fix(events): Correct event API Version. Fixes #2994 (#2999)
 * [be32b207](https://github.com/argoproj/argo-workflows/commit/be32b207ddf4490f90d7e85df9de84b52b46eb6e) build: Correct version
 * [8f696174](https://github.com/argoproj/argo-workflows/commit/8f696174746ed01b9bf1941ad03da62d312df641) Update manifests to v2.8.0

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar
 * dmayle

## v2.8.0-rc4 (2020-05-06)

 * [ee0dc575](https://github.com/argoproj/argo-workflows/commit/ee0dc575dc7d2187e0e97e768c7b58538958608b) Update manifests to v2.8.0-rc4
 * [3a85610a](https://github.com/argoproj/argo-workflows/commit/3a85610a42e4ca4ed4e506fd2017791464db9c59) fix(cli): Remove info logging from watches. Fixes #2955 (#2958)
 * [29c7780d](https://github.com/argoproj/argo-workflows/commit/29c7780dc9311dc734a4f09f683253648ce75dd0) make codegen
 * [265666bf](https://github.com/argoproj/argo-workflows/commit/265666bf7b62d421e939a373ee0c676103d631cd) fix(cli): Re-establish watch on EOF (#2944)
 * [fef4e968](https://github.com/argoproj/argo-workflows/commit/fef4e968900365a79fd623efa054671b66dc8f1e) fix(swagger)!: Fixes invalid K8S definitions in `swagger.json`. Fixes #2888 (#2907)
 * [0f7f9c45](https://github.com/argoproj/argo-workflows/commit/0f7f9c451d7691cc3332b6465ffbfd1163f9b006) test: Use argoproj/argosay:v1 (#2917)
 * [1ea37284](https://github.com/argoproj/argo-workflows/commit/1ea3728441a9c0b6ef0b52eed47d730fd1b4a44e) build: Fix Darwin build (#2920)
 * [54610011](https://github.com/argoproj/argo-workflows/commit/546100114a66923ca2d4a945cd9a1eaab33343f5) ci: Build less and therefore faster (#2839)
 * [249309aa](https://github.com/argoproj/argo-workflows/commit/249309aa7c6d483cb622589afa417cb3b7f4965f) fix(swagger): Generate correct Swagger for inline objects. Fixes #2835 (#2837)
 * [f668c789](https://github.com/argoproj/argo-workflows/commit/f668c789c877504fdbaed929d16646befd26b24f) docs: Document node field selector. Closes #2860 (#2882)
 * [ad28a9c9](https://github.com/argoproj/argo-workflows/commit/ad28a9c955562bbf3f3cb3346118e7c39c84ffe0) fix(controller): Workflow stop and resume by node didn't properly support offloaded nodes. Fixes #2543 (#2548)
 * [db4cfc75](https://github.com/argoproj/argo-workflows/commit/db4cfc7566207c1a705170c2fde12bfc10c6af00) ci: Remove context to stop unauthozied errors on test jobs (#2910)
 * [d9fca8f0](https://github.com/argoproj/argo-workflows/commit/d9fca8f08ffc3a16ee085352831f9b208131661d) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)

### Contributors

 * Alex Collins
 * mark9white
 * shibataka000

## v2.8.0-rc3 (2020-04-28)

 * [2f153b21](https://github.com/argoproj/argo-workflows/commit/2f153b215666b3dc30c65931faeedba749207110) Update manifests to v2.8.0-rc3
 * [dc7e9984](https://github.com/argoproj/argo-workflows/commit/dc7e9984fdab88b377d2d06118c5f1588434f1d5) Merge branch 'master' into release-2.8
 * [d66224e1](https://github.com/argoproj/argo-workflows/commit/d66224e12613c36f8fa91956509fad9fc450af74) fix: Don't error when deleting already-deleted WFs (#2866)
 * [e84acb50](https://github.com/argoproj/argo-workflows/commit/e84acb502cbbba88a700c511ffbf7feee609ccb8) chore: Display wf.Status.Conditions in CLI (#2858)
 * [3c7f3a07](https://github.com/argoproj/argo-workflows/commit/3c7f3a07d90ea6dcdf91673d4e5b4075216628f7) docs: Fix typo ".yam" -> ".yaml" (#2862)
 * [db9e14cf](https://github.com/argoproj/argo-workflows/commit/db9e14cfc7e7907af1a6aac6b06a05c17b52a114) Merge branch 'master' into release-2.8
 * [d7f8e0c4](https://github.com/argoproj/argo-workflows/commit/d7f8e0c4742b62d9271b6272a8f87c53a4fddea2) fix(CLI): Re-establish workflow watch on disconnect. Fixes #2796 (#2830)
 * [31358d6e](https://github.com/argoproj/argo-workflows/commit/31358d6e255e28f20803575f5ee0fdf2015ecb68) feat(CLI): Add -v and --verbose to Argo CLI (#2814)
 * [1d30f708](https://github.com/argoproj/argo-workflows/commit/1d30f70896b8b5f7ddc29e255c2dce0c6d01f4bd) ci: Don't configure Sonar on CI for release branches (#2811)
 * [d9c54075](https://github.com/argoproj/argo-workflows/commit/d9c54075b71baad2742829fe0874e4f07c67c67a) docs: Fix exit code example and docs (#2853)
 * [90743353](https://github.com/argoproj/argo-workflows/commit/90743353fcaf46dae04872935e95ce858e1792b3) feat: Expose workflow.serviceAccountName as global variable (#2838)
 * [f07f7bf6](https://github.com/argoproj/argo-workflows/commit/f07f7bf61147b3444255117c26bfd38261220e95) note that tar.gz'ing output artifacts is optional (#2797)
 * [3fd3fc6c](https://github.com/argoproj/argo-workflows/commit/3fd3fc6c3c789e7a3b357e16aacb02d0f880892b) docs: Document how to label creator (#2827)
 * [b956ec65](https://github.com/argoproj/argo-workflows/commit/b956ec65f372194e0f110e672a2ad50bd51a10d8) fix: Add Step node outputs to global scope (#2826)
 * [bac339af](https://github.com/argoproj/argo-workflows/commit/bac339afe10013a63bc1bb2fb83a883c07e19cb9) chore: Configure webpack dev server to proxy using HTTPS (#2812)
 * [cc136f9c](https://github.com/argoproj/argo-workflows/commit/cc136f9c3d76a5c50a9c03613233c62d118d3457) test: Skip TestStopBehavior. See #2833 (#2834)
 * [52ff43b5](https://github.com/argoproj/argo-workflows/commit/52ff43b54a76f934ae3b491c74e2350fbd2298f2) fix: Artifact panic on unknown artifact. Fixes #2824 (#2829)
 * [554fd06c](https://github.com/argoproj/argo-workflows/commit/554fd06c9daf7ce1147f949d397e489d508c58ba) fix: Enforce metric naming validation (#2819)
 * [dd223669](https://github.com/argoproj/argo-workflows/commit/dd223669a30acc58369a70288fee6ed6e006c189) docs: Add Microba as official Argo user (#2822)
 * [8151f0c4](https://github.com/argoproj/argo-workflows/commit/8151f0c49aea618a6dfcf92ec8388ccb7a5de985) docs: Update tls.md (#2813)

### Contributors

 * Alex Collins
 * Fabio Rigato
 * Michael Crenshaw
 * Mike Seddon
 * Simon Behar

## v2.8.0-rc2 (2020-04-23)

 * [4126d22b](https://github.com/argoproj/argo-workflows/commit/4126d22b6f49e347ae1a75dd3ad6f484bee30f11) Update manifests to v2.8.0-rc2
 * [ce6b23e9](https://github.com/argoproj/argo-workflows/commit/ce6b23e92e193ceafd28b81e6f6bafc7cf644c21) revert
 * [c0cfab52](https://github.com/argoproj/argo-workflows/commit/c0cfab5283a3d18899f0f1c3a03ab3327948703c) Merge branch 'master' into release-2.8
 * [0dbd78ff](https://github.com/argoproj/argo-workflows/commit/0dbd78ff223e592f8761f1334f952e97c9e6ac48) feat: Add TLS support. Closes #2764 (#2766)
 * [510e11b6](https://github.com/argoproj/argo-workflows/commit/510e11b639e0b797cc4253d84e96fb070691b7ab) fix: Allow empty strings in valueFrom.default (#2805)
 * [399591c9](https://github.com/argoproj/argo-workflows/commit/399591c96ed588cfbc96d78268ce35812fcd465b) fix: Don't configure Sonar on CI for release branches
 * [d7f41ac8](https://github.com/argoproj/argo-workflows/commit/d7f41ac8df15b8ed1e68b2e4f44d64418e4c4000) fix: Print correct version in logs. (#2806)
 * [e9c21120](https://github.com/argoproj/argo-workflows/commit/e9c2112064293b3a71e47b493666bdc9b311dfa6) chore: Add GCS native example for output artifact (#2789)
 * [e0f2697e](https://github.com/argoproj/argo-workflows/commit/e0f2697e252e7b62842af3b56f924f324f2c48ec) fix(controller): Include global params when using withParam (#2757)
 * [3441b11a](https://github.com/argoproj/argo-workflows/commit/3441b11aa5bde5fa5d0a6652fbb8fa05a4225686) docs: Fix typo in CronWorkflow doc (#2804)
 * [a2d2b848](https://github.com/argoproj/argo-workflows/commit/a2d2b848a9b6f3cf6fe5c0f0dd3b7b3084f83e37) docs: Add example of recursive for loop (#2801)
 * [29d39e29](https://github.com/argoproj/argo-workflows/commit/29d39e297c93355b68a9726aadeef4c67d4767b2) docs: Update the contributing docs  (#2791)
 * [1ea286eb](https://github.com/argoproj/argo-workflows/commit/1ea286eb237ed86bfde5a4c954927b335ab588f2) fix: ClusterWorkflowTemplate RBAC for  argo server (#2753)
 * [1f14f2a5](https://github.com/argoproj/argo-workflows/commit/1f14f2a5f6054a88f740c6799d443216f694f08f) feat(archive): Implement data retention. Closes #2273 (#2312)
 * [d0cc7764](https://github.com/argoproj/argo-workflows/commit/d0cc7764fe477465ac2c76de9cc406bbf2aac807) feat: Display argo-server version in `argo version` and in UI. (#2740)
 * [8de57281](https://github.com/argoproj/argo-workflows/commit/8de572813ee9f028cf8e06834f45a3592bc73f14) feat(controller): adds Kubernetes node name to workflow node detail in web UI and CLI output. Implements #2540 (#2732)
 * [52fa5fde](https://github.com/argoproj/argo-workflows/commit/52fa5fdee9f021b73eca30a199c65a3760462bd9) MySQL config fix (#2681)
 * [43d9eebb](https://github.com/argoproj/argo-workflows/commit/43d9eebb479242ef23e84135bbe4b9dd252dea46) fix: Rename Submittable API endpoint to `submit` (#2778)
 * [69333a87](https://github.com/argoproj/argo-workflows/commit/69333a87b0ae411972f7f25b196db989500bbe0c) Fix template scope tests (#2779)
 * [bb1abf7f](https://github.com/argoproj/argo-workflows/commit/bb1abf7f4c425494a0878d6cbc2d2cb677e88a97) chore: Add CODEOWNERS file (#2776)
 * [905e0b99](https://github.com/argoproj/argo-workflows/commit/905e0b99312e579dcd8aa8036c2ee57df6fa7a29) fix: Naming error in Makefile (#2774)
 * [7cb2fd17](https://github.com/argoproj/argo-workflows/commit/7cb2fd17765aad691eda25ca4c5acecb89f84394) fix: allow non path output params (#2680)

### Contributors

 * Alex Collins
 * Alex Stein
 * Daisuke Taniwaki
 * Fabio Rigato
 * Kannappan Sirchabesan
 * Michael Crenshaw
 * Saravanan Balasubramanian
 * Simon Behar

## v2.8.0-rc1 (2020-04-20)


### Contributors


## v2.8.0 (2020-05-11)

 * [8f696174](https://github.com/argoproj/argo-workflows/commit/8f696174746ed01b9bf1941ad03da62d312df641) Update manifests to v2.8.0
 * [ee0dc575](https://github.com/argoproj/argo-workflows/commit/ee0dc575dc7d2187e0e97e768c7b58538958608b) Update manifests to v2.8.0-rc4
 * [3a85610a](https://github.com/argoproj/argo-workflows/commit/3a85610a42e4ca4ed4e506fd2017791464db9c59) fix(cli): Remove info logging from watches. Fixes #2955 (#2958)
 * [29c7780d](https://github.com/argoproj/argo-workflows/commit/29c7780dc9311dc734a4f09f683253648ce75dd0) make codegen
 * [265666bf](https://github.com/argoproj/argo-workflows/commit/265666bf7b62d421e939a373ee0c676103d631cd) fix(cli): Re-establish watch on EOF (#2944)
 * [fef4e968](https://github.com/argoproj/argo-workflows/commit/fef4e968900365a79fd623efa054671b66dc8f1e) fix(swagger)!: Fixes invalid K8S definitions in `swagger.json`. Fixes #2888 (#2907)
 * [0f7f9c45](https://github.com/argoproj/argo-workflows/commit/0f7f9c451d7691cc3332b6465ffbfd1163f9b006) test: Use argoproj/argosay:v1 (#2917)
 * [1ea37284](https://github.com/argoproj/argo-workflows/commit/1ea3728441a9c0b6ef0b52eed47d730fd1b4a44e) build: Fix Darwin build (#2920)
 * [54610011](https://github.com/argoproj/argo-workflows/commit/546100114a66923ca2d4a945cd9a1eaab33343f5) ci: Build less and therefore faster (#2839)
 * [249309aa](https://github.com/argoproj/argo-workflows/commit/249309aa7c6d483cb622589afa417cb3b7f4965f) fix(swagger): Generate correct Swagger for inline objects. Fixes #2835 (#2837)
 * [f668c789](https://github.com/argoproj/argo-workflows/commit/f668c789c877504fdbaed929d16646befd26b24f) docs: Document node field selector. Closes #2860 (#2882)
 * [ad28a9c9](https://github.com/argoproj/argo-workflows/commit/ad28a9c955562bbf3f3cb3346118e7c39c84ffe0) fix(controller): Workflow stop and resume by node didn't properly support offloaded nodes. Fixes #2543 (#2548)
 * [db4cfc75](https://github.com/argoproj/argo-workflows/commit/db4cfc7566207c1a705170c2fde12bfc10c6af00) ci: Remove context to stop unauthozied errors on test jobs (#2910)
 * [d9fca8f0](https://github.com/argoproj/argo-workflows/commit/d9fca8f08ffc3a16ee085352831f9b208131661d) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)
 * [2f153b21](https://github.com/argoproj/argo-workflows/commit/2f153b215666b3dc30c65931faeedba749207110) Update manifests to v2.8.0-rc3
 * [dc7e9984](https://github.com/argoproj/argo-workflows/commit/dc7e9984fdab88b377d2d06118c5f1588434f1d5) Merge branch 'master' into release-2.8
 * [d66224e1](https://github.com/argoproj/argo-workflows/commit/d66224e12613c36f8fa91956509fad9fc450af74) fix: Don't error when deleting already-deleted WFs (#2866)
 * [e84acb50](https://github.com/argoproj/argo-workflows/commit/e84acb502cbbba88a700c511ffbf7feee609ccb8) chore: Display wf.Status.Conditions in CLI (#2858)
 * [3c7f3a07](https://github.com/argoproj/argo-workflows/commit/3c7f3a07d90ea6dcdf91673d4e5b4075216628f7) docs: Fix typo ".yam" -> ".yaml" (#2862)
 * [db9e14cf](https://github.com/argoproj/argo-workflows/commit/db9e14cfc7e7907af1a6aac6b06a05c17b52a114) Merge branch 'master' into release-2.8
 * [d7f8e0c4](https://github.com/argoproj/argo-workflows/commit/d7f8e0c4742b62d9271b6272a8f87c53a4fddea2) fix(CLI): Re-establish workflow watch on disconnect. Fixes #2796 (#2830)
 * [31358d6e](https://github.com/argoproj/argo-workflows/commit/31358d6e255e28f20803575f5ee0fdf2015ecb68) feat(CLI): Add -v and --verbose to Argo CLI (#2814)
 * [1d30f708](https://github.com/argoproj/argo-workflows/commit/1d30f70896b8b5f7ddc29e255c2dce0c6d01f4bd) ci: Don't configure Sonar on CI for release branches (#2811)
 * [d9c54075](https://github.com/argoproj/argo-workflows/commit/d9c54075b71baad2742829fe0874e4f07c67c67a) docs: Fix exit code example and docs (#2853)
 * [90743353](https://github.com/argoproj/argo-workflows/commit/90743353fcaf46dae04872935e95ce858e1792b3) feat: Expose workflow.serviceAccountName as global variable (#2838)
 * [f07f7bf6](https://github.com/argoproj/argo-workflows/commit/f07f7bf61147b3444255117c26bfd38261220e95) note that tar.gz'ing output artifacts is optional (#2797)
 * [3fd3fc6c](https://github.com/argoproj/argo-workflows/commit/3fd3fc6c3c789e7a3b357e16aacb02d0f880892b) docs: Document how to label creator (#2827)
 * [b956ec65](https://github.com/argoproj/argo-workflows/commit/b956ec65f372194e0f110e672a2ad50bd51a10d8) fix: Add Step node outputs to global scope (#2826)
 * [bac339af](https://github.com/argoproj/argo-workflows/commit/bac339afe10013a63bc1bb2fb83a883c07e19cb9) chore: Configure webpack dev server to proxy using HTTPS (#2812)
 * [cc136f9c](https://github.com/argoproj/argo-workflows/commit/cc136f9c3d76a5c50a9c03613233c62d118d3457) test: Skip TestStopBehavior. See #2833 (#2834)
 * [52ff43b5](https://github.com/argoproj/argo-workflows/commit/52ff43b54a76f934ae3b491c74e2350fbd2298f2) fix: Artifact panic on unknown artifact. Fixes #2824 (#2829)
 * [554fd06c](https://github.com/argoproj/argo-workflows/commit/554fd06c9daf7ce1147f949d397e489d508c58ba) fix: Enforce metric naming validation (#2819)
 * [dd223669](https://github.com/argoproj/argo-workflows/commit/dd223669a30acc58369a70288fee6ed6e006c189) docs: Add Microba as official Argo user (#2822)
 * [8151f0c4](https://github.com/argoproj/argo-workflows/commit/8151f0c49aea618a6dfcf92ec8388ccb7a5de985) docs: Update tls.md (#2813)
 * [4126d22b](https://github.com/argoproj/argo-workflows/commit/4126d22b6f49e347ae1a75dd3ad6f484bee30f11) Update manifests to v2.8.0-rc2
 * [ce6b23e9](https://github.com/argoproj/argo-workflows/commit/ce6b23e92e193ceafd28b81e6f6bafc7cf644c21) revert
 * [c0cfab52](https://github.com/argoproj/argo-workflows/commit/c0cfab5283a3d18899f0f1c3a03ab3327948703c) Merge branch 'master' into release-2.8
 * [0dbd78ff](https://github.com/argoproj/argo-workflows/commit/0dbd78ff223e592f8761f1334f952e97c9e6ac48) feat: Add TLS support. Closes #2764 (#2766)
 * [510e11b6](https://github.com/argoproj/argo-workflows/commit/510e11b639e0b797cc4253d84e96fb070691b7ab) fix: Allow empty strings in valueFrom.default (#2805)
 * [399591c9](https://github.com/argoproj/argo-workflows/commit/399591c96ed588cfbc96d78268ce35812fcd465b) fix: Don't configure Sonar on CI for release branches
 * [d7f41ac8](https://github.com/argoproj/argo-workflows/commit/d7f41ac8df15b8ed1e68b2e4f44d64418e4c4000) fix: Print correct version in logs. (#2806)
 * [e9c21120](https://github.com/argoproj/argo-workflows/commit/e9c2112064293b3a71e47b493666bdc9b311dfa6) chore: Add GCS native example for output artifact (#2789)
 * [e0f2697e](https://github.com/argoproj/argo-workflows/commit/e0f2697e252e7b62842af3b56f924f324f2c48ec) fix(controller): Include global params when using withParam (#2757)
 * [3441b11a](https://github.com/argoproj/argo-workflows/commit/3441b11aa5bde5fa5d0a6652fbb8fa05a4225686) docs: Fix typo in CronWorkflow doc (#2804)
 * [a2d2b848](https://github.com/argoproj/argo-workflows/commit/a2d2b848a9b6f3cf6fe5c0f0dd3b7b3084f83e37) docs: Add example of recursive for loop (#2801)
 * [29d39e29](https://github.com/argoproj/argo-workflows/commit/29d39e297c93355b68a9726aadeef4c67d4767b2) docs: Update the contributing docs  (#2791)
 * [1ea286eb](https://github.com/argoproj/argo-workflows/commit/1ea286eb237ed86bfde5a4c954927b335ab588f2) fix: ClusterWorkflowTemplate RBAC for  argo server (#2753)
 * [1f14f2a5](https://github.com/argoproj/argo-workflows/commit/1f14f2a5f6054a88f740c6799d443216f694f08f) feat(archive): Implement data retention. Closes #2273 (#2312)
 * [d0cc7764](https://github.com/argoproj/argo-workflows/commit/d0cc7764fe477465ac2c76de9cc406bbf2aac807) feat: Display argo-server version in `argo version` and in UI. (#2740)
 * [8de57281](https://github.com/argoproj/argo-workflows/commit/8de572813ee9f028cf8e06834f45a3592bc73f14) feat(controller): adds Kubernetes node name to workflow node detail in web UI and CLI output. Implements #2540 (#2732)
 * [52fa5fde](https://github.com/argoproj/argo-workflows/commit/52fa5fdee9f021b73eca30a199c65a3760462bd9) MySQL config fix (#2681)
 * [43d9eebb](https://github.com/argoproj/argo-workflows/commit/43d9eebb479242ef23e84135bbe4b9dd252dea46) fix: Rename Submittable API endpoint to `submit` (#2778)
 * [69333a87](https://github.com/argoproj/argo-workflows/commit/69333a87b0ae411972f7f25b196db989500bbe0c) Fix template scope tests (#2779)
 * [bb1abf7f](https://github.com/argoproj/argo-workflows/commit/bb1abf7f4c425494a0878d6cbc2d2cb677e88a97) chore: Add CODEOWNERS file (#2776)
 * [905e0b99](https://github.com/argoproj/argo-workflows/commit/905e0b99312e579dcd8aa8036c2ee57df6fa7a29) fix: Naming error in Makefile (#2774)
 * [7cb2fd17](https://github.com/argoproj/argo-workflows/commit/7cb2fd17765aad691eda25ca4c5acecb89f84394) fix: allow non path output params (#2680)
 * [4a73f45c](https://github.com/argoproj/argo-workflows/commit/4a73f45c38a07e9e517c39ed5611d386bcf518bd) Update manifests to v2.8.0-rc1
 * [af9f61ea](https://github.com/argoproj/argo-workflows/commit/af9f61ea7ce53f629a284a44f0106b9ed73f24e2) ci: Recurl (#2769)
 * [ef08e642](https://github.com/argoproj/argo-workflows/commit/ef08e642b5c92de0571998909b2b34ab3ac89fd4) build: Retry curl 3x (#2768)
 * [dedec906](https://github.com/argoproj/argo-workflows/commit/dedec906f0391b63b341c90e43a67047303c4728) test: Get tests running on release branches (#2767)
 * [1c8318eb](https://github.com/argoproj/argo-workflows/commit/1c8318eb92d17fa2263675cabce5134d3f1e37a2) fix: Add compatiblity mode to templateReference (#2765)
 * [7975952b](https://github.com/argoproj/argo-workflows/commit/7975952b0aa3ac84ea4559b302236598d1d47954) fix: Consider expanded tasks in getTaskFromNode (#2756)
 * [bc421380](https://github.com/argoproj/argo-workflows/commit/bc421380c9dfce1b8a25950d2bdc6a71b2e74a2d) fix: Fix template resolution in UI (#2754)
 * [391c0f78](https://github.com/argoproj/argo-workflows/commit/391c0f78a496dbe0334686dfcabde8c9af8a474f) Make phase and templateRef available for unsuspend and retry selectors (#2723)
 * [a6fa3f71](https://github.com/argoproj/argo-workflows/commit/a6fa3f71fa6bf742cb2fa90292180344f3744def) fix: Improve cookie security. Fixes #2759 (#2763)
 * [57f0183c](https://github.com/argoproj/argo-workflows/commit/57f0183cd194767af8f9bcb5fb84ab083c1661c3) Fix typo on the documentation. It causes error unmarshaling JSON: while (#2730)
 * [c6ef1ff1](https://github.com/argoproj/argo-workflows/commit/c6ef1ff19e1c3f74b4ef146be37e74bd0b748cd7) feat(manifests): add name on workflow-controller-metrics service port (#2744)
 * [af5cd1ae](https://github.com/argoproj/argo-workflows/commit/af5cd1ae0030b20f71ad345f21456100fec74639) docs: Update OWNERS (#2750)
 * [06c4bd60](https://github.com/argoproj/argo-workflows/commit/06c4bd60cf2dc85362b3370acd44e4bc3977dcbc) fix: Make ClusterWorkflowTemplate optional for namespaced Installation (#2670)
 * [25c62463](https://github.com/argoproj/argo-workflows/commit/25c624636d80605c08dd423528cb22b89cebf687) docs: Update README (#2752)
 * [908e1685](https://github.com/argoproj/argo-workflows/commit/908e1685d78d12c87fe955eec8ad0df964b3d98b) docs: Update README.md (#2751)
 * [4ea43e2d](https://github.com/argoproj/argo-workflows/commit/4ea43e2d63385211cc0a29c2aa1b237797a62f71) fix: Children of onExit nodes are also onExit nodes (#2722)
 * [3f1b6667](https://github.com/argoproj/argo-workflows/commit/3f1b6667282cf3d1b7944f7fdc075ef0f1b8ff36) feat: Add Kustomize as supported install option. Closes #2715 (#2724)
 * [691459ed](https://github.com/argoproj/argo-workflows/commit/691459ed3591f72251dc230982d7b03dc3d6f9db) fix: Error pending nodes w/o Pods unless resubmitPendingPods is set (#2721)
 * [874d8776](https://github.com/argoproj/argo-workflows/commit/874d8776c22f54ede8a07ef87b9d18c6ba8198ec) test: Longer timeout for deletion (#2737)
 * [3c8149fa](https://github.com/argoproj/argo-workflows/commit/3c8149fabfcb84bc57d1973c10fe6dbce96232a0) Fix typo (#2741)
 * [98f60e79](https://github.com/argoproj/argo-workflows/commit/98f60e7985ebd77d42ff99c6d6e1276048fb07f6) feat: Added Workflow SubmitFromResource API (#2544)
 * [6253997a](https://github.com/argoproj/argo-workflows/commit/6253997a7e25f3ad9fd3c322ea9ca9ad0b710c83) fix: Reset all conditions when resubmitting (#2702)
 * [e7c67de3](https://github.com/argoproj/argo-workflows/commit/e7c67de30df90ba7bbd649a2833dc6efed8a18de) fix: Maybe fix watch. Fixes #2678 (#2719)
 * [cef6dfb6](https://github.com/argoproj/argo-workflows/commit/cef6dfb6a25445624f864863da45c36380049e6d) fix: Print correct version string. (#2713)
 * [e9589d28](https://github.com/argoproj/argo-workflows/commit/e9589d28a5dbc7cb620f206bd1fee457a8b29dfe) feat: Increase pod workers and workflow workers both to 32 by default. (#2705)
 * [3a1990e0](https://github.com/argoproj/argo-workflows/commit/3a1990e09b353cd963b5dfbf50a702266d49b2fc) test: Fix Goroutine leak that was making controller unit tests slow. (#2701)
 * [9894c29f](https://github.com/argoproj/argo-workflows/commit/9894c29f4258fd40b604ee2c33bd877d03ff5b00) ci: Fix Sonar analysis on master. (#2709)
 * [54f5be36](https://github.com/argoproj/argo-workflows/commit/54f5be361f597d45c97469095a2e5cb5678436a8) style: Camelcase "clusterScope" (#2720)
 * [db6d1416](https://github.com/argoproj/argo-workflows/commit/db6d1416a11dbd9d963a2df6740908a1d8086ff6) fix: Flakey TestNestedClusterWorkflowTemplate testcase failure (#2613)
 * [b4fd4475](https://github.com/argoproj/argo-workflows/commit/b4fd4475c2661f12a92ba48a71b52067536044fe) feat(ui): Add a YAML panel to view the workflow manifest. (#2700)
 * [65d413e5](https://github.com/argoproj/argo-workflows/commit/65d413e5d68b2f1667ef09f3c5938a07c3442fe8) build(ui): Fix compression of UI package. (#2704)
 * [4129528d](https://github.com/argoproj/argo-workflows/commit/4129528d430be282099e94d7e98d61e40d9c78ba) fix: Don't use docker cache when building release images (#2707)
 * [8d0956c9](https://github.com/argoproj/argo-workflows/commit/8d0956c9eb8533d5a399246ffed68f6d343d47a1) test: Increase runCli timeout to 1m (#2703)
 * [9d93e971](https://github.com/argoproj/argo-workflows/commit/9d93e971a66d8f50ad92ff9e15175c6bbfe292c4) Update getting-started.md (#2697)
 * [ee644a35](https://github.com/argoproj/argo-workflows/commit/ee644a35ce4ec6a5565327fbf8cbae17a742603f) docs: Fix CONTRIBUTING.md and running-locally.md. Fixes #2682 (#2699)
 * [2737c0ab](https://github.com/argoproj/argo-workflows/commit/2737c0abf77f1555c9a9a59e564d0f1242d2656e) feat: Allow to pass optional flags to resource template (#1779)
 * [c1a2fc7c](https://github.com/argoproj/argo-workflows/commit/c1a2fc7ca8be7b9286ec01a12a185d8d4360b9f6) Update running-locally.md - fixing incorrect protoc install (#2689)
 * [a1226c46](https://github.com/argoproj/argo-workflows/commit/a1226c4616ad327400b37be19703e65a31919248) fix: Enhanced WorkflowTemplate and ClusterWorkflowTemplate validation to support Global Variables   (#2644)
 * [c21cc2f3](https://github.com/argoproj/argo-workflows/commit/c21cc2f31fead552cbab5f4664d20d56cf291619) fix a typo (#2669)
 * [9430a513](https://github.com/argoproj/argo-workflows/commit/9430a513fe7b5587048a5e74d3c9abc9e36e4304) fix: Namespace-related validation in UI (#2686)
 * [f3eeca6e](https://github.com/argoproj/argo-workflows/commit/f3eeca6e3b72f27f86678de840d1b6b7497e9473) feat: Add exit code as output variable (#2111)
 * [9f95e23a](https://github.com/argoproj/argo-workflows/commit/9f95e23a4dc9104da2218c66c66c4475285dfc3e) fix: Report metric emission errors via Conditions (#2676)
 * [c67f5ff5](https://github.com/argoproj/argo-workflows/commit/c67f5ff55b8e41b465e481d7a38d54d551c07ee4) fix: Leaf task with continueOn should not fail DAG (#2668)
 * [3c20d4c0](https://github.com/argoproj/argo-workflows/commit/3c20d4c072f1ec69954a3db8a9383bf312b495fd) ci: Migrate to use Sonar instead of CodeCov for analysis (#2666)
 * [9c6351fa](https://github.com/argoproj/argo-workflows/commit/9c6351fa643f76a7cf36eef3b80cff9bf5880463) feat: Allow step restart on workflow retry. Closes #2334 (#2431)
 * [cf277eb5](https://github.com/argoproj/argo-workflows/commit/cf277eb5114cd2db4f00d34e400a132d3344bf97) docs: Updates docs for CII. See #2641 (#2643)
 * [e2d0aa23](https://github.com/argoproj/argo-workflows/commit/e2d0aa23ab4ee9b91b018bb556959c60981586e2) fix: Consider offloaded and compressed node in retry and resume (#2645)
 * [a25c6a20](https://github.com/argoproj/argo-workflows/commit/a25c6a20d0ff7b7b7b211fcfe207200036ed5df8) build: Fix codegen for releases (#2662)
 * [4a3ca930](https://github.com/argoproj/argo-workflows/commit/4a3ca930ef1d944dfd8659d5886d8abc7f6ce42f) fix: Correctly emit events. Fixes #2626 (#2629)
 * [4a7d4bdb](https://github.com/argoproj/argo-workflows/commit/4a7d4bdba522870ab9883c4f6ccac7b244bc5bcb) test: Fix flakey DeleteCompleted test (#2659)
 * [41f91e18](https://github.com/argoproj/argo-workflows/commit/41f91e18a4f65d8a6626782ebc8920ca02b3cc86) fix: Add DAG as default in UI filter and reorder (#2661)
 * [f138ada6](https://github.com/argoproj/argo-workflows/commit/f138ada68ba0b3c46f546bfef574e212833759ac) fix: DAG should not fail if its tasks have continueOn (#2656)
 * [e5cbdf6a](https://github.com/argoproj/argo-workflows/commit/e5cbdf6a4be8f111f6353534079fa4a71384e401) ci: Only run CI jobs if needed (#2655)
 * [4c452d5f](https://github.com/argoproj/argo-workflows/commit/4c452d5f7287179b6a7967fc7d60fb0837bd36ca) fix: Don't attempt to resolve artifacts if task is going to be skipped (#2657)
 * [2caf570a](https://github.com/argoproj/argo-workflows/commit/2caf570a35565617ae9af04682883ab34e2692b6) chore: Add newline to fields.md (#2654)
 * [2cb596da](https://github.com/argoproj/argo-workflows/commit/2cb596da3dac3c5683ed44e7a363c014e73a38a5) Storage region should be specified (#2538)
 * [271e4551](https://github.com/argoproj/argo-workflows/commit/271e45512be56bb6187d7665e9b5b65eb2500ad6) chore: Fix-up Yarn deps (#2649)
 * [4c1b0777](https://github.com/argoproj/argo-workflows/commit/4c1b077725a22d183ecdb24f2f147fee0a6e320c) fix: Sort log entries. (#2647)
 * [268fc461](https://github.com/argoproj/argo-workflows/commit/268fc46197ac411339c78018f05d76e102447eef)  docs: Added doc generator code (#2632)
 * [d58b7fc3](https://github.com/argoproj/argo-workflows/commit/d58b7fc39620fb24e40bb4f55f69c4e0fb5fc017) fix: Add input paremeters to metric scope (#2646)
 * [cc3af0b8](https://github.com/argoproj/argo-workflows/commit/cc3af0b83381e2d4a8da1959c36fd0a466c414ff) fix: Validating Item Param in Steps Template (#2608)
 * [6c685c5b](https://github.com/argoproj/argo-workflows/commit/6c685c5baf281116340b7b0708f8a29764d72c47) fix: allow onExit to run if wf exceeds activeDeadlineSeconds. Fixes #2603 (#2605)
 * [ffc43ce9](https://github.com/argoproj/argo-workflows/commit/ffc43ce976973c7c20d6c58d7b27a28969ae206f) feat: Added Client validation on Workflow/WFT/CronWF/CWFT (#2612)
 * [24655cd9](https://github.com/argoproj/argo-workflows/commit/24655cd93246e2a25dc858238116f7acec45ea42) feat(UI): Move Workflow parameters to top of submit (#2640)
 * [0a3b159a](https://github.com/argoproj/argo-workflows/commit/0a3b159ab87bd313896174f8464ffd277b14264c) Use error equals (#2636)
 * [8c29e05c](https://github.com/argoproj/argo-workflows/commit/8c29e05cb5befe5f9f0263ff138eab66f75c54d0) ci: Fix codegen job (#2648)
 * [a78ecb7f](https://github.com/argoproj/argo-workflows/commit/a78ecb7fe040c0040fb12731997351a02e0808a0) docs(users): Add CoreWeave and ConciergeRender (#2641)
 * [14be4670](https://github.com/argoproj/argo-workflows/commit/14be46707f4051db71e9495472e842fbb1eb5ea0) fix: Fix logs part 2 (#2639)
 * [4da6f4f3](https://github.com/argoproj/argo-workflows/commit/4da6f4f3ee75b2e50206381dad1809d5a21c6cce) feat: Add 'outputs.result' to Container templates (#2584)
 * [51bc876d](https://github.com/argoproj/argo-workflows/commit/51bc876d576b6e61f508bb56ab9f2dfbf91b0e85) test: Fixes TestCreateWorkflowDryRun. Closes #2618 (#2628)
 * [212c6d75](https://github.com/argoproj/argo-workflows/commit/212c6d75fa7e5e8d568e80992d1924a2c51cd631) fix: Support minimal mysql version 5.7.8 (#2633)
 * [8facacee](https://github.com/argoproj/argo-workflows/commit/8facaceeb3515d804c3fd276b1802dbd6cf773e8) refactor: Refactor Template context interfaces (#2573)
 * [812813a2](https://github.com/argoproj/argo-workflows/commit/812813a288608e196006d4b8369702d020e61dc4) fix: fix test cases (#2631)
 * [ed028b25](https://github.com/argoproj/argo-workflows/commit/ed028b25f6c925a02596f90d722283856b003ff8) fix: Fix logging problems. See #2589 (#2595)
 * [d4e81238](https://github.com/argoproj/argo-workflows/commit/d4e8123816f3883d876ed715036c5d91d3fe0586) test: Fix teething problems (#2630)
 * [4aad6d55](https://github.com/argoproj/argo-workflows/commit/4aad6d55ed4e7a6c9eaa9a36b78e123655dd4ca4) chore: Add comments to issues (#2627)
 * [54f7a013](https://github.com/argoproj/argo-workflows/commit/54f7a0134ad9933608993bc09eda2032e7a16a80) test: Enhancements and repairs to e2e test framework (#2609)
 * [d95926fe](https://github.com/argoproj/argo-workflows/commit/d95926fe40e48932c25a0f70c671ad99f4149505) fix: Fix WorkflowTemplate icons to be more cohesive (#2607)
 * [0130e1fd](https://github.com/argoproj/argo-workflows/commit/0130e1fd85b7fa5b3b48b07b873858670e1a61a0) docs: Add fields and core concepts doc (#2610)
 * [5a1ac203](https://github.com/argoproj/argo-workflows/commit/5a1ac20352ab6042958f49a59d0f5227329f654c) fix: Fixes panic in toWorkflow method (#2604)
 * [51910292](https://github.com/argoproj/argo-workflows/commit/5191029247ac817dd6ce811e044459c45b2846ee) chore: Lint UI on CI, test diagnostics, skip bad test (#2587)
 * [232bb115](https://github.com/argoproj/argo-workflows/commit/232bb115eba8e2667653fdbdc9831bee112daa85) fix(error handling): use Errorf instead of New when throwing errors with formatted text (#2598)
 * [eeb2f97b](https://github.com/argoproj/argo-workflows/commit/eeb2f97be5c8787180af9f32f2d5e8baee63ed2f) fix(controller): dag continue on failed. Fixes #2596 (#2597)
 * [99c35129](https://github.com/argoproj/argo-workflows/commit/99c35129eae2d283c2e6d81b578d786b494aab11) docs: Fix inaccurate field name in docs (#2591)
 * [21c73779](https://github.com/argoproj/argo-workflows/commit/21c7377932825cd30f67a840d30853f4a48951fa) fix: Fixes lint errors (#2594)
 * [38aca5fa](https://github.com/argoproj/argo-workflows/commit/38aca5fa2a153393b3edb93be07ddce375ad13f4) chore: Added ClusterWorkflowTemplate RBAC on quick-start manifests (#2576)
 * [59f746e1](https://github.com/argoproj/argo-workflows/commit/59f746e1a551180d11e57676f8a2a384b3741599) feat: UI enhancement for Cluster Workflow Template (#2525)
 * [0801a428](https://github.com/argoproj/argo-workflows/commit/0801a4284a948bbeced83852af27a019e7b33535) fix(cli): Show lint errors of all files (#2552)
 * [c3535ba5](https://github.com/argoproj/argo-workflows/commit/c3535ba5ac85e1071a08ccbc930f2ff45cd2f295) docs: Fix wrong Configuring Your Artifact Repository document. (#2586)
 * [79217bc8](https://github.com/argoproj/argo-workflows/commit/79217bc89e892ee82bdd5018b2bba65425924d36) feat(archive): allow specifying a compression level (#2575)
 * [88d261d7](https://github.com/argoproj/argo-workflows/commit/88d261d7fa72faea19745de588c19de45e7fab88) fix: Use outputs of last child instead of retry node itslef (#2565)
 * [5c08292e](https://github.com/argoproj/argo-workflows/commit/5c08292e4ee388c1c5ca5291c601d50b2b3374e7) style: Correct the confused logic (#2577)
 * [3d146144](https://github.com/argoproj/argo-workflows/commit/3d14614459d50b96838fcfd83809ee29499e2917) fix: Fix bug in deleting pods. Fixes #2571 (#2572)
 * [cb739a68](https://github.com/argoproj/argo-workflows/commit/cb739a6897591969b959bd2feebd8ded97b9cb33) feat: Cluster scoped workflow template (#2451)
 * [c63e3d40](https://github.com/argoproj/argo-workflows/commit/c63e3d40be50479ca3c9a7325bfeb5fd9d31fa7c) feat: Show workflow duration in the index UI page (#2568)
 * [1520452a](https://github.com/argoproj/argo-workflows/commit/1520452a381319b414618d8429d6d7e0bb23790d) chore: Error -> Warn when Parent CronWf no longer exists (#2566)
 * [ffbb3b89](https://github.com/argoproj/argo-workflows/commit/ffbb3b899912f7af888d8216bd2ab55bc7106880) fix: Fixes empty/missing CM. Fixes #2285 (#2562)
 * [d0fba6f4](https://github.com/argoproj/argo-workflows/commit/d0fba6f443da013fd9ae8e48f658b337a0a18015) chore: fix typos in the workflow template docs (#2563)
 * [49801e32](https://github.com/argoproj/argo-workflows/commit/49801e32f1624ba20926f1b07a6ddafa2f162301) chore(docker): upgrade base image for executor image (#2561)
 * [c4efb8f8](https://github.com/argoproj/argo-workflows/commit/c4efb8f8b6e28a591794c018f5e61f55dd7d75e3) Add Riskified to the user list (#2558)
 * [8b92d33e](https://github.com/argoproj/argo-workflows/commit/8b92d33eb2f2de3b593459140576ea8eaff8fb4b) feat: Create K8S events on node completion. Closes #2274 (#2521)

### Contributors

 * Adam Gilat
 * Alex Collins
 * Alex Stein
 * CWen
 * Daisuke Taniwaki
 * Derek Wang
 * Dustin Specker
 * Ed Lee
 * Ejiah
 * Fabio Rigato
 * Gabriele Santomaggio
 * Heikki Kesa
 * Kannappan Sirchabesan
 * Marek Čermák
 * Michael Crenshaw
 * Mike Seddon
 * Niklas Hansson
 * Omer Kahani
 * Peng Li
 * Peter Salanki
 * Romain Di Giorgio
 * Saradhi Sreegiriraju
 * Saravanan Balasubramanian
 * Simon Behar
 * Song Juchao
 * Vardan Manucharyan
 * Wei Yan
 * dherman
 * lueenavarro
 * mark9white
 * shibataka000
 * tunoat

## v2.7.7 (2020-05-06)

 * [54154c61](https://github.com/argoproj/argo-workflows/commit/54154c61eb4fe9f052b04328fb00128568dc20d0) Update manifests to v2.7.7
 * [1254dd44](https://github.com/argoproj/argo-workflows/commit/1254dd440816dfb376b815032d02e1094850c5df) fix(cli): Re-establish watch on EOF (#2944)
 * [42d622b6](https://github.com/argoproj/argo-workflows/commit/42d622b63bc2517e24217b580e5ee4f1e3abb015) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)
 * [51ce1063](https://github.com/argoproj/argo-workflows/commit/51ce1063db2595221743eb42c274ed95d922bd48) fix: Print correct version in logs. (#2806)

### Contributors

 * Alex Collins
 * shibataka000

## v2.7.6 (2020-04-28)

 * [70facdb6](https://github.com/argoproj/argo-workflows/commit/70facdb67207dbe115a9029e365f8e974e6156bc) Update manifests to v2.7.6
 * [15f0d741](https://github.com/argoproj/argo-workflows/commit/15f0d741d64af5de3672ff7860c008152823654b) Fix TestGlobalScope
 * [3a906e65](https://github.com/argoproj/argo-workflows/commit/3a906e655780276b0b016ff751a9deb27fe5e77c) Fix build
 * [b6022a9b](https://github.com/argoproj/argo-workflows/commit/b6022a9bdde84d6cebe914c4015ce0255d0e9587) fix(controller): Include global params when using withParam (#2757)
 * [728287e8](https://github.com/argoproj/argo-workflows/commit/728287e8942b30acf02bf8ca60b5ec66e1a21058) fix: allow non path output params (#2680)
 * [83fa9406](https://github.com/argoproj/argo-workflows/commit/83fa94065dc60254a4b6873d5621eabd7f711498) fix: Add Step node outputs to global scope (#2826)
 * [462f6af0](https://github.com/argoproj/argo-workflows/commit/462f6af0c4aa08d535a1ee1982be87e94f62acf1) fix: Enforce metric naming validation (#2819)
 * [ed9f87c5](https://github.com/argoproj/argo-workflows/commit/ed9f87c55c30e7807a2c40e32942aa13e9036f12) fix: Allow empty strings in valueFrom.default (#2805)
 * [4d1690c4](https://github.com/argoproj/argo-workflows/commit/4d1690c437a686ad24c8d62dec5ea725e233876d) fix: Children of onExit nodes are also onExit nodes (#2722)
 * [7452c868](https://github.com/argoproj/argo-workflows/commit/7452c86858c7c8ce97a7b309b1775cad618d49a3) ci: Recurl (#2769)
 * [d40036c3](https://github.com/argoproj/argo-workflows/commit/d40036c3b28dbdcc2799e23c92a6c002f8d64514) fix(CLI): Re-establish workflow watch on disconnect. Fixes #2796 (#2830)
 * [01196831](https://github.com/argoproj/argo-workflows/commit/0119683174ada25151f7f6828b5a629ae4ae0b6a) test: Skip TestStopBehavior. See #2833 (#2834)
 * [f1a331a1](https://github.com/argoproj/argo-workflows/commit/f1a331a1c1639a6070bab51fb473cd37601fc474) fix: Artifact panic on unknown artifact. Fixes #2824 (#2829)

### Contributors

 * Alex Collins
 * Daisuke Taniwaki
 * Simon Behar

## v2.7.5 (2020-04-20)

 * [ede163e1](https://github.com/argoproj/argo-workflows/commit/ede163e1af83cfce29b519038be8127664421329) Update manifests to v2.7.5
 * [ab18ab4c](https://github.com/argoproj/argo-workflows/commit/ab18ab4c07c0881af30a0e7900922d9fdad4d546) Hard-code build opts
 * [ca77a5e6](https://github.com/argoproj/argo-workflows/commit/ca77a5e62e40d6d877700295cd37b51ebe8e0d6c) Resolve conflicts
 * [dacfa20f](https://github.com/argoproj/argo-workflows/commit/dacfa20fec70adfc6777b1d24d8b44c302d3bf46) fix: Error pending nodes w/o Pods unless resubmitPendingPods is set (#2721)
 * [2880f294](https://github.com/argoproj/argo-workflows/commit/2880f294ad7ba1e2012a64e10b60a9c2ccc86923) build: Retry curl 3x (#2768)
 * [e014c6e0](https://github.com/argoproj/argo-workflows/commit/e014c6e0ce67140f3d63a2a29206f304155386b6) Run make manifests
 * [42f49582](https://github.com/argoproj/argo-workflows/commit/42f495828cef9d00bf7f1d2afb32dc8fc8560911) test: Get tests running on release branches (#2767)
 * [ee107969](https://github.com/argoproj/argo-workflows/commit/ee107969da597ef383185b96eaf6d9aca289a7f6) fix: Improve cookie security. Fixes #2759 (#2763)
 * [e8cd8d77](https://github.com/argoproj/argo-workflows/commit/e8cd8d7765fedd7f381845d28804f5aa172f4d62) fix: Consider expanded tasks in getTaskFromNode (#2756)
 * [ca5cdc47](https://github.com/argoproj/argo-workflows/commit/ca5cdc47aab8d7c7acadec678df3edf159615641) fix: Reset all conditions when resubmitting (#2702)
 * [80dd96af](https://github.com/argoproj/argo-workflows/commit/80dd96af702d9002af480f3659a35914c4d71d14) feat: Add Kustomize as supported install option. Closes #2715 (#2724)
 * [306a1189](https://github.com/argoproj/argo-workflows/commit/306a1189b1a6b734a55d9c5a1ec83ce39c939f8d) fix: Maybe fix watch. Fixes #2678 (#2719)
 * [5b05519d](https://github.com/argoproj/argo-workflows/commit/5b05519d15874faf357da6e2e85ba97bd86d7a29) fix: Print correct version string. (#2713)

### Contributors

 * Alex Collins
 * Simon Behar

## v2.7.4 (2020-04-16)

 * [50b209ca](https://github.com/argoproj/argo-workflows/commit/50b209ca14c056fb470ebb8329e255304dd5be90) Update manifests to v2.7.4
 * [a8ecd513](https://github.com/argoproj/argo-workflows/commit/a8ecd513960c2810a7789e43f958517f0884ebd7) chore(docker): upgrade base image for executor image (#2561)

### Contributors

 * Dustin Specker
 * Simon Behar

## v2.7.3 (2020-04-15)

 * [66bd0425](https://github.com/argoproj/argo-workflows/commit/66bd0425280c801c06f21cf9a4bed46ee6f1e660) go mod tidy
 * [a8cd8b83](https://github.com/argoproj/argo-workflows/commit/a8cd8b83473ed3825392b9b4c6bd0090e9671e2a) Update manifests to v2.7.3
 * [b879f5c6](https://github.com/argoproj/argo-workflows/commit/b879f5c629f0cf5aeaa928f5b483c71ecbdedd55) fix: Don't use docker cache when building release images (#2707)
 * [60fe5bd3](https://github.com/argoproj/argo-workflows/commit/60fe5bd3cd9d205246dd96f1f06f2ff818853dc6) fix: Report metric emission errors via Conditions (#2676)
 * [04f79f2b](https://github.com/argoproj/argo-workflows/commit/04f79f2bbde4e650a37a45ca87cd047cd0fdbaa9) fix: Leaf task with continueOn should not fail DAG (#2668)

### Contributors

 * Alex Collins
 * Simon Behar

## v2.7.2 (2020-04-10)

 * [c52a65aa](https://github.com/argoproj/argo-workflows/commit/c52a65aa62426f5e874e1d3f1058af15c43eb35f) Update manifests to v2.7.2
 * [180f9e4d](https://github.com/argoproj/argo-workflows/commit/180f9e4d103782c910ea7a06c463d5de1b0a4ec4) fix: Consider offloaded and compressed node in retry and resume (#2645)
 * [a28fc4fb](https://github.com/argoproj/argo-workflows/commit/a28fc4fbea0e315e75d1fbddc052aeab7f011e51) fix: allow onExit to run if wf exceeds activeDeadlineSeconds. Fixes #2603 (#2605)
 * [6983e56b](https://github.com/argoproj/argo-workflows/commit/6983e56b26f805a152deee256c408325294945c2) fix: Support minimal mysql version 5.7.8 (#2633)
 * [4ab86db5](https://github.com/argoproj/argo-workflows/commit/4ab86db5bd7321f22ad12b2eae08c89c6724aba7) build: Fix codegen for releases (#2662)
 * [f99fa50f](https://github.com/argoproj/argo-workflows/commit/f99fa50fbf46a60f1b99e7b2916a92cacd52a40a) fix: Add DAG as default in UI filter and reorder (#2661)
 * [0a2c0d1a](https://github.com/argoproj/argo-workflows/commit/0a2c0d1a0e9010a612834154784f54379aa6d87c) fix: DAG should not fail if its tasks have continueOn (#2656)
 * [b7a8f6e6](https://github.com/argoproj/argo-workflows/commit/b7a8f6e69bbba6c312df7df188ac78a1a83c6278) fix: Don't attempt to resolve artifacts if task is going to be skipped (#2657)
 * [910db665](https://github.com/argoproj/argo-workflows/commit/910db665513cba47bbbbb4d8810936db2a6d5038) fix: Add input paremeters to metric scope (#2646)
 * [c17aeda0](https://github.com/argoproj/argo-workflows/commit/c17aeda0f72f6e61723520bfb68378552d9e01ff) test: Fix flakey DeleteCompleted test (#2659)
 * [b19753e3](https://github.com/argoproj/argo-workflows/commit/b19753e31afaab69530857be6073d62b1a05bcf1) ci: Fix codegen job (#2648)
 * [05e5ce6d](https://github.com/argoproj/argo-workflows/commit/05e5ce6db97418b248dec274ec5c3dd13585442b) fix: Sort log entries. (#2647)
 * [b35f2337](https://github.com/argoproj/argo-workflows/commit/b35f2337221e77f5deaad79c8b376cb41eeb1fb4) fix: Fix logs part 2 (#2639)
 * [733ace4d](https://github.com/argoproj/argo-workflows/commit/733ace4dd989b124dfaae99fc784f3d10d1ccb34) fix: Fix logging problems. See #2589 (#2595)
 * [bdef4e6e](https://github.com/argoproj/argo-workflows/commit/bdef4e6e59640951770cf8d44fa69edaf4f25f83) test: Fix teething problems (#2630)
 * [e99309b8](https://github.com/argoproj/argo-workflows/commit/e99309b8eb80f94773816e9134f153529cfa8e63) remove file
 * [83cca179](https://github.com/argoproj/argo-workflows/commit/83cca1795a644b60f9c6d50ca46987b15f407a93) chore: Add comments to issues (#2627)
 * [d608ff7d](https://github.com/argoproj/argo-workflows/commit/d608ff7d57f5439937ed318c689aa23c91e92f5a) test: Enhancements and repairs to e2e test framework (#2609)

### Contributors

 * Alex Collins
 * Derek Wang
 * Simon Behar
 * mark9white

## v2.7.1 (2020-04-07)

 * [2a3f59c1](https://github.com/argoproj/argo-workflows/commit/2a3f59c10ae260a460b6ad97a0cadd8667d4b488) Update manifests to v2.7.1
 * [25f673df](https://github.com/argoproj/argo-workflows/commit/25f673dfad7a32c2337c3696d639e8762f6f6eb8) fix: Fixes panic in toWorkflow method (#2604)
 * [8c799b1f](https://github.com/argoproj/argo-workflows/commit/8c799b1f002da0088b37159265aa78db43257894) make codegen
 * [8488033f](https://github.com/argoproj/argo-workflows/commit/8488033f6abf244da5f451ae2a58e62f8d5e08c7) chore: Lint UI on CI, test diagnostics, skip bad test (#2587)
 * [d02c4620](https://github.com/argoproj/argo-workflows/commit/d02c46200d0856bdfb8980325e3d7ed7b07c2d2a) fix(error handling): use Errorf instead of New when throwing errors with formatted text (#2598)
 * [c0d50ca2](https://github.com/argoproj/argo-workflows/commit/c0d50ca2ef43d3d5f9ae37e7f594db43dde9d361) fix(controller): dag continue on failed. Fixes #2596 (#2597)
 * [9ebe026a](https://github.com/argoproj/argo-workflows/commit/9ebe026a7a8d51072031400329f8a8a30c909195) docs: Fix inaccurate field name in docs (#2591)
 * [12ac3387](https://github.com/argoproj/argo-workflows/commit/12ac33877dbb64a74ef910de2e4182eb18ff5395) fix: Fixes lint errors (#2594)
 * [fd49ef2d](https://github.com/argoproj/argo-workflows/commit/fd49ef2d04051f7a04c61ac41be1e5d2079b5725) fix(cli): Show lint errors of all files (#2552)
 * [e697dbc5](https://github.com/argoproj/argo-workflows/commit/e697dbc5ec29c5d6e370f5ebf89b12b94c7a6ac2) fix: Use outputs of last child instead of retry node itslef (#2565)
 * [7623a4f3](https://github.com/argoproj/argo-workflows/commit/7623a4f3640c68e6893238a78ca30ca2f2790f8c) style: Correct the confused logic (#2577)
 * [f619f8ff](https://github.com/argoproj/argo-workflows/commit/f619f8ff1f7cfa19062ef1dca77177efa8338076) fix: Fix bug in deleting pods. Fixes #2571 (#2572)
 * [4c623bee](https://github.com/argoproj/argo-workflows/commit/4c623bee7ff51feaf3a6012258eb062043f0941d) feat: Show workflow duration in the index UI page (#2568)
 * [670b1653](https://github.com/argoproj/argo-workflows/commit/670b16539438d22d663c09d5d93ff28904c133c2) chore: Error -> Warn when Parent CronWf no longer exists (#2566)
 * [49c00156](https://github.com/argoproj/argo-workflows/commit/49c001562d8593161fe75cc7a45339f40ff2799c) Merge commit '2902e144ddba2f8c5a93cdfc8e2437c04705065b' into release-2.7
 * [f97be738](https://github.com/argoproj/argo-workflows/commit/f97be738b25ba7b29064198801a366d86593c8ae) fix: Fixes empty/missing CM. Fixes #2285 (#2562)
 * [4d1175eb](https://github.com/argoproj/argo-workflows/commit/4d1175eb68f6578ed5d599f877be9b4855d33ce9) Update manifests to v2.7.0
 * [2902e144](https://github.com/argoproj/argo-workflows/commit/2902e144ddba2f8c5a93cdfc8e2437c04705065b) feat: Add node type and phase filter to UI (#2555)
 * [fb74ba1c](https://github.com/argoproj/argo-workflows/commit/fb74ba1ce27b96473411c2c5cfe9a86972af589e) fix: Separate global scope processing from local scope building (#2528)
 * [be91ea01](https://github.com/argoproj/argo-workflows/commit/be91ea013f03feacfc6322cb7bb9fe7961bf83a6) Merge branch 'master' into release-2.7
 * [618b6dee](https://github.com/argoproj/argo-workflows/commit/618b6dee4de973b3f3ef1d1164a44b9cb176355e) fix: Fixes --kubeconfig flag. Fixes #2492 (#2553)

### Contributors

 * Alex Collins
 * Heikki Kesa
 * Niklas Hansson
 * Peng Li
 * Simon Behar
 * Vardan Manucharyan
 * Wei Yan

## v2.7.0-rc4 (2020-03-30)

 * [479fa48a](https://github.com/argoproj/argo-workflows/commit/479fa48a963b16903e11475b947b6a860d7a68ba) Update manifests to v2.7.0-rc4
 * [7431b7ff](https://github.com/argoproj/argo-workflows/commit/7431b7ffc8f93bcdfa567c0b43c79bdbdcb08f3c) Merge branch 'master' into release-2.7
 * [79dc969f](https://github.com/argoproj/argo-workflows/commit/79dc969f73e0ec90bdc202e936afec970ff66fc6) test: Increase timeout for flaky test (#2543)
 * [687cb73a](https://github.com/argoproj/argo-workflows/commit/687cb73a4f232f79c0379dd53200800dedb10eed) Merge branch 'master' into release-2.7
 * [15a3c990](https://github.com/argoproj/argo-workflows/commit/15a3c990359c40d791be64a34736e2a1ffa40178) feat: Report SpecWarnings in status.conditions (#2541)
 * [f142f30a](https://github.com/argoproj/argo-workflows/commit/f142f30a99aa9b12cdfbeed31129abb8d4266762) docs: Add example of template-level volume declaration. (#2542)
 * [33156a9c](https://github.com/argoproj/argo-workflows/commit/33156a9c31fd2206ef0a25a69abe99b052d29eda) Merge branch 'master' into release-2.7
 * [93b6be61](https://github.com/argoproj/argo-workflows/commit/93b6be619523ec3d9d8c52c75d9fa540e0272c7f) fix(archive): Fix bug that prevents listing archive workflows. Fixes … (#2523)
 * [b4c9c54f](https://github.com/argoproj/argo-workflows/commit/b4c9c54f79d902f2372192f017192fa519800fd8) fix: Omit config key in configure artifact document. (#2539)
 * [864bf1e5](https://github.com/argoproj/argo-workflows/commit/864bf1e56812b0ea1434b3952073a3e15dd9f046) fix: Show template on its own field in CLI (#2535)
 * [555aaf06](https://github.com/argoproj/argo-workflows/commit/555aaf06306d066268c04e4dd50ec2fecadd22cc) test: fix master (#2534)
 * [94862b98](https://github.com/argoproj/argo-workflows/commit/94862b985ef97e39d01fcafc95109b1b3507b21e) chore: Remove deprecated example (#2533)
 * [5e1e7829](https://github.com/argoproj/argo-workflows/commit/5e1e78295df4df0205a47adcedde6f1d5915af95) fix: Validate CronWorkflow before creation (#2532)
 * [c9241339](https://github.com/argoproj/argo-workflows/commit/c92413393404bd4caeb00606b3ba8775eeadf231) fix: Fix wrong assertions (#2531)
 * [67fe04bb](https://github.com/argoproj/argo-workflows/commit/67fe04bb78ac7b402bb6ef5b58d5cca33ecd74db) Revert "fix: fix template scope tests (#2498)" (#2526)
 * [ddfa1ad0](https://github.com/argoproj/argo-workflows/commit/ddfa1ad03f2835b64efac96eb4fb10d14e3ed987) docs: couple of examples for REST API usage of argo-server (#2519)
 * [30542be7](https://github.com/argoproj/argo-workflows/commit/30542be7a121cf8774352bf987ee658b5d8b96c8) chore(docs): Update docs for useSDKCreds (#2518)
 * [e2cc6988](https://github.com/argoproj/argo-workflows/commit/e2cc6988018e50956c05ed20c665ead01766278d) feat: More control over resuming suspended nodes Fixes #1893 (#1904)
 * [b2771249](https://github.com/argoproj/argo-workflows/commit/b2771249b0be9c782ee2ae190dd76ec3bba2a562) chore: minor fix and refactory (#2517)
 * [b1ad163a](https://github.com/argoproj/argo-workflows/commit/b1ad163ac17312d103c03bf6a88069f1b055ea7d) fix: fix template scope tests (#2498)

### Contributors

 * Alex Collins
 * Daisuke Taniwaki
 * Daniel Moran
 * Derek Wang
 * Ejiah
 * Simon Behar
 * Zach Aller
 * mark9white
 * maryoush

## v2.7.0-rc3 (2020-03-25)

 * [2bb0a7a4](https://github.com/argoproj/argo-workflows/commit/2bb0a7a4fd7bbf3da12ac449c3d20f8d5baf0995) Update manifests to v2.7.0-rc3
 * [d2a50750](https://github.com/argoproj/argo-workflows/commit/d2a507504c1eb01c5797b0eb2d0ab36f138d0ca5) Merge branch 'master' into release-2.7
 * [661d1b67](https://github.com/argoproj/argo-workflows/commit/661d1b6748b25488b288811dc5c0089b49b75a52) Increase client gRPC max size to match server (#2514)
 * [d8aa477f](https://github.com/argoproj/argo-workflows/commit/d8aa477f7f5089505df5fd26560f53f508f5b29f) fix: Fix potential panic (#2516)
 * [1afb692e](https://github.com/argoproj/argo-workflows/commit/1afb692eeb6a63cb0539cbc6762d8219b2b2dd00) fix: Allow runtime resolution for workflow parameter names (#2501)
 * [243ea338](https://github.com/argoproj/argo-workflows/commit/243ea338de767a39947f5fb4450321083a6f9c67) fix(controller): Ensure we copy any executor securityContext when creating wait containers; fixes #2512 (#2510)
 * [6e8c7bad](https://github.com/argoproj/argo-workflows/commit/6e8c7badcfa3f2eb7d5cb76f229e0570f3325f61) feat: Extend workflowDefaults to full Workflow and clean up docs and code (#2508)
 * [06cfc129](https://github.com/argoproj/argo-workflows/commit/06cfc1294a5a913a8b23bc4337ffa019717c4af2) feat: Native Google Cloud Storage support for artifact. Closes #1911 (#2484)
 * [999b1e1d](https://github.com/argoproj/argo-workflows/commit/999b1e1d9a6c9d69def35fd43d01b03c75748e62)  fix: Read ConfigMap before starting servers  (#2507)
 * [3d6e9b61](https://github.com/argoproj/argo-workflows/commit/3d6e9b61b3c7214ab5c62438e7d0ea750c3ae3f7) docs: Add separate ConfigMap doc for 2.7+ (#2505)
 * [e5bd6a7e](https://github.com/argoproj/argo-workflows/commit/e5bd6a7ed35a4d5ed75023719814541423affc48) fix(controller): Updates GetTaskAncestry to skip visited nod. Fixes #1907 (#1908)
 * [183a29e4](https://github.com/argoproj/argo-workflows/commit/183a29e40314ac97dfa6d7ff2e61f59ee6484279) docs: add official user (#2499)
 * [e636000b](https://github.com/argoproj/argo-workflows/commit/e636000bc457d654d487e065c1bcacd15ed75a74) feat: Updated arm64 support patch (#2491)
 * [559cb005](https://github.com/argoproj/argo-workflows/commit/559cb00596acbcc9a6a9cce001ca25fdcc561b2b) feat(ui): Report resources duration in UI. Closes #2460 (#2489)
 * [09291d9d](https://github.com/argoproj/argo-workflows/commit/09291d9d59e1fe51b1622b90ac18c6a5985b6a85) feat: Add default field in parameters.valueFrom (#2500)
 * [33cd4f2b](https://github.com/argoproj/argo-workflows/commit/33cd4f2b86e8b0993563d70c6b0d6f0f91b14535) feat(config): Make configuration mangement easier. Closes #2463 (#2464)

### Contributors

 * Alex Collins
 * Derek Wang
 * Rafael Rodrigues
 * Simon Behar
 * StoneHuang
 * Xin Wang
 * mark9white
 * vatine

## v2.7.0-rc2 (2020-03-23)

 * [240d7ad9](https://github.com/argoproj/argo-workflows/commit/240d7ad9298c60a69d4ce056e3d83ef9283a83ec) Update manifests to v2.7.0-rc2
 * [3bd1c4fc](https://github.com/argoproj/argo-workflows/commit/3bd1c4fc1c6e326194b1e94b01e83dd4b2b9c3e0) Merge branch 'master' into release-2.7
 * [f3df9660](https://github.com/argoproj/argo-workflows/commit/f3df9660be9f4d52975720e79bd01a6efe6fa18d) test: Fix test (#2490)
 * [bfaf1c21](https://github.com/argoproj/argo-workflows/commit/bfaf1c215f5491526edd020055ed8a15eb804a04) chore: Move quickstart Prometheus port to 9090 (#2487)
 * [487ed425](https://github.com/argoproj/argo-workflows/commit/487ed425840dc5698a4ef3a3c8f214b6c08949cc) feat: Logging the Pod Spec in controller log (#2476)
 * [96c80e3e](https://github.com/argoproj/argo-workflows/commit/96c80e3e2c6eb6867e360dde3dea97047b963c2f) fix(cli): Rearrange the order of chunk size argument in list command. Closes #2420 (#2485)
 * [47bd70a0](https://github.com/argoproj/argo-workflows/commit/47bd70a092debe980075195efd802e7bfb59c82f) chore: Fix Swagger for PDB to support Java client (#2483)
 * [53a10564](https://github.com/argoproj/argo-workflows/commit/53a10564aebc6ee17eb8e3e121b4c36b2a334b87) feat(usage): Report resource duration. Closes #1066 (#2219)
 * [063d9bc6](https://github.com/argoproj/argo-workflows/commit/063d9bc657b00e23ce7722d5d08ca69347fe7205) Revert "feat: Add support for arm64 platform (#2364)" (#2482)
 * [735d25e9](https://github.com/argoproj/argo-workflows/commit/735d25e9d719b409a7517685bcb4148278bef5a1) fix: Build image with SHA tag when a git tag is not available (#2479)
 * [c55bb3b2](https://github.com/argoproj/argo-workflows/commit/c55bb3b211be8ccc9680f8282f98f8a8bf647ca7) ci: Run lint on CI and fix GolangCI (#2470)
 * [e1c9f7af](https://github.com/argoproj/argo-workflows/commit/e1c9f7afcb4f685f615235ae1d0b6000add93635) fix ParallelSteps child type so replacements happen correctly; fixes argoproj-labs/argo-client-gen#5 (#2478)
 * [55c315db](https://github.com/argoproj/argo-workflows/commit/55c315db2e87fe28dcc26f49f4ee969bae9c7ea1) feat: Add support for IRSA and aws default provider chain. (#2468)
 * [c724c7c1](https://github.com/argoproj/argo-workflows/commit/c724c7c1afca646e09c0cb82acf8b59f8c413780) feat: Add support for arm64 platform (#2364)
 * [315dc164](https://github.com/argoproj/argo-workflows/commit/315dc164dcd24d0443b49ac95d49eb06b2c2a64f) feat: search archived wf by startat. Closes #2436 (#2473)

### Contributors

 * Alex Collins
 * Derek Wang
 * Huan-Cheng Chang
 * Michael Crenshaw
 * Saravanan Balasubramanian
 * Simon Behar
 * Xin Wang
 * Zach Aller

## v2.7.0-rc1 (2020-03-18)


### Contributors


## v2.7.0 (2020-03-31)

 * [4d1175eb](https://github.com/argoproj/argo-workflows/commit/4d1175eb68f6578ed5d599f877be9b4855d33ce9) Update manifests to v2.7.0
 * [be91ea01](https://github.com/argoproj/argo-workflows/commit/be91ea013f03feacfc6322cb7bb9fe7961bf83a6) Merge branch 'master' into release-2.7
 * [618b6dee](https://github.com/argoproj/argo-workflows/commit/618b6dee4de973b3f3ef1d1164a44b9cb176355e) fix: Fixes --kubeconfig flag. Fixes #2492 (#2553)
 * [479fa48a](https://github.com/argoproj/argo-workflows/commit/479fa48a963b16903e11475b947b6a860d7a68ba) Update manifests to v2.7.0-rc4
 * [7431b7ff](https://github.com/argoproj/argo-workflows/commit/7431b7ffc8f93bcdfa567c0b43c79bdbdcb08f3c) Merge branch 'master' into release-2.7
 * [79dc969f](https://github.com/argoproj/argo-workflows/commit/79dc969f73e0ec90bdc202e936afec970ff66fc6) test: Increase timeout for flaky test (#2543)
 * [687cb73a](https://github.com/argoproj/argo-workflows/commit/687cb73a4f232f79c0379dd53200800dedb10eed) Merge branch 'master' into release-2.7
 * [15a3c990](https://github.com/argoproj/argo-workflows/commit/15a3c990359c40d791be64a34736e2a1ffa40178) feat: Report SpecWarnings in status.conditions (#2541)
 * [f142f30a](https://github.com/argoproj/argo-workflows/commit/f142f30a99aa9b12cdfbeed31129abb8d4266762) docs: Add example of template-level volume declaration. (#2542)
 * [33156a9c](https://github.com/argoproj/argo-workflows/commit/33156a9c31fd2206ef0a25a69abe99b052d29eda) Merge branch 'master' into release-2.7
 * [93b6be61](https://github.com/argoproj/argo-workflows/commit/93b6be619523ec3d9d8c52c75d9fa540e0272c7f) fix(archive): Fix bug that prevents listing archive workflows. Fixes … (#2523)
 * [b4c9c54f](https://github.com/argoproj/argo-workflows/commit/b4c9c54f79d902f2372192f017192fa519800fd8) fix: Omit config key in configure artifact document. (#2539)
 * [864bf1e5](https://github.com/argoproj/argo-workflows/commit/864bf1e56812b0ea1434b3952073a3e15dd9f046) fix: Show template on its own field in CLI (#2535)
 * [555aaf06](https://github.com/argoproj/argo-workflows/commit/555aaf06306d066268c04e4dd50ec2fecadd22cc) test: fix master (#2534)
 * [94862b98](https://github.com/argoproj/argo-workflows/commit/94862b985ef97e39d01fcafc95109b1b3507b21e) chore: Remove deprecated example (#2533)
 * [5e1e7829](https://github.com/argoproj/argo-workflows/commit/5e1e78295df4df0205a47adcedde6f1d5915af95) fix: Validate CronWorkflow before creation (#2532)
 * [c9241339](https://github.com/argoproj/argo-workflows/commit/c92413393404bd4caeb00606b3ba8775eeadf231) fix: Fix wrong assertions (#2531)
 * [67fe04bb](https://github.com/argoproj/argo-workflows/commit/67fe04bb78ac7b402bb6ef5b58d5cca33ecd74db) Revert "fix: fix template scope tests (#2498)" (#2526)
 * [ddfa1ad0](https://github.com/argoproj/argo-workflows/commit/ddfa1ad03f2835b64efac96eb4fb10d14e3ed987) docs: couple of examples for REST API usage of argo-server (#2519)
 * [30542be7](https://github.com/argoproj/argo-workflows/commit/30542be7a121cf8774352bf987ee658b5d8b96c8) chore(docs): Update docs for useSDKCreds (#2518)
 * [e2cc6988](https://github.com/argoproj/argo-workflows/commit/e2cc6988018e50956c05ed20c665ead01766278d) feat: More control over resuming suspended nodes Fixes #1893 (#1904)
 * [b2771249](https://github.com/argoproj/argo-workflows/commit/b2771249b0be9c782ee2ae190dd76ec3bba2a562) chore: minor fix and refactory (#2517)
 * [2bb0a7a4](https://github.com/argoproj/argo-workflows/commit/2bb0a7a4fd7bbf3da12ac449c3d20f8d5baf0995) Update manifests to v2.7.0-rc3
 * [b1ad163a](https://github.com/argoproj/argo-workflows/commit/b1ad163ac17312d103c03bf6a88069f1b055ea7d) fix: fix template scope tests (#2498)
 * [d2a50750](https://github.com/argoproj/argo-workflows/commit/d2a507504c1eb01c5797b0eb2d0ab36f138d0ca5) Merge branch 'master' into release-2.7
 * [661d1b67](https://github.com/argoproj/argo-workflows/commit/661d1b6748b25488b288811dc5c0089b49b75a52) Increase client gRPC max size to match server (#2514)
 * [d8aa477f](https://github.com/argoproj/argo-workflows/commit/d8aa477f7f5089505df5fd26560f53f508f5b29f) fix: Fix potential panic (#2516)
 * [1afb692e](https://github.com/argoproj/argo-workflows/commit/1afb692eeb6a63cb0539cbc6762d8219b2b2dd00) fix: Allow runtime resolution for workflow parameter names (#2501)
 * [243ea338](https://github.com/argoproj/argo-workflows/commit/243ea338de767a39947f5fb4450321083a6f9c67) fix(controller): Ensure we copy any executor securityContext when creating wait containers; fixes #2512 (#2510)
 * [6e8c7bad](https://github.com/argoproj/argo-workflows/commit/6e8c7badcfa3f2eb7d5cb76f229e0570f3325f61) feat: Extend workflowDefaults to full Workflow and clean up docs and code (#2508)
 * [06cfc129](https://github.com/argoproj/argo-workflows/commit/06cfc1294a5a913a8b23bc4337ffa019717c4af2) feat: Native Google Cloud Storage support for artifact. Closes #1911 (#2484)
 * [999b1e1d](https://github.com/argoproj/argo-workflows/commit/999b1e1d9a6c9d69def35fd43d01b03c75748e62)  fix: Read ConfigMap before starting servers  (#2507)
 * [3d6e9b61](https://github.com/argoproj/argo-workflows/commit/3d6e9b61b3c7214ab5c62438e7d0ea750c3ae3f7) docs: Add separate ConfigMap doc for 2.7+ (#2505)
 * [e5bd6a7e](https://github.com/argoproj/argo-workflows/commit/e5bd6a7ed35a4d5ed75023719814541423affc48) fix(controller): Updates GetTaskAncestry to skip visited nod. Fixes #1907 (#1908)
 * [183a29e4](https://github.com/argoproj/argo-workflows/commit/183a29e40314ac97dfa6d7ff2e61f59ee6484279) docs: add official user (#2499)
 * [e636000b](https://github.com/argoproj/argo-workflows/commit/e636000bc457d654d487e065c1bcacd15ed75a74) feat: Updated arm64 support patch (#2491)
 * [559cb005](https://github.com/argoproj/argo-workflows/commit/559cb00596acbcc9a6a9cce001ca25fdcc561b2b) feat(ui): Report resources duration in UI. Closes #2460 (#2489)
 * [09291d9d](https://github.com/argoproj/argo-workflows/commit/09291d9d59e1fe51b1622b90ac18c6a5985b6a85) feat: Add default field in parameters.valueFrom (#2500)
 * [33cd4f2b](https://github.com/argoproj/argo-workflows/commit/33cd4f2b86e8b0993563d70c6b0d6f0f91b14535) feat(config): Make configuration mangement easier. Closes #2463 (#2464)
 * [240d7ad9](https://github.com/argoproj/argo-workflows/commit/240d7ad9298c60a69d4ce056e3d83ef9283a83ec) Update manifests to v2.7.0-rc2
 * [3bd1c4fc](https://github.com/argoproj/argo-workflows/commit/3bd1c4fc1c6e326194b1e94b01e83dd4b2b9c3e0) Merge branch 'master' into release-2.7
 * [f3df9660](https://github.com/argoproj/argo-workflows/commit/f3df9660be9f4d52975720e79bd01a6efe6fa18d) test: Fix test (#2490)
 * [bfaf1c21](https://github.com/argoproj/argo-workflows/commit/bfaf1c215f5491526edd020055ed8a15eb804a04) chore: Move quickstart Prometheus port to 9090 (#2487)
 * [487ed425](https://github.com/argoproj/argo-workflows/commit/487ed425840dc5698a4ef3a3c8f214b6c08949cc) feat: Logging the Pod Spec in controller log (#2476)
 * [96c80e3e](https://github.com/argoproj/argo-workflows/commit/96c80e3e2c6eb6867e360dde3dea97047b963c2f) fix(cli): Rearrange the order of chunk size argument in list command. Closes #2420 (#2485)
 * [47bd70a0](https://github.com/argoproj/argo-workflows/commit/47bd70a092debe980075195efd802e7bfb59c82f) chore: Fix Swagger for PDB to support Java client (#2483)
 * [53a10564](https://github.com/argoproj/argo-workflows/commit/53a10564aebc6ee17eb8e3e121b4c36b2a334b87) feat(usage): Report resource duration. Closes #1066 (#2219)
 * [063d9bc6](https://github.com/argoproj/argo-workflows/commit/063d9bc657b00e23ce7722d5d08ca69347fe7205) Revert "feat: Add support for arm64 platform (#2364)" (#2482)
 * [735d25e9](https://github.com/argoproj/argo-workflows/commit/735d25e9d719b409a7517685bcb4148278bef5a1) fix: Build image with SHA tag when a git tag is not available (#2479)
 * [c55bb3b2](https://github.com/argoproj/argo-workflows/commit/c55bb3b211be8ccc9680f8282f98f8a8bf647ca7) ci: Run lint on CI and fix GolangCI (#2470)
 * [e1c9f7af](https://github.com/argoproj/argo-workflows/commit/e1c9f7afcb4f685f615235ae1d0b6000add93635) fix ParallelSteps child type so replacements happen correctly; fixes argoproj-labs/argo-client-gen#5 (#2478)
 * [55c315db](https://github.com/argoproj/argo-workflows/commit/55c315db2e87fe28dcc26f49f4ee969bae9c7ea1) feat: Add support for IRSA and aws default provider chain. (#2468)
 * [c724c7c1](https://github.com/argoproj/argo-workflows/commit/c724c7c1afca646e09c0cb82acf8b59f8c413780) feat: Add support for arm64 platform (#2364)
 * [315dc164](https://github.com/argoproj/argo-workflows/commit/315dc164dcd24d0443b49ac95d49eb06b2c2a64f) feat: search archived wf by startat. Closes #2436 (#2473)
 * [55702224](https://github.com/argoproj/argo-workflows/commit/55702224cdb1da698b84fdcfb7ae1199afde8eee) Update manifests to v2.7.0-rc1
 * [23d230bd](https://github.com/argoproj/argo-workflows/commit/23d230bd54e04af264a0977545db365a2c0d6a6d) feat(ui): add Env to Node Container Info pane. Closes #2471 (#2472)
 * [10a0789b](https://github.com/argoproj/argo-workflows/commit/10a0789b9477b1b6c1b7adda71101925989d02de) fix: ParallelSteps swagger.json (#2459)
 * [a59428e7](https://github.com/argoproj/argo-workflows/commit/a59428e72c092e12b17c2bd8f22ee2e86eec043f) fix: Duration must be a string. Make it a string. (#2467)
 * [47bc6f3b](https://github.com/argoproj/argo-workflows/commit/47bc6f3b7450895aa35f9275b326077bb08453b5) feat: Add `argo stop` command (#2352)
 * [14478bc0](https://github.com/argoproj/argo-workflows/commit/14478bc07f42ae9ee362cc1531b1cf00d923211d) feat(ui): Add the ability to have links to logging facility in UI. Closes #2438 (#2443)
 * [2864c745](https://github.com/argoproj/argo-workflows/commit/2864c745877c9e44a5b14140f4317f8e2d45975a) chore: make codegen + make start (#2465)
 * [a85f62c5](https://github.com/argoproj/argo-workflows/commit/a85f62c5e8ee1a51f5fa8fd715ebdf4140d2483d) feat: Custom, step-level, and usage metrics (#2254)
 * [64ac0298](https://github.com/argoproj/argo-workflows/commit/64ac02980ea641d92f22328442e5a12893600d67) fix: Deprecate template.{template,templateRef,arguments} (#2447)
 * [6cb79e4e](https://github.com/argoproj/argo-workflows/commit/6cb79e4e5414277932e5cf755761cec4cda7e1b7) fix: Postgres persistence SSL Mode (#1866) (#1867)
 * [2205c0e1](https://github.com/argoproj/argo-workflows/commit/2205c0e162c93645a5ae1d883aec6ae33fec3c8f) fix(controller): Updates to add condition to workflow status. Fixes #2421 (#2453)
 * [9d96ab2f](https://github.com/argoproj/argo-workflows/commit/9d96ab2ffd6cec9fc65f0182234e103664ab9cd5) fix: make dir if needed (#2455)
 * [5346609e](https://github.com/argoproj/argo-workflows/commit/5346609e79de4fc4f6fc9d833f0f2a85790821aa) test: Maybe fix TestPendingRetryWorkflowWithRetryStrategy. Fixes #2446 (#2456)
 * [3448ccf9](https://github.com/argoproj/argo-workflows/commit/3448ccf91cbff2e3901a99e23e57a0e1ad97044c) fix: Delete PVCs unless WF Failed/Errored (#2449)
 * [782bc8e7](https://github.com/argoproj/argo-workflows/commit/782bc8e7c5d1fd102f1a16d07f209aed3bfdc689) fix: Don't error when optional artifacts are not found (#2445)
 * [fc18f3cf](https://github.com/argoproj/argo-workflows/commit/fc18f3cf27c525ff94a6b190a0aff0a9a3d45426) chore: Master needs codegen (#2448)
 * [32fc2f78](https://github.com/argoproj/argo-workflows/commit/32fc2f78212d031f99f1dfc5ad3a3642617ce7e7) feat: Support workflow templates submission. Closes #2007 (#2222)
 * [050a143d](https://github.com/argoproj/argo-workflows/commit/050a143d7639ad38dc01a685edce536917409a37) fix(archive): Fix edge-cast error for archiving. Fixes #2427 (#2434)
 * [9455c1b8](https://github.com/argoproj/argo-workflows/commit/9455c1b88d85f80091aa4fd2c8d4dc53b6cc73f8) doc: update CHANGELOG.md (#2425)
 * [1baa7ee4](https://github.com/argoproj/argo-workflows/commit/1baa7ee4ec7149afe789d73ed6e64abfe13387a7) feat(ui): cache namespace selection. Closes #2439 (#2441)
 * [91d29881](https://github.com/argoproj/argo-workflows/commit/91d29881f41642273fe0494bef70f2b9c41350e2) feat: Retry pending nodes (#2385)
 * [7094433e](https://github.com/argoproj/argo-workflows/commit/7094433e12b668236a87c034445daf88d659231f) test: Skip flakey tests in operator_template_scope_test.go. See #2432 (#2433)
 * [30332b14](https://github.com/argoproj/argo-workflows/commit/30332b14fb1043e22a66db594f1af252c5932853) fix: Allow numbers in steps.args.params.value (#2414)
 * [e9a06dde](https://github.com/argoproj/argo-workflows/commit/e9a06dde297e9f907d10ec88da93fbb90df5ebaf) feat: instanceID support for argo server. Closes #2004 (#2365)
 * [3f8be0cd](https://github.com/argoproj/argo-workflows/commit/3f8be0cd48963958c493e7669a1d03bb719b375a) fix "Unable to retry workflow" on argo-server (#2409)
 * [dd3029ab](https://github.com/argoproj/argo-workflows/commit/dd3029abdd13a6b4053934660ca1078e23780809) docs: Example showing how to use default settings for workflow spec. Related to ##2388 (#2411)
 * [13508828](https://github.com/argoproj/argo-workflows/commit/135088284acd1ced004374d20928c017fbf9cac7) fix: Check child node status before backoff in retry (#2407)
 * [b59419c9](https://github.com/argoproj/argo-workflows/commit/b59419c9f58422f60c7d5185c89b4d55ac278660) fix: Build with the correct version if you check out a specific version (#2423)
 * [6d834d54](https://github.com/argoproj/argo-workflows/commit/6d834d545bc816cde9b74b224116d9746db5b799) chore: document BASE_HREF (#2418)
 * [184c3653](https://github.com/argoproj/argo-workflows/commit/184c3653085bc8821bdcd65f5476fbe24f24b00e) fix: Remove lazy workflow template (#2417)
 * [918d0d17](https://github.com/argoproj/argo-workflows/commit/918d0d17c0455b6a0644c6d851dbea3f945db21c) docs: Added Survey Results (#2416)
 * [20d6e27b](https://github.com/argoproj/argo-workflows/commit/20d6e27bdf11389f23b2efe1be4ef737f333221d) Update CONTRIBUTING.md (#2410)
 * [f2ca045e](https://github.com/argoproj/argo-workflows/commit/f2ca045e1cad03d5ec7566ff7200fd8ca575ec5d) feat: Allow WF metadata spec on Cron WF (#2400)
 * [068a4336](https://github.com/argoproj/argo-workflows/commit/068a43362b2088f53d408623bc7ab078e0e7a9d0) fix: Correctly report version. Fixes #2374 (#2402)
 * [e19a398c](https://github.com/argoproj/argo-workflows/commit/e19a398c810fada879facd624a7663501306e1ef) Update pull_request_template.md (#2401)
 * [7c99c109](https://github.com/argoproj/argo-workflows/commit/7c99c109e3dd726f6453c94a594d69bca709ccf6) chore: Fix typo (#2405)
 * [175b164c](https://github.com/argoproj/argo-workflows/commit/175b164c33aee7fe2873df60915a881502ec9163) Change font family for class yaml (#2394)
 * [d1194755](https://github.com/argoproj/argo-workflows/commit/d11947558bc758e5102238162036650890731ec6) fix: Don't display Retry Nodes in UI if len(children) == 1 (#2390)
 * [b8623ec7](https://github.com/argoproj/argo-workflows/commit/b8623ec7b4a19713f5965cc0d628f26b81af39a2) docs: Create USERS.md (#2389)
 * [1d21d3f5](https://github.com/argoproj/argo-workflows/commit/1d21d3f5600feca4b63e3dc4b1d94d2830fa6e24) fix(doc strings): Fix bug related documentation/clean up of default configurations #2331 (#2388)
 * [77e11fc4](https://github.com/argoproj/argo-workflows/commit/77e11fc4838ff92de9d9cae91159fb88755dff0b) chore: add noindex meta tag to solve #2381; add kustomize to build docs (#2383)
 * [42200fad](https://github.com/argoproj/argo-workflows/commit/42200fad45b4925b8f4aac48a580e6e369de2ad4) fix(controller): Mount volumes defined in script templates. Closes #1722 (#2377)
 * [96af36d8](https://github.com/argoproj/argo-workflows/commit/96af36d85d70d4721b1ac3e6e0ef14db65e7aec3) fix: duration must be a string (#2380)
 * [7bf08192](https://github.com/argoproj/argo-workflows/commit/7bf0819267543808d80acaa5f39f40c1fdba511e) fix: Say no logs were outputted when pod is done (#2373)
 * [847c3507](https://github.com/argoproj/argo-workflows/commit/847c3507dafdd3ff2cd1acca4669c1a54a680ee2) fix(ui): Removed tailLines from EventSource (#2330)
 * [3890a124](https://github.com/argoproj/argo-workflows/commit/3890a12431bfacc83cc75d862f956ddfbc1d2a37) feat: Allow for setting default configurations for workflows, Fixes #1923, #2044 (#2331)
 * [81ab5385](https://github.com/argoproj/argo-workflows/commit/81ab538594ad0428a97e99f34b18041f31a1c753) Update readme (#2379)
 * [91810273](https://github.com/argoproj/argo-workflows/commit/91810273318ab3ea84ecf73b9d0a6f1ba7f43c2a) feat: Log version (structured) on component start-up (#2375)
 * [d0572a74](https://github.com/argoproj/argo-workflows/commit/d0572a74069a1a6c38fa860e1964fa0564fd28cd) docs: Make Getting Started agnostic to version (#2371)
 * [d3a3f6b1](https://github.com/argoproj/argo-workflows/commit/d3a3f6b195b984a97eb214e99f29498c0bd39c85) docs: Add Prudential to the users list (#2353)
 * [4714c880](https://github.com/argoproj/argo-workflows/commit/4714c88099f25a3ffe2db14574016b069f85335d) chore: Master needs codegen (#2369)
 * [5b6b8257](https://github.com/argoproj/argo-workflows/commit/5b6b8257890d3c7aa93d8e98b10090add08a22e1) fix(docker): fix streaming of combined stdout/stderr (#2368)
 * [97438313](https://github.com/argoproj/argo-workflows/commit/9743831306714cc85b762487ac070f77e25f85d6) fix: Restart server ConfigMap watch when closed (#2360)
 * [64d0cec0](https://github.com/argoproj/argo-workflows/commit/64d0cec080bb27e147632fb8993f75e16c92e4a7) chore: Master needs make lint (#2361)
 * [12386fc6](https://github.com/argoproj/argo-workflows/commit/12386fc6029f5533921c75797455efc62e4cc9ce) fix: rerun codegen after merging OSS artifact support (#2357)
 * [40586ed5](https://github.com/argoproj/argo-workflows/commit/40586ed5c3a539d2e13f8a34509a40367563874a) fix: Always validate templates (#2342)
 * [897db894](https://github.com/argoproj/argo-workflows/commit/897db89434079fa3b3b902253d1c624c39af1422) feat: Add support for Alibaba Cloud OSS artifact (#1919)
 * [7e2dba03](https://github.com/argoproj/argo-workflows/commit/7e2dba03674219ec35e88b2ce785fdf120f855fd) feat(ui): Circles for nodes (#2349)
 * [e85f6169](https://github.com/argoproj/argo-workflows/commit/e85f6169fadf503c220ecc2385334fc0f2073ca4) chore: update getting started guide to use 2.6.0 (#2350)
 * [7ae4ec78](https://github.com/argoproj/argo-workflows/commit/7ae4ec78f627b620197a323b190fa33c31ffcbcc) docker: remove NopCloser from the executor. (#2345)
 * [5895b364](https://github.com/argoproj/argo-workflows/commit/5895b3642a691629b6c8aa145cf17627a227665f) feat: Expose workflow.paramteres with JSON string of all params (#2341)
 * [a9850b43](https://github.com/argoproj/argo-workflows/commit/a9850b43b16e05d9f74f52c789a8475d493f4c92) Fix the default (#2346)
 * [c3763d34](https://github.com/argoproj/argo-workflows/commit/c3763d34ed02bc63d166e8ef4f2f724786a2cf7c) fix: Simplify completion detection logic in DAGs (#2344)
 * [d8a9ea09](https://github.com/argoproj/argo-workflows/commit/d8a9ea09be395241664d929e8dbca7d02aecb049) fix(auth): Fixed returning  expired  Auth token for GKE (#2327)
 * [6fef0454](https://github.com/argoproj/argo-workflows/commit/6fef0454073fb60b4dd6216accef07f5195ec7e9) fix: Add timezone support to startingDeadlineSeconds (#2335)
 * [c28731b9](https://github.com/argoproj/argo-workflows/commit/c28731b9f602b3ed79c76dd4e3383f39419e463f) chore: Add go mod tidy to codegen (#2332)
 * [a66c8802](https://github.com/argoproj/argo-workflows/commit/a66c8802c7d0dbec9b13d408b91655e41531a97a) feat: Allow Worfklows to be submitted as files from UI (#2340)
 * [a9c1d547](https://github.com/argoproj/argo-workflows/commit/a9c1d547e5b044d9d375ebf527c132b0545455b0) docs: Update Argo Rollouts description (#2336)
 * [8672b97f](https://github.com/argoproj/argo-workflows/commit/8672b97f134dacb553592c367399229891aaf5c8) fix(Dockerfile): Using `--no-install-recommends` (Optimization) (#2329)
 * [c3fe1ae1](https://github.com/argoproj/argo-workflows/commit/c3fe1ae1b3ad662bc94a4b46e72f20c957dd4475) fix(ui): fixed worflow UI refresh. Fixes ##2337 (#2338)
 * [d7690e32](https://github.com/argoproj/argo-workflows/commit/d7690e32faf2ac5842468831daf1443283703c25) feat(ui): Adds ability zoom and hide successful steps. POC (#2319)
 * [e9e13d4c](https://github.com/argoproj/argo-workflows/commit/e9e13d4cbbc0f456c2d1dafbb1a95739127f6ab4) feat: Allow retry strategy on non-leaf nodes, eg for step groups. Fixes #1891 (#1892)
 * [62e6db82](https://github.com/argoproj/argo-workflows/commit/62e6db826ea4e0a02ac839bc59ec5f70ce3b9b29) feat: Ability to include or exclude fields in the response (#2326)
 * [52ba89ad](https://github.com/argoproj/argo-workflows/commit/52ba89ad4911fd4c7b13fd6dbc7f019971354ea0) fix(swagger): Fix the broken swagger. (#2317)
 * [efb8a1ac](https://github.com/argoproj/argo-workflows/commit/efb8a1ac8fc9961f0caa00ec6df7cf006d25e87a) docs: Update CODE_OF_CONDUCT.md (#2323)
 * [1c77e864](https://github.com/argoproj/argo-workflows/commit/1c77e864ac004f9cc6aff0e204ea9fd4b056c84b) fix(swagger): Fix the broken swagger. (#2317)
 * [aa052346](https://github.com/argoproj/argo-workflows/commit/aa05234694bc79e649e02adcc9790778cef0154d) feat: Support workflow level poddisruptionbudge for workflow pods #1728 (#2286)
 * [8da88d7e](https://github.com/argoproj/argo-workflows/commit/8da88d7ed20d8e533252e610337c15737445a225) chore: update getting-started guide for 2.5.2 and apply other tweaks (#2311)
 * [2f97c261](https://github.com/argoproj/argo-workflows/commit/2f97c261a9eafa022b464e0aea5b5d34d6f99100) build: Improve reliability of release. (#2309)
 * [5dcb84bb](https://github.com/argoproj/argo-workflows/commit/5dcb84bb549429ba5f46a21873e873a2c1c5bf67) chore(cli): Clean-up code. Closes #2117 (#2303)
 * [e49dd8c4](https://github.com/argoproj/argo-workflows/commit/e49dd8c4f9f69551be7e31c2044fef043d2992b2) chore(cli): Migrate `argo logs` to use API client. See #2116 (#2177)
 * [5c3d9cf9](https://github.com/argoproj/argo-workflows/commit/5c3d9cf93079ecbbfb024ea273d6e57e56c2506d) chore(cli): Migrate `argo wait` to use API client. See #2116 (#2282)
 * [baf03f67](https://github.com/argoproj/argo-workflows/commit/baf03f672728a6ed8b2aeb986d84ce35e9d7717a) fix(ui): Provide a link to archived logs. Fixes #2300 (#2301)

### Contributors

 * Aaron Curtis
 * Alex Collins
 * Antoine Dao
 * Antonio Macías Ojeda
 * Daisuke Taniwaki
 * Daniel Moran
 * Derek Wang
 * EDGsheryl
 * Ejiah
 * Huan-Cheng Chang
 * Michael Crenshaw
 * Mingjie Tang
 * Mukulikak
 * Niklas Hansson
 * Pascal VanDerSwalmen
 * Pratik Raj
 * Rafael Rodrigues
 * Roman Galeev
 * Saradhi Sreegiriraju
 * Saravanan Balasubramanian
 * Simon Behar
 * StoneHuang
 * Theodore Messinezis
 * Tristan Colgate-McFarlane
 * Xin Wang
 * Zach Aller
 * fsiegmund
 * mark9white
 * maryoush
 * tkilpela
 * vatine
 * モハメド

## v2.6.4 (2020-04-15)

 * [e6caf984](https://github.com/argoproj/argo-workflows/commit/e6caf9845976c9c61e5dc66842c30fd41bde952b) Update manifests to v2.6.4
 * [5aeb3ecf](https://github.com/argoproj/argo-workflows/commit/5aeb3ecf3b58708722243692017ef562636a2d14) fix: Don't use docker cache when building release images (#2707)

### Contributors

 * Alex Collins
 * Simon Behar

## v2.6.3 (2020-03-16)

 * [2e8ac609](https://github.com/argoproj/argo-workflows/commit/2e8ac609cba1ad3d69c765dea19bc58ea4b8a8c3) Update manifests to v2.6.3
 * [9633bad1](https://github.com/argoproj/argo-workflows/commit/9633bad1d0b9084a1094b8524cac06b7407268e7) fix: Delete PVCs unless WF Failed/Errored (#2449)
 * [a0b933a0](https://github.com/argoproj/argo-workflows/commit/a0b933a0ed03a8ee89087f7d24305aa161872290) fix: Don't error when optional artifacts are not found (#2445)
 * [d1513e68](https://github.com/argoproj/argo-workflows/commit/d1513e68b17af18469930556762e880d656d2584) fix: Allow numbers in steps.args.params.value (#2414)
 * [9c608e50](https://github.com/argoproj/argo-workflows/commit/9c608e50a51bfb2101482144086f35c157fc5204) fix: Check child node status before backoff in retry (#2407)
 * [8ad643c4](https://github.com/argoproj/argo-workflows/commit/8ad643c402bb68ee0f549966e2ed55633af98fd2) fix: Say no logs were outputted when pod is done (#2373)
 * [60fcfe90](https://github.com/argoproj/argo-workflows/commit/60fcfe902a8f376bef096a3dcd58466ba0f7a164) fix(ui): Removed tailLines from EventSource (#2330)
 * [6ec81d35](https://github.com/argoproj/argo-workflows/commit/6ec81d351f6dfb8a6441d4793f5b8203c4a1b0bd) fix "Unable to retry workflow" on argo-server (#2409)
 * [642ccca2](https://github.com/argoproj/argo-workflows/commit/642ccca249598e754fa99cdbf51f5d8a452d4e76) fix: Build with the correct version if you check out a specific version (#2423)

### Contributors

 * Alex Collins
 * EDGsheryl
 * Simon Behar
 * tkilpela

## v2.6.2 (2020-03-12)

 * [be0a0bb4](https://github.com/argoproj/argo-workflows/commit/be0a0bb46ba50ed4d48ab2fd74c81216d4558b56) Update manifests to v2.6.2
 * [09ec9a0d](https://github.com/argoproj/argo-workflows/commit/09ec9a0df76b7234f50e4a6ccecdd14c2c27fc02) fix(docker): fix streaming of combined stdout/stderr (#2368)
 * [64b6f3a4](https://github.com/argoproj/argo-workflows/commit/64b6f3a48865e466f8efe58d923187ab0fbdd550) fix: Correctly report version. Fixes #2374 (#2402)

### Contributors

 * Alex Collins

## v2.6.1 (2020-03-04)

 * [842739d7](https://github.com/argoproj/argo-workflows/commit/842739d7831cc5b417c4f524ed85288408a32bbf) Update manifests to v2.6.1
 * [64c6aa43](https://github.com/argoproj/argo-workflows/commit/64c6aa43e34a25674180cbd5073a72f634df99cd) fix: Restart server ConfigMap watch when closed (#2360)
 * [9ff429aa](https://github.com/argoproj/argo-workflows/commit/9ff429aa4eea32330194968fda2a2386aa252644) fix: Always validate templates (#2342)
 * [51c3ad33](https://github.com/argoproj/argo-workflows/commit/51c3ad3357fa621fddb77f154f1411a817d1623f) fix: Simplify completion detection logic in DAGs (#2344)
 * [3de7e513](https://github.com/argoproj/argo-workflows/commit/3de7e5139b55f754624acd50da3852874c82fd76) fix(auth): Fixed returning  expired  Auth token for GKE (#2327)
 * [fa2a3023](https://github.com/argoproj/argo-workflows/commit/fa2a302336afab94d357c379c4849d772edc1915) fix: Add timezone support to startingDeadlineSeconds (#2335)
 * [a9b6a254](https://github.com/argoproj/argo-workflows/commit/a9b6a254ab2312737bef9756159a05e31b52d781) fix(ui): fixed worflow UI refresh. Fixes ##2337 (#2338)
 * [793c072e](https://github.com/argoproj/argo-workflows/commit/793c072edba207ae12bd07d7b47e827cec8d914e) docker: remove NopCloser from the executor. (#2345)
 * [5d3bdd56](https://github.com/argoproj/argo-workflows/commit/5d3bdd56607eea962183a9e45009e3d08fafdf9b) Update manifests to v2.6.0

### Contributors

 * Alex Collins
 * Derek Wang
 * Saravanan Balasubramanian
 * Simon Behar
 * Tristan Colgate-McFarlane
 * fsiegmund

## v2.6.0-rc3 (2020-02-25)

 * [fc24de46](https://github.com/argoproj/argo-workflows/commit/fc24de462b9b7aa5882ee2ecc2051853c919da37) Update manifests to v2.6.0-rc3
 * [ef297d4c](https://github.com/argoproj/argo-workflows/commit/ef297d4c328c2fa0b6379cb8b8ed7208e8955e9a) Merge branch 'rel-enhance' into release-2.6
 * [bc9de69f](https://github.com/argoproj/argo-workflows/commit/bc9de69f1e5d002ac33e6f6fdbd89b18c6225667) Merge branch 'master' into release-2.6
 * [39ab8046](https://github.com/argoproj/argo-workflows/commit/39ab804696010e17314f3256622226ab7d496768) build: Improve reliability of release.
 * [b5947165](https://github.com/argoproj/argo-workflows/commit/b5947165564246a3c55375500f3fc1aea4dc6966) feat: Create API clients (#2218)
 * [214c4515](https://github.com/argoproj/argo-workflows/commit/214c451535ebeb6e68f1599c2c0a4a4d174ade25) fix(controller): Get correct Step or DAG name. Fixes #2244 (#2304)
 * [19460276](https://github.com/argoproj/argo-workflows/commit/19460276159ee04386d9bf5539e157d5b7cb8ea2) Merge branch 'master' into release-2.6
 * [c4d26466](https://github.com/argoproj/argo-workflows/commit/c4d2646612d190ec73f38ec840259110a9ce89e0) fix: Remove active wf from Cron when deleted (#2299)
 * [0eff938d](https://github.com/argoproj/argo-workflows/commit/0eff938d62764abffcfdc741dfaca5fd6c8ae53f) fix: Skip empty withParam steps (#2284)
 * [636ea443](https://github.com/argoproj/argo-workflows/commit/636ea443c38869beaccfff19f4b72dd23755b2ff) chore(cli): Migrate `argo terminate` to use API client. See #2116 (#2280)
 * [d0a9b528](https://github.com/argoproj/argo-workflows/commit/d0a9b528e383a1b9ea737e0f919c93969d3d393b) chore(cli): Migrate `argo template` to use API client. Closes #2115 (#2296)
 * [f69a6c5f](https://github.com/argoproj/argo-workflows/commit/f69a6c5fa487d3b6c2d5383aa588695d6dcdb6de) chore(cli): Migrate `argo cron` to use API client. Closes #2114 (#2295)
 * [80b9b590](https://github.com/argoproj/argo-workflows/commit/80b9b590ebca1dbe69c5c7df0dd1c2f1feae5eea) chore(cli): Migrate `argo retry` to use API client. See #2116 (#2277)

### Contributors

 * Alex Collins
 * Derek Wang
 * Simon Behar

## v2.6.0-rc2 (2020-02-21)

 * [9f7ef614](https://github.com/argoproj/argo-workflows/commit/9f7ef614fb8a4291d64c6a4374910edb67678da9) Update manifests to v2.6.0-rc2
 * [21163db3](https://github.com/argoproj/argo-workflows/commit/21163db3e876978663a804f1ab035731b49d9ce5) Merge branch 'master' into release-2.6
 * [cdbc6194](https://github.com/argoproj/argo-workflows/commit/cdbc61945e09ae4dab8a56a085d050a0c358b896) fix(sequence): broken in 2.5. Fixes #2248 (#2263)
 * [0d3955a7](https://github.com/argoproj/argo-workflows/commit/0d3955a7f617c58f74c2892894036dfbdebaa5aa) refactor(cli): 2x simplify migration to API client. See #2116 (#2290)
 * [df8493a1](https://github.com/argoproj/argo-workflows/commit/df8493a1c05d3bac19a8f95f608d5543ba96ac82) fix: Start Argo server with out Configmap #2285 (#2293)
 * [51cdf95b](https://github.com/argoproj/argo-workflows/commit/51cdf95b18c8532f0bdb72c7ca20d56bdafc3a60) doc: More detail for namespaced installation (#2292)
 * [a7302697](https://github.com/argoproj/argo-workflows/commit/a730269767bdd10c4a9c5901c7e73f6bb25429c2) build(swagger): Fix argo-server swagger so version does not change. (#2291)
 * [47b4fc28](https://github.com/argoproj/argo-workflows/commit/47b4fc284df3cff9dfb4ea6622a0236bf1613096) fix(cli): Reinstate `argo wait`. Fixes #2281 (#2283)
 * [1793887b](https://github.com/argoproj/argo-workflows/commit/1793887b95446d341102b81523931403e30ef0f7) chore(cli): Migrate `argo suspend` and `argo resume` to use API client. See #2116 (#2275)
 * [1f3d2f5a](https://github.com/argoproj/argo-workflows/commit/1f3d2f5a0c9d772d7b204b13529f56bc33703a45) chore(cli): Update `argo resubmit` to support client API. See #2116 (#2276)
 * [c33f6cda](https://github.com/argoproj/argo-workflows/commit/c33f6cda39a3be40cc2e829c4c8d0b4c54704896) fix(archive): Fix bug in migrating cluster name. Fixes #2272 (#2279)
 * [fb0acbbf](https://github.com/argoproj/argo-workflows/commit/fb0acbbffb0a7c754223e516f55a40b957277fe4) fix: Fixes double logging in UI. Fixes #2270 (#2271)
 * [acf37c2d](https://github.com/argoproj/argo-workflows/commit/acf37c2db0d69def2045a6fc0f37a2b9db0c41fe) fix: Correctly report version. Fixes #2264 (#2268)
 * [b30f1af6](https://github.com/argoproj/argo-workflows/commit/b30f1af6528046a3af29c82ac1e29d9d300eec22) fix: Removes Template.Arguments as this is never used. Fixes #2046 (#2267)

### Contributors

 * Alex Collins
 * Derek Wang
 * Saravanan Balasubramanian
 * mark9white

## v2.6.0-rc1 (2020-02-19)


### Contributors


## v2.6.0 (2020-02-28)

 * [5d3bdd56](https://github.com/argoproj/argo-workflows/commit/5d3bdd56607eea962183a9e45009e3d08fafdf9b) Update manifests to v2.6.0
 * [fc24de46](https://github.com/argoproj/argo-workflows/commit/fc24de462b9b7aa5882ee2ecc2051853c919da37) Update manifests to v2.6.0-rc3
 * [ef297d4c](https://github.com/argoproj/argo-workflows/commit/ef297d4c328c2fa0b6379cb8b8ed7208e8955e9a) Merge branch 'rel-enhance' into release-2.6
 * [bc9de69f](https://github.com/argoproj/argo-workflows/commit/bc9de69f1e5d002ac33e6f6fdbd89b18c6225667) Merge branch 'master' into release-2.6
 * [39ab8046](https://github.com/argoproj/argo-workflows/commit/39ab804696010e17314f3256622226ab7d496768) build: Improve reliability of release.
 * [b5947165](https://github.com/argoproj/argo-workflows/commit/b5947165564246a3c55375500f3fc1aea4dc6966) feat: Create API clients (#2218)
 * [214c4515](https://github.com/argoproj/argo-workflows/commit/214c451535ebeb6e68f1599c2c0a4a4d174ade25) fix(controller): Get correct Step or DAG name. Fixes #2244 (#2304)
 * [19460276](https://github.com/argoproj/argo-workflows/commit/19460276159ee04386d9bf5539e157d5b7cb8ea2) Merge branch 'master' into release-2.6
 * [c4d26466](https://github.com/argoproj/argo-workflows/commit/c4d2646612d190ec73f38ec840259110a9ce89e0) fix: Remove active wf from Cron when deleted (#2299)
 * [0eff938d](https://github.com/argoproj/argo-workflows/commit/0eff938d62764abffcfdc741dfaca5fd6c8ae53f) fix: Skip empty withParam steps (#2284)
 * [636ea443](https://github.com/argoproj/argo-workflows/commit/636ea443c38869beaccfff19f4b72dd23755b2ff) chore(cli): Migrate `argo terminate` to use API client. See #2116 (#2280)
 * [d0a9b528](https://github.com/argoproj/argo-workflows/commit/d0a9b528e383a1b9ea737e0f919c93969d3d393b) chore(cli): Migrate `argo template` to use API client. Closes #2115 (#2296)
 * [f69a6c5f](https://github.com/argoproj/argo-workflows/commit/f69a6c5fa487d3b6c2d5383aa588695d6dcdb6de) chore(cli): Migrate `argo cron` to use API client. Closes #2114 (#2295)
 * [80b9b590](https://github.com/argoproj/argo-workflows/commit/80b9b590ebca1dbe69c5c7df0dd1c2f1feae5eea) chore(cli): Migrate `argo retry` to use API client. See #2116 (#2277)
 * [9f7ef614](https://github.com/argoproj/argo-workflows/commit/9f7ef614fb8a4291d64c6a4374910edb67678da9) Update manifests to v2.6.0-rc2
 * [21163db3](https://github.com/argoproj/argo-workflows/commit/21163db3e876978663a804f1ab035731b49d9ce5) Merge branch 'master' into release-2.6
 * [cdbc6194](https://github.com/argoproj/argo-workflows/commit/cdbc61945e09ae4dab8a56a085d050a0c358b896) fix(sequence): broken in 2.5. Fixes #2248 (#2263)
 * [0d3955a7](https://github.com/argoproj/argo-workflows/commit/0d3955a7f617c58f74c2892894036dfbdebaa5aa) refactor(cli): 2x simplify migration to API client. See #2116 (#2290)
 * [df8493a1](https://github.com/argoproj/argo-workflows/commit/df8493a1c05d3bac19a8f95f608d5543ba96ac82) fix: Start Argo server with out Configmap #2285 (#2293)
 * [51cdf95b](https://github.com/argoproj/argo-workflows/commit/51cdf95b18c8532f0bdb72c7ca20d56bdafc3a60) doc: More detail for namespaced installation (#2292)
 * [a7302697](https://github.com/argoproj/argo-workflows/commit/a730269767bdd10c4a9c5901c7e73f6bb25429c2) build(swagger): Fix argo-server swagger so version does not change. (#2291)
 * [47b4fc28](https://github.com/argoproj/argo-workflows/commit/47b4fc284df3cff9dfb4ea6622a0236bf1613096) fix(cli): Reinstate `argo wait`. Fixes #2281 (#2283)
 * [1793887b](https://github.com/argoproj/argo-workflows/commit/1793887b95446d341102b81523931403e30ef0f7) chore(cli): Migrate `argo suspend` and `argo resume` to use API client. See #2116 (#2275)
 * [1f3d2f5a](https://github.com/argoproj/argo-workflows/commit/1f3d2f5a0c9d772d7b204b13529f56bc33703a45) chore(cli): Update `argo resubmit` to support client API. See #2116 (#2276)
 * [c33f6cda](https://github.com/argoproj/argo-workflows/commit/c33f6cda39a3be40cc2e829c4c8d0b4c54704896) fix(archive): Fix bug in migrating cluster name. Fixes #2272 (#2279)
 * [fb0acbbf](https://github.com/argoproj/argo-workflows/commit/fb0acbbffb0a7c754223e516f55a40b957277fe4) fix: Fixes double logging in UI. Fixes #2270 (#2271)
 * [acf37c2d](https://github.com/argoproj/argo-workflows/commit/acf37c2db0d69def2045a6fc0f37a2b9db0c41fe) fix: Correctly report version. Fixes #2264 (#2268)
 * [b30f1af6](https://github.com/argoproj/argo-workflows/commit/b30f1af6528046a3af29c82ac1e29d9d300eec22) fix: Removes Template.Arguments as this is never used. Fixes #2046 (#2267)
 * [bd89f9cb](https://github.com/argoproj/argo-workflows/commit/bd89f9cbe1bd0ab4d70fa0fa919278fb8266956d) Update manifests to v2.6.0-rc1
 * [79b09ed4](https://github.com/argoproj/argo-workflows/commit/79b09ed43550bbf958c631386f8514b2d474062c) fix: Removed duplicate Watch Command (#2262)
 * [b5c47266](https://github.com/argoproj/argo-workflows/commit/b5c47266c4e33ba8739277ea43fe4b8023542367) feat(ui): Add filters for archived workflows (#2257)
 * [d30aa335](https://github.com/argoproj/argo-workflows/commit/d30aa3357738a272e1864d9f352f3c160c1608fc) fix(archive): Return correct next page info. Fixes #2255 (#2256)
 * [8c97689e](https://github.com/argoproj/argo-workflows/commit/8c97689e5d9d956a0dd9493c4c53088a6e8a87fa) fix: Ignore bookmark events for restart. Fixes #2249 (#2253)
 * [63858eaa](https://github.com/argoproj/argo-workflows/commit/63858eaa919c430bf0683dc33d81c94d4237b45b) fix(offloading): Change offloaded nodes datatype to JSON to support 1GB. Fixes #2246 (#2250)
 * [4d88374b](https://github.com/argoproj/argo-workflows/commit/4d88374b70e272eb454395f066c371ad2977abef) Add Cartrack into officially using Argo (#2251)
 * [d309d5c1](https://github.com/argoproj/argo-workflows/commit/d309d5c1a134502a11040757ff85230f7199510f) feat(archive): Add support to filter list by labels. Closes #2171 (#2205)
 * [79f13373](https://github.com/argoproj/argo-workflows/commit/79f13373fd8c4d0e9c9ff56f2133fa6009d1ed07) feat: Add a new symbol for suspended nodes. Closes #1896 (#2240)
 * [82b48821](https://github.com/argoproj/argo-workflows/commit/82b48821a83e012ac7ea5740d45addb046e3c8ee) Fix presumed typo (#2243)
 * [af94352f](https://github.com/argoproj/argo-workflows/commit/af94352f6c93e4bdbb69a1fc92b5d596c647d1a0) feat: Reduce API calls when changing filters. Closes #2231 (#2232)
 * [a58cbc7d](https://github.com/argoproj/argo-workflows/commit/a58cbc7dd12fe919614768ca0fa4714853091b7f) BasisAI uses Argo (#2241)
 * [68e3c9fd](https://github.com/argoproj/argo-workflows/commit/68e3c9fd9f597b6b4599dc7e9dbc5d71252ac5cf) feat: Add Pod Name to UI (#2227)
 * [eef85072](https://github.com/argoproj/argo-workflows/commit/eef85072691a9302e4168a072cfdffed6908a5d6) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)
 * [4e4565cd](https://github.com/argoproj/argo-workflows/commit/4e4565cdbb5d2e5c215af1b8b2f03695b45c2bba) feat: Label workflow-created pvc with workflow name (#1890)
 * [8bd5ecbc](https://github.com/argoproj/argo-workflows/commit/8bd5ecbc16f1063ef332ca3445ed9a9b953efa4f) fix: display error message when deleting archived workflow fails. (#2235)
 * [ae381ae5](https://github.com/argoproj/argo-workflows/commit/ae381ae57e5d2d3226114c773264595b3d672c39) feat: This add support to enable debug logging for all CLI commands (#2212)
 * [1b1927fc](https://github.com/argoproj/argo-workflows/commit/1b1927fc6fa519b7bf277e4273f4c7cede16ed64) feat(swagger): Adds a make api/argo-server/swagger.json (#2216)
 * [5d7b4c8c](https://github.com/argoproj/argo-workflows/commit/5d7b4c8c2d5819116b060f1ee656571b77b873bd) Update README.md (#2226)
 * [170abfa5](https://github.com/argoproj/argo-workflows/commit/170abfa5875227a74381764de93aa345aa5cca19) chore: Run `go mod tidy` (#2225)
 * [2981e6ff](https://github.com/argoproj/argo-workflows/commit/2981e6ff4c053b898a425d366fa696c8530ffeb0) fix: Enforce UnknownField requirement in WorkflowStep (#2210)
 * [affc235c](https://github.com/argoproj/argo-workflows/commit/affc235cd07bb01ee0ef8bb226b7a4c6470dc1e7) feat: Add failed node info to exit handler (#2166)
 * [af1f6d60](https://github.com/argoproj/argo-workflows/commit/af1f6d60078c5562b2c9d538d2b104c277c82593) fix: UI Responsive design on filter box (#2221)
 * [a445049c](https://github.com/argoproj/argo-workflows/commit/a445049ca3f67b499b9bef95c9e43075c8e10250) fix: Fixed race condition in kill container method. Fixes #1884 (#2208)
 * [2672857f](https://github.com/argoproj/argo-workflows/commit/2672857f2fbaabf727e354b040b1af2431ea70e5) feat: upgrade to Go 1.13. Closes #1375 (#2097)
 * [7466efa9](https://github.com/argoproj/argo-workflows/commit/7466efa99adfeeb3833b02c5afa7a33cdf8f87bc) feat: ArtifactRepositoryRef ConfigMap is now taken from the workflow namespace (#1821)
 * [50f331d0](https://github.com/argoproj/argo-workflows/commit/50f331d0e686f603440500c026ffe9d1f5133c1c) build: Fix ARGO_TOKEN (#2215)
 * [7f090351](https://github.com/argoproj/argo-workflows/commit/7f09035156e5dce68af203df21e688476d05ce12) test: Correctly report diagnostics (#2214)
 * [f2bd74bc](https://github.com/argoproj/argo-workflows/commit/f2bd74bca116f1b1ad9990aef9dbad98e0068900) fix: Remove quotes from UI (#2213)
 * [62f46680](https://github.com/argoproj/argo-workflows/commit/62f4668064e71046532505a11c67a675aa29afcf) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [e30b77fc](https://github.com/argoproj/argo-workflows/commit/e30b77fcd5b140074065491988985779b800c4d7) feat(ui): Add label filter to workflow list page. Fixes #802 (#2196)
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)

### Contributors

 * Aaron Curtis
 * Alex Collins
 * Alexey Volkov
 * Daisuke Taniwaki
 * Derek Wang
 * Dineshmohan Rajaveeran
 * Huan-Cheng Chang
 * Jialu Zhu
 * Juan C. Muller
 * Nasrudin Bin Salim
 * Nick Groszewski
 * Rafał Bigaj
 * Roman Galeev
 * Saravanan Balasubramanian
 * Simon Behar
 * Tom Wieczorek
 * Tristan Colgate-McFarlane
 * fsiegmund
 * mark9white
 * mdvorakramboll
 * tkilpela

## v2.5.3-rc4 (2020-01-27)


### Contributors


## v2.5.2 (2020-02-24)

 * [4b25e2ac](https://github.com/argoproj/argo-workflows/commit/4b25e2ac1d495991261e97c86d211d658423ab7f) Update manifests to v2.5.2
 * [6092885c](https://github.com/argoproj/argo-workflows/commit/6092885c91c040435cba7134e30e8c1c92574c7b) fix(archive): Fix bug in migrating cluster name. Fixes #2272 (#2279)

### Contributors

 * Alex Collins

## v2.5.1 (2020-02-20)

 * [fb496a24](https://github.com/argoproj/argo-workflows/commit/fb496a244383822af5d4c71431062cebd6de0ee4) Update manifests to v2.5.1
 * [61114d62](https://github.com/argoproj/argo-workflows/commit/61114d62ec7b01c1cd9c68dd1917732673ddbca2) fix: Fixes double logging in UI. Fixes #2270 (#2271)
 * [4737c8a2](https://github.com/argoproj/argo-workflows/commit/4737c8a26c30ca98e3ef2ea6147e8bcee45decbb) fix: Correctly report version. Fixes #2264 (#2268)
 * [e096feaf](https://github.com/argoproj/argo-workflows/commit/e096feaf330b7ebf8c2be31c5f0f932a1670158c) fix: Removed duplicate Watch Command (#2262)
 * [11d2232e](https://github.com/argoproj/argo-workflows/commit/11d2232edfc4ac1176cc1ed4a47c77aeec48aeb7) Update manifests to v2.5.0
 * [661f8a11](https://github.com/argoproj/argo-workflows/commit/661f8a1113a2a02eb521a6a5e5286d38b42e5f84) fix: Ignore bookmark events for restart. Fixes #2249 (#2253)
 * [6c1a6601](https://github.com/argoproj/argo-workflows/commit/6c1a6601b151efb4a9ada9a9c997130e319daf3f) fix(offloading): Change offloaded nodes datatype to JSON to support 1GB. Fixes #2246 (#2250)
 * [befd3594](https://github.com/argoproj/argo-workflows/commit/befd3594f1d54e9e1bedd08d781025d43e6bed5b) Update manifests to v2.5.0-rc12
 * [4670c99e](https://github.com/argoproj/argo-workflows/commit/4670c99ec819dcc91c807def6c2b4e7128e2b987) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)
 * [47d9a41a](https://github.com/argoproj/argo-workflows/commit/47d9a41a902c18797e36c9371e3ab7a3e261605b) Update manifests to v2.5.0-rc11
 * [04917cde](https://github.com/argoproj/argo-workflows/commit/04917cde047098c1fdf07965a01e07c97d2e36af) fix: Remove quotes from UI (#2213)
 * [2705a114](https://github.com/argoproj/argo-workflows/commit/2705a114195aa7dfc2617f2ebba54fbf603b1fd2) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [cee3a771](https://github.com/argoproj/argo-workflows/commit/cee3a771bda5667183b704af0da92e3a257d67ee) Merge commit '930ced39241b427a521b609c403e7a39f6cc8c48' into release-2.5
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)
 * [b557eeb9](https://github.com/argoproj/argo-workflows/commit/b557eeb981f0e7ac3b12f4e861ff9ca099338143) Update manifests to v2.5.0-rc10
 * [f8b8efc7](https://github.com/argoproj/argo-workflows/commit/f8b8efc788f42edf7c2015fe675e23aed93975d5) Merge branch 'master' into release-2.5
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [073216c8](https://github.com/argoproj/argo-workflows/commit/073216c8fc3c440f3f0d84afd9bf5c3adf28a9b9) Merge branch 'master' into release-2.5
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [cbfbb98b](https://github.com/argoproj/argo-workflows/commit/cbfbb98b504e110ec61003efa6f28a0dde52b24f) Merge branch 'master' into release-2.5
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)

### Contributors

 * Alex Collins
 * Dineshmohan Rajaveeran
 * Saravanan Balasubramanian
 * Simon Behar
 * Tom Wieczorek
 * fsiegmund
 * tkilpela

## v2.5.0-rc9 (2020-02-06)

 * [bea41b49](https://github.com/argoproj/argo-workflows/commit/bea41b498fd3ece93e0d2f344b58ca31e1f28080) Update manifests to v2.5.0-rc9
 * [58f38ba7](https://github.com/argoproj/argo-workflows/commit/58f38ba788b9569bf2698de48c93f0725f375686) Merge branch 'master' into release-2.5
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [3fed36f0](https://github.com/argoproj/argo-workflows/commit/3fed36f0016f2317a0d59158c74b8c7fb024aa2d) Merge branch 'master' into release-2.5
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [4d53cc47](https://github.com/argoproj/argo-workflows/commit/4d53cc47b261d69b8beea1a7627384f64cb234e4) Merge branch 'master' into release-2.5
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)

### Contributors

 * Alex Collins
 * Juan C. Muller
 * Saravanan Balasubramanian
 * Simon Behar
 * fsiegmund

## v2.5.0-rc8 (2020-02-03)

 * [392de814](https://github.com/argoproj/argo-workflows/commit/392de814471abb3ca6c12ad7243c72c1a52591ff) Update manifests to v2.5.0-rc8
 * [3d84a935](https://github.com/argoproj/argo-workflows/commit/3d84a9356b7ccc12973ee048a5c25681e8c10777) Merge branch 'master' into release-2.5
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [9b327658](https://github.com/argoproj/argo-workflows/commit/9b3276580c8abd503320f4c1fc045651d881e45f) Merge branch 'master' into release-2.5
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [a61f1457](https://github.com/argoproj/argo-workflows/commit/a61f14576728d95bc9117554d4e11e6bfa7ca0be) Merge branch 'master' into release-2.5
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [1d0a5234](https://github.com/argoproj/argo-workflows/commit/1d0a52342e8d3c9c343b92f9a292fced20d48dd1) Merge branch 'master' into release-2.5
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [adbe67c0](https://github.com/argoproj/argo-workflows/commit/adbe67c00f63ec2a6ab3b59c9085204e2f72863d) Merge branch 'master' into release-2.5
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [7bee02d8](https://github.com/argoproj/argo-workflows/commit/7bee02d89f68ef207bf038e40ca2c04646e33492) build: correct version

### Contributors

 * Alex Collins
 * Simon Behar
 * Tristan Colgate-McFarlane
 * fsiegmund

## v2.5.0-rc7 (2020-01-31)

 * [40e7ca37](https://github.com/argoproj/argo-workflows/commit/40e7ca37cf5834e5ad8f799ea9ede61f7549a7d9) Update manifests to v2.5.0-rc7
 * [98702cae](https://github.com/argoproj/argo-workflows/commit/98702caea70c18f4a3c1b8c83cb00d58c83c0885) Merge branch 'master' into release-2.5
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [26f9bcad](https://github.com/argoproj/argo-workflows/commit/26f9bcadcf8adb255de3477b20aff26ca29123b4) Merge branch 'master' into release-2.5
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [3c8eced6](https://github.com/argoproj/argo-workflows/commit/3c8eced61b2c952268c4a256d9a9e9106b1147dd) Merge branch 'master' into release-2.5
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)

### Contributors

 * Alex Collins
 * Jialu Zhu
 * Saravanan Balasubramanian
 * Simon Behar

## v2.5.0-rc6 (2020-01-30)

 * [7b7fcf01](https://github.com/argoproj/argo-workflows/commit/7b7fcf01a2c7819aa7da8d4ab6e5ae93e5b81436) Update manifests to v2.5.0-rc6
 * [c1cb415e](https://github.com/argoproj/argo-workflows/commit/c1cb415ef13ae5f171716bb67753f84bec892135) Merge branch 'master' into release-2.5
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)

### Contributors

 * Alex Collins
 * Derek Wang
 * Rafał Bigaj
 * Simon Behar

## v2.5.0-rc5 (2020-01-29)

 * [4609f3d7](https://github.com/argoproj/argo-workflows/commit/4609f3d70fef44c35634c743b15060d7865e0879) Update manifests to v2.5.0-rc5
 * [af14e452](https://github.com/argoproj/argo-workflows/commit/af14e4523f0df8064adf0b6b1a00e11a40b54caf) Merge branch 'master' into release-2.5
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [ed223e9d](https://github.com/argoproj/argo-workflows/commit/ed223e9d1e922ac35c56b2b1e7c02819fe3762e3) build: use the latest tag for codegen
 * [2db76d24](https://github.com/argoproj/argo-workflows/commit/2db76d2426e6ebe4da2d4cfd96d34401487ecffc) Merge branch 'master' into release-2.5
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)

### Contributors

 * Alex Collins
 * Daisuke Taniwaki
 * Derek Wang
 * Nick Groszewski

## v2.5.0-rc4 (2020-01-27)

 * [2afcb0f2](https://github.com/argoproj/argo-workflows/commit/2afcb0f27cd32cf5a6600f8d4826ace578f9ee20) Update manifests to v2.5.0-rc4
 * [e2f4d640](https://github.com/argoproj/argo-workflows/commit/e2f4d6406c1aea3a0dcbc63a05532cd8e7839c34) Merge branch 'master' into release-2.5
 * [c4f49cf0](https://github.com/argoproj/argo-workflows/commit/c4f49cf074ad874996145674d635165f6256ca15) refactor: Move server code (cmd/server/ -> server/) (#2071)
 * [2542454c](https://github.com/argoproj/argo-workflows/commit/2542454c1daf61bc3826fa370c21799059904093) fix(controller): Do not crash if cm is empty. Fixes #2069 (#2070)

### Contributors

 * Alex Collins
 * Simon Behar

## v2.5.0-rc3 (2020-01-27)

 * [091c2f7e](https://github.com/argoproj/argo-workflows/commit/091c2f7e892bed287cf701cafe9bee0ccf5c0ce8) lint
 * [67a51858](https://github.com/argoproj/argo-workflows/commit/67a5185895379e7299be3739c4d708132b0a6fc8) build: simplify release
 * [3572d4df](https://github.com/argoproj/argo-workflows/commit/3572d4dfb59d888ccfa06a97e81c00d31a6a14ef) build: force tag
 * [f1c03bb3](https://github.com/argoproj/argo-workflows/commit/f1c03bb375f4120b6faee385945c4826cdeee6df) build: only tag if committing changes
 * [30775fac](https://github.com/argoproj/argo-workflows/commit/30775fac8a92cf7bdf84ada11746a7643d464885) Update manifests to v2.5.0-rc3
 * [9afa6783](https://github.com/argoproj/argo-workflows/commit/9afa6783292b85353f8775aa799aecae623f26fc) Merge branch 'master' into release-2.5
 * [85fa9aaf](https://github.com/argoproj/argo-workflows/commit/85fa9aafa70a98ce999157bb900971f24bd81101) fix: Do not expect workflowChange to always be defined (#2068)
 * [6f65bc2b](https://github.com/argoproj/argo-workflows/commit/6f65bc2b77ddcf4616c78d6db4955bf839a0c21a) fix: "base64 -d" not always available, using "base64 --decode" (#2067)
 * [5e755c61](https://github.com/argoproj/argo-workflows/commit/5e755c61e15b6fc4eed5000f91dfdef9cc266c74) build: correct image tag
 * [e7cf886b](https://github.com/argoproj/argo-workflows/commit/e7cf886bb51735c27dce7f800a7cd62ad0d72c3d) ci: install kustomize
 * [5328389a](https://github.com/argoproj/argo-workflows/commit/5328389aac14da059148ad840a9a72c322947e9e) adds "verify-manifests" target
 * [ef1c403e](https://github.com/argoproj/argo-workflows/commit/ef1c403e3f49cf06f9bbed2bfdcc7d89548031cb) fix: generate no-db manifests
 * [6f2c8802](https://github.com/argoproj/argo-workflows/commit/6f2c880280d490ba746a86d828ade61d8b58c7a5) feat(ui): Use cookies in the UI. Closes #1949 (#2058)
 * [4592aec6](https://github.com/argoproj/argo-workflows/commit/4592aec6805ce1110edcb7dc4e3e7454a2042441) fix(api): Change `CronWorkflowName` to `Name`. Fixes #1982 (#2033)
 * [a37562a0](https://github.com/argoproj/argo-workflows/commit/a37562a0e2af06f932332a53573d12920b3301e8) ci: DEV_IMAGE=true
 * [4676a946](https://github.com/argoproj/argo-workflows/commit/4676a9465ac4c2faa856f971706766f46e08edef) try and improve the release tasks
 * [fe64ae11](https://github.com/argoproj/argo-workflows/commit/fe64ae11c7e2ca3bd3cec93b38036be82eee39e7) Merge branch 'master' into release-2.5
 * [e26c11af](https://github.com/argoproj/argo-workflows/commit/e26c11af747651c6642cf0abd3cbc4ccac7b95de) fix: only run archived wf testing when persistence is enabled (#2059)
 * [b3cab5df](https://github.com/argoproj/argo-workflows/commit/b3cab5dfbb5e5973b1dc448946d16ee0cd690d6a) fix: Fix permission test cases (#2035)

### Contributors

 * Alex Collins
 * Derek Wang
 * Simon Behar

## v2.5.0-rc2 (2020-01-24)


### Contributors


## v2.5.0-rc12 (2020-02-13)

 * [befd3594](https://github.com/argoproj/argo-workflows/commit/befd3594f1d54e9e1bedd08d781025d43e6bed5b) Update manifests to v2.5.0-rc12
 * [4670c99e](https://github.com/argoproj/argo-workflows/commit/4670c99ec819dcc91c807def6c2b4e7128e2b987) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)

### Contributors

 * Alex Collins

## v2.5.0-rc11 (2020-02-11)

 * [47d9a41a](https://github.com/argoproj/argo-workflows/commit/47d9a41a902c18797e36c9371e3ab7a3e261605b) Update manifests to v2.5.0-rc11
 * [04917cde](https://github.com/argoproj/argo-workflows/commit/04917cde047098c1fdf07965a01e07c97d2e36af) fix: Remove quotes from UI (#2213)
 * [2705a114](https://github.com/argoproj/argo-workflows/commit/2705a114195aa7dfc2617f2ebba54fbf603b1fd2) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [cee3a771](https://github.com/argoproj/argo-workflows/commit/cee3a771bda5667183b704af0da92e3a257d67ee) Merge commit '930ced39241b427a521b609c403e7a39f6cc8c48' into release-2.5
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)

### Contributors

 * Alex Collins
 * fsiegmund

## v2.5.0-rc10 (2020-02-07)

 * [b557eeb9](https://github.com/argoproj/argo-workflows/commit/b557eeb981f0e7ac3b12f4e861ff9ca099338143) Update manifests to v2.5.0-rc10
 * [f8b8efc7](https://github.com/argoproj/argo-workflows/commit/f8b8efc788f42edf7c2015fe675e23aed93975d5) Merge branch 'master' into release-2.5
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [073216c8](https://github.com/argoproj/argo-workflows/commit/073216c8fc3c440f3f0d84afd9bf5c3adf28a9b9) Merge branch 'master' into release-2.5
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [cbfbb98b](https://github.com/argoproj/argo-workflows/commit/cbfbb98b504e110ec61003efa6f28a0dde52b24f) Merge branch 'master' into release-2.5
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)
 * [bea41b49](https://github.com/argoproj/argo-workflows/commit/bea41b498fd3ece93e0d2f344b58ca31e1f28080) Update manifests to v2.5.0-rc9
 * [58f38ba7](https://github.com/argoproj/argo-workflows/commit/58f38ba788b9569bf2698de48c93f0725f375686) Merge branch 'master' into release-2.5
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [3fed36f0](https://github.com/argoproj/argo-workflows/commit/3fed36f0016f2317a0d59158c74b8c7fb024aa2d) Merge branch 'master' into release-2.5
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [4d53cc47](https://github.com/argoproj/argo-workflows/commit/4d53cc47b261d69b8beea1a7627384f64cb234e4) Merge branch 'master' into release-2.5
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [392de814](https://github.com/argoproj/argo-workflows/commit/392de814471abb3ca6c12ad7243c72c1a52591ff) Update manifests to v2.5.0-rc8
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)
 * [3d84a935](https://github.com/argoproj/argo-workflows/commit/3d84a9356b7ccc12973ee048a5c25681e8c10777) Merge branch 'master' into release-2.5
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [9b327658](https://github.com/argoproj/argo-workflows/commit/9b3276580c8abd503320f4c1fc045651d881e45f) Merge branch 'master' into release-2.5
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [a61f1457](https://github.com/argoproj/argo-workflows/commit/a61f14576728d95bc9117554d4e11e6bfa7ca0be) Merge branch 'master' into release-2.5
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [1d0a5234](https://github.com/argoproj/argo-workflows/commit/1d0a52342e8d3c9c343b92f9a292fced20d48dd1) Merge branch 'master' into release-2.5
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [adbe67c0](https://github.com/argoproj/argo-workflows/commit/adbe67c00f63ec2a6ab3b59c9085204e2f72863d) Merge branch 'master' into release-2.5
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [7bee02d8](https://github.com/argoproj/argo-workflows/commit/7bee02d89f68ef207bf038e40ca2c04646e33492) build: correct version
 * [40e7ca37](https://github.com/argoproj/argo-workflows/commit/40e7ca37cf5834e5ad8f799ea9ede61f7549a7d9) Update manifests to v2.5.0-rc7
 * [98702cae](https://github.com/argoproj/argo-workflows/commit/98702caea70c18f4a3c1b8c83cb00d58c83c0885) Merge branch 'master' into release-2.5
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [26f9bcad](https://github.com/argoproj/argo-workflows/commit/26f9bcadcf8adb255de3477b20aff26ca29123b4) Merge branch 'master' into release-2.5
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [3c8eced6](https://github.com/argoproj/argo-workflows/commit/3c8eced61b2c952268c4a256d9a9e9106b1147dd) Merge branch 'master' into release-2.5
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)
 * [7b7fcf01](https://github.com/argoproj/argo-workflows/commit/7b7fcf01a2c7819aa7da8d4ab6e5ae93e5b81436) Update manifests to v2.5.0-rc6
 * [c1cb415e](https://github.com/argoproj/argo-workflows/commit/c1cb415ef13ae5f171716bb67753f84bec892135) Merge branch 'master' into release-2.5
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)
 * [4609f3d7](https://github.com/argoproj/argo-workflows/commit/4609f3d70fef44c35634c743b15060d7865e0879) Update manifests to v2.5.0-rc5
 * [af14e452](https://github.com/argoproj/argo-workflows/commit/af14e4523f0df8064adf0b6b1a00e11a40b54caf) Merge branch 'master' into release-2.5
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [ed223e9d](https://github.com/argoproj/argo-workflows/commit/ed223e9d1e922ac35c56b2b1e7c02819fe3762e3) build: use the latest tag for codegen
 * [2db76d24](https://github.com/argoproj/argo-workflows/commit/2db76d2426e6ebe4da2d4cfd96d34401487ecffc) Merge branch 'master' into release-2.5
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)
 * [2afcb0f2](https://github.com/argoproj/argo-workflows/commit/2afcb0f27cd32cf5a6600f8d4826ace578f9ee20) Update manifests to v2.5.0-rc4
 * [e2f4d640](https://github.com/argoproj/argo-workflows/commit/e2f4d6406c1aea3a0dcbc63a05532cd8e7839c34) Merge branch 'master' into release-2.5
 * [091c2f7e](https://github.com/argoproj/argo-workflows/commit/091c2f7e892bed287cf701cafe9bee0ccf5c0ce8) lint
 * [67a51858](https://github.com/argoproj/argo-workflows/commit/67a5185895379e7299be3739c4d708132b0a6fc8) build: simplify release
 * [c4f49cf0](https://github.com/argoproj/argo-workflows/commit/c4f49cf074ad874996145674d635165f6256ca15) refactor: Move server code (cmd/server/ -> server/) (#2071)
 * [2542454c](https://github.com/argoproj/argo-workflows/commit/2542454c1daf61bc3826fa370c21799059904093) fix(controller): Do not crash if cm is empty. Fixes #2069 (#2070)
 * [3572d4df](https://github.com/argoproj/argo-workflows/commit/3572d4dfb59d888ccfa06a97e81c00d31a6a14ef) build: force tag
 * [f1c03bb3](https://github.com/argoproj/argo-workflows/commit/f1c03bb375f4120b6faee385945c4826cdeee6df) build: only tag if committing changes
 * [30775fac](https://github.com/argoproj/argo-workflows/commit/30775fac8a92cf7bdf84ada11746a7643d464885) Update manifests to v2.5.0-rc3
 * [9afa6783](https://github.com/argoproj/argo-workflows/commit/9afa6783292b85353f8775aa799aecae623f26fc) Merge branch 'master' into release-2.5
 * [85fa9aaf](https://github.com/argoproj/argo-workflows/commit/85fa9aafa70a98ce999157bb900971f24bd81101) fix: Do not expect workflowChange to always be defined (#2068)
 * [6f65bc2b](https://github.com/argoproj/argo-workflows/commit/6f65bc2b77ddcf4616c78d6db4955bf839a0c21a) fix: "base64 -d" not always available, using "base64 --decode" (#2067)
 * [5e755c61](https://github.com/argoproj/argo-workflows/commit/5e755c61e15b6fc4eed5000f91dfdef9cc266c74) build: correct image tag
 * [e7cf886b](https://github.com/argoproj/argo-workflows/commit/e7cf886bb51735c27dce7f800a7cd62ad0d72c3d) ci: install kustomize
 * [5328389a](https://github.com/argoproj/argo-workflows/commit/5328389aac14da059148ad840a9a72c322947e9e) adds "verify-manifests" target
 * [ef1c403e](https://github.com/argoproj/argo-workflows/commit/ef1c403e3f49cf06f9bbed2bfdcc7d89548031cb) fix: generate no-db manifests
 * [6f2c8802](https://github.com/argoproj/argo-workflows/commit/6f2c880280d490ba746a86d828ade61d8b58c7a5) feat(ui): Use cookies in the UI. Closes #1949 (#2058)
 * [4592aec6](https://github.com/argoproj/argo-workflows/commit/4592aec6805ce1110edcb7dc4e3e7454a2042441) fix(api): Change `CronWorkflowName` to `Name`. Fixes #1982 (#2033)
 * [a37562a0](https://github.com/argoproj/argo-workflows/commit/a37562a0e2af06f932332a53573d12920b3301e8) ci: DEV_IMAGE=true
 * [4676a946](https://github.com/argoproj/argo-workflows/commit/4676a9465ac4c2faa856f971706766f46e08edef) try and improve the release tasks
 * [fe64ae11](https://github.com/argoproj/argo-workflows/commit/fe64ae11c7e2ca3bd3cec93b38036be82eee39e7) Merge branch 'master' into release-2.5
 * [e26c11af](https://github.com/argoproj/argo-workflows/commit/e26c11af747651c6642cf0abd3cbc4ccac7b95de) fix: only run archived wf testing when persistence is enabled (#2059)
 * [243eeceb](https://github.com/argoproj/argo-workflows/commit/243eecebc96fe2c8905cf4a5a7870e7d6c7c60e8) make manifests
 * [c74d0f40](https://github.com/argoproj/argo-workflows/commit/c74d0f4067ad390dc390e9b6ade10ec623bc1dff) build: use GIT_TAG as VERSION
 * [b1fd43f7](https://github.com/argoproj/argo-workflows/commit/b1fd43f7b725733b2de3545b3261d59fde14f471) Merge branch 'release-2.5' of https://github.com/argoproj/argo into release-2.5
 * [8663652a](https://github.com/argoproj/argo-workflows/commit/8663652a75717ea77f983a9602ccf32aa187b137) make manifesets
 * [c8abcb92](https://github.com/argoproj/argo-workflows/commit/c8abcb921d4387472427b2889cec37a2b1bdfab8) Merge branch 'master' into release-2.5
 * [b3cab5df](https://github.com/argoproj/argo-workflows/commit/b3cab5dfbb5e5973b1dc448946d16ee0cd690d6a) fix: Fix permission test cases (#2035)
 * [6cf64a21](https://github.com/argoproj/argo-workflows/commit/6cf64a21bbe4ab1abd210844298a28b5803d6f59) Update Makefile
 * [216d14ad](https://github.com/argoproj/argo-workflows/commit/216d14ad10d0e8508a58ebe54383880f5d513160) fixed makefile
 * [ba2f7891](https://github.com/argoproj/argo-workflows/commit/ba2f7891ae8021ac2d235080aa35cd6391226989) merge conflict
 * [8752f026](https://github.com/argoproj/argo-workflows/commit/8752f026c569e4fe29ed9cc1539ee537a8e9fcef) merge conflict
 * [50777ed8](https://github.com/argoproj/argo-workflows/commit/50777ed8868745db8051970b51e69fb1a930acf2) fix: nil pointer in GC (#2055)
 * [b408e7cd](https://github.com/argoproj/argo-workflows/commit/b408e7cd28b95a08498f6e30fcbef385d0ff89f5) fix: nil pointer in GC (#2055)
 * [7ed058c3](https://github.com/argoproj/argo-workflows/commit/7ed058c3c30d9aea2a2cf6cc44893dfbeb886419) fix: offload Node Status in Get and List api call (#2051)
 * [4ac11560](https://github.com/argoproj/argo-workflows/commit/4ac115606bf6f0b3c5c837020efd41bf90789a00) fix: offload Node Status in Get and List api call (#2051)
 * [dfdde1d0](https://github.com/argoproj/argo-workflows/commit/dfdde1d08b2a39d074729f1d64053a6e37453b32) ci: Run using our own cowsay image (#2047)
 * [aa6a536d](https://github.com/argoproj/argo-workflows/commit/aa6a536deae7d67ae7dd2995d94849bc1861e21e) fix(persistence): Allow `argo server` to run without persistence (#2050)
 * [71ba8238](https://github.com/argoproj/argo-workflows/commit/71ba823822c190bfdb71073604bb987bb938cff4) Update README.md (#2045)
 * [c7953052](https://github.com/argoproj/argo-workflows/commit/c795305268d5793e6672252ae6ff7fb6a54f23fd) fix(persistence): Allow `argo server` to run without persistence (#2050)

### Contributors

 * Alex Collins
 * Daisuke Taniwaki
 * Derek Wang
 * Dineshmohan Rajaveeran
 * Ed Lee
 * Jialu Zhu
 * Juan C. Muller
 * Nick Groszewski
 * Rafał Bigaj
 * Saravanan Balasubramanian
 * Simon Behar
 * Tom Wieczorek
 * Tristan Colgate-McFarlane
 * fsiegmund

## v2.5.0-rc1 (2020-01-23)


### Contributors


## v2.5.0 (2020-02-18)

 * [11d2232e](https://github.com/argoproj/argo-workflows/commit/11d2232edfc4ac1176cc1ed4a47c77aeec48aeb7) Update manifests to v2.5.0
 * [661f8a11](https://github.com/argoproj/argo-workflows/commit/661f8a1113a2a02eb521a6a5e5286d38b42e5f84) fix: Ignore bookmark events for restart. Fixes #2249 (#2253)
 * [6c1a6601](https://github.com/argoproj/argo-workflows/commit/6c1a6601b151efb4a9ada9a9c997130e319daf3f) fix(offloading): Change offloaded nodes datatype to JSON to support 1GB. Fixes #2246 (#2250)
 * [befd3594](https://github.com/argoproj/argo-workflows/commit/befd3594f1d54e9e1bedd08d781025d43e6bed5b) Update manifests to v2.5.0-rc12
 * [4670c99e](https://github.com/argoproj/argo-workflows/commit/4670c99ec819dcc91c807def6c2b4e7128e2b987) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)
 * [47d9a41a](https://github.com/argoproj/argo-workflows/commit/47d9a41a902c18797e36c9371e3ab7a3e261605b) Update manifests to v2.5.0-rc11
 * [04917cde](https://github.com/argoproj/argo-workflows/commit/04917cde047098c1fdf07965a01e07c97d2e36af) fix: Remove quotes from UI (#2213)
 * [2705a114](https://github.com/argoproj/argo-workflows/commit/2705a114195aa7dfc2617f2ebba54fbf603b1fd2) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [cee3a771](https://github.com/argoproj/argo-workflows/commit/cee3a771bda5667183b704af0da92e3a257d67ee) Merge commit '930ced39241b427a521b609c403e7a39f6cc8c48' into release-2.5
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)
 * [b557eeb9](https://github.com/argoproj/argo-workflows/commit/b557eeb981f0e7ac3b12f4e861ff9ca099338143) Update manifests to v2.5.0-rc10
 * [f8b8efc7](https://github.com/argoproj/argo-workflows/commit/f8b8efc788f42edf7c2015fe675e23aed93975d5) Merge branch 'master' into release-2.5
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [073216c8](https://github.com/argoproj/argo-workflows/commit/073216c8fc3c440f3f0d84afd9bf5c3adf28a9b9) Merge branch 'master' into release-2.5
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [cbfbb98b](https://github.com/argoproj/argo-workflows/commit/cbfbb98b504e110ec61003efa6f28a0dde52b24f) Merge branch 'master' into release-2.5
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)
 * [bea41b49](https://github.com/argoproj/argo-workflows/commit/bea41b498fd3ece93e0d2f344b58ca31e1f28080) Update manifests to v2.5.0-rc9
 * [58f38ba7](https://github.com/argoproj/argo-workflows/commit/58f38ba788b9569bf2698de48c93f0725f375686) Merge branch 'master' into release-2.5
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [3fed36f0](https://github.com/argoproj/argo-workflows/commit/3fed36f0016f2317a0d59158c74b8c7fb024aa2d) Merge branch 'master' into release-2.5
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [4d53cc47](https://github.com/argoproj/argo-workflows/commit/4d53cc47b261d69b8beea1a7627384f64cb234e4) Merge branch 'master' into release-2.5
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [392de814](https://github.com/argoproj/argo-workflows/commit/392de814471abb3ca6c12ad7243c72c1a52591ff) Update manifests to v2.5.0-rc8
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)
 * [3d84a935](https://github.com/argoproj/argo-workflows/commit/3d84a9356b7ccc12973ee048a5c25681e8c10777) Merge branch 'master' into release-2.5
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [9b327658](https://github.com/argoproj/argo-workflows/commit/9b3276580c8abd503320f4c1fc045651d881e45f) Merge branch 'master' into release-2.5
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [a61f1457](https://github.com/argoproj/argo-workflows/commit/a61f14576728d95bc9117554d4e11e6bfa7ca0be) Merge branch 'master' into release-2.5
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [1d0a5234](https://github.com/argoproj/argo-workflows/commit/1d0a52342e8d3c9c343b92f9a292fced20d48dd1) Merge branch 'master' into release-2.5
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [adbe67c0](https://github.com/argoproj/argo-workflows/commit/adbe67c00f63ec2a6ab3b59c9085204e2f72863d) Merge branch 'master' into release-2.5
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [7bee02d8](https://github.com/argoproj/argo-workflows/commit/7bee02d89f68ef207bf038e40ca2c04646e33492) build: correct version
 * [40e7ca37](https://github.com/argoproj/argo-workflows/commit/40e7ca37cf5834e5ad8f799ea9ede61f7549a7d9) Update manifests to v2.5.0-rc7
 * [98702cae](https://github.com/argoproj/argo-workflows/commit/98702caea70c18f4a3c1b8c83cb00d58c83c0885) Merge branch 'master' into release-2.5
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [26f9bcad](https://github.com/argoproj/argo-workflows/commit/26f9bcadcf8adb255de3477b20aff26ca29123b4) Merge branch 'master' into release-2.5
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [3c8eced6](https://github.com/argoproj/argo-workflows/commit/3c8eced61b2c952268c4a256d9a9e9106b1147dd) Merge branch 'master' into release-2.5
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)
 * [7b7fcf01](https://github.com/argoproj/argo-workflows/commit/7b7fcf01a2c7819aa7da8d4ab6e5ae93e5b81436) Update manifests to v2.5.0-rc6
 * [c1cb415e](https://github.com/argoproj/argo-workflows/commit/c1cb415ef13ae5f171716bb67753f84bec892135) Merge branch 'master' into release-2.5
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)
 * [4609f3d7](https://github.com/argoproj/argo-workflows/commit/4609f3d70fef44c35634c743b15060d7865e0879) Update manifests to v2.5.0-rc5
 * [af14e452](https://github.com/argoproj/argo-workflows/commit/af14e4523f0df8064adf0b6b1a00e11a40b54caf) Merge branch 'master' into release-2.5
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [ed223e9d](https://github.com/argoproj/argo-workflows/commit/ed223e9d1e922ac35c56b2b1e7c02819fe3762e3) build: use the latest tag for codegen
 * [2db76d24](https://github.com/argoproj/argo-workflows/commit/2db76d2426e6ebe4da2d4cfd96d34401487ecffc) Merge branch 'master' into release-2.5
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)
 * [2afcb0f2](https://github.com/argoproj/argo-workflows/commit/2afcb0f27cd32cf5a6600f8d4826ace578f9ee20) Update manifests to v2.5.0-rc4
 * [e2f4d640](https://github.com/argoproj/argo-workflows/commit/e2f4d6406c1aea3a0dcbc63a05532cd8e7839c34) Merge branch 'master' into release-2.5
 * [091c2f7e](https://github.com/argoproj/argo-workflows/commit/091c2f7e892bed287cf701cafe9bee0ccf5c0ce8) lint
 * [67a51858](https://github.com/argoproj/argo-workflows/commit/67a5185895379e7299be3739c4d708132b0a6fc8) build: simplify release
 * [c4f49cf0](https://github.com/argoproj/argo-workflows/commit/c4f49cf074ad874996145674d635165f6256ca15) refactor: Move server code (cmd/server/ -> server/) (#2071)
 * [2542454c](https://github.com/argoproj/argo-workflows/commit/2542454c1daf61bc3826fa370c21799059904093) fix(controller): Do not crash if cm is empty. Fixes #2069 (#2070)
 * [3572d4df](https://github.com/argoproj/argo-workflows/commit/3572d4dfb59d888ccfa06a97e81c00d31a6a14ef) build: force tag
 * [f1c03bb3](https://github.com/argoproj/argo-workflows/commit/f1c03bb375f4120b6faee385945c4826cdeee6df) build: only tag if committing changes
 * [30775fac](https://github.com/argoproj/argo-workflows/commit/30775fac8a92cf7bdf84ada11746a7643d464885) Update manifests to v2.5.0-rc3
 * [9afa6783](https://github.com/argoproj/argo-workflows/commit/9afa6783292b85353f8775aa799aecae623f26fc) Merge branch 'master' into release-2.5
 * [85fa9aaf](https://github.com/argoproj/argo-workflows/commit/85fa9aafa70a98ce999157bb900971f24bd81101) fix: Do not expect workflowChange to always be defined (#2068)
 * [6f65bc2b](https://github.com/argoproj/argo-workflows/commit/6f65bc2b77ddcf4616c78d6db4955bf839a0c21a) fix: "base64 -d" not always available, using "base64 --decode" (#2067)
 * [5e755c61](https://github.com/argoproj/argo-workflows/commit/5e755c61e15b6fc4eed5000f91dfdef9cc266c74) build: correct image tag
 * [e7cf886b](https://github.com/argoproj/argo-workflows/commit/e7cf886bb51735c27dce7f800a7cd62ad0d72c3d) ci: install kustomize
 * [5328389a](https://github.com/argoproj/argo-workflows/commit/5328389aac14da059148ad840a9a72c322947e9e) adds "verify-manifests" target
 * [ef1c403e](https://github.com/argoproj/argo-workflows/commit/ef1c403e3f49cf06f9bbed2bfdcc7d89548031cb) fix: generate no-db manifests
 * [6f2c8802](https://github.com/argoproj/argo-workflows/commit/6f2c880280d490ba746a86d828ade61d8b58c7a5) feat(ui): Use cookies in the UI. Closes #1949 (#2058)
 * [4592aec6](https://github.com/argoproj/argo-workflows/commit/4592aec6805ce1110edcb7dc4e3e7454a2042441) fix(api): Change `CronWorkflowName` to `Name`. Fixes #1982 (#2033)
 * [a37562a0](https://github.com/argoproj/argo-workflows/commit/a37562a0e2af06f932332a53573d12920b3301e8) ci: DEV_IMAGE=true
 * [4676a946](https://github.com/argoproj/argo-workflows/commit/4676a9465ac4c2faa856f971706766f46e08edef) try and improve the release tasks
 * [fe64ae11](https://github.com/argoproj/argo-workflows/commit/fe64ae11c7e2ca3bd3cec93b38036be82eee39e7) Merge branch 'master' into release-2.5
 * [e26c11af](https://github.com/argoproj/argo-workflows/commit/e26c11af747651c6642cf0abd3cbc4ccac7b95de) fix: only run archived wf testing when persistence is enabled (#2059)
 * [243eeceb](https://github.com/argoproj/argo-workflows/commit/243eecebc96fe2c8905cf4a5a7870e7d6c7c60e8) make manifests
 * [c74d0f40](https://github.com/argoproj/argo-workflows/commit/c74d0f4067ad390dc390e9b6ade10ec623bc1dff) build: use GIT_TAG as VERSION
 * [b1fd43f7](https://github.com/argoproj/argo-workflows/commit/b1fd43f7b725733b2de3545b3261d59fde14f471) Merge branch 'release-2.5' of https://github.com/argoproj/argo into release-2.5
 * [8663652a](https://github.com/argoproj/argo-workflows/commit/8663652a75717ea77f983a9602ccf32aa187b137) make manifesets
 * [c8abcb92](https://github.com/argoproj/argo-workflows/commit/c8abcb921d4387472427b2889cec37a2b1bdfab8) Merge branch 'master' into release-2.5
 * [b3cab5df](https://github.com/argoproj/argo-workflows/commit/b3cab5dfbb5e5973b1dc448946d16ee0cd690d6a) fix: Fix permission test cases (#2035)
 * [6cf64a21](https://github.com/argoproj/argo-workflows/commit/6cf64a21bbe4ab1abd210844298a28b5803d6f59) Update Makefile
 * [216d14ad](https://github.com/argoproj/argo-workflows/commit/216d14ad10d0e8508a58ebe54383880f5d513160) fixed makefile
 * [ba2f7891](https://github.com/argoproj/argo-workflows/commit/ba2f7891ae8021ac2d235080aa35cd6391226989) merge conflict
 * [8752f026](https://github.com/argoproj/argo-workflows/commit/8752f026c569e4fe29ed9cc1539ee537a8e9fcef) merge conflict
 * [50777ed8](https://github.com/argoproj/argo-workflows/commit/50777ed8868745db8051970b51e69fb1a930acf2) fix: nil pointer in GC (#2055)
 * [b408e7cd](https://github.com/argoproj/argo-workflows/commit/b408e7cd28b95a08498f6e30fcbef385d0ff89f5) fix: nil pointer in GC (#2055)
 * [7ed058c3](https://github.com/argoproj/argo-workflows/commit/7ed058c3c30d9aea2a2cf6cc44893dfbeb886419) fix: offload Node Status in Get and List api call (#2051)
 * [4ac11560](https://github.com/argoproj/argo-workflows/commit/4ac115606bf6f0b3c5c837020efd41bf90789a00) fix: offload Node Status in Get and List api call (#2051)
 * [dfdde1d0](https://github.com/argoproj/argo-workflows/commit/dfdde1d08b2a39d074729f1d64053a6e37453b32) ci: Run using our own cowsay image (#2047)
 * [aa6a536d](https://github.com/argoproj/argo-workflows/commit/aa6a536deae7d67ae7dd2995d94849bc1861e21e) fix(persistence): Allow `argo server` to run without persistence (#2050)
 * [71ba8238](https://github.com/argoproj/argo-workflows/commit/71ba823822c190bfdb71073604bb987bb938cff4) Update README.md (#2045)
 * [c7953052](https://github.com/argoproj/argo-workflows/commit/c795305268d5793e6672252ae6ff7fb6a54f23fd) fix(persistence): Allow `argo server` to run without persistence (#2050)
 * [b0ee44ac](https://github.com/argoproj/argo-workflows/commit/b0ee44ac19604abe0de447027d8aea5ce32c68ea) fixed git push
 * [e4cfefee](https://github.com/argoproj/argo-workflows/commit/e4cfefee7af541a73d1f6cd3b5c132ae5c52ed24) revert cmd/server/static/files.go
 * [ecdb8b09](https://github.com/argoproj/argo-workflows/commit/ecdb8b09337ef1a9bf04681619774a10b6f07607) v2.5.0-rc1
 * [6638936d](https://github.com/argoproj/argo-workflows/commit/6638936df69f2ab9016091a06f7dd2fd2c8945ea) Update manifests to 2.5.0-rc1
 * [c3e02d81](https://github.com/argoproj/argo-workflows/commit/c3e02d81844ad486111a1691333b18f921d6bf7b) Update Makefile
 * [43656c6e](https://github.com/argoproj/argo-workflows/commit/43656c6e6d82fccf06ff2c267cdc634d0345089c) Update Makefile
 * [b49d82d7](https://github.com/argoproj/argo-workflows/commit/b49d82d71d07e0cdcedb7d1318d0eb53f19ce8cd) Update manifests to v2.5.0-rc1
 * [38bc90ac](https://github.com/argoproj/argo-workflows/commit/38bc90ac7fe91d99823b37e825fda11f33598cb2) Update Makefile
 * [1db74e1a](https://github.com/argoproj/argo-workflows/commit/1db74e1a2658fa7de925cd4c81fbfd98f648cd99) fix(archive): upsert archive + ci: Pin images on CI, add readiness probes, clean-up logging and other tweaks (#2038)
 * [c46c6836](https://github.com/argoproj/argo-workflows/commit/c46c6836706dce54aea4a13deee864bd3c6cb906) feat: Allow workflow-level parameters to be modified in the UI when submitting a workflow (#2030)
 * [faa9dbb5](https://github.com/argoproj/argo-workflows/commit/faa9dbb59753a068c64a1aa5923e3e359c0866d8) fix(Makefile): Rename staticfiles make target. Fixes #2010 (#2040)
 * [79a42d48](https://github.com/argoproj/argo-workflows/commit/79a42d48cec9c41269fbe736a61f3975fe2a9aea) docs: Update link to configure-artifact-repository.md (#2041)
 * [1a96007f](https://github.com/argoproj/argo-workflows/commit/1a96007fed6a57d14a0e364000b54a364293438b) fix: Redirect to correct page when using managed namespace. Fixes #2015 (#2029)
 * [78726314](https://github.com/argoproj/argo-workflows/commit/787263142162b62085572660f5e6497279f82ab1) fix(api): Updates proto message naming (#2034)
 * [4a1307c8](https://github.com/argoproj/argo-workflows/commit/4a1307c89e58f554af8e0cdc44e5e66e4623dfb4) feat: Adds support for MySQL. Fixes #1945 (#2013)
 * [d843e608](https://github.com/argoproj/argo-workflows/commit/d843e6085d51f409d32aefe6b6cf18bf6fd6bbd1) chore: Smoke tests are timing out, give them more time (#2032)
 * [5c98a14e](https://github.com/argoproj/argo-workflows/commit/5c98a14ecdc78a5be48f34c455d90782157c4cbe) feat(controller): Add audit logs to workflows. Fixes #1769 (#1930)
 * [2982c1a8](https://github.com/argoproj/argo-workflows/commit/2982c1a82cd6f1e7fb755a948d7a165aa0aeebc0) fix(validate): Allow placeholder in values taken from inputs. Fixes #1984 (#2028)
 * [3293c83f](https://github.com/argoproj/argo-workflows/commit/3293c83f6170ad4dc022067bb37f12d07d2834c1) feat: Add version to offload nodes. Fixes #1944 and #1946 (#1974)
 * [283bbf8d](https://github.com/argoproj/argo-workflows/commit/283bbf8df50d615dee867becc21569be760fc59e) build: `make clean` now only deletes dist directories (#2019)
 * [72fa88c9](https://github.com/argoproj/argo-workflows/commit/72fa88c9daf9ae42a8a1feb297a0b118505b32b0) build: Enable linting for tests. Closes #1971 (#2025)
 * [f8569ae9](https://github.com/argoproj/argo-workflows/commit/f8569ae913053c8ba4cd9ca72c9c237dd83200c0) feat: Auth refactoring to support single version token (#1998)
 * [eb360d60](https://github.com/argoproj/argo-workflows/commit/eb360d60ea81e8deefbaf41bcb76921acd08b16f) Fix README (#2023)
 * [ef1bd3a3](https://github.com/argoproj/argo-workflows/commit/ef1bd3a32c434c565defc7b325463e8d831262f2) fix typo (#2021)
 * [f25a45de](https://github.com/argoproj/argo-workflows/commit/f25a45deb4a7179044034da890884432e750d98a) feat(controller): Exposes container runtime executor as CLI option. (#2014)
 * [3b26af7d](https://github.com/argoproj/argo-workflows/commit/3b26af7dd4cc3d08ee50f3bc2f389efd516b9248) Enable s3 trace support. Bump version to v2.5.0. Tweak proto id to match Workflow (#2009)
 * [5eb15bb5](https://github.com/argoproj/argo-workflows/commit/5eb15bb5409f54f1a4759dde2479b7569e5f81e4) fix: Fix workflow level timeouts (#1369)
 * [5868982b](https://github.com/argoproj/argo-workflows/commit/5868982bcddf3b9c9ddb98151bf458f6868dce81) fix: Fixes the `test` job on master (#2008)
 * [29c85072](https://github.com/argoproj/argo-workflows/commit/29c850728fa701d62078910e1641588c959c28c5) fix: Fixed grammar on TTLStrategy (#2006)
 * [2f58d202](https://github.com/argoproj/argo-workflows/commit/2f58d202c21910500ecc4abdb9e23270c9791d0a) fix: v2 token bug (#1991)
 * [ed36d92f](https://github.com/argoproj/argo-workflows/commit/ed36d92f99ea65e06dc78b82923d74c57130dfc3) feat: Add quick start manifests to Git. Change auth-mode to default to server. Fixes #1990 (#1993)
 * [d1965c93](https://github.com/argoproj/argo-workflows/commit/d1965c9352c43d486b2d7cf99b0141fdb17eac2b) docs: Encourage users to upvote issues relevant to them (#1996)
 * [91331a89](https://github.com/argoproj/argo-workflows/commit/91331a894d713f085207e30406e72b8f65ad0227) fix: No longer delete the argo ns as this is dangerous (#1995)
 * [1a777cc6](https://github.com/argoproj/argo-workflows/commit/1a777cc6662b0c95ccf3de12c1a328c4cb12bc78) feat(cron): Added timezone support to cron workflows. Closes #1931 (#1986)
 * [48b85e57](https://github.com/argoproj/argo-workflows/commit/48b85e5705a235257b5926d0714eeb173b4347cb) fix: WorkflowTempalteTest fix (#1992)
 * [51dab8a4](https://github.com/argoproj/argo-workflows/commit/51dab8a4a79e5180d795ef10586e31ecf4075214) feat: Adds `argo server` command. Fixes #1966 (#1972)
 * [732e03bb](https://github.com/argoproj/argo-workflows/commit/732e03bb6cdc94ecd264fa76ecf71c29114b7769) chore: Added WorkflowTemplate test (#1989)
 * [27387d4b](https://github.com/argoproj/argo-workflows/commit/27387d4b52e99f83fe1c6ac9a0e65add669463d9) chore: Fix UI TODOs (#1987)
 * [dd704dd6](https://github.com/argoproj/argo-workflows/commit/dd704dd6557e972c8dc3c9816996305a23c80f37) feat: Renders namespace in UI. Fixes #1952 and #1959 (#1965)
 * [14d58036](https://github.com/argoproj/argo-workflows/commit/14d58036faa444ee49a4905a632db7e0a5ab60ba) feat(server): Argo Server. Closes #1331 (#1882)
 * [f69655a0](https://github.com/argoproj/argo-workflows/commit/f69655a09c82236d91703fbce2ee1a07fc3641be) fix: Added decompress in retry, resubmit and resume. (#1934)
 * [1e7ccb53](https://github.com/argoproj/argo-workflows/commit/1e7ccb53e8604654c073f6578ae024fd341f048a) updated jq version to 1.6 (#1937)
 * [c51c1302](https://github.com/argoproj/argo-workflows/commit/c51c1302f48cec5b9c6009b9b7e50962d338c679) feat: Enhancement for namespace installation mode configuration (#1939)
 * [6af100d5](https://github.com/argoproj/argo-workflows/commit/6af100d5470137cc17c019546f3cad2acf5e4a31) feat: Add suspend and resume to CronWorkflows CLI (#1925)
 * [232a465d](https://github.com/argoproj/argo-workflows/commit/232a465d00b6104fe4801b773b0b3ceffdafb116) feat: Added onExit handlers to Step and DAG (#1716)
 * [071eb112](https://github.com/argoproj/argo-workflows/commit/071eb1126cae351c5059246d2c375dc47175a3d6) docs: Update PR template to demand tests. (#1929)
 * [ae58527e](https://github.com/argoproj/argo-workflows/commit/ae58527eed40947078a7cb71da1dc3ab9c052a56) docs: Add CyberAgent to the list of Argo users (#1926)
 * [02022e4b](https://github.com/argoproj/argo-workflows/commit/02022e4bb36977253ff2e362f844b9596e768102) docs: Minor formatting fix (#1922)
 * [e4107bb8](https://github.com/argoproj/argo-workflows/commit/e4107bb831af9eb4b99753f7e324ec33042cdc55) Updated Readme.md for companies using Argo: (#1916)
 * [7e9b2b58](https://github.com/argoproj/argo-workflows/commit/7e9b2b58915c5cb51276e21c81344e010472cbae) feat: Support for scheduled Workflows with CronWorkflow CRD (#1758)
 * [5d7e9185](https://github.com/argoproj/argo-workflows/commit/5d7e91852b09ca2f3f912a8f1efaa6c28e07b524) feat: Provide values of withItems maps as JSON in {{item}}. Fixes #1905 (#1906)
 * [de3ffd78](https://github.com/argoproj/argo-workflows/commit/de3ffd78b9c16ed09065aeb16e966904e964a572)  feat: Enhanced Different TTLSecondsAfterFinished depending on if job is in Succeeded, Failed or Error, Fixes (#1883)
 * [94449876](https://github.com/argoproj/argo-workflows/commit/94449876f4a571ab279802d5ca4d5e938ca3d44d) docs: Add question option to issue templates (#1910)
 * [83ae2df4](https://github.com/argoproj/argo-workflows/commit/83ae2df4130468a95b720ce33c9b9e27e7005b17) fix: Decrease docker build time by ignoring node_modules (#1909)
 * [59a19069](https://github.com/argoproj/argo-workflows/commit/59a190697286bf19ee4a5c398c1af590a2419003) feat: support iam roles for service accounts in artifact storage (#1899)
 * [6526b6cc](https://github.com/argoproj/argo-workflows/commit/6526b6cc5e4671317fa0bc8c62440364c37a9700) fix: Revert node creation logic (#1818)
 * [160a7940](https://github.com/argoproj/argo-workflows/commit/160a794046299c9d0420ae1710641814f30a9b7f) fix: Update Gopkg.lock with dep ensure -update (#1898)
 * [ce78227a](https://github.com/argoproj/argo-workflows/commit/ce78227abe5a3c901e5b7a7dd823fb2551dff584) fix: quick fail after pod termination (#1865)
 * [cd3bd235](https://github.com/argoproj/argo-workflows/commit/cd3bd235f550fbc24c31d1763fde045c9c321fbe) refactor: Format Argo UI using prettier (#1878)
 * [b48446e0](https://github.com/argoproj/argo-workflows/commit/b48446e09e29d4f18f6a0cf0e6ff1166770286b1) fix: Fix support for continueOn failed for DAG. Fixes #1817 (#1855)
 * [48256961](https://github.com/argoproj/argo-workflows/commit/482569615734d7cb5e24c90d399f3ec98fb2ed96) fix: Fix template scope (#1836)
 * [eb585ef7](https://github.com/argoproj/argo-workflows/commit/eb585ef7381c4c9547eb9c2e922e175c0556da03) fix: Use dynamically generated placeholders (#1844)
 * [c821cfcc](https://github.com/argoproj/argo-workflows/commit/c821cfcce488222bcd5a4514cd94c66582885f33) test: Adds 'test' and 'ui' jobs to CI (#1869)
 * [54f44909](https://github.com/argoproj/argo-workflows/commit/54f44909a0e68bc24209e9e83999421b814e80c9) feat: Always archive logs if in config. Closes #1790 (#1860)
 * [1e25d6cf](https://github.com/argoproj/argo-workflows/commit/1e25d6cfa9c4c2f805717f94bd67ec612746a862) docs: Fix e2e testing link (#1873)
 * [f5f40728](https://github.com/argoproj/argo-workflows/commit/f5f40728c4be2d852e8199a5754aee39ed72399f) fix: Minor comment fix (#1872)
 * [72fad7ec](https://github.com/argoproj/argo-workflows/commit/72fad7ec0cf3aa463bd9c2c8c8f961738408cf93) Update docs (#1870)
 * [90352865](https://github.com/argoproj/argo-workflows/commit/9035286554768119b83e00294ea7c0b400b5de83) docs: Update doc based on helm 3.x changes (#1843)
 * [78889895](https://github.com/argoproj/argo-workflows/commit/788898954f7eff5b096f7597e74fc68104d8bf78) Move Workflows UI from https://github.com/argoproj/argo-ui (#1859)
 * [4b96172f](https://github.com/argoproj/argo-workflows/commit/4b96172f71f3fb36a691499b11e52a0d5650448a) docs: Refactored and cleaned up docs (#1856)
 * [6ba4598f](https://github.com/argoproj/argo-workflows/commit/6ba4598fd19c4add40b66d32df18592194c4cf4c) test: Adds core e2e test infra. Fixes #678 (#1854)
 * [87f26c8d](https://github.com/argoproj/argo-workflows/commit/87f26c8de2adc9563a3811aacc1eb31475a84f0b) fix: Move ISSUE_TEMPLATE/ under .github/ (#1858)
 * [bd78d159](https://github.com/argoproj/argo-workflows/commit/bd78d1597e82bf2bf0193e4bf49b6386c68e8222) fix: Ensure timer channel is empty after stop (#1829)
 * [afc63024](https://github.com/argoproj/argo-workflows/commit/afc63024de79c2e211a1ed0e0ede87b99825c63f) Code duplication (#1482)
 * [5b136713](https://github.com/argoproj/argo-workflows/commit/5b1367137d2b511b0310ac322596ff5395ed148d) docs: biobox analytics (#1830)
 * [68b72a8f](https://github.com/argoproj/argo-workflows/commit/68b72a8fd1773ba5f1afb4ec6ba9bf8a4d2b7ad4) add CCRi to list of users in README (#1845)
 * [941f30aa](https://github.com/argoproj/argo-workflows/commit/941f30aaf4e51e1eec13e842a0b8d46767929cec) Add Sidecar Technologies to list of who uses Argo (#1850)
 * [a08048b6](https://github.com/argoproj/argo-workflows/commit/a08048b6de84ff7355728b85851aa84b08be0851) Adding Wavefront to the users list (#1852)
 * [1cb68c98](https://github.com/argoproj/argo-workflows/commit/1cb68c9829099eb5218995159fb11fb58a147032) docs: Updates issue and PR templates. (#1848)
 * [cb0598ea](https://github.com/argoproj/argo-workflows/commit/cb0598ea82bd676fefd98e2040752cfa06516a98) Fixed Panic if DB context has issue (#1851)
 * [e5fb8848](https://github.com/argoproj/argo-workflows/commit/e5fb884853d2ad0d1f32022723e211b902841945) fix: Fix a couple of nil derefs (#1847)
 * [b3d45850](https://github.com/argoproj/argo-workflows/commit/b3d458504b319b3b02b82a872a5e13c59cb3128f) Add HOVER to the list of who uses Argo (#1825)
 * [99db30d6](https://github.com/argoproj/argo-workflows/commit/99db30d67b42cbd9c7fa35bbdd35a57040c2f222) InsideBoard uses Argo (#1835)
 * [ac8efcf4](https://github.com/argoproj/argo-workflows/commit/ac8efcf40e45750ae3c78f696f160049ea85dc8e) Red Hat uses Argo (#1828)
 * [41ed3acf](https://github.com/argoproj/argo-workflows/commit/41ed3acfb68c1200ea5f03643120cac81f7d3df6) Adding Fairwinds to the list of companies that use Argo (#1820)
 * [5274afb9](https://github.com/argoproj/argo-workflows/commit/5274afb97686a4d2a58c50c3b23dd2b680b881e6) Add exponential back-off to retryStrategy (#1782)
 * [e522e30a](https://github.com/argoproj/argo-workflows/commit/e522e30acebc17793540ac4270d14747b2617b26) Handle operation level errors PVC in Retry (#1762)
 * [f2e6054e](https://github.com/argoproj/argo-workflows/commit/f2e6054e9376f2d2be1d928ee79746b8b49937df) Do not resolve remote templates in lint (#1787)
 * [3852bc3f](https://github.com/argoproj/argo-workflows/commit/3852bc3f3311e9ac174976e9a3e8f625b87888eb) SSL enabled database connection for workflow repository (#1712) (#1756)
 * [f2676c87](https://github.com/argoproj/argo-workflows/commit/f2676c875e0af8e43b8967c669a33871bc02995c) Fix retry node name issue on error (#1732)
 * [d38a107c](https://github.com/argoproj/argo-workflows/commit/d38a107c84b91ad476f4760d984450efda296fdc) Refactoring Template Resolution Logic (#1744)
 * [23e94604](https://github.com/argoproj/argo-workflows/commit/23e9460451566e04b14acd336fccf54b0623efc4) Error occurred on pod watch should result in an error on the wait container (#1776)
 * [57d051b5](https://github.com/argoproj/argo-workflows/commit/57d051b52de7c9b78d926f0be7b158adb08803c8) Added hint when using certain tokens in when expressions (#1810)
 * [0e79edff](https://github.com/argoproj/argo-workflows/commit/0e79edff4b879558a19132035446fca2fbe3f2ca) Make kubectl print status and start/finished time (#1766)
 * [723b3c15](https://github.com/argoproj/argo-workflows/commit/723b3c15e55d2f8dceb86f1ac0a6dc7d1a58f10b) Fix code-gen docs (#1811)
 * [711bb114](https://github.com/argoproj/argo-workflows/commit/711bb11483a0ccb46600795c636c98d9c3a7f16c) Fix withParam node naming issue (#1800)
 * [4351a336](https://github.com/argoproj/argo-workflows/commit/4351a3360f6b20298a28a06be545bc349b22b9e4) Minor doc fix (#1808)
 * [efb748fe](https://github.com/argoproj/argo-workflows/commit/efb748fe35c6f24c736db8e002078abd02b57141) Fix some issues in examples (#1804)
 * [a3e31289](https://github.com/argoproj/argo-workflows/commit/a3e31289915e4d129a743b9284442775ef41a15c) Add documentation for executors (#1778)
 * [1ac75b39](https://github.com/argoproj/argo-workflows/commit/1ac75b39040e6f292ee322122a157e05f55f1f73) Add  to linter (#1777)
 * [3bead0db](https://github.com/argoproj/argo-workflows/commit/3bead0db3d2777638992ba5e11a2de1c65be162c) Add ability to retry nodes after errors (#1696)
 * [b50845e2](https://github.com/argoproj/argo-workflows/commit/b50845e22e8910d27291bab30f0c3dbef1fe5dad) Support no-headers flag (#1760)
 * [7ea2b2f8](https://github.com/argoproj/argo-workflows/commit/7ea2b2f8c10c3004c3c13a49d200df704895f93c) Minor rework of suspened node (#1752)
 * [9ab1bc88](https://github.com/argoproj/argo-workflows/commit/9ab1bc88f58c551208ce5e76eea0c6fb83359710) Update README.md (#1768)
 * [e66fa328](https://github.com/argoproj/argo-workflows/commit/e66fa328e396fe35dfad8ab1e3088ab088aea8be) Fixed lint issues (#1739)
 * [63e12d09](https://github.com/argoproj/argo-workflows/commit/63e12d0986cb4b138715b8f2b9c483de5547f64e) binary up version (#1748)
 * [1b7f9bec](https://github.com/argoproj/argo-workflows/commit/1b7f9becdfc47688018e6d71ac417fb7278637ab) Minor typo fix (#1754)
 * [4c002677](https://github.com/argoproj/argo-workflows/commit/4c002677e360beb9d6e4398618bafdce025cda42) fix blank lines (#1753)
 * [fae73826](https://github.com/argoproj/argo-workflows/commit/fae7382686d917d78e3909d1f6db79c272a1aa11) Fail suspended steps after deadline (#1704)
 * [b2d7ee62](https://github.com/argoproj/argo-workflows/commit/b2d7ee62e903c062b62da35dc390e38c05ba1591) Fix typo in docs (#1745)
 * [f2592448](https://github.com/argoproj/argo-workflows/commit/f2592448636bc35b7f9ec0fdc48b92135ba9852f) Removed uneccessary debug Println (#1741)
 * [846d01ed](https://github.com/argoproj/argo-workflows/commit/846d01eddc271f330e00414d1ea2277ac390651b) Filter workflows in list  based on name prefix (#1721)
 * [8ae688c6](https://github.com/argoproj/argo-workflows/commit/8ae688c6cbcc9494195431be7754fe69eb33a9f4) Added ability to auto-resume from suspended state (#1715)
 * [fb617b63](https://github.com/argoproj/argo-workflows/commit/fb617b63a09679bb74427cd5d13192b1fd8f48cf) unquote strings from parameter-file (#1733)
 * [34120341](https://github.com/argoproj/argo-workflows/commit/34120341747e0261425b49a5600c42efbb1812a3) example for pod spec from output of previous step (#1724)
 * [12b983f4](https://github.com/argoproj/argo-workflows/commit/12b983f4c00bda3f9bedd14a316b0beade6158ed) Add gonum.org/v1/gonum/graph to Gopkg.toml (#1726)
 * [327fcb24](https://github.com/argoproj/argo-workflows/commit/327fcb242b20107c859142b3dd68745b3440e5eb) Added  Protobuf extension  (#1601)
 * [602e5ad8](https://github.com/argoproj/argo-workflows/commit/602e5ad8e4002f7df0bd02014505cbc7de3fd37c) Fix invitation link. (#1710)
 * [eb29ae4c](https://github.com/argoproj/argo-workflows/commit/eb29ae4c89b89d4d4192a5f8c08d44ad31fa4cd2) Fixes bugs in demo (#1700)
 * [ebb25b86](https://github.com/argoproj/argo-workflows/commit/ebb25b861b1b452207582b6dea0060bf418037ff) `restartPolicy` -> `retryStrategy` in examples (#1702)
 * [167d65b1](https://github.com/argoproj/argo-workflows/commit/167d65b15ac0d3483071e0506f3e98a92a034183) Fixed incorrect `pod.name` in retry pods (#1699)
 * [e0818029](https://github.com/argoproj/argo-workflows/commit/e0818029d190cfd616527cccf208b5a9866224e1) fixed broke metrics endpoint per #1634 (#1695)
 * [36fd09a1](https://github.com/argoproj/argo-workflows/commit/36fd09a1321fd145b36b4f9067b61fabad363926) Apply Strategic merge patch against the pod spec (#1687)
 * [d3546467](https://github.com/argoproj/argo-workflows/commit/d35464670439b660c7c9ab0bcd9d3686ffe08687) Fix retry node processing (#1694)
 * [dd517e4c](https://github.com/argoproj/argo-workflows/commit/dd517e4c2db59b4c704ed7aeaed8505a757a60f7) Print multiple workflows in one command (#1650)
 * [09a6cb4e](https://github.com/argoproj/argo-workflows/commit/09a6cb4e81c1d9f5c8c082c9e96ce783fa20796f) Added status of previous steps as variables (#1681)
 * [ad3dd4d4](https://github.com/argoproj/argo-workflows/commit/ad3dd4d4a41b58e30983e8a93f06c1526c8aa9a0) Fix issue that workflow.priority substitution didn't pass validation (#1690)
 * [095d67f8](https://github.com/argoproj/argo-workflows/commit/095d67f8d0f1d309529c8a400cb16d0a0e2765b9) Store locally referenced template properly (#1670)
 * [30a91ef0](https://github.com/argoproj/argo-workflows/commit/30a91ef002e7c8850f45e6fe7ac01a7966ff31b8) Handle retried node properly (#1669)
 * [263cb703](https://github.com/argoproj/argo-workflows/commit/263cb7038b927fabe0f67b4455e17534b51c2989) Update README.md  Argo Ansible role: Provisioning Argo Workflows on Kubernetes/OpenShift (#1673)
 * [867f5ff7](https://github.com/argoproj/argo-workflows/commit/867f5ff7e72bc8b5d9b6be5a5f8849ccd2a1108c) Handle sidecar killing properly (#1675)
 * [f0ab9df9](https://github.com/argoproj/argo-workflows/commit/f0ab9df9ef8090fc388c32adbe9180dbaee683f5) Fix typo (#1679)
 * [502db42d](https://github.com/argoproj/argo-workflows/commit/502db42db84f317af8660d862ddd48c28cbd3b8e) Don't provision VM for empty artifacts (#1660)
 * [b5dcac81](https://github.com/argoproj/argo-workflows/commit/b5dcac8114d6f4b5fe32bae049d2c70b4dea4d15) Resolve WorkflowTemplate lazily (#1655)
 * [d15994bb](https://github.com/argoproj/argo-workflows/commit/d15994bbbb0a1ca8fc60b452ae532b10510c4762) [User] Update Argo users list (#1661)
 * [4a654ca6](https://github.com/argoproj/argo-workflows/commit/4a654ca6914923656bd1dc21ca5b8c4aa75b9e25) Stop failing if artifact file exists, but empty (#1653)
 * [c6cddafe](https://github.com/argoproj/argo-workflows/commit/c6cddafe19854d91bff41f093f48ac444a781c0d) Bug fixes in getting started (#1656)
 * [ec788373](https://github.com/argoproj/argo-workflows/commit/ec7883735e20f87fe483b26c947bd891a695a2bd) Update workflow_level_host_aliases.yaml (#1657)
 * [7e5af474](https://github.com/argoproj/argo-workflows/commit/7e5af4748d406f244378da86fda339a0c9e74476) Fix child node template handling (#1654)
 * [7f385a6b](https://github.com/argoproj/argo-workflows/commit/7f385a6bbf67ab780ab86c941cbd426f9b003834) Use stored templates to raggregate step outputs (#1651)
 * [cd6f3627](https://github.com/argoproj/argo-workflows/commit/cd6f3627992b6947dd47c98420d0a0fec4de9112) Fix dag output aggregation correctly (#1649)
 * [706075a5](https://github.com/argoproj/argo-workflows/commit/706075a55f694f94cfe729efca8eacb31d14f7f0) Fix DAG output aggregation (#1648)
 * [fa32dabd](https://github.com/argoproj/argo-workflows/commit/fa32dabdc0a5a74469a0e86e04b9868508503a73) Fix missing merged changes in validate.go (#1647)
 * [45716027](https://github.com/argoproj/argo-workflows/commit/457160275cc42be4c5fa6c1050c6e61a614b9544) fixed example wrong comment (#1643)
 * [69fd8a58](https://github.com/argoproj/argo-workflows/commit/69fd8a58d4877d616f3b576a2e8c8cbd224e029a) Delay killing sidecars until artifacts are saved (#1645)
 * [ec5f9860](https://github.com/argoproj/argo-workflows/commit/ec5f98605429f8d757f3b92fe6b2a2e8a4cb235f) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [4b84f975](https://github.com/argoproj/argo-workflows/commit/4b84f975f14714cedad2dc9697c9a181075b04ea) Fix global lint issue (#1641)
 * [bb579138](https://github.com/argoproj/argo-workflows/commit/bb579138c6104baab70f859e8ed05954718c5ee8) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [cbf99682](https://github.com/argoproj/argo-workflows/commit/cbf99682c7a84306066b059834a625892b86d28c) Fix regression where parallelism could cause workflow to fail (#1639)

### Contributors

 * Adam Thornton
 * Aditya Sundaramurthy
 * Akshay Chitneni
 * Alessandro Marrella
 * Alex Collins
 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Andrew Suderman
 * Antoine Dao
 * Avi Weit
 * Daisuke Taniwaki
 * David Seapy
 * Deepen Mehta
 * Derek Wang
 * Dineshmohan Rajaveeran
 * Ed Lee
 * Elton
 * Erik Parmann
 * Huan-Cheng Chang
 * Jesse Suen
 * Jialu Zhu
 * Jonathan Steele
 * Jonathon Belotti
 * Juan C. Muller
 * Julian Fahrer
 * Julian Mazzitelli
 * Marek Čermák
 * MengZeLee
 * Michael Crenshaw
 * Neutron Soutmun
 * Nick Groszewski
 * Niklas Hansson
 * Patryk Jeziorowski
 * Pavel Kravchenko
 * Per Buer
 * Praneet Chandra
 * Rafał Bigaj
 * Rick Avendaño
 * Saravanan Balasubramanian
 * Shubham Koli (FaultyCarry)
 * Simon Behar
 * Takashi Abe
 * Tobias Bradtke
 * Tom Wieczorek
 * Tristan Colgate-McFarlane
 * Vincent Boulineau
 * Wei Yan
 * William Reed
 * Zhipeng Wang
 * descrepes
 * dherman
 * fsiegmund
 * gerdos82
 * mark9white
 * nglinh
 * sang
 * vdinesh2461990
 * zhujl1991

## v2.4.3 (2019-12-05)

 * [cfe5f377](https://github.com/argoproj/argo-workflows/commit/cfe5f377bc3552fba90afe6db7a76edd92c753cd) Update version to v2.4.3
 * [256e9a2a](https://github.com/argoproj/argo-workflows/commit/256e9a2abb21f3fc3f3e5434852ff01ffb715a3b) Update version to v2.4.3
 * [b99e6a0e](https://github.com/argoproj/argo-workflows/commit/b99e6a0ea326c0c4616a4ca6a26b8ce22243adb9) Error occurred on pod watch should result in an error on the wait container (#1776)
 * [b00fea14](https://github.com/argoproj/argo-workflows/commit/b00fea143e269f28e0b3a2ba80aef4a1fa4b0ae7) SSL enabled database connection for workflow repository (#1712) (#1756)
 * [400274f4](https://github.com/argoproj/argo-workflows/commit/400274f490ee8407a8cf49f9c5023c0290ecfc4c) Added hint when using certain tokens in when expressions (#1810)
 * [15a0aa7a](https://github.com/argoproj/argo-workflows/commit/15a0aa7a7080bddf00fc6b228d9bf87db194de3b) Handle operation level errors PVC in Retry (#1762)
 * [81c7f5bd](https://github.com/argoproj/argo-workflows/commit/81c7f5bd79e6c792601bcbe9d43acccd9399f5fc) Do not resolve remote templates in lint (#1787)
 * [20cec1d9](https://github.com/argoproj/argo-workflows/commit/20cec1d9bbbae8d9da9a2cd25f74922c940e6d96) Fix retry node name issue on error (#1732)
 * [468cb8fe](https://github.com/argoproj/argo-workflows/commit/468cb8fe52b2208a82e65106a1e5e8cab29d8cac) Refactoring Template Resolution Logic (#1744)
 * [67369fb3](https://github.com/argoproj/argo-workflows/commit/67369fb370fc3adf76dfaee858e3abc5db1a3ceb) Support no-headers flag (#1760)
 * [340ab073](https://github.com/argoproj/argo-workflows/commit/340ab073417df98f2ae698b523e78e1ed0099fce) Filter workflows in list  based on name prefix (#1721)
 * [e9581273](https://github.com/argoproj/argo-workflows/commit/e9581273b5e56066e936ce7f2eb9ccd2652d15cc) Added ability to auto-resume from suspended state (#1715)
 * [a0a1b6fb](https://github.com/argoproj/argo-workflows/commit/a0a1b6fb1b0afbbd19d9815b36a3a32c0126dd4c) Fixed incorrect `pod.name` in retry pods (#1699)

### Contributors

 * Antoine Dao
 * Daisuke Taniwaki
 * Saravanan Balasubramanian
 * Simon Behar
 * gerdos82
 * sang

## v2.4.2 (2019-10-21)

 * [675c6626](https://github.com/argoproj/argo-workflows/commit/675c66267f0c916de0f233d8101aa0646acb46d4) fixed broke metrics endpoint per #1634 (#1695)
 * [1a9310c6](https://github.com/argoproj/argo-workflows/commit/1a9310c6fd089b9f8f848b324cdf219d86684bd4) Apply Strategic merge patch against the pod spec (#1687)
 * [0d0562aa](https://github.com/argoproj/argo-workflows/commit/0d0562aa122b4ef48fd81c3fc2aa9a7bd92ae4ce) Fix retry node processing (#1694)
 * [08f49d01](https://github.com/argoproj/argo-workflows/commit/08f49d01cf6b634f5a2b4e16f4da04bfc51037ab) Print multiple workflows in one command (#1650)
 * [defbc297](https://github.com/argoproj/argo-workflows/commit/defbc297d7e1abb4c729278e362c438cc09d23c7) Added status of previous steps as variables (#1681)
 * [6ac44330](https://github.com/argoproj/argo-workflows/commit/6ac4433020fe48cacfeda60f0f296861e92e742f) Fix issue that workflow.priority substitution didn't pass validation (#1690)
 * [ab9d710a](https://github.com/argoproj/argo-workflows/commit/ab9d710a007eb65f8dc5fddf344d65dca5348ddb) Update version to v2.4.2
 * [338af3e7](https://github.com/argoproj/argo-workflows/commit/338af3e7a4f5b22ef6eead04dffd774baec56391) Store locally referenced template properly (#1670)
 * [be0929dc](https://github.com/argoproj/argo-workflows/commit/be0929dcd89188054a1a3f0ca424d990468d1381) Handle retried node properly (#1669)
 * [88e210de](https://github.com/argoproj/argo-workflows/commit/88e210ded6354f1867837165292901bfb72c2670) Update README.md  Argo Ansible role: Provisioning Argo Workflows on Kubernetes/OpenShift (#1673)
 * [946b0fa2](https://github.com/argoproj/argo-workflows/commit/946b0fa26a11090498b118e69f3f4a840d89afd2) Handle sidecar killing properly (#1675)
 * [4ce972bd](https://github.com/argoproj/argo-workflows/commit/4ce972bd7dba747a0208b5ac1457db4e19390e85) Fix typo (#1679)

### Contributors

 * Daisuke Taniwaki
 * Marek Čermák
 * Rick Avendaño
 * Saravanan Balasubramanian
 * Simon Behar
 * Tobias Bradtke
 * mark9white

## v2.4.1 (2019-10-08)

 * [d7f09999](https://github.com/argoproj/argo-workflows/commit/d7f099992d8cf93c280df2ed38a0b9a1b2614e56) Update version to v2.4.1
 * [6b876b20](https://github.com/argoproj/argo-workflows/commit/6b876b20599e171ff223aaee21e56b39ab978ed7) Don't provision VM for empty artifacts (#1660)
 * [0d00a52e](https://github.com/argoproj/argo-workflows/commit/0d00a52ed28653e3135b3956e62e02efffa62cac) Resolve WorkflowTemplate lazily (#1655)
 * [effd7c33](https://github.com/argoproj/argo-workflows/commit/effd7c33cd73c82ae762cc35b312b180d5ab282e) Stop failing if artifact file exists, but empty (#1653)
 * [a6576314](https://github.com/argoproj/argo-workflows/commit/a65763142ecc2dbd3507f1da860f64220c535f5b) Fix child node template handling (#1654)
 * [982c7c55](https://github.com/argoproj/argo-workflows/commit/982c7c55994c87bab15fd71ef2a17bd905d63edd) Use stored templates to raggregate step outputs (#1651)
 * [a8305ed7](https://github.com/argoproj/argo-workflows/commit/a8305ed7e6f3a4ac5876b1468245716e88e71e92) Fix dag output aggregation correctly (#1649)
 * [f14dd56d](https://github.com/argoproj/argo-workflows/commit/f14dd56d9720ae5116fa6b0e3d320a05fc8bc6f4) Fix DAG output aggregation (#1648)
 * [30c3b937](https://github.com/argoproj/argo-workflows/commit/30c3b937240c0d12eb2ad020d55fe246759a5bbe) Fix missing merged changes in validate.go (#1647)
 * [85f50e30](https://github.com/argoproj/argo-workflows/commit/85f50e30a452a78aab547f17c19fe8464a10685c) fixed example wrong comment (#1643)
 * [09e22fb2](https://github.com/argoproj/argo-workflows/commit/09e22fb257554a33f86bac9dff2532ae23975093) Delay killing sidecars until artifacts are saved (#1645)
 * [99e28f1c](https://github.com/argoproj/argo-workflows/commit/99e28f1ce2baf35d686f04974b878f99e4ca4827) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [885aae40](https://github.com/argoproj/argo-workflows/commit/885aae40589dc4f004a0e1027cd651a816e493ee) Fix global lint issue (#1641)
 * [d9c4d236](https://github.com/argoproj/argo-workflows/commit/d9c4d2364dac59750f7f3db3e7e7b48b86ea9694) Merge branch 'release-2.4' of https://github.com/argoproj/argo into release-2.4
 * [972abdd6](https://github.com/argoproj/argo-workflows/commit/972abdd623265777b7ceb6271139812a02471a56) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [7272bec4](https://github.com/argoproj/argo-workflows/commit/7272bec4655affc5bae7254f1630c5b68948fe15) Fix regression where parallelism could cause workflow to fail (#1639)
 * [6b77abb2](https://github.com/argoproj/argo-workflows/commit/6b77abb2aa40b6c321dd7a6671a2f9ce18e38955) Add back SetGlogLevel calls
 * [e7544f3d](https://github.com/argoproj/argo-workflows/commit/e7544f3d82909b267335b7ee19a4fc6a2f0e5c5b) Update version to v2.4.0
 * [35eae441](https://github.com/argoproj/argo-workflows/commit/35eae4410446098ef379ab84ff73eb5bba4645b0) Merge branch 'master' into release-2.4
 * [45d65889](https://github.com/argoproj/argo-workflows/commit/45d658899be6d2f26eba04a7ce0486280f589c23) Merge branch 'master' into release-2.4
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)

### Contributors

 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Anes Benmerzoug
 * Brian Mericle
 * Daisuke Taniwaki
 * David Seapy
 * Ed Lee
 * Erik Parmann
 * Ian Howell
 * Jesse Suen
 * John Wass
 * Jonathon Belotti
 * Mostapha Sadeghipour Roudsari
 * Pablo Osinaga
 * Premkumar Masilamani
 * Saravanan Balasubramanian
 * Simon Behar
 * Takayuki Kasai
 * Xianlu Bird
 * Xie.CS
 * mark9white

## v2.4.0-rc1 (2019-08-08)


### Contributors


## v2.4.0 (2019-10-08)

 * [a6576314](https://github.com/argoproj/argo-workflows/commit/a65763142ecc2dbd3507f1da860f64220c535f5b) Fix child node template handling (#1654)
 * [982c7c55](https://github.com/argoproj/argo-workflows/commit/982c7c55994c87bab15fd71ef2a17bd905d63edd) Use stored templates to raggregate step outputs (#1651)
 * [a8305ed7](https://github.com/argoproj/argo-workflows/commit/a8305ed7e6f3a4ac5876b1468245716e88e71e92) Fix dag output aggregation correctly (#1649)
 * [f14dd56d](https://github.com/argoproj/argo-workflows/commit/f14dd56d9720ae5116fa6b0e3d320a05fc8bc6f4) Fix DAG output aggregation (#1648)
 * [30c3b937](https://github.com/argoproj/argo-workflows/commit/30c3b937240c0d12eb2ad020d55fe246759a5bbe) Fix missing merged changes in validate.go (#1647)
 * [85f50e30](https://github.com/argoproj/argo-workflows/commit/85f50e30a452a78aab547f17c19fe8464a10685c) fixed example wrong comment (#1643)
 * [09e22fb2](https://github.com/argoproj/argo-workflows/commit/09e22fb257554a33f86bac9dff2532ae23975093) Delay killing sidecars until artifacts are saved (#1645)
 * [99e28f1c](https://github.com/argoproj/argo-workflows/commit/99e28f1ce2baf35d686f04974b878f99e4ca4827) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [885aae40](https://github.com/argoproj/argo-workflows/commit/885aae40589dc4f004a0e1027cd651a816e493ee) Fix global lint issue (#1641)
 * [d9c4d236](https://github.com/argoproj/argo-workflows/commit/d9c4d2364dac59750f7f3db3e7e7b48b86ea9694) Merge branch 'release-2.4' of https://github.com/argoproj/argo into release-2.4
 * [972abdd6](https://github.com/argoproj/argo-workflows/commit/972abdd623265777b7ceb6271139812a02471a56) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [7272bec4](https://github.com/argoproj/argo-workflows/commit/7272bec4655affc5bae7254f1630c5b68948fe15) Fix regression where parallelism could cause workflow to fail (#1639)
 * [6b77abb2](https://github.com/argoproj/argo-workflows/commit/6b77abb2aa40b6c321dd7a6671a2f9ce18e38955) Add back SetGlogLevel calls
 * [e7544f3d](https://github.com/argoproj/argo-workflows/commit/e7544f3d82909b267335b7ee19a4fc6a2f0e5c5b) Update version to v2.4.0
 * [35eae441](https://github.com/argoproj/argo-workflows/commit/35eae4410446098ef379ab84ff73eb5bba4645b0) Merge branch 'master' into release-2.4
 * [45d65889](https://github.com/argoproj/argo-workflows/commit/45d658899be6d2f26eba04a7ce0486280f589c23) Merge branch 'master' into release-2.4
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [6131721f](https://github.com/argoproj/argo-workflows/commit/6131721f43545196399d7ffe3a72c1b9dc04df87) Remove GLog config from argo executor (#1537)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [8e94ca37](https://github.com/argoproj/argo-workflows/commit/8e94ca3709c55dd2004509790e2326d1863de272) Update main.go (#1536)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)
 * [dfb06b6d](https://github.com/argoproj/argo-workflows/commit/dfb06b6dfa8868324103bb67fbaf712c69238206) Update version to v2.4.0-rc1
 * [9fca1441](https://github.com/argoproj/argo-workflows/commit/9fca144128c97499d11f07a0ee008a9921e1f5f8) Update argo dependencies to kubernetes v1.14 (#1530)
 * [0246d184](https://github.com/argoproj/argo-workflows/commit/0246d184add04e44f77ffbe00e796b3adaf535d2) Use cache to retrieve WorkflowTemplates (#1534)
 * [4864c32f](https://github.com/argoproj/argo-workflows/commit/4864c32ffa40861c5ca066f67615da6d52eaa8b5) Update README.md (#1533)
 * [4df114fa](https://github.com/argoproj/argo-workflows/commit/4df114fae66e87727cfcb871731ec002af1515c7) Update CHANGELOG for v2.4 (#1531)
 * [c7e5cba1](https://github.com/argoproj/argo-workflows/commit/c7e5cba14a835fbfd0aba88b99197675ce1f0c66) Introduce podGC strategy for deleting completed/successful pods (#1234)
 * [bb0d14af](https://github.com/argoproj/argo-workflows/commit/bb0d14af9d320a141cb307b6a883c1eaafa498c3) Update ISSUE_TEMPLATE.md (#1528)
 * [b5702d8a](https://github.com/argoproj/argo-workflows/commit/b5702d8ae725c5caa4058d39f77e6d1e7e549da4) Format sources and order imports with the help of goimports (#1504)
 * [d3ff77bf](https://github.com/argoproj/argo-workflows/commit/d3ff77bf475095c73f034fb3b23c279c62f4269e) Added Architecture doc (#1515)
 * [fc1ec1a5](https://github.com/argoproj/argo-workflows/commit/fc1ec1a51462c9a114417db801e3a9715d3dc6b4) WorkflowTemplate CRD (#1312)
 * [f99d3266](https://github.com/argoproj/argo-workflows/commit/f99d3266d1879579338f124c56f1fc14867308a3) Expose all input parameters to template as JSON (#1488)
 * [bea60526](https://github.com/argoproj/argo-workflows/commit/bea605261be82d8bb91bf703ad68875f1093ebb8) Fix argo logs empty content when workflow run in virtual kubelet env (#1201)
 * [d82de881](https://github.com/argoproj/argo-workflows/commit/d82de8813910afaf9b3fb77d029faa7953bfee3a) Implemented support for WorkflowSpec.ArtifactRepositoryRef (#1350)
 * [0fa20c7b](https://github.com/argoproj/argo-workflows/commit/0fa20c7ba317d8c9a837bcc37d92f3fe79808499) Fix validation (#1508)
 * [87e2cb60](https://github.com/argoproj/argo-workflows/commit/87e2cb6043a305839ca37cc77c7611aaa7bdbd44) Add --dry-run option to `argo submit` (#1506)
 * [e7e50af6](https://github.com/argoproj/argo-workflows/commit/e7e50af6e56b1eeddccc82a2dbc8b421d1a63942) Support git shallow clones and additional ref fetches (#1521)
 * [605489cd](https://github.com/argoproj/argo-workflows/commit/605489cd5dd688527e60efee0aff239e3439c2dc) Allow overriding workflow labels in 'argo submit' (#1475)
 * [47eba519](https://github.com/argoproj/argo-workflows/commit/47eba519107c229edf61dbe024a6a5e0f1618a8d) Fix issue [Documentation] kubectl get service argo-artifacts -o wide (#1516)
 * [02f38262](https://github.com/argoproj/argo-workflows/commit/02f38262c40901346ddd622685bc6bfd344a2717) Fixed #1287 Executor kubectl version is obsolete (#1513)
 * [f62105e6](https://github.com/argoproj/argo-workflows/commit/f62105e659a22ccc0875151698eab540090885f6) Allow Makefile variables to be set from the command line (#1501)
 * [e62be65b](https://github.com/argoproj/argo-workflows/commit/e62be65ba25ae68a1bed10bddf33b4dae4991249) Fix a compiler error in a unit test (#1514)
 * [5c5c29af](https://github.com/argoproj/argo-workflows/commit/5c5c29af729b39f5f9b8a7fe6b8c1dede53eae3a) Fix the lint target (#1505)
 * [e03287bf](https://github.com/argoproj/argo-workflows/commit/e03287bfb7f97f639c8d81617808f709ca547eaa) Allow output parameters with .value, not only .valueFrom (#1336)
 * [781d3b8a](https://github.com/argoproj/argo-workflows/commit/781d3b8ae243b2c32ea3c4abd5b4a99fe9fc9cad) Implemented Conditionally annotate outputs of script template only when consumed #1359 (#1462)
 * [b028e61d](https://github.com/argoproj/argo-workflows/commit/b028e61db71e74b5730469a5f23a734937ddb8d9) change 'continue-on-fail' example to better reflect its description (#1494)
 * [97e824c9](https://github.com/argoproj/argo-workflows/commit/97e824c9a5b71baea658e8de6130bee089fb764d) Readme update to add argo and airflow comparison (#1502)
 * [414d6ce7](https://github.com/argoproj/argo-workflows/commit/414d6ce7b8aebcbd3b8822f407ec71ed465c103d) Fix a compiler error (#1500)
 * [ca1d5e67](https://github.com/argoproj/argo-workflows/commit/ca1d5e671519aaa9f38f5f2564eb70c138fadda7) Fix: Support the List within List type in withParam #1471 (#1473)
 * [75cb8b9c](https://github.com/argoproj/argo-workflows/commit/75cb8b9cd92cd7fcce4b921b88232bb05f2672b2) Fix #1366 unpredictable global artifact behavior (#1461)
 * [082e5c4f](https://github.com/argoproj/argo-workflows/commit/082e5c4f617c4120584ad601a8d85e0a3ce36a26) Exposed workflow priority as a variable (#1476)
 * [38c4def7](https://github.com/argoproj/argo-workflows/commit/38c4def7fb100e954757649553db8c04ea64f318) Fix: Argo CLI should show warning if there is no workflow definition in file #1486
 * [af7e496d](https://github.com/argoproj/argo-workflows/commit/af7e496db6ee8c10c9a2b6b51a27265bc6b0ee6d) Add Commodus Tech as official user (#1484)
 * [8c559642](https://github.com/argoproj/argo-workflows/commit/8c559642f2ec8abaea3204279fa3d6ff5ad40add) Update OWNERS (#1485)
 * [007d1f88](https://github.com/argoproj/argo-workflows/commit/007d1f8816736a758fa3720f0081e01dbc4200e3) Fix: 1008 `argo wait` and `argo submit --wait` should exit 1 if workflow fails  (#1467)
 * [3ab7bc94](https://github.com/argoproj/argo-workflows/commit/3ab7bc94c01d7a470bd05198b99c33e1a0221847) Document the insecureIgnoreHostKey git flag (#1483)
 * [7d9bb51a](https://github.com/argoproj/argo-workflows/commit/7d9bb51ae328f1a8cc7daf7d8ef108cf190df0ce) Fix failFast bug:   When a node in the middle fails, the entire workflow will hang (#1468)
 * [42adbf32](https://github.com/argoproj/argo-workflows/commit/42adbf32e8d4c626c544795c2fc1adb70676e968) Add --no-color flag to logs (#1479)
 * [67fc29c5](https://github.com/argoproj/argo-workflows/commit/67fc29c57db795a7020f355ab32cd883cfaf701e) fix typo: symboloic > symbolic (#1478)
 * [7c3e1901](https://github.com/argoproj/argo-workflows/commit/7c3e1901f49fe34cbe9d084274f6e64c48270635) Added Codec to the Argo community list (#1477)
 * [0a9cf9d3](https://github.com/argoproj/argo-workflows/commit/0a9cf9d3b06a3b304c0c690a298d8dc3d51c015b) Add doc about failFast feature (#1453)
 * [6a590300](https://github.com/argoproj/argo-workflows/commit/6a5903000fe8a7b3610c32435b2363cbf6334d1b) Support PodSecurityContext (#1463)
 * [e392d854](https://github.com/argoproj/argo-workflows/commit/e392d854bf78db89413782a23e62b0e38cf9c780) issue-1445: changing temp directory for output artifacts from root to tmp (#1458)
 * [7a21adfe](https://github.com/argoproj/argo-workflows/commit/7a21adfeb0af18c2452648a8bb3698a687f99b5e) New Feature:  provide failFast flag, allow a DAG to run all branches of the DAG (either success or failure) (#1443)
 * [b9b87b7f](https://github.com/argoproj/argo-workflows/commit/b9b87b7fa0cd3177c2b89cacff189f4893c5af95) Centralized Longterm workflow persistence storage  (#1344)
 * [cb09609b](https://github.com/argoproj/argo-workflows/commit/cb09609bd646a394c3a6f739dd447022a2bdb327) mention sidecar in failure message for sidecar containers (#1430)
 * [373bbe6e](https://github.com/argoproj/argo-workflows/commit/373bbe6ec9e819c39152292f79752792ce40b94d) Fix demo's doc issue of install minio chart (#1450)
 * [83552334](https://github.com/argoproj/argo-workflows/commit/835523341bcc96b6e9358be71e7432d0ac4058c5) Add threekit to user list (#1444)
 * [83f82ad1](https://github.com/argoproj/argo-workflows/commit/83f82ad172de0472643495d3ef3e0ce6d959900a) Improve bash completion (#1437)
 * [ee0ec78a](https://github.com/argoproj/argo-workflows/commit/ee0ec78ac98eaa112d343906a6e9b6490c39817f) Update documentation for workflow.outputs.artifacts (#1439)
 * [9e30c06e](https://github.com/argoproj/argo-workflows/commit/9e30c06e32b072b87e0d17095448d114175c713f) Revert "Update demo.md (#1396)" (#1433)
 * [c08de630](https://github.com/argoproj/argo-workflows/commit/c08de6300c3b394c34a5b3596455dcb50c29af48) Add paging function for list command (#1420)
 * [bba2f9cb](https://github.com/argoproj/argo-workflows/commit/bba2f9cbe9aa0eb053c19b03bc8fa7c002f579b0) Fixed:  Implemented Template level service account (#1354)
 * [d635c1de](https://github.com/argoproj/argo-workflows/commit/d635c1def74936869edbd8b9037ac81ea0af1772) Ability to configure hostPath mount for `/var/run/docker.sock` (#1419)
 * [d2f7162a](https://github.com/argoproj/argo-workflows/commit/d2f7162ac26550642ebe1792c65fb5e6ca9c0e7a) Terminate all containers within pod after main container completes (#1423)
 * [1607d74a](https://github.com/argoproj/argo-workflows/commit/1607d74a8de0704b82627364645a99b699d40cc0) PNS executor intermitently failed to capture entire log of script templates (#1406)
 * [5e47256c](https://github.com/argoproj/argo-workflows/commit/5e47256c7f86b56cfbf2ce53f73ed093eef2e3b6) Fix typo (#1431)
 * [5635c33a](https://github.com/argoproj/argo-workflows/commit/5635c33aa263080fe84e29a11a52f86fee583ca2) Update demo.md (#1396)
 * [83425455](https://github.com/argoproj/argo-workflows/commit/83425455bff34527e65ca1371347eed5203ae99a) Add OVH as official user (#1417)
 * [82e5f63d](https://github.com/argoproj/argo-workflows/commit/82e5f63d3680e7e4a22747803b0753b5ec31d2ad) Typo fix in ARTIFACT_REPO.md (#1425)
 * [15fa6f52](https://github.com/argoproj/argo-workflows/commit/15fa6f52d926ee5e839321900f613f6e546e6b6e) Update OWNERS (#1429)
 * [96b9a40e](https://github.com/argoproj/argo-workflows/commit/96b9a40e9aafe9c0132ce1b9f1eb01f05c3894ca) Orders uses alphabetically (#1411)
 * [6550e2cb](https://github.com/argoproj/argo-workflows/commit/6550e2cb10112ddf6435755958387ffa6ada0ef5) chore: add IBM to official users section in README.md (#1409)
 * [bc81fe28](https://github.com/argoproj/argo-workflows/commit/bc81fe288ebf9811774b36dd6eba9a851ac7717e) Fiixed: persistentvolumeclaims already exists #1130 (#1363)
 * [6a042d1f](https://github.com/argoproj/argo-workflows/commit/6a042d1f7eb01f1f369c2325aecebf71a3bea3a4) Update README.md (#1404)
 * [aa811fbd](https://github.com/argoproj/argo-workflows/commit/aa811fbdb914fe386cfbf3fa84a51bfd5104b5d0) Update README.md (#1402)
 * [abe3c99f](https://github.com/argoproj/argo-workflows/commit/abe3c99f19a1ec28775a276b50ad588a2dd660ca) Add Mirantis as an official user (#1401)
 * [18ab750a](https://github.com/argoproj/argo-workflows/commit/18ab750aea4de8f7dc67433f4e73505c80e13222) Added Argo Rollouts to README (#1388)
 * [67714f99](https://github.com/argoproj/argo-workflows/commit/67714f99b4bf664eb5e853b25ebf4b12bb98f733) Make locating kubeconfig in example os independent (#1393)
 * [672dc04f](https://github.com/argoproj/argo-workflows/commit/672dc04f737a3be099fe64c343587c35074b0938) Fixed: withParam parsing of JSON/YAML lists #1389 (#1397)
 * [b9aec5f9](https://github.com/argoproj/argo-workflows/commit/b9aec5f9833d5fa2055d06d1a71fdb75709eea21) Fixed: make verify-codegen is failing on the master branch (#1399) (#1400)
 * [270aabf1](https://github.com/argoproj/argo-workflows/commit/270aabf1d8cabd69b9851209ad5d9c874348e21d) Fixed:  failed to save outputs: verify serviceaccount default:default has necessary privileges (#1362)
 * [163f4a5d](https://github.com/argoproj/argo-workflows/commit/163f4a5d322352bd98f9a88ebd6089cf5e5b49ad) Fixed: Support hostAliases in WorkflowSpec #1265 (#1365)
 * [abb17478](https://github.com/argoproj/argo-workflows/commit/abb174788dce1bc6bed993a2967f7d8e112e44ca) Add Max Kelsen to USERS in README.md (#1374)
 * [dc549193](https://github.com/argoproj/argo-workflows/commit/dc5491930e09eebe700952e28359deeb8e0d2314) Update docs for the v2.3.0 release and to use the stable tag
 * [4001c964](https://github.com/argoproj/argo-workflows/commit/4001c964dbc70962e1cc1d80a4aff64cf8594ec3) Update README.md (#1372)
 * [6c18039b](https://github.com/argoproj/argo-workflows/commit/6c18039be962996d971145be8349d2ed3e396c80) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [d7e74fe3](https://github.com/argoproj/argo-workflows/commit/d7e74fe3a96277ba532e4a2f40303a92d2d0ce94) Validate action for resource templates (#1346)
 * [810949d5](https://github.com/argoproj/argo-workflows/commit/810949d5106b4d1d533b647d1d61559c208b590a) Fixed :  CLI Does Not Honor metadata.namespace #1288 (#1352)
 * [e58859d7](https://github.com/argoproj/argo-workflows/commit/e58859d79516508838fead8222f0e26a6c2a2861) [Fix #1242] Failed DAG nodes are now kept and set to running on RetryWorkflow. (#1250)
 * [d5fe5f98](https://github.com/argoproj/argo-workflows/commit/d5fe5f981fb112ba01ed77521ae688f8a15f67b9) Use golangci-lint instead of deprecated gometalinter (#1335)
 * [26744d10](https://github.com/argoproj/argo-workflows/commit/26744d100e91eb757f48bfedd539e7e4a044faf3) Support an easy way to set owner reference (#1333)
 * [8bf7578e](https://github.com/argoproj/argo-workflows/commit/8bf7578e1884c61128603bbfaa677fd79cc17ea8) Add --status filter for get command (#1325)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions

### Contributors

 * Aisuko
 * Alex Capras
 * Alex Collins
 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Anes Benmerzoug
 * Ben Wells
 * Brandon Steinman
 * Brian Mericle
 * Christian Muehlhaeuser
 * Cristian Pop
 * Daisuke Taniwaki
 * Daniel Duvall
 * David Seapy
 * Ed Lee
 * Edwin Jacques
 * Erik Parmann
 * Ian Howell
 * Jacob O'Farrell
 * Jaime
 * Jean-Louis Queguiner
 * Jesse Suen
 * John Wass
 * Jonathon Belotti
 * Mostapha Sadeghipour Roudsari
 * Mukulikak
 * Orion Delwaterman
 * Pablo Osinaga
 * Paul Brit
 * Premkumar Masilamani
 * Saravanan Balasubramanian
 * Semjon Kopp
 * Stephen Steiner
 * Takayuki Kasai
 * Tim Schrodi
 * Xianlu Bird
 * Xie.CS
 * Ziyang Wang
 * alex weidner
 * commodus-sebastien
 * hidekuro
 * ianCambrio
 * jacky
 * mark9white
 * tralexa

## v2.3.0-rc3 (2019-05-07)

 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing

### Contributors

 * Daisuke Taniwaki
 * Hideto Inamura
 * Ilias Katsakioris
 * Jesse Suen
 * Saravanan Balasubramanian
 * almariah

## v2.3.0-rc2 (2019-04-21)

 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md

### Contributors

 * Chris Chambers
 * Ed Lee
 * Ilias Katsakioris
 * Jesse Suen
 * Saravanan Balasubramanian

## v2.3.0-rc1 (2019-04-10)


### Contributors


## v2.3.0 (2019-05-20)

 * [88fcc70d](https://github.com/argoproj/argo-workflows/commit/88fcc70dcf6e60697e6716edc7464a403c49b27e) Update VERSION to v2.3.0, changelog, and manifests
 * [1731cd7c](https://github.com/argoproj/argo-workflows/commit/1731cd7c2cd6a739d9efb369a7732bc15498460f) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions
 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing
 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md
 * [40f9a875](https://github.com/argoproj/argo-workflows/commit/40f9a87593d312a46f7fa24aaf32e125458cc701) Reorganize manifests to kustomize 2 and update version to v2.3.0-rc1
 * [75b28a37](https://github.com/argoproj/argo-workflows/commit/75b28a37b923e278fc89fd647f78a42e7a3bf029) Implement support for PNS (Process Namespace Sharing) executor (#1214)
 * [b4edfd30](https://github.com/argoproj/argo-workflows/commit/b4edfd30b0e3034d98e938b491cf5bd054b36525) Fix SIGSEGV in watch/CheckAndDecompress. Consolidate duplicate code (resolves #1315)
 * [02550be3](https://github.com/argoproj/argo-workflows/commit/02550be31e53da79f1f4dbebda3ede7dc1052086) Archive location should conditionally be added to template only when needed
 * [c60010da](https://github.com/argoproj/argo-workflows/commit/c60010da29bd36c10c6e627802df6d6a06c1a59a) Fix nil pointer dereference with secret volumes (#1314)
 * [db89c477](https://github.com/argoproj/argo-workflows/commit/db89c477d65a29fc0a95ca55f68e1bd23d0170e0) Fix formatting issues in examples documentation (#1310)
 * [0d400f2c](https://github.com/argoproj/argo-workflows/commit/0d400f2ce6db9478b4eaa6fe24849a686c9d1d44) Refactor checkandEstimate to optimize podReconciliation (#1311)
 * [bbdf2e2c](https://github.com/argoproj/argo-workflows/commit/bbdf2e2c8f1b5a8dc83e88fedba9b1899f6bc78b) Add alibaba cloud to officially using argo list (#1313)
 * [abb77062](https://github.com/argoproj/argo-workflows/commit/abb77062fc06ae964ce7ccd1a534ec8bbdf3747c) CheckandEstimate implementation to optimize podReconciliation (#1308)
 * [1a028d54](https://github.com/argoproj/argo-workflows/commit/1a028d5458ffef240f8af31caeecda91f057c3ba) Secrets should be passed to pods using volumes instead of API calls (#1302)
 * [e34024a3](https://github.com/argoproj/argo-workflows/commit/e34024a3ca285d1af3b5ba3b3235dc7adc0472b7) Add support for init containers (#1183)
 * [4591e44f](https://github.com/argoproj/argo-workflows/commit/4591e44fe0e4de543f4c4339de0808346e0807e3) Added support for artifact path references (#1300)
 * [928e4df8](https://github.com/argoproj/argo-workflows/commit/928e4df81c4b33f0c0750f01b3aa3c4fc7ff256c) Add Karius to users in README.md (#1305)
 * [de779f36](https://github.com/argoproj/argo-workflows/commit/de779f36122205790915622f5ee91c9a9d5b9086) Add community meeting notes link (#1304)
 * [a8a55579](https://github.com/argoproj/argo-workflows/commit/a8a55579131605d4dc769cb599bc99c06350dfb7) Speed up podReconciliation using parallel goroutine (#1286)
 * [93451119](https://github.com/argoproj/argo-workflows/commit/934511192e4045b87be1675ff7e9dfa79faa9fcb) Add dns config support (#1301)
 * [850f3f15](https://github.com/argoproj/argo-workflows/commit/850f3f15dd1965e99cd636711a5e3306bc4bd0c0) Admiralty: add link to blog post, add user (#1295)
 * [d5f4b428](https://github.com/argoproj/argo-workflows/commit/d5f4b428ce02de34a37d5cb2fdba4dfa9fd16e75) Fix for Resource creation where template has same parameter templating (#1283)
 * [9b555cdb](https://github.com/argoproj/argo-workflows/commit/9b555cdb30f6092d5f53891f318fb74b8371c039) Issue#896 Workflow steps with non-existant output artifact path will succeed (#1277)
 * [adab9ed6](https://github.com/argoproj/argo-workflows/commit/adab9ed6bc4f8f337105182c56abad39bccb9676) Argo CI is current inactive (#1285)
 * [59fcc5cc](https://github.com/argoproj/argo-workflows/commit/59fcc5cc33ce67c057064dc37a463707501615e1) Add workflow labels and annotations global vars (#1280)
 * [1e111caa](https://github.com/argoproj/argo-workflows/commit/1e111caa1d2cc672b3b53c202b96a5f660a7e9b2) Fix bug with DockerExecutor's CopyFile (#1275)
 * [73a37f2b](https://github.com/argoproj/argo-workflows/commit/73a37f2b2a12d74ddf6a4b54e04b50fa1a7c68a1) Add the `mergeStrategy` option to resource patching (#1269)
 * [e6105243](https://github.com/argoproj/argo-workflows/commit/e6105243c785d9f53aef6fcfd344e855ad4f7d84) Reduce redundancy pod label action (#1271)
 * [4bfbb20b](https://github.com/argoproj/argo-workflows/commit/4bfbb20bc23f8bf4611a6314fb80f8138b17b9b9) Error running 1000s of tasks: "etcdserver: request is too large" #1186 (#1264)
 * [b2743f30](https://github.com/argoproj/argo-workflows/commit/b2743f30c411f5ad8f8c8b481a5d6b6ff83c33bd) Proxy Priority and PriorityClassName to pods (#1179)
 * [70c130ae](https://github.com/argoproj/argo-workflows/commit/70c130ae626f7c58d9e5ac0eed8977f51696fcbd) Update versions (#1218)
 * [b0384129](https://github.com/argoproj/argo-workflows/commit/b03841297e4b0dab0380b441cf41f5ed34db44bf) Git cloning via SSH was not verifying host public key (#1261)
 * [3f06385b](https://github.com/argoproj/argo-workflows/commit/3f06385b129c02e23ea283f7c66d347cb8899564) Issue#1165 fake outputs don't notify and task completes successfully (#1247)
 * [fa042aa2](https://github.com/argoproj/argo-workflows/commit/fa042aa285947c5fa365ef06a9565d0b4e20da0e) typo, executo -> executor (#1243)
 * [1cb88bae](https://github.com/argoproj/argo-workflows/commit/1cb88baee9ded1ede27a9d3f1e31f06f4369443d) Fixed Issue#1223 Kubernetes Resource action: patch is not supported (#1245)
 * [2b0b8f1c](https://github.com/argoproj/argo-workflows/commit/2b0b8f1c3f46aa41e4b4ddaf14ad1fdebccfaf8a) Fix the Prometheus address references (#1237)
 * [94cda3d5](https://github.com/argoproj/argo-workflows/commit/94cda3d53c6a72e3fc225ba08796bfd9420eccd6) Add feature to continue workflow on failed/error steps/tasks (#1205)
 * [3f1fb9d5](https://github.com/argoproj/argo-workflows/commit/3f1fb9d5e61d300c4922e48a748dc17285e07f07) Add Gardener to "Who uses Argo" (#1228)
 * [cde5cd32](https://github.com/argoproj/argo-workflows/commit/cde5cd320fa987ac6dd539a3126f29c73cd7277a) Include stderr when retrieving docker logs (#1225)
 * [2b1d56e7](https://github.com/argoproj/argo-workflows/commit/2b1d56e7d4e583e2e06b37904714b350faf03d97) Update README.md (#1224)
 * [eeac5a0e](https://github.com/argoproj/argo-workflows/commit/eeac5a0e11b4a6f4bc28757a3b0684598b8c4974) Remove extra quotes around output parameter value (#1232)
 * [8b67e1bf](https://github.com/argoproj/argo-workflows/commit/8b67e1bfdc7ed5ea153cb17f9a740afe2bd4efa8) Update README.md (#1236)
 * [baa3e622](https://github.com/argoproj/argo-workflows/commit/baa3e622121e66c9fec7c612c88027b7cacbd1b2) Update README with typo fixes (#1220)
 * [f6b0c8f2](https://github.com/argoproj/argo-workflows/commit/f6b0c8f285217fd0e6089b0cf03ca4926d1b4758) Executor can access the k8s apiserver with a out-of-cluster config file (#1134)
 * [0bda53c7](https://github.com/argoproj/argo-workflows/commit/0bda53c77c54b037e7d91b18554053362b1e4d35) fix dag retries (#1221)
 * [8aae2931](https://github.com/argoproj/argo-workflows/commit/8aae29317a8cfef2edc084a4c74a44c83d845936) Issue #1190 - Fix incorrect retry node handling (#1208)
 * [f1797f78](https://github.com/argoproj/argo-workflows/commit/f1797f78044504dbf2e1f7285cc9c18ac79f5e81) Add schedulerName to workflow and template spec (#1184)
 * [2ddae161](https://github.com/argoproj/argo-workflows/commit/2ddae161037f603d2a3c12ba6b495dc422547b58) Set executor image pull policy for resource template (#1174)
 * [edcb5629](https://github.com/argoproj/argo-workflows/commit/edcb56296255267a3c8fa639c3ad26a016caab80) Dockerfile: argoexec base image correction (fixes #1209) (#1213)
 * [f92284d7](https://github.com/argoproj/argo-workflows/commit/f92284d7108ebf92907008d8f12a0696ee467a43) Minor spelling, formatting, and style updates. (#1193)
 * [bd249a83](https://github.com/argoproj/argo-workflows/commit/bd249a83e119d6161fa1c593b09fb381db448a0d) Issue #1128 - Use polling instead of fs notify to get annotation changes (#1194)
 * [14a432e7](https://github.com/argoproj/argo-workflows/commit/14a432e75119e37d42715b7e83992789c6dac454) Update community/README (#1197)
 * [eda7e084](https://github.com/argoproj/argo-workflows/commit/eda7e08438d2314bb5eb178a1335a3c28555ab34) Updated OWNERS (#1198)
 * [73504a24](https://github.com/argoproj/argo-workflows/commit/73504a24e885c6df9d1cceb4aa123c79eca7b7cd) Fischerjulian adds ruby to rest docs (#1196)
 * [311ad86f](https://github.com/argoproj/argo-workflows/commit/311ad86f101c58a1de1cef313a1516b4c79e643f) Fix missing docker binary in argoexec image. Improve reuse of image layers
 * [831e2198](https://github.com/argoproj/argo-workflows/commit/831e2198e22503394acca1cce0dbcf8dcebb2931) Issue #988 - Submit should not print logs to stdout unless output is 'wide' (#1192)
 * [17250f3a](https://github.com/argoproj/argo-workflows/commit/17250f3a51d545c49114882d0da6ca29eda7c6f2) Add documentation how to use parameter-file's (#1191)
 * [01ce5c3b](https://github.com/argoproj/argo-workflows/commit/01ce5c3bcf0dde5536b596d48bd48a93b3f2eee0) Add Docker Hub build hooks
 * [93289b42](https://github.com/argoproj/argo-workflows/commit/93289b42f96cd49cdc048d84626cb28ef6932940) Refactor Makefile/Dockerfile to remove volume binding in favor of build stages (#1189)
 * [8eb4c666](https://github.com/argoproj/argo-workflows/commit/8eb4c66639c5fd1a607c73a4d765468a99c43da1) Issue #1123 - Fix 'kubectl get' failure if resource namespace is different from workflow namespace (#1171)
 * [eaaad7d4](https://github.com/argoproj/argo-workflows/commit/eaaad7d47257302f203bab24bce1b7d479453351) Increased S3 artifact retry time and added log (#1138)
 * [f07b5afe](https://github.com/argoproj/argo-workflows/commit/f07b5afeaf950f49f87cdffb5116e82c8b0d43a1) Issue #1113 - Wait for daemon pods completion to handle annotations (#1177)
 * [2b2651b0](https://github.com/argoproj/argo-workflows/commit/2b2651b0a7f5d6873c8470fad137d42f9b7d7240) Do not mount unnecessary docker socket (#1178)
 * [1fc03144](https://github.com/argoproj/argo-workflows/commit/1fc03144c55f987993c7777b190b1848fc3833cd) Argo users: Equinor (#1175)
 * [e381653b](https://github.com/argoproj/argo-workflows/commit/e381653b6d6d6a6babba2e8f05f6f103e81a191d) Update README. (#1173) (#1176)
 * [5a917140](https://github.com/argoproj/argo-workflows/commit/5a917140cb56a27e7b6f3b1d5068f4838863c273) Update README and preview notice in CLA.
 * [521eb25a](https://github.com/argoproj/argo-workflows/commit/521eb25aeb2b8351d72bad4a3d3aa2d1fa55eb23) Validate ArchiveLocation artifacts (#1167)
 * [528e8f80](https://github.com/argoproj/argo-workflows/commit/528e8f803683ee462ccc05fc9b00dc57858c0e93) Add missing patch in namespace kustomization.yaml (#1170)
 * [0b41ca0a](https://github.com/argoproj/argo-workflows/commit/0b41ca0a2410b01205712a2186dd12851eecb707) Add Preferred Networks to users in README.md (#1172)
 * [649d64d1](https://github.com/argoproj/argo-workflows/commit/649d64d1bd375f779cd150446bddce94582067d2) Add GitHub to users in README.md (#1151)
 * [864c7090](https://github.com/argoproj/argo-workflows/commit/864c7090a0bfcaa12237ff6e894a9d26ab463a7a) Update codegen for network config (#1168)
 * [c3cc51be](https://github.com/argoproj/argo-workflows/commit/c3cc51be2e14e931d6e212aa30842a2c514082d1) Support HDFS Artifact (#1159)
 * [8db00066](https://github.com/argoproj/argo-workflows/commit/8db0006667dec74c58cbab744b014c67fda55c65) add support for hostNetwork & dnsPolicy config (#1161)
 * [149d176f](https://github.com/argoproj/argo-workflows/commit/149d176fdf3560d74afa91fe91a0ee38bf7ec3bd) Replace exponential retry with poll (#1166)
 * [31e5f63c](https://github.com/argoproj/argo-workflows/commit/31e5f63cba89b06abc2cdce0d778c6b8d937a23e) Fix tests compilation error (#1157)
 * [6726d9a9](https://github.com/argoproj/argo-workflows/commit/6726d9a961a2c3ed5467430d3631a36cfbf361de) Fix failing TestAddGlobalArtifactToScope unit test
 * [4fd758c3](https://github.com/argoproj/argo-workflows/commit/4fd758c38fc232bf26bb5e1d4e7e23321ba91416) Add slack badge to README (#1164)
 * [3561bff7](https://github.com/argoproj/argo-workflows/commit/3561bff70ad6bfeca8967be6aa4ac24fbbc8ac27) Issue #1136 - Fix metadata for DAG with loops (#1149)
 * [c7fec9d4](https://github.com/argoproj/argo-workflows/commit/c7fec9d41c0e2d3369e111f8b1d0f1d0ca77edae) Reflect minio chart changes in documentation (#1147)
 * [f6ce7833](https://github.com/argoproj/argo-workflows/commit/f6ce78334762cbc3c6de1604c11ea4f5f618c275) add support for other archs (#1137)
 * [cb538489](https://github.com/argoproj/argo-workflows/commit/cb538489a187134577e2146afcf9367f45088ff7) Fix issue where steps with exhausted retires would not complete (#1148)
 * [e400b65c](https://github.com/argoproj/argo-workflows/commit/e400b65c5eca2de2aa891f8489dcd835ef0e161c) Fix global artifact overwriting in nested workflow (#1086)
 * [174eb20a](https://github.com/argoproj/argo-workflows/commit/174eb20a6a110c9bf647b040460df83b6ab031c4) Issue #1040 - Kill daemoned step if workflow consist of single daemoned step (#1144)
 * [e078032e](https://github.com/argoproj/argo-workflows/commit/e078032e469effdfc492c8eea97eb2701ceda0c2) Issue #1132 - Fix panic in ttl controller (#1143)
 * [e09d9ade](https://github.com/argoproj/argo-workflows/commit/e09d9ade25535ae7e78ca23636e4d158a98bba84) Issue #1104 - Remove container wait timeout from 'argo logs --follow' (#1142)
 * [0f84e514](https://github.com/argoproj/argo-workflows/commit/0f84e5148dd34c225a35eab7a1f5953afb45e724) Allow owner reference to be set in submit util (#1120)
 * [3484099c](https://github.com/argoproj/argo-workflows/commit/3484099c856716f6da5e02ad75a48b568f547695) Update generated swagger to fix verify-codegen (#1131)
 * [587ab1a0](https://github.com/argoproj/argo-workflows/commit/587ab1a02772cd9b7ae7cd94f91b815ac4774297) Fix output artifact and parameter conflict (#1125)
 * [6bb3adbc](https://github.com/argoproj/argo-workflows/commit/6bb3adbc596349100c4f19155cfe976f4ea0e6fb) Adding Quantibio in Who uses Argo (#1111)
 * [1ae3696c](https://github.com/argoproj/argo-workflows/commit/1ae3696c27f343c947d9225c5cc2294c8b7c45e5) Install mime-support in argoexec to set proper mime types for S3 artifacts (resolves #1119)
 * [515a9005](https://github.com/argoproj/argo-workflows/commit/515a9005057dfd260a8b60c4ba1ab8c3aa614f48) add support for ppc64le and s390x (#1102)
 * [78142837](https://github.com/argoproj/argo-workflows/commit/78142837836cb100f6858d246d84100b74794cc6) Remove docker_lib mount volume which is not needed anymore (#1115)
 * [e59398ad](https://github.com/argoproj/argo-workflows/commit/e59398adf39b8ef1d0ce273263e80d49e370c510) Fix examples docs of parameters. (#1110)
 * [ec20d94b](https://github.com/argoproj/argo-workflows/commit/ec20d94b6f1d0d88d579c8a27b964f6e9915ff55) Issue #1114 - Set FORCE_NAMESPACE_ISOLATION env variable in namespace install manifests (#1116)
 * [49c1fa4f](https://github.com/argoproj/argo-workflows/commit/49c1fa4f42e1c19ce3b8f4ac2c339894e1ed90d7) Update docs with examples using the K8s REST API
 * [bb8a6a58](https://github.com/argoproj/argo-workflows/commit/bb8a6a58fee8170d6db65c73a50c5fe640f3cb7d) Update ROADMAP.md
 * [46855dcd](https://github.com/argoproj/argo-workflows/commit/46855dcde1d9ba904a1c94a97e602d0510f5e0d4) adding logo to be used by the OS Site (#1099)
 * [438330c3](https://github.com/argoproj/argo-workflows/commit/438330c38da69a68d6b0b0b24f6aae0053fc35ee) #1081 added retry logic to s3 load and save function (#1082)
 * [cb8b036b](https://github.com/argoproj/argo-workflows/commit/cb8b036b8db3ebeb6ef73d9f2070a1ddaf0d2150) Initialize child node before marking phase. Fixes panic on invalid `When` (#1075)
 * [60b508dd](https://github.com/argoproj/argo-workflows/commit/60b508dd9ec36ef45013d72ec6166dd9a30d77fe) Drop reference to removed `argo install` command. (#1074)
 * [62b24368](https://github.com/argoproj/argo-workflows/commit/62b24368a93d57eb505bf226e042a8eb0bf72da4) Fix typo in demo.md (#1089)
 * [b5dfa021](https://github.com/argoproj/argo-workflows/commit/b5dfa0217470c97d8e83716a22cf3bd274c4a2d5) Use relative links on README file (#1087)
 * [95b72f38](https://github.com/argoproj/argo-workflows/commit/95b72f38c94d12735e79bb8bec1a46b10514603c) Update docs to outline bare minimum set of privileges for a workflow
 * [d4ef6e94](https://github.com/argoproj/argo-workflows/commit/d4ef6e944c302b5d2b75d4c49e1833c3a28c1f9a) Add new article and minor edits. (#1083)
 * [afdac9bb](https://github.com/argoproj/argo-workflows/commit/afdac9bb34fe8a01ad511323a00ccf6c07e41137) Issue #740 - System level workflow parallelism limits & priorities (#1065)
 * [a53a76e9](https://github.com/argoproj/argo-workflows/commit/a53a76e9401fab701eaa150307b21a28825c97ce) fix #1078 Azure AKS authentication issues (#1079)
 * [79b3e307](https://github.com/argoproj/argo-workflows/commit/79b3e30746f779e3cec3a28beaecb9c0df7024e1) Fix string format arguments in workflow utilities. (#1070)
 * [76b14f54](https://github.com/argoproj/argo-workflows/commit/76b14f54520a92b81ced78d4cae2632655f396fc) Auto-complete workflow names (#1061)
 * [f2914d63](https://github.com/argoproj/argo-workflows/commit/f2914d63e9c8b41a13b5932f7962f208b7e5a0da) Support nested steps workflow parallelism (#1046)
 * [eb48c23a](https://github.com/argoproj/argo-workflows/commit/eb48c23a2525a62bbc1b8b4c94e3d50fd91014bd) Raise not implemented error when artifact saving is unsupported (#1062)
 * [036969c0](https://github.com/argoproj/argo-workflows/commit/036969c0f4f6ce6a3c948b5d161c0367cf07176b) Add Cratejoy to list of users (#1063)
 * [a07bbe43](https://github.com/argoproj/argo-workflows/commit/a07bbe431cecbb1d50356f94111d3bd2dbc48bb6) Adding SAP Hybris in Who uses Argo (#1064)
 * [7ef1cea6](https://github.com/argoproj/argo-workflows/commit/7ef1cea68c94f7f0e1e2f8bd75bedc5a7df8af90) Update dependencies to K8s v1.12 and client-go 9.0
 * [23d733ba](https://github.com/argoproj/argo-workflows/commit/23d733bae386db44ec80639daf91b29dbf86b335) Add namespace explicitly to pod metadata (#1059)
 * [79ed7665](https://github.com/argoproj/argo-workflows/commit/79ed7665d7419e7fbfe8b120c4cbcd486bebee57) Parameter and Argument names should support snake case (#1048)
 * [6e6c59f1](https://github.com/argoproj/argo-workflows/commit/6e6c59f13ff84fd6b4f1e7f836c783941c434ce7) Submodules are dirty after checkout -- need to update (#1052)
 * [f18716b7](https://github.com/argoproj/argo-workflows/commit/f18716b74c6f52d0c8bf4d64c05eae9db75bfb1f) Support for K8s API based Executor (#1010)
 * [e297d195](https://github.com/argoproj/argo-workflows/commit/e297d19501a8116b5a18c925a3c72d7c7e106ea0) Updated examples/README.md (#1051)
 * [19d6cee8](https://github.com/argoproj/argo-workflows/commit/19d6cee8149917c994b737510d9c8dbfc6dbdd27) Updated ARTIFACT_REPO.md (#1049)

### Contributors

 * Adrien Trouillaud
 * Alexander Matyushentsev
 * Alexey Volkov
 * Andrei Miulescu
 * Anna Winkler
 * Bastian Echterhölter
 * Chen Zhiwei
 * Chris Chambers
 * Clemens Lange
 * Daisuke Taniwaki
 * Dan Norris
 * Divya Vavili
 * Ed Lee
 * Edward Lee
 * Erik Parmann
 * Fred Dubois
 * Greg Roodt
 * Hamel Husain
 * Hideto Inamura
 * Howie Benefiel
 * Ian Howell
 * Ilias K
 * Ilias Katsakioris
 * Ismail Alidzhikov
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Joshua Carp
 * Julian Fischer
 * Konstantin Zadorozhny
 * Marcin Karkocha
 * Matthew Coleman
 * Miyamae Yuuya
 * Naoto Migita
 * Naresh Kumar Amrutham
 * Nick Stott
 * Pengfei Zhao
 * Rocio Montes
 * Saravanan Balasubramanian
 * Tang Lee
 * Tim Schrodi
 * Val Sichkovskyi
 * WeiYan
 * Xianlu Bird
 * almariah
 * gerardaus
 * houz
 * jacky
 * jdfalko
 * kshamajain99
 * shahin
 * xubofei1983

## v2.2.1 (2018-10-11)

 * [0a928e93](https://github.com/argoproj/argo-workflows/commit/0a928e93dac6d8522682931a0a68c52add310cdb) Update installation manifests to use v2.2.1
 * [3b52b261](https://github.com/argoproj/argo-workflows/commit/3b52b26190163d1f72f3aef1a39f9f291378dafb) Fix linter warnings and update swagger
 * [7d0e77ba](https://github.com/argoproj/argo-workflows/commit/7d0e77ba74587d913b1f4aceb1443228a04d35de) Update changelog and bump version to 2.2.1
 * [b402e12f](https://github.com/argoproj/argo-workflows/commit/b402e12feefe5cd1380e9479b2cc9bae838357bf) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)
 * [3f2e986e](https://github.com/argoproj/argo-workflows/commit/3f2e986e130ca136514767fb1593d745ca418236) fix typo in examples/README.md (#1025)
 * [9c5e056a](https://github.com/argoproj/argo-workflows/commit/9c5e056a858a9b510cdacdbc5deb5857a97662f8) Replace tabs with spaces (#1027)
 * [091f1407](https://github.com/argoproj/argo-workflows/commit/091f1407180990c745e981b24169c3bb4868dbe3) Update README.md (#1030)
 * [159fe09c](https://github.com/argoproj/argo-workflows/commit/159fe09c99c16738c0897f9d74087ec1b264954d) Fix format issues to resolve build errors (#1023)
 * [363bd97b](https://github.com/argoproj/argo-workflows/commit/363bd97b72ae5cb7fc52a560b6f7939248cdb72d) Fix error in env syntax (#1014)
 * [ae7bf0a5](https://github.com/argoproj/argo-workflows/commit/ae7bf0a5f7ddb1e5211e724bef15951198610942) Issue #1018 - Workflow controller should save information about archived logs in step outputs (#1019)
 * [15d006c5](https://github.com/argoproj/argo-workflows/commit/15d006c54ee7149b0d86e6d60453ecc8c071c953) Add example of workflow using imagePullSecrets (resolves #1013)
 * [2388294f](https://github.com/argoproj/argo-workflows/commit/2388294fa412e153d8366910e4d47ba564f29856) Fix RBAC roles to include workflow delete for GC to work properly (resolves #1004)
 * [6f611cb9](https://github.com/argoproj/argo-workflows/commit/6f611cb9383610471f941b5cab4227ce8bfea7c5) Fix issue where resubmission of a terminated workflow creates a terminated workflow (issue #1011)
 * [4a7748f4](https://github.com/argoproj/argo-workflows/commit/4a7748f433f888fdc50b592db1002244ea466bdb) Disable Persistence in the demo example (#997)
 * [55ae0cb2](https://github.com/argoproj/argo-workflows/commit/55ae0cb242a9cf6b390822ca6c0aa0868f5b06e3) Fix example pod name (#1002)
 * [c275e7ac](https://github.com/argoproj/argo-workflows/commit/c275e7acb7b5e8f9820a09d8b0cb635f710b8674) Add imagePullPolicy config for executors (#995)
 * [b1eed124](https://github.com/argoproj/argo-workflows/commit/b1eed124e6d943c453d87a9b4291ba10198d0bc6) `tar -tf` will detect compressed tars correctly. (#998)
 * [03a7137c](https://github.com/argoproj/argo-workflows/commit/03a7137c9ca9459727b57fb0a0e95584c5305844) Add new organization using argo (#994)
 * [83884528](https://github.com/argoproj/argo-workflows/commit/8388452870ed9a2d2e348a2844d3d7d1c4d61b05) Update argoproj/pkg to trim leading/trailing whitespace in S3 credentials (resolves #981)
 * [978b4938](https://github.com/argoproj/argo-workflows/commit/978b49383d30cdbc7c9708eb281b7800ee5412df) Add syntax highlighting for all YAML snippets and most shell snippets (#980)
 * [60d5dc11](https://github.com/argoproj/argo-workflows/commit/60d5dc11c73e888898160b4cc329e87747cee4d2) Give control to decide whether or not to archive logs at a template level
 * [8fab73b1](https://github.com/argoproj/argo-workflows/commit/8fab73b142b96f943592c66932ae0c5183e8c3db) Detect and indicate when container was OOMKilled
 * [47a9e556](https://github.com/argoproj/argo-workflows/commit/47a9e5560229c789b70a6624f23fb4433412fbc4) Update config map doc with instructions to enable log archiving
 * [79dbbaa1](https://github.com/argoproj/argo-workflows/commit/79dbbaa1ed30cae6279eabd9a84650107f4387b3) Add instructions to match git URL format to auth type in git example (issue #979)
 * [429f03f5](https://github.com/argoproj/argo-workflows/commit/429f03f5b26db42f1857a93b7599b545642c2f0a) Add feature list to README.md. Tweaks to getting started.
 * [36fd1948](https://github.com/argoproj/argo-workflows/commit/36fd19482c6bebfb21076cba81b924deaff14f52) Update getting started guide with v2.2.0 instructions

### Contributors

 * Alexander Matyushentsev
 * Appréderisse Benjamin
 * Daisuke Taniwaki
 * David Bernard
 * Feynman Liang
 * Ilya Sotkov
 * Jesse Suen
 * Marco Sanvido
 * Matt Hillsdon
 * Sean Fern
 * WeiYan

## v2.2.0 (2018-08-30)

 * [af636ddd](https://github.com/argoproj/argo-workflows/commit/af636ddd8455660f307d835814d3112b90815dfd) Update installation manifests to use v2.2.0
 * [7864ad36](https://github.com/argoproj/argo-workflows/commit/7864ad36788dc78d035d59ddb27ecd979f7216f4) Introduce `withSequence` to iterate a range of numbers in a loop (resolves #527)
 * [99e9977e](https://github.com/argoproj/argo-workflows/commit/99e9977e4ccf61171ca1e347f6a182ba1d8dba83) Introduce `argo terminate` to terminate a workflow without deleting it (resolves #527)
 * [f52c0450](https://github.com/argoproj/argo-workflows/commit/f52c045087abff478603db4817de1933bddce5e7) Reorganize codebase to make CLI functionality available as a library
 * [311169f7](https://github.com/argoproj/argo-workflows/commit/311169f7e71c58fe9bf879a94681ee274ddf623c) Fix issue where sidecars and daemons were not reliably killed (resolves #879)
 * [67ffb6eb](https://github.com/argoproj/argo-workflows/commit/67ffb6eb7519936e1149f36e11dc9fda0f70a242) Add a reason/message for Unschedulable Pending pods
 * [69c390f2](https://github.com/argoproj/argo-workflows/commit/69c390f288ccaaeefba1d5a7961acebfe2e7771a) Support for workflow level timeouts (resolves #848)
 * [f88732ec](https://github.com/argoproj/argo-workflows/commit/f88732ec09413716bf14927bef10355b21b88516) Update docs to use keyFormat field
 * [0df022e7](https://github.com/argoproj/argo-workflows/commit/0df022e777f35bf0ea39ebbacfe4e5f92f099a62) Rename keyPattern to keyFormat. Remove pending pod query during pod reconciliation
 * [75a9983b](https://github.com/argoproj/argo-workflows/commit/75a9983b17869b76a93621f108ee85c70b8d8533) Fix potential panic in `argo watch`
 * [9cb46449](https://github.com/argoproj/argo-workflows/commit/9cb4644975d16dbebc3607ffb91364c93bc14e30) Add TTLSecondsAfterFinished field and controller to garbage collect completed workflows (resolves #911)
 * [7540714a](https://github.com/argoproj/argo-workflows/commit/7540714a47f04f664362c7083c886058c62408f8) Add ability to archive container logs to the artifact repository (resolves #454)
 * [11e57f4d](https://github.com/argoproj/argo-workflows/commit/11e57f4dea93fde60b204a5e7675fec999c66f56) Introduce archive strategies with ability to disable tar.gz archiving (resolves #784)
 * [e180b547](https://github.com/argoproj/argo-workflows/commit/e180b547133aa461bd5cc282a59f8954485d5b8f) Update CHANGELOG.md
 * [5670bf5a](https://github.com/argoproj/argo-workflows/commit/5670bf5a65cbac898b298edd682e603666ed5cb6) Introduce `argo watch` command to watch live workflows from terminal (resolves #969)
 * [57394361](https://github.com/argoproj/argo-workflows/commit/5739436199980ec765b070f8e78669bc37115ad6) Support additional container runtimes through kubelet executor (#952)
 * [a9c84c97](https://github.com/argoproj/argo-workflows/commit/a9c84c97de8f088cd4ee91cd72cf75012fc70438) Error workflows which hit k8s/etcd 1M resource size limit (resolves #913)
 * [67792eb8](https://github.com/argoproj/argo-workflows/commit/67792eb89e5aa678ffc52540dbc232d8598ce43f) Add parameter-file support (#966)
 * [841832a3](https://github.com/argoproj/argo-workflows/commit/841832a3507be3b92e3b2a05fef1052b1cd6e20d) Aggregate workflow RBAC roles to built-in admin/edit/view clusterroles (resolves #960)
 * [35bb7093](https://github.com/argoproj/argo-workflows/commit/35bb70936cf1b76e53f7f6f0e6acaccb9c6d06bf) Allow scaling of workflow and pod workers via controller CLI flags (resolves #962)
 * [b479fa10](https://github.com/argoproj/argo-workflows/commit/b479fa10647bd1c1b86410b7837668c375b327be) Improve workflow configmap documentation for keyPattern
 * [f1802f91](https://github.com/argoproj/argo-workflows/commit/f1802f91d8934b2e4b9d1f64230230bc2a0b5baf) Introduce `keyPattern` workflow config to enable flexibility in archive location path (issue #953)
 * [a5648a96](https://github.com/argoproj/argo-workflows/commit/a5648a9644fcea5f498c24a573a038290b92016f) Fix kubectl proxy link for argo-ui Service (#963)
 * [09f05912](https://github.com/argoproj/argo-workflows/commit/09f0591205ec81b4ec03f0f5c534a13648346f41) Introduce Pending node state to highlight failures when start workflow pods
 * [a3ff464f](https://github.com/argoproj/argo-workflows/commit/a3ff464f67a862d4110848d94a46be39876ce57e) Speed up CI job
 * [88627e84](https://github.com/argoproj/argo-workflows/commit/88627e842c082ddc4d75d15a3e2dc6c7ab4f1db8) Update base images to debian:9.5-slim. Use stable metalinter
 * [753c5945](https://github.com/argoproj/argo-workflows/commit/753c5945b62be209f05025c2e415a0753f5e0b01) Update argo-ci-builder image with new dependencies
 * [674b61bb](https://github.com/argoproj/argo-workflows/commit/674b61bb473787a157e543c10dcf158fa35bb39a) Remove unnecessary dependency on argo-cd and obsolete RBAC constants
 * [60658de0](https://github.com/argoproj/argo-workflows/commit/60658de0cf7403c4be014e92b7a3bb4772f4ad5f) Refactor linting/validation into standalone package. Support linting of .json files
 * [f55d579a](https://github.com/argoproj/argo-workflows/commit/f55d579a9478ed33755874f24656faec04611777) Detect and fail upon unknown fields during argo submit & lint (resolves #892)
 * [edf6a574](https://github.com/argoproj/argo-workflows/commit/edf6a5741de8bdf3a20852a55581883f1ec80d9a) Migrate to using argoproj.io/pkg packages
 * [5ee1e0c7](https://github.com/argoproj/argo-workflows/commit/5ee1e0c7daed4e2c8dca5643a800292ece067fca) Update artifact config docs (#957)
 * [faca49c0](https://github.com/argoproj/argo-workflows/commit/faca49c009bead218ee974bfad2ccc36f84de1fb) Updated README
 * [936c6df7](https://github.com/argoproj/argo-workflows/commit/936c6df7eaae08082c1cc7ad750f664ff8a4c54c) Add table of content to examples (#956)
 * [d2c03f67](https://github.com/argoproj/argo-workflows/commit/d2c03f67c2fd45ff54c04db706c9ebf252fca6f2) Correct image used in install manifests
 * [ec3b7be0](https://github.com/argoproj/argo-workflows/commit/ec3b7be065aa65aae207bd34930001b593009b80) Remove CLI installer/uninstaller. Executor image configured via CLI argument (issue #928) Remove redundant/unused downward API metadata
 * [3a85e242](https://github.com/argoproj/argo-workflows/commit/3a85e2429154a4d97c8fc7c92f9e8f482de6639f) Rely on `git checkout` instead of go-git checkout for more reliable revision resolution
 * [ecef0e3d](https://github.com/argoproj/argo-workflows/commit/ecef0e3dd506eefc222c1ebed58ab81265ac9638) Rename Prometheus metrics (#948)
 * [b9cffe9c](https://github.com/argoproj/argo-workflows/commit/b9cffe9cd7b347905a42cf3e217cc3b039bdfb3f) Issue #896 - Prometheus metrics and telemetry (#935)
 * [290dee52](https://github.com/argoproj/argo-workflows/commit/290dee52bfb94679870cee94ca9560bbe8bd7813) Support parameter aggregation of map results in scripts
 * [fc20f5d7](https://github.com/argoproj/argo-workflows/commit/fc20f5d787ed11f03a24439c042b9ef45349eb95) Fix errors when submodules are from different URL (#939)
 * [b4f1a00a](https://github.com/argoproj/argo-workflows/commit/b4f1a00ad2862e6545dd4ad16279a49cd4585676) Add documentation about workflow variables
 * [4a242518](https://github.com/argoproj/argo-workflows/commit/4a242518c6ea81cd0d1e5aaab2822231d9b36d46) Update readme.md (#943)
 * [a5baca60](https://github.com/argoproj/argo-workflows/commit/a5baca60d1dfb8fb8c82a936ab383d49e075cff3) Support referencing of global workflow artifacts (issue #900)
 * [9b5c8563](https://github.com/argoproj/argo-workflows/commit/9b5c85631765285b4593b7707ede014178f77679) Support for sophisticated expressions in `when` conditionals (issue #860)
 * [ecc0f027](https://github.com/argoproj/argo-workflows/commit/ecc0f0272f2257600abab8f4779c478957644d7c) Resolve revision added ability to specify shorthand revision and other things like HEAD~2 etc (#936)
 * [11024318](https://github.com/argoproj/argo-workflows/commit/11024318c0e2a9106f8a8b4a719daba12adf9f36) Support conditions with DAG tasks. Support aggregated outputs from scripts (issue #921)
 * [d07c1d2f](https://github.com/argoproj/argo-workflows/commit/d07c1d2f3b7c916887185eea749db2278bf9d043) Support withItems/withParam and parameter aggregation with DAG templates (issue #801)
 * [94c195cb](https://github.com/argoproj/argo-workflows/commit/94c195cb014ba2e5c5943d96dc0a3cc3243edb6a) Bump VERSION to v2.2.0
 * [9168c59d](https://github.com/argoproj/argo-workflows/commit/9168c59dc486f840dc2b9713d92c14bdccebbaf8) Fix outbound node metadata with retry nodes causing disconnected nodes to be rendered in UI (issue #880)
 * [c6ce48d0](https://github.com/argoproj/argo-workflows/commit/c6ce48d086638168b9bd8b998d65a2e3a4801540) Fix outbound node metadata issue with steps template causing incorrect edges to be rendered in UI
 * [520b33d5](https://github.com/argoproj/argo-workflows/commit/520b33d5fc6e7e670c33015fd74c5a2f3bd74a21) Add ability to aggregate and reference output parameters expanded by loops (issue #861)
 * [ece1eef8](https://github.com/argoproj/argo-workflows/commit/ece1eef85ac1f92d2fad8a2fef8c657f04b4599a) Support submission of workflows as json, and from stdin (resolves #926)
 * [4c31d61d](https://github.com/argoproj/argo-workflows/commit/4c31d61da2891e92a3ae0d09b6924655a07fc59f) Add `argo delete --older` to delete completed workflows older than specified duration (resolves #930)
 * [c87cd33c](https://github.com/argoproj/argo-workflows/commit/c87cd33c1bc46c06314129c882fec80269af8133) Update golang version to v1.10.3
 * [618b7eb8](https://github.com/argoproj/argo-workflows/commit/618b7eb84678e177a38e5aa81fa59ed891459aa5) Proper fix for assessing overall DAG phase. Add some DAG unit tests (resolves #885)
 * [f223e5ad](https://github.com/argoproj/argo-workflows/commit/f223e5ad62115399cf1394db4e9e65f05ae6da8b) Fix issue where a DAG would fail even if retry was successful (resolves #885)
 * [143477f3](https://github.com/argoproj/argo-workflows/commit/143477f3d5e0ab0d65dd97774aabdcd736ae4fbe) Start use of argoproj/pkg shared libraries
 * [1220d080](https://github.com/argoproj/argo-workflows/commit/1220d0801b8aa78c5364a4586cd119553d96bca5) Update argo-cluster-role to work with OpenShift (resolves #922)
 * [4744f45a](https://github.com/argoproj/argo-workflows/commit/4744f45a9c110b11fa73070a52e4166406fa5da4) Added SSH clone and proper git clone using go-git (#919)
 * [d657abf4](https://github.com/argoproj/argo-workflows/commit/d657abf4a37c9f2987b5cc2ee337743c981c3e48) Regenerate code and address OpenAPI rule validation errors (resolves #923)
 * [c5ec4cf6](https://github.com/argoproj/argo-workflows/commit/c5ec4cf6194ab5f741eb2e1d4e387dcf32ba3ce7) Upgrade k8s dependencies to v1.10 (resolves #908)
 * [ba8061ab](https://github.com/argoproj/argo-workflows/commit/ba8061abd296895555ea3d1d6ca7418fcd07d633) Redundant verifyResolvedVariables check in controller precluded the ability to use {{ }} in other circumstances
 * [05a61449](https://github.com/argoproj/argo-workflows/commit/05a614496bb921b5fa081605227de1a8832260cd) Added link to community meetings (#912)
 * [f33624d6](https://github.com/argoproj/argo-workflows/commit/f33624d67d0cf348dcdece46832081346c26bf80) Add an example on how to submit and wait on a workflow
 * [aeed7f9d](https://github.com/argoproj/argo-workflows/commit/aeed7f9da490d8dc4ad40c00ac2272a19da4ff17) Added new members
 * [288e4fc8](https://github.com/argoproj/argo-workflows/commit/288e4fc8577890e7fa6cc546f92aef4c954ce18c) Added Argo Events link.
 * [3322506e](https://github.com/argoproj/argo-workflows/commit/3322506e5a1d07e198f69cadd210b0b6cc6cfbc9) Updated README
 * [3ce640a2](https://github.com/argoproj/argo-workflows/commit/3ce640a24509454302a5126c972fd5424673c00e) Issue #889 - Support retryStrategy for scripts (#890)
 * [91c6afb2](https://github.com/argoproj/argo-workflows/commit/91c6afb2cc07c113e4999f114279638aa6809fd6) adding BlackRock as corporate contributor/user (#886)
 * [c8667b5c](https://github.com/argoproj/argo-workflows/commit/c8667b5c81068326638a5e35c20336223b3894db) Fix issue where `argo lint` required spec level arguments to be supplied
 * [ed7dedde](https://github.com/argoproj/argo-workflows/commit/ed7dedde1f8be2a5f7be828a31ac9bb4025919e1) Update influx-ci example to choose a stable InfluxDB branch
 * [135813e1](https://github.com/argoproj/argo-workflows/commit/135813e10e932a2187d007284766a816d9aa4442) Add datadog to the argo users (#882)
 * [f1038948](https://github.com/argoproj/argo-workflows/commit/f103894843e9ed8cbaf4212e765c10311bec5989) Fix `make verify-codegen` build target when run in CI
 * [785f2cbd](https://github.com/argoproj/argo-workflows/commit/785f2cbd114e6d0097e21240d5cacece0b6d071e) Update references to v2.1.1. Add better checks in release Makefile target
 * [d65e1cd3](https://github.com/argoproj/argo-workflows/commit/d65e1cd3e77efbe6fc877ac689fd4cd19bc35093) readme: add Interline Technologies to user list (#867)
 * [c903168e](https://github.com/argoproj/argo-workflows/commit/c903168ee12f296f71f4953cda2163b8fa8cd409) Add documentation on global parameters (#871)

### Contributors

 * Andrei Miulescu
 * David Van Loon
 * Drew Dara-Abrams
 * Ed Lee
 * Edward Lee
 * Jesse Suen
 * Julien Balestra
 * Konstantin Zadorozhny
 * Matthew Magaldi
 * Nándor István Krácser
 * Val Sichkovskyi
 * Vincent Smith
 * dthomson25

## v2.1.2 (2018-10-11)

 * [b82ce5b0](https://github.com/argoproj/argo-workflows/commit/b82ce5b0b558ec5df70b760c0f67fc7e84cdfdf1) Update version to 2.1.2
 * [01a1214e](https://github.com/argoproj/argo-workflows/commit/01a1214e6ae6680663168d308399b11aa7224d7e) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)

### Contributors

 * Alexander Matyushentsev

## v2.11.3 (2020-10-07)

 * [a00a8f14](https://github.com/argoproj/argo-workflows/commit/a00a8f141c221f50e397aea8f86a54171441e395) Update manifests to v2.11.3
 * [e48fe222](https://github.com/argoproj/argo-workflows/commit/e48fe222d405efc84331e8f3d9dadd8072d18325) fixed merge conflict
 * [3f8ebfdd](https://github.com/argoproj/argo-workflows/commit/3f8ebfdda02c4b9186595d556d7daa9bc7a7a670) chore: Fix merge issues
 * [51068f72](https://github.com/argoproj/argo-workflows/commit/51068f72d5cc014576b4977b1a651c0d5b89f925) fix(controller): Support int64 for param value. Fixes #4169 (#4202)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian

## v2.11.2 (2020-10-05)

 * [0dfeb8e5](https://github.com/argoproj/argo-workflows/commit/0dfeb8e56071e7a1332370732949bc2e15073005) Update manifests to v2.11.2
 * [5b69ab42](https://github.com/argoproj/argo-workflows/commit/5b69ab429c0da3d1cf63f209c2d4f61a3ea05d16) chore: Enahnce logging around pod failures (#4220)
 * [461a36a1](https://github.com/argoproj/argo-workflows/commit/461a36a15ecb8c11dcb62694c0c5bd624b835bd4) fix(controller): Apply Workflow default on normal workflow scenario Fixes #4208 (#4213)
 * [4b9cf5d2](https://github.com/argoproj/argo-workflows/commit/4b9cf5d28ae661873847238203b0098a2722a97a) fix(controller): reduce withItem/withParams memory usage. Fixes #3907 (#4207)
 * [8fea7bf6](https://github.com/argoproj/argo-workflows/commit/8fea7bf6b5cf0c89cf9c3bb0c3f57c1397236f5e) Revert "Revert "chore: use build matrix and cache (#4111)""
 * [efb20eea](https://github.com/argoproj/argo-workflows/commit/efb20eea05afc919652ebf17c6456791a283d4d2) Revert "chore: use build matrix and cache (#4111)"
 * [de1c9e52](https://github.com/argoproj/argo-workflows/commit/de1c9e52d48d8f91545dcfd32f426c235d001469) refactor: Refactor Synchronization code (#4114)
 * [605d0895](https://github.com/argoproj/argo-workflows/commit/605d0895aa436d8543ad43eee179cc169b792863) fix: Ensure CronWorkflows are persisted once per operation (#4172)
 * [6f738db0](https://github.com/argoproj/argo-workflows/commit/6f738db0733da6aa16f851d1dbefa235e987bcf8) Revert "chore: Update Go module to argo/v2"
 * [bcebdf00](https://github.com/argoproj/argo-workflows/commit/bcebdf0043028613f8849e84520e2ea9fb92d52a) chore: Update Go module to argo/v2

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.11.1 (2020-09-29)

 * [13b51d56](https://github.com/argoproj/argo-workflows/commit/13b51d569d580ab9493e977fe2944889784d2a0a) Update manifests to v2.11.1
 * [3f88216e](https://github.com/argoproj/argo-workflows/commit/3f88216e61e3b408083956ad848c1603145c8507) fix: Render full tree of onExit nodes in UI (#4109)
 * [d6c2a57b](https://github.com/argoproj/argo-workflows/commit/d6c2a57be0b0c3cc4d46bff36cdf3e426f760b82) fix: Fix unintended inf recursion (#4067)
 * [4fda60f4](https://github.com/argoproj/argo-workflows/commit/4fda60f402bbbd5d3c0cadbd886feb065f255e19) fix: Tolerate malformed workflows when retrying (#4028)
 * [995d59cc](https://github.com/argoproj/argo-workflows/commit/995d59cc52d054f92c8ac54959e8115d4117dbf2) fix: Changing DeletePropagation to background in TTL Controller and Argo CLI (#4133)
 * [aaef0a28](https://github.com/argoproj/argo-workflows/commit/aaef0a2846afc0943f9bb7688d2fba6e11b49f62) fix(ui): Ignore referenced nodes that don't exist in UI. Fixes #4079 (#4099)
 * [fedae45a](https://github.com/argoproj/argo-workflows/commit/fedae45ad6e4bfe297d1078928a6deb4269ebac0) fix(controller): Process workflows at least once every 20m (#4103)
 * [6de464e8](https://github.com/argoproj/argo-workflows/commit/6de464e809ecf39bfe9b12eaf28fb8e7b20a27a9) fix(server): argo-server-role to allow submitting cronworkflows from UI (#4112)
 * [ce3b90e2](https://github.com/argoproj/argo-workflows/commit/ce3b90e2553d4646f8f5bc95a88e48765ad1de19) fix(controller): Treat annotation and conditions changes as significant (#4104)
 * [bf98b977](https://github.com/argoproj/argo-workflows/commit/bf98b9778b556e68ef39a4290e489819d3142d6f) fix(ui): No longer redirect to `undefined` namespace. See #4084 (#4115)
 * [af60b37d](https://github.com/argoproj/argo-workflows/commit/af60b37dc5909c70730da01e9322605ad2852283) fix(cli): Reinstate --gloglevel flag. Fixes #4093 (#4100)
 * [38b63008](https://github.com/argoproj/argo-workflows/commit/38b63008abac9450b3677bbb620193efcc8d55b2) chore: use build matrix and cache (#4111)
 * [2cd6a967](https://github.com/argoproj/argo-workflows/commit/2cd6a9677f0665931230fbdb6c8203381d9c9b77) fix(server): Optional timestamp inclusion when retrieving workflow logs. Closes #4033 (#4075)
 * [2f7c4035](https://github.com/argoproj/argo-workflows/commit/2f7c4035fe7f16b75bf418a67778db97c836ecf0) fix(controller): Correct the order merging the fields in WorkflowTemplateRef scenario. Fixes #4044 (#4063)
 * [f8e750de](https://github.com/argoproj/argo-workflows/commit/f8e750de5ebab6f3c494c972889b31ef24c73c9b) Update manifests to v2.11.0
 * [c06db575](https://github.com/argoproj/argo-workflows/commit/c06db57572843b38322b301aba783685c774045b) fix(ui): Tiny modal DAG tweaks. Fixes #4039 (#4043)

### Contributors

 * Alex Collins
 * Markus Lippert
 * Saravanan Balasubramanian
 * Simon Behar
 * Tomáš Coufal
 * ivancili

## v2.11.0-rc3 (2020-09-14)

 * [1b4cf3f1](https://github.com/argoproj/argo-workflows/commit/1b4cf3f1f26f6abf93355a0108f5048be9677978) Update manifests to v2.11.0-rc3
 * [e2594eca](https://github.com/argoproj/argo-workflows/commit/e2594eca965ec2ea14b07f3c1acee4b288b02789) fix: Fix children is not defined error (#3950)
 * [2ed8025e](https://github.com/argoproj/argo-workflows/commit/2ed8025eb0fbf0599c20efc1bccfedfe51c88215) fix: Fix UI selection issues (#3928)
 * [8dc0e94e](https://github.com/argoproj/argo-workflows/commit/8dc0e94e68881693b504f6f2777f937e6f3c3e42) fix: Create global scope before workflow-level realtime metrics (#3979)
 * [cdeabab7](https://github.com/argoproj/argo-workflows/commit/cdeabab722fac97a326e70b956a92d4cb5d58f2c) fix(controller): Script Output didn't set if template has RetryStrategy (#4002)
 * [9c83fac8](https://github.com/argoproj/argo-workflows/commit/9c83fac80594fb0abef18b0de0ff563132ee84ae) fix(ui): Do not save undefined namespace. Fixes #4019 (#4021)
 * [7fd2ecb1](https://github.com/argoproj/argo-workflows/commit/7fd2ecb1d057cbf1e1b8139c30c20eccf86611ea) fix(ui): Correctly show pod events. Fixes #4016 (#4018)
 * [11242c8b](https://github.com/argoproj/argo-workflows/commit/11242c8be5c3bbaf2dbcff68198958504ea88e43) fix(ui): Allow you to view timeline tab. Fixes #4005 (#4006)
 * [3770f618](https://github.com/argoproj/argo-workflows/commit/3770f618ab073fbac6654c9edcc4b53a1e010fea) fix(ui): Report errors when uploading files. Fixes #3994 (#3995)
 * [0fed28ce](https://github.com/argoproj/argo-workflows/commit/0fed28ce26f12a42f3321afee9188e9f59acfea7) fix: Custom metrics are not recorded for DAG tasks Fixes #3872 (#3886)
 * [9146636e](https://github.com/argoproj/argo-workflows/commit/9146636e75e950149ce39df33e4fc6f7346c7282) feat(ui): Introduce modal DAG renderer. Fixes: #3595 (#3967)
 * [4b7a4694](https://github.com/argoproj/argo-workflows/commit/4b7a4694c436c724cb75e09564fcd8c87923d6d7) fix(controller): Revert `resubmitPendingPods` mistake. Fixes #4001 (#4004)
 * [49752fb5](https://github.com/argoproj/argo-workflows/commit/49752fb5f9aa6ab151f311bb62faa021b2ebffa5) fix(controller): Revert parameter value to `*string`. Fixes #3960 (#3963)
 * [ddf850b1](https://github.com/argoproj/argo-workflows/commit/ddf850b1bd99a8343b5e94e7d3634912031e8d44) fix: Consider WorkflowTemplate metadata during validation (#3988)
 * [a8ba447e](https://github.com/argoproj/argo-workflows/commit/a8ba447e3ed4fff3d90cd772fc551db8c225a1c0) fix(server): Remove XSS vulnerability. Fixes #3942 (#3975)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.11.0-rc2 (2020-09-09)

 * [f930c029](https://github.com/argoproj/argo-workflows/commit/f930c0296c41c8723a6f826260a098bb0647efce) Update manifests to v2.11.0-rc2
 * [21cceb0f](https://github.com/argoproj/argo-workflows/commit/21cceb0fd743777c696245ad988a78f03fd5dc08) build: Allow build with older `docker`. Fixes #3977
 * [b6890adb](https://github.com/argoproj/argo-workflows/commit/b6890adb1b5c40ddb4b1aa41c39c337f0f08df12) fix(cli): Allow `argo version` without KUBECONFIG. Fixes #3943 (#3945)
 * [354733e7](https://github.com/argoproj/argo-workflows/commit/354733e72f8b50645d4818236a5842c258d5627c) fix(swagger): Correct item type. Fixes #3926 (#3932)
 * [1e461766](https://github.com/argoproj/argo-workflows/commit/1e461766f2e7214c5723d15c724a77d14e908340) fix(server): Adds missing webhook permissions. Fixes #3927 (#3929)
 * [88486192](https://github.com/argoproj/argo-workflows/commit/8848619262850a9f1c44d08084300a445a0c0ffb) feat: Step and Task Level Global Timeout (#3686)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian

## v2.11.0-rc1 (2020-09-01)


### Contributors


## v2.11.0 (2020-09-17)

 * [f8e750de](https://github.com/argoproj/argo-workflows/commit/f8e750de5ebab6f3c494c972889b31ef24c73c9b) Update manifests to v2.11.0
 * [c06db575](https://github.com/argoproj/argo-workflows/commit/c06db57572843b38322b301aba783685c774045b) fix(ui): Tiny modal DAG tweaks. Fixes #4039 (#4043)
 * [1b4cf3f1](https://github.com/argoproj/argo-workflows/commit/1b4cf3f1f26f6abf93355a0108f5048be9677978) Update manifests to v2.11.0-rc3
 * [e2594eca](https://github.com/argoproj/argo-workflows/commit/e2594eca965ec2ea14b07f3c1acee4b288b02789) fix: Fix children is not defined error (#3950)
 * [2ed8025e](https://github.com/argoproj/argo-workflows/commit/2ed8025eb0fbf0599c20efc1bccfedfe51c88215) fix: Fix UI selection issues (#3928)
 * [8dc0e94e](https://github.com/argoproj/argo-workflows/commit/8dc0e94e68881693b504f6f2777f937e6f3c3e42) fix: Create global scope before workflow-level realtime metrics (#3979)
 * [cdeabab7](https://github.com/argoproj/argo-workflows/commit/cdeabab722fac97a326e70b956a92d4cb5d58f2c) fix(controller): Script Output didn't set if template has RetryStrategy (#4002)
 * [9c83fac8](https://github.com/argoproj/argo-workflows/commit/9c83fac80594fb0abef18b0de0ff563132ee84ae) fix(ui): Do not save undefined namespace. Fixes #4019 (#4021)
 * [7fd2ecb1](https://github.com/argoproj/argo-workflows/commit/7fd2ecb1d057cbf1e1b8139c30c20eccf86611ea) fix(ui): Correctly show pod events. Fixes #4016 (#4018)
 * [11242c8b](https://github.com/argoproj/argo-workflows/commit/11242c8be5c3bbaf2dbcff68198958504ea88e43) fix(ui): Allow you to view timeline tab. Fixes #4005 (#4006)
 * [3770f618](https://github.com/argoproj/argo-workflows/commit/3770f618ab073fbac6654c9edcc4b53a1e010fea) fix(ui): Report errors when uploading files. Fixes #3994 (#3995)
 * [0fed28ce](https://github.com/argoproj/argo-workflows/commit/0fed28ce26f12a42f3321afee9188e9f59acfea7) fix: Custom metrics are not recorded for DAG tasks Fixes #3872 (#3886)
 * [9146636e](https://github.com/argoproj/argo-workflows/commit/9146636e75e950149ce39df33e4fc6f7346c7282) feat(ui): Introduce modal DAG renderer. Fixes: #3595 (#3967)
 * [4b7a4694](https://github.com/argoproj/argo-workflows/commit/4b7a4694c436c724cb75e09564fcd8c87923d6d7) fix(controller): Revert `resubmitPendingPods` mistake. Fixes #4001 (#4004)
 * [49752fb5](https://github.com/argoproj/argo-workflows/commit/49752fb5f9aa6ab151f311bb62faa021b2ebffa5) fix(controller): Revert parameter value to `*string`. Fixes #3960 (#3963)
 * [ddf850b1](https://github.com/argoproj/argo-workflows/commit/ddf850b1bd99a8343b5e94e7d3634912031e8d44) fix: Consider WorkflowTemplate metadata during validation (#3988)
 * [a8ba447e](https://github.com/argoproj/argo-workflows/commit/a8ba447e3ed4fff3d90cd772fc551db8c225a1c0) fix(server): Remove XSS vulnerability. Fixes #3942 (#3975)
 * [f930c029](https://github.com/argoproj/argo-workflows/commit/f930c0296c41c8723a6f826260a098bb0647efce) Update manifests to v2.11.0-rc2
 * [21cceb0f](https://github.com/argoproj/argo-workflows/commit/21cceb0fd743777c696245ad988a78f03fd5dc08) build: Allow build with older `docker`. Fixes #3977
 * [b6890adb](https://github.com/argoproj/argo-workflows/commit/b6890adb1b5c40ddb4b1aa41c39c337f0f08df12) fix(cli): Allow `argo version` without KUBECONFIG. Fixes #3943 (#3945)
 * [354733e7](https://github.com/argoproj/argo-workflows/commit/354733e72f8b50645d4818236a5842c258d5627c) fix(swagger): Correct item type. Fixes #3926 (#3932)
 * [1e461766](https://github.com/argoproj/argo-workflows/commit/1e461766f2e7214c5723d15c724a77d14e908340) fix(server): Adds missing webhook permissions. Fixes #3927 (#3929)
 * [88486192](https://github.com/argoproj/argo-workflows/commit/8848619262850a9f1c44d08084300a445a0c0ffb) feat: Step and Task Level Global Timeout (#3686)
 * [f446f735](https://github.com/argoproj/argo-workflows/commit/f446f735b4c8c16c95f1306ad3453af7f8ed0108) Update manifests to v2.11.0-rc1
 * [de2185c8](https://github.com/argoproj/argo-workflows/commit/de2185c81ae54736177e0476acae42b8e2dc0af5) feat(controller): Set retry factor to 2. Closes #3911 (#3919)
 * [be91d762](https://github.com/argoproj/argo-workflows/commit/be91d7621d82c6fb23e18ab4eebc9be58a59d81f) fix: Workflow should fail on Pod failure before container starts Fixes #3879 (#3890)
 * [c4c80069](https://github.com/argoproj/argo-workflows/commit/c4c800691b20fccf894422075cf41094c39cffc0) test: Fix TestRetryOmit and TestStopBehavior (#3910)
 * [650869fd](https://github.com/argoproj/argo-workflows/commit/650869fde66158a9e03e58aae8aeabe698fe0da5) feat(server): Display events involved in the workflow. Closes #3673 (#3726)
 * [5b5d2359](https://github.com/argoproj/argo-workflows/commit/5b5d2359ef9f573121fe6429e386f03dd8652ece) fix(controller): Cron re-apply update (#3883)
 * [fd3fca80](https://github.com/argoproj/argo-workflows/commit/fd3fca804ef998c875ce0ee2914605a918d9d01a) feat(artifacts): retrieve subpath from unarchived ref artifact. Closes #3061 (#3063)
 * [6a452ccd](https://github.com/argoproj/argo-workflows/commit/6a452ccd4de538ca3b95febf395151e72195c25f) test: Fix flaky e2e tests (#3909)
 * [6e82bf38](https://github.com/argoproj/argo-workflows/commit/6e82bf382a0b41df46db2cc3a1a3925d009f42e1) feat(controller): Emit events for malformed cron workflows. See #3881 (#3889)
 * [f04bdd6a](https://github.com/argoproj/argo-workflows/commit/f04bdd6afa9f17d86833f1537f8ad6713a441bcb) Update workflow-controller-configmap.yaml (#3901)
 * [bb79e3f5](https://github.com/argoproj/argo-workflows/commit/bb79e3f5a00a62e58056e4abd07b129a0f01617d) fix(executor): Replace default retry in executor with an increased value retryer (#3891)
 * [b681c113](https://github.com/argoproj/argo-workflows/commit/b681c1130a41942291e964f29336f8dca53ec4b2) fix(ui): use absolute URL to redirect from autocomplete list. Closes #3903 (#3906)
 * [712c77f5](https://github.com/argoproj/argo-workflows/commit/712c77f5c46cdbb6f03ec2b020fbca9de08d6894) chore(users): Add Fynd Trak to the list of Users (#3900)
 * [d55402db](https://github.com/argoproj/argo-workflows/commit/d55402db1072ee0598597142807407029f4e728e) ci: Fix broken Multiplatform builds (#3908)
 * [9681a4e2](https://github.com/argoproj/argo-workflows/commit/9681a4e2d22d64bbbd4dab6f377fbd0e7a5e39e5) fix(ui): Improve error recovery. Fixes #3867 (#3869)
 * [b926f8c0](https://github.com/argoproj/argo-workflows/commit/b926f8c0c318dd0012f445abd885b918b5c7d2d7) chore: Remove unused imports (#3892)
 * [4c18a06b](https://github.com/argoproj/argo-workflows/commit/4c18a06ba0a46037d40713a91f69320869b3bdc8) feat(controller): Always retry when `IsTransientErr` to tolerate transient errors. Fixes #3217 (#3853)
 * [0cf7709f](https://github.com/argoproj/argo-workflows/commit/0cf7709ff5b9409fcbaa5322601c5a9045ecbe40) fix(controller): Failure tolerant workflow archiving and offloading. Fixes #3786 and #3837 (#3787)
 * [359ee8db](https://github.com/argoproj/argo-workflows/commit/359ee8db4e89d15effd542680aaebdddcbbb2fd0) fix: Corrects CRD and Swagger types. Fixes #3578 (#3809)
 * [58ac52b8](https://github.com/argoproj/argo-workflows/commit/58ac52b892c15c785f9209aac86d6374199400f1) chore(ui): correct a typo (#3876)
 * [dae0f2df](https://github.com/argoproj/argo-workflows/commit/dae0f2df1ffcc8a2ff4f3dce1ea7da3f34587e2f) feat(controller): Do not try to create pods we know exists to prevent `exceeded quota` errors. Fixes #3791 (#3851)
 * [9781a1de](https://github.com/argoproj/argo-workflows/commit/9781a1de7ebe8d920207329dbf3b104d7061c33e) ci: Create manifest from images again (#3871)
 * [c6b51362](https://github.com/argoproj/argo-workflows/commit/c6b51362eb91f042c63ce64e5c6996fef13c90a7) test: E2E test refactoring (#3849)
 * [04898fee](https://github.com/argoproj/argo-workflows/commit/04898fee31dd362c31f2e57e03c772c0b4b20d5d) chore: Added unittest for PVC exceed quota Closes #3561 (#3860)
 * [4e42208c](https://github.com/argoproj/argo-workflows/commit/4e42208c05cafce169c043040944125a37a64e6d) ci: Changed tagging and amend multi-arch manifest. (#3854)
 * [c352f69d](https://github.com/argoproj/argo-workflows/commit/c352f69d95ce6cb72bbd1f464655b6ba519b8b87) chore: Reduce the 2x workflow save on Semaphore scenario (#3846)
 * [a24bc944](https://github.com/argoproj/argo-workflows/commit/a24bc944822c9f5eed92c0b5b07284d7992908fa) feat(controller): Mutexes. Closes #2677 (#3631)
 * [a821c6d4](https://github.com/argoproj/argo-workflows/commit/a821c6d47c404d676672617fc6b8b60e43e94952) ci: Fix build by providing clean repo inside Docker (#3848)
 * [99fe11a7](https://github.com/argoproj/argo-workflows/commit/99fe11a7b9b2c26c25701c6aa29ee535089c979d) feat: Show next scheduled cron run in UI/CLI (#3847)
 * [6aaceeb9](https://github.com/argoproj/argo-workflows/commit/6aaceeb9541f46ee6af97e072be8d935812b7bc5) fix: Treat collapsed nodes as their siblings (#3808)
 * [7f5acd6f](https://github.com/argoproj/argo-workflows/commit/7f5acd6f2df9310fee45e6dff740ed610fefd93f) docs: Add 23mofang to USERS.md
 * [10cb447a](https://github.com/argoproj/argo-workflows/commit/10cb447a92b5f1be814e4b8a03be47aced7bd531) docs: Update example README for duration (#3844)
 * [1678e58c](https://github.com/argoproj/argo-workflows/commit/1678e58c76160f8a5d862e374ec07b35c777783b) ci: Remove external build dependency (#3831)
 * [743ec536](https://github.com/argoproj/argo-workflows/commit/743ec53652bf1989931a2c23c2db5e29043e3582) fix(ui): crash when workflow node has no memoization info (#3839)
 * [a2f54da1](https://github.com/argoproj/argo-workflows/commit/a2f54da15de54b025859f7ba48779a062d42d8f3) fix(docs): Amend link to the Workflow CRD (#3828)
 * [ca8ab468](https://github.com/argoproj/argo-workflows/commit/ca8ab468dc72eb3fc2c038b4916c3b124a7e7b99) fix: Carry over ownerReferences from resubmitted workflow. Fixes #3818 (#3820)
 * [da43086a](https://github.com/argoproj/argo-workflows/commit/da43086a19f88c0b7ac71fdb888f913fd619962b) fix(docs): Add Entrypoint Cron Backfill example  Fixes #3807 (#3814)
 * [ed749a55](https://github.com/argoproj/argo-workflows/commit/ed749a5581b3478ee3cad8931f970acdaf9df190) test: Skip TestStopBehavior and TestRetryOmit (#3822)
 * [9292ae1e](https://github.com/argoproj/argo-workflows/commit/9292ae1e84cd93ed05c53ce70fe1eac9819ecbb8) ci: static files not being built with Homebrew and dirty binary. Fixes #3769 (#3801)
 * [c840adb2](https://github.com/argoproj/argo-workflows/commit/c840adb246122c2da6609339af1a573718a8dc93) docs: memory base amount denominator documentation
 * [8e1a3db5](https://github.com/argoproj/argo-workflows/commit/8e1a3db58c2edf73c36f21a8ef87a1a1e40576d9) feat(ui): add node memoization information to node summary view (#3741)
 * [9de49e2e](https://github.com/argoproj/argo-workflows/commit/9de49e2e657f272ecd81a8fdeafed4401c7a0dcc) ci: Change workflow for pushing images. Fixes #2080
 * [d235c7d5](https://github.com/argoproj/argo-workflows/commit/d235c7d52810d701e473723ab3d1a85c0c38e9c4) fix: Consider all children of TaskGroups in DAGs (#3740)
 * [3540d152](https://github.com/argoproj/argo-workflows/commit/3540d152a62261d0af25c48756acbae710684db0) Add SYS_PTRACE to ease the setup of non-root deployments with PNS executor. (#3785)
 * [2f654971](https://github.com/argoproj/argo-workflows/commit/2f6549714e1502f2efce4a6d96e5e5f5a1d982f3) chore: add New Relic to USERS.md (#3810)
 * [ce5da590](https://github.com/argoproj/argo-workflows/commit/ce5da590abf3946c2c939109cd2feb37b98d5892) docs: Add section on CronWorkflow crash recovery (#3804)
 * [0ca83924](https://github.com/argoproj/argo-workflows/commit/0ca8392485f32c3acdef312befe348ced037b7fb) feat: Github Workflow multi arch. Fixes #2080 (#3744)
 * [bee0e040](https://github.com/argoproj/argo-workflows/commit/bee0e040d0921b9d6d5c15c5d1d1ea6c27bdc2d5) docs: Remove confusing namespace (#3772)
 * [7ad6eb84](https://github.com/argoproj/argo-workflows/commit/7ad6eb8456456f3aea1bf35f1b5bae5058ffd962) fix(ui): Remove outdated download links. Fixes #3762 (#3783)
 * [22636782](https://github.com/argoproj/argo-workflows/commit/226367827dbf62f0a3155abbdc9de0b6d57f693c) fix(ui): Correctly load and store namespace. Fixes #3773 and #3775 (#3778)
 * [a9577ab9](https://github.com/argoproj/argo-workflows/commit/a9577ab96d226dc68a62e9a38093efca8607f81b) test: Increase cron test timeout to 7m (#3799)
 * [ed90d403](https://github.com/argoproj/argo-workflows/commit/ed90d4039d73894bf3073dd39735152833b87457) fix(controller): Support exit handler on workflow templates.  Fixes #3737 (#3782)
 * [dc75ee81](https://github.com/argoproj/argo-workflows/commit/dc75ee8116ceb75e0ec9b6d9175d26ab5f08912e) test: Simplify E2E test tear-down (#3749)
 * [821e40a2](https://github.com/argoproj/argo-workflows/commit/821e40a2b210fe71f82b445c2c72621ac34e4742) build: Retry downloading Kustomize (#3792)
 * [f15a8f77](https://github.com/argoproj/argo-workflows/commit/f15a8f77834e369b291c9e6955bdcef324afc6cd) fix: workflow template ref does not work in other namespace (#3795)
 * [ef44a03d](https://github.com/argoproj/argo-workflows/commit/ef44a03d363b1e7e2a89d268260e9a834553de7b) fix: Increase the requeue duration on checkForbiddenErrorAndResubmitAllowed (#3794)
 * [0125ab53](https://github.com/argoproj/argo-workflows/commit/0125ab5307249e6713d6706975d870a78c5046a5) fix(server): Trucate creator label at 63 chars. Fixes #3756 (#3758)
 * [a38101f4](https://github.com/argoproj/argo-workflows/commit/a38101f449cd462847a3ac99ee65fa70e40acd80) feat(ui): Sign-post IDE set-up. Closes #3720 (#3723)
 * [21dc23db](https://github.com/argoproj/argo-workflows/commit/21dc23dbe3571f745bd124edd0f0e0c7cf09aced) chore: Format test code (#3777)
 * [ee910b55](https://github.com/argoproj/argo-workflows/commit/ee910b5510c9e00bd07c32d2e8ef0846663a330a) feat(server): Emit audit events for workflow event binding errors (#3704)
 * [e9b29e8c](https://github.com/argoproj/argo-workflows/commit/e9b29e8c1f2cdc99e7ccde11f939b865b51e2320) fix: TestWorkflowLevelSemaphore flakiness (#3764)
 * [fadd6d82](https://github.com/argoproj/argo-workflows/commit/fadd6d828e152f88236bcd5483bae39c619d2622) fix: Fix workflow onExit nodes not being displayed in UI (#3765)
 * [df06e901](https://github.com/argoproj/argo-workflows/commit/df06e90193f706da48946e03642b1f758f0d3f2d) docs: Correct typo in `--instanceid`
 * [82a671c0](https://github.com/argoproj/argo-workflows/commit/82a671c00da25b99470a297ed98c794745a3241a) build: Lint e2e test files (#3752)
 * [513675bc](https://github.com/argoproj/argo-workflows/commit/513675bc5b9be6eda48983cb5c8b4ad4d42c9efb) fix(executor): Add retry on pods watch to handle timeout. (#3675)
 * [e35a86ff](https://github.com/argoproj/argo-workflows/commit/e35a86ff108e247b6fd7dfbf947300f086d2e912) feat: Allow parametrizable int fields (#3610)
 * [da115f9d](https://github.com/argoproj/argo-workflows/commit/da115f9db328af9bcc9152afd58b55ba929f7764) fix(controller): Tolerate malformed resources. Fixes #3677 (#3680)
 * [407f9e63](https://github.com/argoproj/argo-workflows/commit/407f9e63c065d154ee2e6a77a7040ae863e329aa) docs: Remove misleading argument in workflow template dag examples. (#3735) (#3736)
 * [f8053ae3](https://github.com/argoproj/argo-workflows/commit/f8053ae379a8244b53a8da6787fe6d9769158cbe) feat(operator): Add scope params for step startedAt and finishedAt (#3724)
 * [54c2134f](https://github.com/argoproj/argo-workflows/commit/54c2134fcdf4a4143b99590730340b79e57e180d) fix: Couldn't Terminate/Stop the ResourceTemplate Workflow (#3679)
 * [12ddc1f6](https://github.com/argoproj/argo-workflows/commit/12ddc1f69a0495331eea83a3cd6be9c453658c9a) fix: Argo linting does not respect namespace of declared resource (#3671)
 * [acfda260](https://github.com/argoproj/argo-workflows/commit/acfda260e78e4035757bdfb7923238b7e48bf0f9) feat(controller): controller logs to be structured #2308 (#3727)
 * [cc2e42a6](https://github.com/argoproj/argo-workflows/commit/cc2e42a691e01b6c254124c7aed52c11540e8475) fix(controller): Tolerate PDB delete race. Fixes #3706 (#3717)
 * [5eda8b86](https://github.com/argoproj/argo-workflows/commit/5eda8b867d32ab09be6643ad111383014f58b0e9) fix: Ensure target task's onExit handlers are run (#3716)
 * [811a4419](https://github.com/argoproj/argo-workflows/commit/811a441938ebfe1a9f7e634e6b4b8c1a98084df4) docs(windows): Add note about artifacts on windows (#3714)
 * [5e5865fb](https://github.com/argoproj/argo-workflows/commit/5e5865fb7ad2eddfefaf6192492bccbd07cbfc35) fix: Ingress docs (#3713)
 * [eeb3c9d1](https://github.com/argoproj/argo-workflows/commit/eeb3c9d1afb6b8e19423a71ca7eb24838358be8d) fix: Fix bug with 'argo delete --older' (#3699)
 * [6134a565](https://github.com/argoproj/argo-workflows/commit/6134a56540e9bbb744fe06ce5be69eca99e95b32) chore: Introduce convenience methods for intstr. (#3702)
 * [7aa536ed](https://github.com/argoproj/argo-workflows/commit/7aa536edaeb24d271593b4633cd211039df8beb6) feat: Upgrade Minio v7 with support IRSA (#3700)
 * [4065f265](https://github.com/argoproj/argo-workflows/commit/4065f265bafd1a5e410f48a8fb0e25b505ad3b61) docs: Correct version. Fixes #3697 (#3701)
 * [71d61281](https://github.com/argoproj/argo-workflows/commit/71d6128154587f2e966d1fc2bad4195bc0b4fba8) feat(server): Trigger workflows from webhooks. Closes #2667  (#3488)
 * [a5d995dc](https://github.com/argoproj/argo-workflows/commit/a5d995dc49caa9837e0ccf86290fd485f72ec065) fix(controller): Adds ALL_POD_CHANGES_SIGNIFICANT (#3689)
 * [9f00cdc9](https://github.com/argoproj/argo-workflows/commit/9f00cdc9d73b44569a071d18535586e28c469b8e) fix: Fixed workflow queue duration if PVC creation is forbidden (#3691)
 * [2baaf914](https://github.com/argoproj/argo-workflows/commit/2baaf914dfa0de517a5e39490e44ad682404f5c3) chore: Update issue templates (#3681)
 * [41ebbe8e](https://github.com/argoproj/argo-workflows/commit/41ebbe8e38861e1ad09db6687512757fda2487d7) fix: Re-introduce 1 second sleep to reconcile informer (#3684)
 * [6e3c5bef](https://github.com/argoproj/argo-workflows/commit/6e3c5bef5c2bbfbef4a74b4c9c91e288b8e94735) feat(ui): Make UI errors recoverable. Fixes #3666 (#3674)
 * [27fea1bb](https://github.com/argoproj/argo-workflows/commit/27fea1bbd3dcb5f420beb85926a1fb2434b33b7e) chore(ui): Add label to 'from' section in Workflow Drawer (#3685)
 * [32d6f752](https://github.com/argoproj/argo-workflows/commit/32d6f75212e07004bcbf2c34973160c0ded2023a) feat(ui): Add links to wft, cwf, or cwft to workflow list and details. Closes #3621 (#3662)
 * [1c95a985](https://github.com/argoproj/argo-workflows/commit/1c95a985b486c4e23622322faf8caccbdd991c89) fix: Fix collapsible nodes rendering (#3669)
 * [87b62bbb](https://github.com/argoproj/argo-workflows/commit/87b62bbb56241c948e8c46bef4e9d01fe2c67429) build: Use http in dev server (#3670)
 * [dbb39368](https://github.com/argoproj/argo-workflows/commit/dbb39368295cbc0ef886e78236338572c37607a1) feat: Add submit options to 'argo cron create' (#3660)
 * [2b6db45b](https://github.com/argoproj/argo-workflows/commit/2b6db45b2775cf8bff22b89b0a30e4dda700ecf9) fix(controller): Fix nested maps. Fixes #3653 (#3661)
 * [3f293a4d](https://github.com/argoproj/argo-workflows/commit/3f293a4d647c6c10cf1bafc8d340453e87bd4351) fix: interface{} values should be expanded with '%v' (#3659)
 * [f08ab972](https://github.com/argoproj/argo-workflows/commit/f08ab9727d6c2f3f12f42f554ad896a21abb6b9c) docs: Fix type in default-workflow-specs.md (#3654)
 * [a8f4da00](https://github.com/argoproj/argo-workflows/commit/a8f4da00b6157a2a457eef74cfe9c46b7a39f9ff) fix(server): Report v1.Status errors. Fixes #3608 (#3652)
 * [a3a4ea0a](https://github.com/argoproj/argo-workflows/commit/a3a4ea0a43c1421d04198dacd2000a0b8ecb17ad) fix: Avoid overriding the Workflow parameter when it is merging with WorkflowTemplate parameter (#3651)
 * [9ce1d824](https://github.com/argoproj/argo-workflows/commit/9ce1d824eb0ad607035db7d3bfaa6a54fbe6dc34) fix: Enforce metric Help must be the same for each metric Name (#3613)
 * [4eca0481](https://github.com/argoproj/argo-workflows/commit/4eca048136a2ef5a5e066b0458315655ba40ea76) docs: Update link to examples so works in raw github.com view (#3623)
 * [f77780f5](https://github.com/argoproj/argo-workflows/commit/f77780f5bdeb875506b4f619b63c40295b66810a) fix(controller): Carry-over labels for re-submitted workflows. Fixes #3622 (#3638)
 * [3f3a4c91](https://github.com/argoproj/argo-workflows/commit/3f3a4c916229acde263933fb689187b8c4fcb278) docs: Add comment to config map about SSO auth-mode (#3634)
 * [d9090c99](https://github.com/argoproj/argo-workflows/commit/d9090c993907bb8e96481c64af214b4941f88418) build: Disable TLS for dev mode. Fixes #3617 (#3618)
 * [bcc6e1f7](https://github.com/argoproj/argo-workflows/commit/bcc6e1f79c42f006b2720e1e185af59a984103d5) fix: Fixed flaky unit test TestFailSuspendedAndPendingNodesAfterDeadline (#3640)
 * [8f70d224](https://github.com/argoproj/argo-workflows/commit/8f70d2243e07c04254222b1cabf8088245ca55e2) fix: Don't panic on invalid template creation (#3643)
 * [5b0210dc](https://github.com/argoproj/argo-workflows/commit/5b0210dccff725b6288799a0c215550fe6fc6247) fix: Simplify the WorkflowTemplateRef field validation to support all fields in WorkflowSpec except `Templates` (#3632)
 * [2375878a](https://github.com/argoproj/argo-workflows/commit/2375878af4ce02af81326e7a672b32c7ce8bfbb1) fix: Fix 'malformed request: field selector' error (#3636)
 * [87ea54c9](https://github.com/argoproj/argo-workflows/commit/87ea54c9dec767f617a1b8fcdd466dd00264f2ea) docs: Add documentation for configuring OSS artifact storage (#3639)
 * [861afd36](https://github.com/argoproj/argo-workflows/commit/861afd369ce63e46c085c0e95ca7bf9ed2175373) docs: Correct indentation for codeblocks within bullet-points for "workflow-templates" (#3627)
 * [0f37e81a](https://github.com/argoproj/argo-workflows/commit/0f37e81abd42fbdece9ea70b2091256dbecd1220) fix: DAG level Output Artifacts on K8S and Kubelet executor (#3624)
 * [a89261bf](https://github.com/argoproj/argo-workflows/commit/a89261bf6b6ab5b83037044c30f3a55cc1162d62) build(cli)!: Zip binaries binaries. Closes #3576 (#3614)
 * [7f844473](https://github.com/argoproj/argo-workflows/commit/7f844473167df32840720437953da478b3bdffa2) fix(controller): Panic when outputs in a cache entry are nil (#3615)
 * [86f03a3f](https://github.com/argoproj/argo-workflows/commit/86f03a3fbd871164cff95005d00b04c220ba58be) fix(controller): Treat TooManyError same as Forbidden (i.e. try again). Fixes #3606 (#3607)
 * [2e299df3](https://github.com/argoproj/argo-workflows/commit/2e299df34f86e0ad80122f84083e7b92bd542171) build: Increase timeout (#3616)
 * [e0a4f13d](https://github.com/argoproj/argo-workflows/commit/e0a4f13d1f3df93fd2c003146d7db2dd2dd924e6) fix(server): Re-establish watch on v1.Status errors. Fixes #3608 (#3609)
 * [cdbb5711](https://github.com/argoproj/argo-workflows/commit/cdbb57116fc12d28be3060ff1fff2498ebc18837) docs: Memoization Documentation (#3598)
 * [7abead2a](https://github.com/argoproj/argo-workflows/commit/7abead2a564876a695201cf7539bd20d1fc67888) docs: fix typo - replace "workfow" with "workflow" (#3612)
 * [f7be20c1](https://github.com/argoproj/argo-workflows/commit/f7be20c1cc0e7b6ab708d7d7a1f60c6898c834e4) fix: Fix panic and provide better error message on watch endpoint (#3605)
 * [491f4f74](https://github.com/argoproj/argo-workflows/commit/491f4f747619783384937348effaaa56143ea8f1) fix: Argo Workflows does not honour global timeout if step/pod is not able to schedule (#3581)
 * [5d8f85d5](https://github.com/argoproj/argo-workflows/commit/5d8f85d5072b5e580a33358cf5fea1fac372baa4) feat(ui): Enhanced workflow submission. Closes #3498 (#3580)
 * [a4a26414](https://github.com/argoproj/argo-workflows/commit/a4a26414e5eef85b61e96789264a4b96a6effc10) build: Initialize npm before installing swagger-markdown (#3602)
 * [ad3441dc](https://github.com/argoproj/argo-workflows/commit/ad3441dc84b207df57094df570f01915634c073d) feat: Add 'argo node set' command (#3277)
 * [a43bf129](https://github.com/argoproj/argo-workflows/commit/a43bf129e4c7e1f6fcea2af0acdd2f07cc5a2287) docs: Migrate to homebrew-core (#3567) (#3568)
 * [17b46bdb](https://github.com/argoproj/argo-workflows/commit/17b46bdbbe72072d87f83625b4cf1873f9c5379b) fix(controller): Fix bug in util/RecoverWorkflowNameFromSelectorString. Add error handling (#3596)
 * [c968877c](https://github.com/argoproj/argo-workflows/commit/c968877c82dc5ad4019d11c449477af6e060aec1) docs: Document ingress set-up. Closes #3080 (#3592)
 * [8b6e43f6](https://github.com/argoproj/argo-workflows/commit/8b6e43f6dafbb95168eaa8c0b2a52f9e177ba075) fix(ui): Fix multiple UI issues (#3573)
 * [cdc935ae](https://github.com/argoproj/argo-workflows/commit/cdc935ae76b3d7cc50a486695b40ff2f647b49bc) feat(cli): Support deleting resubmitted workflows (#3554)
 * [1b757ea9](https://github.com/argoproj/argo-workflows/commit/1b757ea9bc75a379262928be76a4179ea75aa658) feat(ui): Change default language for Resource Editor to YAML and store preference in localStorage. Fixes #3543 (#3560)
 * [c583bc04](https://github.com/argoproj/argo-workflows/commit/c583bc04c672d3aac6955024568a7daebe928932) fix(server): Ignore not-JWT server tokens. Fixes #3562 (#3579)
 * [5afbc131](https://github.com/argoproj/argo-workflows/commit/5afbc131f2e43a0096857534a2814a9fdd9b95f9) fix(controller): Do not panic on nil output value. Fixes #3505 (#3509)
 * [c409624b](https://github.com/argoproj/argo-workflows/commit/c409624b43cdc8823ab02b30ff9f3bc5b4d66c1a) docs: Synchronization documentation (#3537)
 * [0bca0769](https://github.com/argoproj/argo-workflows/commit/0bca07696ccf930ebdf4b3af7c6a44ddcb65e679) docs: Workflow of workflows pattern (#3536)
 * [827106de](https://github.com/argoproj/argo-workflows/commit/827106de2f8f3e03f267a3ebbb6095a1f9b4a0e6) fix: Skip TestStorageQuotaLimit (#3566)
 * [13b1d3c1](https://github.com/argoproj/argo-workflows/commit/13b1d3c19e94047ae97a071e4468b1050b8e292b) feat(controller): Step level memoization. Closes #944 (#3356)
 * [96e520eb](https://github.com/argoproj/argo-workflows/commit/96e520eb68afb36894b5d2373d55505cc3703a94) fix: Exceeding quota with volumeClaimTemplates (#3490)
 * [144c9b65](https://github.com/argoproj/argo-workflows/commit/144c9b65ecbc671c30d41a0bd65546957a34c713) fix(ui): cannot push to nil when filtering by label (#3555)
 * [7e4a7808](https://github.com/argoproj/argo-workflows/commit/7e4a780854fc5f39fcfc77e4354620c307ee21f1) feat: Collapse children in UI Workflow viewer (#3526)
 * [7536982a](https://github.com/argoproj/argo-workflows/commit/7536982ae7451a1a8bcd4b9ddfe6385b138fd782) fix: Fix flakey TestRetryOmitted (#3552)
 * [05d573d7](https://github.com/argoproj/argo-workflows/commit/05d573d789d4c95ece17e058a72c487fad0992ff) docs: Change formatting to put content into code block (#3553)
 * [dcee3484](https://github.com/argoproj/argo-workflows/commit/dcee34849ba6302a126d2eaf684a06d246080fd0) fix: Fix links in fields doc (#3539)
 * [fb67c1be](https://github.com/argoproj/argo-workflows/commit/fb67c1beb69c141604322bb19cf43596f9059cf9) Fix issue #3546 (#3547)
 * [d07a0e74](https://github.com/argoproj/argo-workflows/commit/d07a0e74888254fe78fa653e532c5f1963056598) ci: Make builds marginally faster. Fixes #3515 (#3519)
 * [4cb6aa04](https://github.com/argoproj/argo-workflows/commit/4cb6aa0488ca43158c9a7809c23126e062becd20) chore: Enable no-response bot (#3510)
 * [31afa92a](https://github.com/argoproj/argo-workflows/commit/31afa92ab0c91e8026bba29d216e6fcc2d150ee7) fix(artifacts): support optional input artifacts, Fixes #3491 (#3512)
 * [977beb46](https://github.com/argoproj/argo-workflows/commit/977beb462dcb11afd1913a4e1397136b1b14915b) fix: Fix when retrying Workflows with Omitted nodes (#3528)
 * [ab4ef5c5](https://github.com/argoproj/argo-workflows/commit/ab4ef5c5a290196878d3cf18a9a7036c8bfc9144) fix: Panic on CLI Watch command (#3532)
 * [b901b279](https://github.com/argoproj/argo-workflows/commit/b901b2790fe3c7c350b393e9a0943721ea76f3af) fix(controller): Backoff exponent is off by one. Fixes #3513 (#3514)
 * [49ef5c0f](https://github.com/argoproj/argo-workflows/commit/49ef5c0fe5b7b92ec0035e859a09cf906e4f02f2) fix: String interpreted as boolean in labels (#3518)
 * [19e700a3](https://github.com/argoproj/argo-workflows/commit/19e700a3388552d9440ae75dd259efcbeb0a3657) fix(cli): Check mutual exclusivity for argo CLI flags (#3493)
 * [7d45ff7f](https://github.com/argoproj/argo-workflows/commit/7d45ff7f014d011ef895b9c808da781000ea32a5) fix: Panic on releaseAllWorkflowLocks if Object is not Unstructured type (#3504)
 * [1b68a5a1](https://github.com/argoproj/argo-workflows/commit/1b68a5a15af12fb0866f4d5a4dcd9fb5da3f2ab4) fix: ui/package.json & ui/yarn.lock to reduce vulnerabilities (#3501)
 * [7f262fd8](https://github.com/argoproj/argo-workflows/commit/7f262fd81bae1f8b9bc7707d8bf02f10174cc87d) fix(cli)!: Enable CLI to work without kube config. Closes #3383, #2793 (#3385)
 * [2976e7ac](https://github.com/argoproj/argo-workflows/commit/2976e7ac517ec680b1077e64aa499d92c5d39a0d) build: Clear cmd docs before generating them (#3499)
 * [27528ba3](https://github.com/argoproj/argo-workflows/commit/27528ba34538b764db9254d41761a4edeba6694c) feat: Support completions for more resources (#3494)
 * [5bd2ad7a](https://github.com/argoproj/argo-workflows/commit/5bd2ad7a9d0ad5437fb7d1b7955e0b8e0c9b52ca) fix: Merge WorkflowTemplateRef with defaults workflow spec (#3480)
 * [e244337b](https://github.com/argoproj/argo-workflows/commit/e244337be239e462086a2bcad46f71ffb57a7a62) chore: Added examples for exit handler for step and dag level (#3495)
 * [bcb32547](https://github.com/argoproj/argo-workflows/commit/bcb325476ba49877df6b2dd9622bc64dfe9ad5f4) build: Use `git rev-parse` to accomodate older gits (#3497)
 * [3eb6e2f9](https://github.com/argoproj/argo-workflows/commit/3eb6e2f90c700070c4f1d2730a727aea7746c776) docs: Add link to GitHub Actions in the badge (#3492)
 * [69179e72](https://github.com/argoproj/argo-workflows/commit/69179e72c0872cde9131cc9d68192d5c472d64c9) fix: link to server auth mode docs, adds Tulip as official user (#3486)
 * [7a8e2b34](https://github.com/argoproj/argo-workflows/commit/7a8e2b34631aa8ae7037059deb5c2108a2ca2cb4) docs: Add comments to NodePhase definition. Closes #1117. (#3467)
 * [24d1e529](https://github.com/argoproj/argo-workflows/commit/24d1e52996d8af27909cf4477a5a14950a9a6da7) build: Simplify builds (#3478)
 * [acf56f9f](https://github.com/argoproj/argo-workflows/commit/acf56f9f0d2da426eab9cacc03b7ebadb4aa9ea3) feat(server): Label workflows with creator. Closes #2437 (#3440)
 * [3b8ac065](https://github.com/argoproj/argo-workflows/commit/3b8ac065a1db8ebe629d7cf02c1a8585b34ea2b7) fix: Pass resolved arguments to onExit handler (#3477)
 * [58097a9e](https://github.com/argoproj/argo-workflows/commit/58097a9ec2a9203dfebce9c75fdddc84ac48885e) docs: Add controller-level metrics (#3464)
 * [f6f1844b](https://github.com/argoproj/argo-workflows/commit/f6f1844b73d4e643614f575075401946b9aa7a7c) feat: Attempt to resolve nested tags (#3339)
 * [48e15d6f](https://github.com/argoproj/argo-workflows/commit/48e15d6fce2f980ae5dd5b5d2ff405f496b8f644) feat(cli): List only resubmitted workflows option (#3357)
 * [25e9c0cd](https://github.com/argoproj/argo-workflows/commit/25e9c0cdf73a3c9fa712fc3b544f1f8f33980515) docs, quick-start. Use http, not https for link (#3476)
 * [7a2d7642](https://github.com/argoproj/argo-workflows/commit/7a2d76427da0ae6440f91adbb2f97e62b28355e6) fix: Metric emission with retryStrategy (#3470)
 * [f5876e04](https://github.com/argoproj/argo-workflows/commit/f5876e041a2d87c8d48983751d2c3b4959fb1d93) test(controller): Ensure resubmitted workflows have correct labels (#3473)
 * [aa92ec03](https://github.com/argoproj/argo-workflows/commit/aa92ec03885b2c58c537b33161809f9966faf968) fix(controller): Correct fail workflow when pod is deleted with --force. Fixes #3097 (#3469)
 * [a1945d63](https://github.com/argoproj/argo-workflows/commit/a1945d635b24963af7f52bd73b19a7da52d647e3) fix(controller): Respect the volumes of a workflowTemplateRef. Fixes … (#3451)
 * [847ba530](https://github.com/argoproj/argo-workflows/commit/847ba5305273a16a65333c278e705dc157b9c723) test(controller): Add memoization tests. See #3214 (#3455) (#3466)
 * [f5183aed](https://github.com/argoproj/argo-workflows/commit/f5183aed8bb42b5c267b838c7b31b0f38fec28e8) docs: Fix CLI docs (#3465)
 * [1e42813a](https://github.com/argoproj/argo-workflows/commit/1e42813aaaaee55b9e4483338f7a8554ba9f9eab) test(controller): Add memoization tests. See #3214 (#3455)
 * [abe768c4](https://github.com/argoproj/argo-workflows/commit/abe768c4ba5433fe72f9e6d5a1dde09d37d4d20d) feat(cli): Allow to view previously terminated container logs (#3423)
 * [7581025f](https://github.com/argoproj/argo-workflows/commit/7581025ffac0da6a4c9b125dac3173d0c84aef4f) fix: Allow ints for sequence start/end/count. Fixes #3420 (#3425)
 * [b82f900a](https://github.com/argoproj/argo-workflows/commit/b82f900ae5e446d14a9899302c143c8e32447eab) Fixed typos (#3456)
 * [23760119](https://github.com/argoproj/argo-workflows/commit/23760119d4664f0825536d368b65cdde356e0ff3) feat: Workflow Semaphore Support (#3141)
 * [81cba832](https://github.com/argoproj/argo-workflows/commit/81cba832ed1d4f5b116dc9e43f1f3ad79c190c44) feat: Support WorkflowMetadata in WorkflowTemplate and ClusterWorkflowTemplate (#3364)
 * [568c032b](https://github.com/argoproj/argo-workflows/commit/568c032b3b86c39b39ae38d772b33bc1cbb757de) chore: update aws-sdk-go version (#3376)
 * [bd27d9f3](https://github.com/argoproj/argo-workflows/commit/bd27d9f3216bae609de2cb482a89af3783f0d132) chore: Upgrade node-sass (#3450)
 * [b1e601e5](https://github.com/argoproj/argo-workflows/commit/b1e601e586d376ef3b022acf684cf5de648dc3dc) docs: typo in argo stop --help (#3439)
 * [308c7083](https://github.com/argoproj/argo-workflows/commit/308c7083bded1b6a1fb91bcd963e1e9b8d0b4152) fix(controller): Prevent panic on nil node. Fixes #3436 (#3437)
 * [8ab06f53](https://github.com/argoproj/argo-workflows/commit/8ab06f532b24944e5e9c3ed33c4adc249203cad4) feat(controller): Add log message count as metrics. (#3362)
 * [5d0c436d](https://github.com/argoproj/argo-workflows/commit/5d0c436d3d148d70fd766fa50f97be6b2fef0d45) chore: Fix GitHub Actions Docker Image build  (#3442)
 * [e54b4ab5](https://github.com/argoproj/argo-workflows/commit/e54b4ab5cfaddec4e5f3e3cdecd6ea931501f6fb) docs: Add Sohu as official Argo user (#3430)
 * [ee6c8760](https://github.com/argoproj/argo-workflows/commit/ee6c8760e3d46dfdab0f8d3a63dbf1995322ad4b) fix: Ensure task dependencies run after onExit handler is fulfilled (#3435)
 * [6dc04b39](https://github.com/argoproj/argo-workflows/commit/6dc04b39c7986046c2be1535d2a933e4cba25e03) chore: Use GitHub Actions to build Docker Images to allow publishing Windows Images (#3291)
 * [05b3590b](https://github.com/argoproj/argo-workflows/commit/05b3590b5dc70963700b4a7a5cef4afd76b4943d) feat(controller): Add support for Docker workflow executor for Windows nodes (#3301)
 * [676868f3](https://github.com/argoproj/argo-workflows/commit/676868f31da1bce361e89bebfa1eea81471784ac) fix(docs): Update kubectl proxy URL (#3433)
 * [3507c3e6](https://github.com/argoproj/argo-workflows/commit/3507c3e6e8e9c420a6028a43b930a3ef6b221705) docs: Make https://argoproj.github.io/argo/  (#3369)
 * [733e95f7](https://github.com/argoproj/argo-workflows/commit/733e95f742ff14fb7c303d8b1dbf30403e9e8983) fix: Add struct-wide RWMutext to metrics (#3421)
 * [0463f241](https://github.com/argoproj/argo-workflows/commit/0463f24165e360344b5ff743915d16a12fef0ba0) fix: Use a unique queue to visit nodes (#3418)
 * [eddcac63](https://github.com/argoproj/argo-workflows/commit/eddcac6398e674aa24b59aea2e449492cf2c0c02) fix: Script steps fail with exceededQuota (#3407)
 * [c631a545](https://github.com/argoproj/argo-workflows/commit/c631a545e824682652569e49eb764844a7f5cb05) feat(ui): Add Swagger UI (#3358)
 * [910f636d](https://github.com/argoproj/argo-workflows/commit/910f636dcfad66c999aa859e11a31a9a772ccc79) fix: No panic on watch. Fixes #3411 (#3426)
 * [b4da1bcc](https://github.com/argoproj/argo-workflows/commit/b4da1bccc7f961200b8fe8551e4b286d1d5d5a9f) fix(sso): Remove unused `groups` claim. Fixes #3411 (#3427)
 * [330d4a0a](https://github.com/argoproj/argo-workflows/commit/330d4a0a2085b986855f9d3f4c5e27fbbe261ca9) fix: panic on wait command if event is null (#3424)
 * [7c439424](https://github.com/argoproj/argo-workflows/commit/7c4394245437d36245a4c9246a51ceb92edeaf42) docs: Include timezone name reference (#3414)
 * [03cbb8cf](https://github.com/argoproj/argo-workflows/commit/03cbb8cf2c75f5b241ae543259ea9db02e9339fd) fix(ui): Render DAG with exit node (#3408)
 * [3d50f985](https://github.com/argoproj/argo-workflows/commit/3d50f9852b481692235a3f075c4c0966e6404104) feat: Expose certain queue metrics (#3371)
 * [c7b35e05](https://github.com/argoproj/argo-workflows/commit/c7b35e054e3eee38f750c0eaf4a5431a56f80c49) fix: Ensure non-leaf DAG tasks have their onExit handler's run (#3403)
 * [70111600](https://github.com/argoproj/argo-workflows/commit/70111600d464bd7dd99014aa88b5f2cbab64a573) fix: Fix concurrency issues with metrics (#3401)
 * [d307f96f](https://github.com/argoproj/argo-workflows/commit/d307f96f2307da4897685b96ef54251b064de239) docs: Update config example to include useSDKCreds (#3398)
 * [637d50bc](https://github.com/argoproj/argo-workflows/commit/637d50bc132c346885caa4e70eee47ad5c96648e) chore: maybe -> may be (#3392)
 * [e70a8863](https://github.com/argoproj/argo-workflows/commit/e70a8863582e6fab7e2c5ea7c95a7fc0b4ab374d) chore: Added CWFT WorkflowTemplateRef example (#3386)
 * [bc4faf5f](https://github.com/argoproj/argo-workflows/commit/bc4faf5f739e9172b7968e198dc595f27d506f7b) fix: Fix bug parsing parmeters (#3372)
 * [4934ad22](https://github.com/argoproj/argo-workflows/commit/4934ad227f043a5554c9a4f717f09f70d2c18cbf) fix: Running pods are garaged in PodGC onSuccess
 * [0541cfda](https://github.com/argoproj/argo-workflows/commit/0541cfda611a656ab16dbfcd7bed858b7c8b2f3c) chore(ui): Remove unused interfaces for artifacts (#3377)
 * [20382cab](https://github.com/argoproj/argo-workflows/commit/20382cab7bbbbd5646a3dbfac6ee18586a6eada5) docs: Fix incorrect example of global parameter (#3375)
 * [1db93c06](https://github.com/argoproj/argo-workflows/commit/1db93c062c4f7e417bf74afe253e9a44e5381802) perf: Optimize time-based filtering on large number of workflows (#3340)
 * [2ab9495f](https://github.com/argoproj/argo-workflows/commit/2ab9495f0f3d944243d845411bafe7ebe496642b) fix: Don't double-count metric events (#3350)
 * [7bd3e720](https://github.com/argoproj/argo-workflows/commit/7bd3e7209018d0d7716ca0dbd0ffb1863165892d) fix(ui): Confirmation of workflow actions (#3370)
 * [488790b2](https://github.com/argoproj/argo-workflows/commit/488790b247191dd22babadd9592efae11f4fd245) Wellcome is using Argo in our Data Labs division (#3365)
 * [63e71192](https://github.com/argoproj/argo-workflows/commit/63e71192852138685d68156a0f6b1133ecfdaf74) chore: Remove unused code (#3367)
 * [a64ceb03](https://github.com/argoproj/argo-workflows/commit/a64ceb03f165513e30e5c9614d1bb64273219140) build: Enable Stale Bot (#3363)
 * [e4b08abb](https://github.com/argoproj/argo-workflows/commit/e4b08abbcfe6f3886e0cd28e8ea8c1860ef8c9e1) fix(server): Remove `context cancelled` error. Fixes #3073 (#3359)
 * [74ba5162](https://github.com/argoproj/argo-workflows/commit/74ba516220423cae5960b7dd51c4a8d5a37012b5) fix: Fix UI bug in DAGs (#3368)
 * [5e60decf](https://github.com/argoproj/argo-workflows/commit/5e60decf96e85a4077cd70d1d4e8da299d1d963d) feat(crds)!: Adds CRD generation and enhanced UI resource editor. Closes #859 (#3075)
 * [c2347f35](https://github.com/argoproj/argo-workflows/commit/c2347f3542d48467e8a0bede67db17ecce890f56) chore: Simplify deps by removing YAML (#3353)
 * [1323f9f4](https://github.com/argoproj/argo-workflows/commit/1323f9f418a407d7cbb92e7bb67e00faefe17e51) test: Add e2e tags (#3354)
 * [731a1b4a](https://github.com/argoproj/argo-workflows/commit/731a1b4a670078b8ba8e2f36bdd433afe22f2631) fix(controller): Allow events to be sent to non-argo namespace. Fixes #3342 (#3345)
 * [916e0db2](https://github.com/argoproj/argo-workflows/commit/916e0db25880cef3058e4c3c3f6d118e14312be1) Adding InVision to Users (#3352)
 * [6caf10fa](https://github.com/argoproj/argo-workflows/commit/6caf10fad7b116f9e3a6aaee4eb02243e37f2779) fix: Ensure child pods respect maxDuration (#3280)
 * [8f4945f5](https://github.com/argoproj/argo-workflows/commit/8f4945f5e6f7a6d503f400079b607715151a2a41) docs: Field fix (ParallelSteps -> WorkflowStep) (#3338)
 * [2b4b7340](https://github.com/argoproj/argo-workflows/commit/2b4b7340a6afb8317e27e3d58c46fba3c3db8ff0) fix: Remove broken SSO from quick-starts (#3327)
 * [26570fd5](https://github.com/argoproj/argo-workflows/commit/26570fd51ec2eebe86cd0f3bc05ab43272f957c5) fix(controller)!: Support nested items. Fixes #3288 (#3290)
 * [c3d85716](https://github.com/argoproj/argo-workflows/commit/c3d85716420048dd0567ccc5cda894a9717598ae) chore: Avoid variable name collision with imported package name (#3335)
 * [ca822af0](https://github.com/argoproj/argo-workflows/commit/ca822af0c4353bb30a51f0a4edfccdd4226c7043) build: Fix path to go-to-protobuf binary (#3308)
 * [769a964f](https://github.com/argoproj/argo-workflows/commit/769a964fcf51f58c76f2d4900c736f4dd945bd7f) feat(controller): Label workflows with their source workflow template (#3328)
 * [0785be24](https://github.com/argoproj/argo-workflows/commit/0785be24caaf93d62f5b77b2ee142a0691992b86) fix(ui): runtime error from null savedOptions props (#3330)
 * [200be0e1](https://github.com/argoproj/argo-workflows/commit/200be0e1e34f9cf6689e9739e3e4aea7f5bf7fde) feat: Save pagination limit and selected phases/labels to local storage (#3322)
 * [b5ed90fe](https://github.com/argoproj/argo-workflows/commit/b5ed90fe8611a10df7982e3fb2e6670400acf2d2) feat: Allow to change priority when resubmitting workflows (#3293)
 * [60c86c84](https://github.com/argoproj/argo-workflows/commit/60c86c84c60ac38c5a876d8df5362b5896700d73) fix(ui): Compiler error from workflows toolbar (#3317)
 * [3fe6ecc4](https://github.com/argoproj/argo-workflows/commit/3fe6ecc424fe1474b2ce765e47f1dc69ec9ef98e) docs: Document access token creation and usage (#3316)
 * [ab3c081e](https://github.com/argoproj/argo-workflows/commit/ab3c081e310835f7f2e7a3424042944adde39afd) docs: Rename Ant Financial to Ant Group (#3304)
 * [baad42ea](https://github.com/argoproj/argo-workflows/commit/baad42ea8fed83b2158721766e518b203664ebe1) feat(ui): Add ability to select multiple workflows from list and perform actions on them. Fixes #3185 (#3234)
 * [b6118939](https://github.com/argoproj/argo-workflows/commit/b6118939bf0948e856bb20955f6911743106af4d) fix(controller): Fix panic logging. (#3315)
 * [633ea71e](https://github.com/argoproj/argo-workflows/commit/633ea71ebf624530c75b1f9aeb713a92510cf62a) build: Pin `goimports` to working version (#3311)
 * [436c1259](https://github.com/argoproj/argo-workflows/commit/436c12590d80010e300a63be3acb3bd24ac3bf93) ci: Remove CircleCI (#3302)
 * [8e340229](https://github.com/argoproj/argo-workflows/commit/8e340229cfd3fb976b1261dbf32d038bfd2f7706) build: Remove generated Swagger files. (#3297)
 * [e021d7c5](https://github.com/argoproj/argo-workflows/commit/e021d7c512f01721e2f25d39836829752226c290) Clean up unused constants (#3298)
 * [48d86f03](https://github.com/argoproj/argo-workflows/commit/48d86f03ce9ac49f5099c46dd7995305eb59eb11) build: Upload E2E diagnostics after failure (#3294)
 * [8b12f433](https://github.com/argoproj/argo-workflows/commit/8b12f433a2e32cc69714ee456ee0d83e904ff31c) feat(cli): Add --logs to `argo [submit|resubmit|retry]. Closes #3183 (#3279)
 * [07b450e8](https://github.com/argoproj/argo-workflows/commit/07b450e8134e1afe0b58c45b21dc0c13d91ecdb5) fix: Reapply Update if CronWorkflow resource changed (#3272)
 * [8af01491](https://github.com/argoproj/argo-workflows/commit/8af014911901678ee24bea9b2ab652fb0af5bc48) docs: ArchiveLabelSelector document (#3284)
 * [38c908a2](https://github.com/argoproj/argo-workflows/commit/38c908a272e8a59b2843ad5514c6334ba1c7a693) docs: Add example for handling large output resutls (#3276)
 * [d44d264c](https://github.com/argoproj/argo-workflows/commit/d44d264c72649c540204ccb54e9a57550f48d1fc) Fixes validation of overridden ref template parameters. (#3286)
 * [62e54fb6](https://github.com/argoproj/argo-workflows/commit/62e54fb68778030245bed87f0675694ef3c58b57) fix: Fix delete --complete (#3278)
 * [a3c379bb](https://github.com/argoproj/argo-workflows/commit/a3c379bb5df171d635a200b9dec7a9ca89c3295d) docs: Updated WorkflowTemplateRef  on WFT and CWFT (#3137)
 * [824de95b](https://github.com/argoproj/argo-workflows/commit/824de95bfb2de0e325f92c0544f42267242486e4) fix(git): Fixes Git when using auth or fetch. Fixes #2343 (#3248)
 * [018fcc23](https://github.com/argoproj/argo-workflows/commit/018fcc23dc9fad051d15db2f9a83c2710d50c828) Update releasing.md (#3283)
 * [acee573b](https://github.com/argoproj/argo-workflows/commit/acee573b88bf96160b69d18bcc8031caf119c647) docs: Update CI Badges (#3282)
 * [9eb182c0](https://github.com/argoproj/argo-workflows/commit/9eb182c04957f2ca587ff1de84b79fc274f91788) build: Allow to change k8s namespace for installation (#3281)
 * [2bcfafb5](https://github.com/argoproj/argo-workflows/commit/2bcfafb56230194fd2d23adcfa5a1294066ec91e) fix: Add {{workflow.status}} to workflow-metrics (#3271)
 * [e6aab605](https://github.com/argoproj/argo-workflows/commit/e6aab605122356a10cb21df3a08e1ddeac6d2593) fix(jqFilter)!: remove extra quotes around output parameter value (#3251)
 * [f4580163](https://github.com/argoproj/argo-workflows/commit/f4580163f4187f798f93b8d778415e8bec001dda) fix(ui): Allow render of templates without entrypoint. Fixes #2891 (#3274)
 * [f30c05c7](https://github.com/argoproj/argo-workflows/commit/f30c05c74f598b6400b66bb20a752d78eca05e45) build: Add warning to ensure 'v' is present on release versions (#3273)
 * [d1cb1992](https://github.com/argoproj/argo-workflows/commit/d1cb1992cd22e9f69894532f214fa0e00312ff36) fixed archiveLabelSelector nil (#3270)
 * [c7e4c180](https://github.com/argoproj/argo-workflows/commit/c7e4c1808cf097857b8ee89d326ef9f32384fc1b) fix(ui): Update workflow drawer with new duration format (#3256)
 * [f2381a54](https://github.com/argoproj/argo-workflows/commit/f2381a5448e9d49a7b6ed0c9583ac8cf9b257938) fix(controller): More structured logging. Fixes #3260 (#3262)
 * [acba084a](https://github.com/argoproj/argo-workflows/commit/acba084abb01b967c239952d49e8e3d7775cbf2c) fix: Avoid unnecessary nil check for annotations of resubmitted workflow (#3268)
 * [55e13705](https://github.com/argoproj/argo-workflows/commit/55e13705ae57f86ca6c5846eb5de3e80370bc1d4) feat: Append previous workflow name as label to resubmitted workflow (#3261)
 * [2dae7244](https://github.com/argoproj/argo-workflows/commit/2dae724496a96ce2e0993daea0a3b6a473f784da) feat: Add mode to require Workflows to use workflowTemplateRef (#3149)
 * [56694abe](https://github.com/argoproj/argo-workflows/commit/56694abe27267c1cb855064b44bc7c32d61ca66c) Fixed onexit on workflowtempalteRef (#3263)
 * [54dd72c2](https://github.com/argoproj/argo-workflows/commit/54dd72c2439b5a6ef389eab4cb39bd412db9fd42) update mysql yaml port (#3258)
 * [fb502632](https://github.com/argoproj/argo-workflows/commit/fb502632419409e528e23f1ef70e7f610812d175) feat: Configure ArchiveLabelSelector for Workflow Archive (#3249)
 * [5467c899](https://github.com/argoproj/argo-workflows/commit/5467c8995e07e5501d685384e44585fc1b02c6b8) fix(controller): set pod finish timestamp when it is deleted (#3230)
 * [04bc5492](https://github.com/argoproj/argo-workflows/commit/04bc5492d582d45633a4a18ec691a10d913a73a3) build: Disable Circle CI and Sonar (#3253)
 * [23ca07a7](https://github.com/argoproj/argo-workflows/commit/23ca07a790714ad8c97ecab71ffa439843a7ad6c) chore: Covered steps.<STEPNAME>.outputs.parameters in variables document (#3245)
 * [4bd33c6c](https://github.com/argoproj/argo-workflows/commit/4bd33c6c6ce6dcb9f0c85dab40f162608d5f67a6) chore(cli): Add examples of @latest alias for relevant commands. Fixes #3225 (#3242)
 * [17108df1](https://github.com/argoproj/argo-workflows/commit/17108df1cea937f49f099ec26b7a25bd376b16a5) fix: Ensure subscription is closed in log viewer (#3247)
 * [495dc89b](https://github.com/argoproj/argo-workflows/commit/495dc89b5cfb2419b0438c4a53cfb3b13cb5785a) docs: Correct available fields in {{workflow.failures}} (#3238)
 * [4db1c4c8](https://github.com/argoproj/argo-workflows/commit/4db1c4c8495d0b8e13c718207175273fe98555a2) fix: Support the TTLStrategy for WorkflowTemplateRef (#3239)
 * [47f50693](https://github.com/argoproj/argo-workflows/commit/47f5069376f3c61b09ff02ff5729e5c3e6e58e45) feat(logging): Made more controller err/warn logging structured (#3240)
 * [c25e2880](https://github.com/argoproj/argo-workflows/commit/c25e28809863435d718d7e5ab303591d8039c724) build: Migrate to Github Actions (#3233)
 * [ef159f9a](https://github.com/argoproj/argo-workflows/commit/ef159f9ad6be552de1abf58c3dc4dc6911c49733) feat: Tick CLI Workflow watch even if there are no new events (#3219)
 * [ff1627b7](https://github.com/argoproj/argo-workflows/commit/ff1627b71789c42f604c0f83a9a3328d7e6b8248) fix(events): Adds config flag. Reduce number of dupe events emitted. (#3205)
 * [eae8f681](https://github.com/argoproj/argo-workflows/commit/eae8f68144acaf5c2ec0145ef0d136097cca7fcc) feat: Validate CronWorkflows before execution (#3223)
 * [4470a8a2](https://github.com/argoproj/argo-workflows/commit/4470a8a29bca9e16ac7e5d7d8c8a2310d0200efa) fix(ui/server): Fix broken label filter functionality on UI due to bug on server. Fix #3226 (#3228)
 * [e5e6456b](https://github.com/argoproj/argo-workflows/commit/e5e6456be37b52856205c4f7600a05ffef6daab1) feat(cli): Add --latest flag for argo get command as per #3128 (#3179)
 * [34608594](https://github.com/argoproj/argo-workflows/commit/34608594b98257c4ae47a280831d462bab7c53b4) fix(ui): Correctly update workflow list when workflow are modified/deleted (#3220)
 * [a7d8546c](https://github.com/argoproj/argo-workflows/commit/a7d8546cf9515ea70d686b8c669bf0a1d9b7538d) feat(controller): Improve throughput of many workflows. Fixes #2908 (#2921)
 * [a37d0a72](https://github.com/argoproj/argo-workflows/commit/a37d0a729c206040463d41e88e09814c1bf622dd) build: Change "DB=..." to "PROFILE=..." (#3216)
 * [15885d3e](https://github.com/argoproj/argo-workflows/commit/15885d3edc6d4754bc66f950251450eea8f29170) feat(sso): Allow reading SSO clientID from a secret. (#3207)
 * [723e9d5f](https://github.com/argoproj/argo-workflows/commit/723e9d5f40448ae425631fac8af2863a1f1ff1f5) fix: Ensrue image name is present in containers (#3215)
 * [0ee5e112](https://github.com/argoproj/argo-workflows/commit/0ee5e11253282eb5c36a5163086c20306cc09019) feat: Only process significant pod changes (#3181)
 * [c89a81f3](https://github.com/argoproj/argo-workflows/commit/c89a81f3ad3a76e22b98570a6045fd8eb358dbdb) feat: Add '--schedule' flag to 'argo cron create' (#3199)
 * [591f649a](https://github.com/argoproj/argo-workflows/commit/591f649a306edf826b667d0069ee04cb345dcd26) refactor: Refactor assesDAGPhase logic (#3035)
 * [285eda6b](https://github.com/argoproj/argo-workflows/commit/285eda6bbe9008ffa394edbc4b510e88119a1fd0) chore: Remove unused pod in addArchiveLocation() (#3200)
 * [8e1d56cb](https://github.com/argoproj/argo-workflows/commit/8e1d56cb78f8e039f4dbeea991bdaa1935738130) feat(controller): Add default name for artifact repository ref. (#3060)
 * [f1cdba18](https://github.com/argoproj/argo-workflows/commit/f1cdba18b3ef476e11f02e50a69fc33924158be7) feat(controller): Add `--qps` and `--burst` flags to controller (#3180)
 * [b86949f0](https://github.com/argoproj/argo-workflows/commit/b86949f0e9523e10c69e0f6b10b0f35413a20520) fix: Ensure stable desc/hash for metrics (#3196)
 * [e26d2f08](https://github.com/argoproj/argo-workflows/commit/e26d2f08c2d08dd83413b91a35e38ea6ed0d3839) docs: Update Getting Started (#3099)
 * [47bfea5d](https://github.com/argoproj/argo-workflows/commit/47bfea5d4e23d506c616fa8726c6bc751104bc94) docs: Add Graviti as official Argo user (#3187)
 * [04c77f49](https://github.com/argoproj/argo-workflows/commit/04c77f490b00ffc05f74a941f1c9ccf76a5bf789) fix(server): Allow field selection for workflow-event endpoint (fixes #3163) (#3165)
 * [0c38e66e](https://github.com/argoproj/argo-workflows/commit/0c38e66e619e243a5344f0f11a5e01194c7c5cb6) chore: Update Community Meeting link and specify Go@v1.13 (#3178)
 * [81846d41](https://github.com/argoproj/argo-workflows/commit/81846d416ecc84241ae8423d91280d6a39d9b4c2) build: Only check Dex in hosts file when SSO is enabled (#3177)
 * [a130d488](https://github.com/argoproj/argo-workflows/commit/a130d488ab69cf4d4d543c7348a45e4cd34f972e) feat(ui): Add drawer with more details for each workflow in Workflow List (#3151)
 * [fa84e203](https://github.com/argoproj/argo-workflows/commit/fa84e203239b35976210a441387d6480d951f034) fix: Do not use alphabetical order if index exists (#3174)
 * [138af597](https://github.com/argoproj/argo-workflows/commit/138af5977b81e619681eb2cfa20fd3891c752510) fix(cli): Sort expanded nodes by index. Closes #3145 (#3146)
 * [a9ec4d08](https://github.com/argoproj/argo-workflows/commit/a9ec4d08bf1e3a4b4ae55055011d5c64a1197bc0) docs: Fix api swagger file path in docs (#3167)
 * [c42e4d3a](https://github.com/argoproj/argo-workflows/commit/c42e4d3aeaf4093581d0a5d92b4d7750be205225) feat(metrics): Add node-level resources duration as Argo variable for metrics. Closes #3110 (#3161)
 * [e36fe66e](https://github.com/argoproj/argo-workflows/commit/e36fe66ee795fcde237360e593c34879873f0e36) docs: Add instructions on using Minikube as an alternative to K3D (#3162)
 * [edfa5b93](https://github.com/argoproj/argo-workflows/commit/edfa5b93fb58c0b243e1f019b92f02e846f7b83d) feat(metrics): Report controller error counters via metrics. Closes #3034 (#3144)
 * [8831e4ea](https://github.com/argoproj/argo-workflows/commit/8831e4ead39acfe3d49801271a95907a3b737d49) feat(argo-server): Add support for SSO. See #1813 (#2745)
 * [b62184c2](https://github.com/argoproj/argo-workflows/commit/b62184c2e3715fd7ddd9077e11513db25a512c93) feat(cli): More `argo list` and `argo delete` options (#3117)
 * [c6565d7c](https://github.com/argoproj/argo-workflows/commit/c6565d7c3c8c4b40c6725a1f682186e04e0a8f36) fix(controller): Maybe bug with nil woc.wfSpec. Fixes #3121 (#3160)
 * [06ca71d7](https://github.com/argoproj/argo-workflows/commit/06ca71d7a8b5f9ecc448006d3fae73baf88f9d18) build: Fix path to staticfiles and goreman binaries (#3159)
 * [cad84cab](https://github.com/argoproj/argo-workflows/commit/cad84cab7817141d259785f7565f82fd3c3dc540) chore: Remove unused nodeType in initializeNodeOrMarkError() (#3153)
 * [be425513](https://github.com/argoproj/argo-workflows/commit/be42551364ec9a792171588a662489ff32347ec1) chore: Master needs lint (#3152)
 * [70b56f25](https://github.com/argoproj/argo-workflows/commit/70b56f25baf78d67253a2f29bd4057279b0e9558) enhancement(ui): Add workflow labels column to workflow list. Fixes #2782 (#3143)
 * [3318c115](https://github.com/argoproj/argo-workflows/commit/3318c1152ac0654816e36c0b4eb8679c45b6250b) chore: Move default metrics server port/path to consts (#3135)
 * [a0062adf](https://github.com/argoproj/argo-workflows/commit/a0062adfe895ee39572db3aa6f259913279c6db3) feat(ui): Add Alibaba Cloud OSS related models in UI (#3140)
 * [1469991c](https://github.com/argoproj/argo-workflows/commit/1469991ce34333697df07ca750adb247b21cc3a9) fix: Update container delete grace period to match Kubernetes default (#3064)
 * [df725bbd](https://github.com/argoproj/argo-workflows/commit/df725bbddac2f3a216010b069363f0344a2f5a80) fix(ui): Input artifacts labelled in UI. Fixes #3098 (#3131)
 * [c0d59cc2](https://github.com/argoproj/argo-workflows/commit/c0d59cc283a62f111123728f70c24df5954d98e4) feat: Persist DAG rendering options in local storage (#3126)
 * [8715050b](https://github.com/argoproj/argo-workflows/commit/8715050b441f0fb5c84ae0a0a19695c89bf2e7b9) fix(ui): Fix label error (#3130)
 * [1814ea2e](https://github.com/argoproj/argo-workflows/commit/1814ea2e4a6702eacd567aefd1194bd6aec212ed) fix(item): Support ItemValue.Type == List. Fixes #2660 (#3129)
 * [12b72546](https://github.com/argoproj/argo-workflows/commit/12b72546eb49b8af5b4374577107f30484a6e975) fix: Panic on invalid WorkflowTemplateRef (#3127)
 * [09092147](https://github.com/argoproj/argo-workflows/commit/09092147cf26939e775848d75f687d5c8fc15aa9) fix(ui): Display error message instead of DAG when DAG cannot be rendered. Fixes #3091 (#3125)
 * [2d9a74de](https://github.com/argoproj/argo-workflows/commit/2d9a74de9b2ad28318dfb6bfdbc1db6f4db716db) docs: Document cost optimizations. Fixes #1139 (#2972)
 * [69c9e5f0](https://github.com/argoproj/argo-workflows/commit/69c9e5f053195e46871176c6a31d646144532c3a) fix: Remove unnecessary panic (#3123)
 * [2f3aca89](https://github.com/argoproj/argo-workflows/commit/2f3aca8988cee483f5fac116a8e99cdec7fd89cc) add AppDirect to the list of users (#3124)
 * [257355e4](https://github.com/argoproj/argo-workflows/commit/257355e4c54b8ca37e056e73718a112441faddb4) feat: Add 'submit --from' to CronWorkflow and WorkflowTemplate in UI. Closes #3112 (#3116)
 * [6e5dd2e1](https://github.com/argoproj/argo-workflows/commit/6e5dd2e19a3094f88e6f927f786f866eccc5f500) Add Alibaba OSS to the list of supported artifacts (#3108)
 * [1967b45b](https://github.com/argoproj/argo-workflows/commit/1967b45b1465693b71e3a0ccac9563886641694c) support sso (#3079)
 * [9229165f](https://github.com/argoproj/argo-workflows/commit/9229165f83011b3d5b867ac511793f8934bdcfab) feat(ui): Add cost optimisation nudges. (#3089)
 * [e88124db](https://github.com/argoproj/argo-workflows/commit/e88124dbf64128388cf0e6fa6d30b2f756e57d23) fix(controller): Do not panic of woc.orig in not hydrated. Fixes #3118 (#3119)
 * [132b947a](https://github.com/argoproj/argo-workflows/commit/132b947ad6ba5a5b81e281c469f08cb97748e42d) fix: Differentiate between Fulfilled and Completed (#3083)
 * [a93968ff](https://github.com/argoproj/argo-workflows/commit/a93968ff36a1472402ec9655458e6ad7b04401a8) docs: Document how to backfill a cron workflow (#3094)
 * [4de99746](https://github.com/argoproj/argo-workflows/commit/4de9974681034d7bb7223d2131eba1cd0e5d254d) feat: Added Label selector and Field selector in Argo list  (#3088)
 * [6229353b](https://github.com/argoproj/argo-workflows/commit/6229353b2355c9425f42509e3504e64ee7c7ae92) chore: goimports (#3107)
 * [8491e00f](https://github.com/argoproj/argo-workflows/commit/8491e00f31f1f744ee1af729e5598a7e8894ff5f) docs: Add link to USERS.md in PR template (#3086)
 * [bb2ce9f7](https://github.com/argoproj/argo-workflows/commit/bb2ce9f77894982f5bcae4e772795d0e679bf405) fix: Graceful error handling of malformatted log lines in watch (#3071)
 * [4fd27c31](https://github.com/argoproj/argo-workflows/commit/4fd27c314810ae43b39a5c2d36cef2dbbf5691af) build(swagger): Fix Swagger build problems (#3084)
 * [e4e0dfb6](https://github.com/argoproj/argo-workflows/commit/e4e0dfb6c66fd2c0dbbba240b1cfe8c12dcb93c2) test: fix TestContinueOnFailDag (#3101)
 * [fa69c1bb](https://github.com/argoproj/argo-workflows/commit/fa69c1bb7157e19755eea669bf44434e2bedd157) feat: Add CronWorkflowConditions to report errors (#3055)
 * [50ad3cec](https://github.com/argoproj/argo-workflows/commit/50ad3cec2b002b81e30a5d6975e7dc044a83b301) adds millisecond-level timestamps to argoexec (#2950)
 * [6464bd19](https://github.com/argoproj/argo-workflows/commit/6464bd199eff845da66d59d263f2d04479663020) fix(controller): Implement offloading for workflow updates that are re-applied. Fixes #2856 (#2941)
 * [6c369e61](https://github.com/argoproj/argo-workflows/commit/6c369e614281df0342d5cc46871551282da71ea9) chore: Rename files that include 'top-level' terminology (#3076)
 * [bd40b80b](https://github.com/argoproj/argo-workflows/commit/bd40b80bc0c6b81a824da04cbb892a5e93deeebb) docs: Document work avoidance. (#3066)
 * [6df0b2d3](https://github.com/argoproj/argo-workflows/commit/6df0b2d3538cd1525223c8d85581662ece172cf9) feat: Support Top level workflow template reference  (#2912)
 * [0709ad28](https://github.com/argoproj/argo-workflows/commit/0709ad28c3dbd4696404aa942478a7505e9e9a67) feat: Enhanced filters for argo {watch,get,submit} (#2450)
 * [784c1385](https://github.com/argoproj/argo-workflows/commit/784c1385f3bec1bacdc1ef80e223a33476696ed0) build: Use goreman for starting locally. (#3074)
 * [5b5bae9a](https://github.com/argoproj/argo-workflows/commit/5b5bae9a6e46a82f5830f68f87598ee0c7dc2ff7) docs: Add Isbank to users.md (#3068)
 * [2b038ed2](https://github.com/argoproj/argo-workflows/commit/2b038ed2e61781e5c4b8a796aba4c4afe4850305) feat: Enhanced depends logic (#2673)
 * [4c3387b2](https://github.com/argoproj/argo-workflows/commit/4c3387b273d802419a1552345dfb95dd05b8555b) fix: Linters should error if nothing was validated (#3011)
 * [51dd05b5](https://github.com/argoproj/argo-workflows/commit/51dd05b5f16e0554bdd33511f8332f3198604690) fix(artifacts): Explicit archive strategy. Fixes #2140 (#3052)
 * [ada2209e](https://github.com/argoproj/argo-workflows/commit/ada2209ef94e2380c4415cf19a8e321324650405) Revert "fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)" (#3047)
 * [b7ff9f09](https://github.com/argoproj/argo-workflows/commit/b7ff9f09c46c8f313378f7f6091260be4f6363e5) chore: Add ability to configure maximum DB connection lifetime (#3032)
 * [38a995b7](https://github.com/argoproj/argo-workflows/commit/38a995b749b83a76b5f1f2542df959898489210b) fix(executor): Properly handle empty resource results, like for a missing get (#3037)
 * [a1ac8bcf](https://github.com/argoproj/argo-workflows/commit/a1ac8bcf548c4f8fcff6b7df25aa61ad9e4c15ed) fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)
 * [f12d79ca](https://github.com/argoproj/argo-workflows/commit/f12d79cad9d4a9b2169f634183b6c7837c9e4615) fix(controller)!: Correctly format workflow.creationTimepstamp as RFC3339. Fixes #2974 (#3023)
 * [d10e949a](https://github.com/argoproj/argo-workflows/commit/d10e949a061de541f5312645dfa19c5732a302ff) fix: Consider metric nodes that were created and completed in the same operation (#3033)
 * [202d4ab3](https://github.com/argoproj/argo-workflows/commit/202d4ab31a2883d4f2448c309c30404f67761727) fix(executor): Optional input artifacts. Fixes #2990 (#3019)
 * [f17e946c](https://github.com/argoproj/argo-workflows/commit/f17e946c4d006cda4e161380fb5a0ba52dcebfd1) fix(executor): Save script results before artifacts in case of error. Fixes #1472 (#3025)
 * [3d216ae6](https://github.com/argoproj/argo-workflows/commit/3d216ae6d5ad96b996ce40c42793a2031a392bb1) fix: Consider missing optional input/output artifacts with same name (#3029)
 * [3717dd63](https://github.com/argoproj/argo-workflows/commit/3717dd636949e4a78e8a6ddee4320e6a98cc3c81) fix: Improve robustness of releases. Fixes #3004 (#3009)
 * [9f86a4e9](https://github.com/argoproj/argo-workflows/commit/9f86a4e941ecca4399267f7780fbb2e7ddcd2199) feat(ui): Enable CSP, HSTS, X-Frame-Options. Fixes #2760, #1376, #2761 (#2971)
 * [cb71d585](https://github.com/argoproj/argo-workflows/commit/cb71d585c73c72513aead057d570c279ba46e74b) refactor(metrics)!: Refactor Metric interface (#2979)
 * [c0ee1eb2](https://github.com/argoproj/argo-workflows/commit/c0ee1eb2293f268f6c56f343e77ff64480562f4a) docs: Add Ravelin as a user of Argo (#3020)
 * [052e6c51](https://github.com/argoproj/argo-workflows/commit/052e6c5197a6e8b4dfb14d18c2b923ca93fcb84c) Fix isTarball to handle the small gzipped file (#3014)
 * [cdcba3c4](https://github.com/argoproj/argo-workflows/commit/cdcba3c4d6849668238180903e59f37affdff01d) fix(ui): Displays command args correctl pre-formatted. (#3018)
 * [b5160988](https://github.com/argoproj/argo-workflows/commit/b516098804443b6741e9253cc211ddbf208898ab) build: Mockery v1.1.1 (#3015)
 * [a04d8f28](https://github.com/argoproj/argo-workflows/commit/a04d8f28b3028ebb3c9dacd525c563c448b19215) docs: Add StatefulSet and Service doc (#3008)
 * [8412526c](https://github.com/argoproj/argo-workflows/commit/8412526cb2d3675b4e9df5c0d4abb369eaf16380) docs: Fix Deprecated formatting (#3010)
 * [cc0fe433](https://github.com/argoproj/argo-workflows/commit/cc0fe433aebc0397c648ff4ddc8c1f99df042568) fix(events): Correct event API Version. Fixes #2994 (#2999)
 * [d5d6f750](https://github.com/argoproj/argo-workflows/commit/d5d6f750bf9324e8277fc0f05d8214b5dee255cd) feat(controller)!: Updates the resource duration calculation. Fixes #2934 (#2937)
 * [fa3801a5](https://github.com/argoproj/argo-workflows/commit/fa3801a5d89d58208f07977b73a8686e3aa2c3c9) feat(ui): Render 2000+ nodes DAG acceptably. (#2959)
 * [f952df51](https://github.com/argoproj/argo-workflows/commit/f952df517bae1f423063d61e7542c4f0c4c667e1) fix(executor/pns): remove sleep before sigkill (#2995)
 * [2a9ee21f](https://github.com/argoproj/argo-workflows/commit/2a9ee21f47dbd36ba1d2020d0939c73fc198b333) feat(ui): Add Suspend and Resume to CronWorkflows in UI (#2982)
 * [eefe120f](https://github.com/argoproj/argo-workflows/commit/eefe120f9f1e0fe5eb4876a24b00b1eb5147cebb) test: Upgrade to argosay:v2 (#3001)
 * [47472f73](https://github.com/argoproj/argo-workflows/commit/47472f73d9cec8ac601814a41388064185d2eae7) chore: Update Mockery (#3000)
 * [46b11e1e](https://github.com/argoproj/argo-workflows/commit/46b11e1eca9d25ab3dc936e959316ec587a86f52) docs: Use keyFormat instead of keyPrefix in docs (#2997)
 * [60d5fdc7](https://github.com/argoproj/argo-workflows/commit/60d5fdc7f91b675055ab0b1c7f450fa6feb0fac5) fix: Begin counting maxDuration from first child start (#2976)
 * [76aca493](https://github.com/argoproj/argo-workflows/commit/76aca4936290823c5fd0da0be8429e6d4d92efee) build: Fix Docker build. Fixes #2983 (#2984)
 * [d8cb66e7](https://github.com/argoproj/argo-workflows/commit/d8cb66e785c170030bd503ca4626ab4e6e4f8c6c) feat: Add Argo variable {{retries}} to track retry attempt (#2911)
 * [14b7a459](https://github.com/argoproj/argo-workflows/commit/14b7a459ec4ad58a3ae77c74c293a283cafdc33b) docs: Fix typo with WorkflowTemplates link (#2977)
 * [3c442232](https://github.com/argoproj/argo-workflows/commit/3c4422326dceea456df94a71270df80e9cbf7177) fix: Remove duplicate node event. Fixes #2961 (#2964)
 * [d8ab13f2](https://github.com/argoproj/argo-workflows/commit/d8ab13f24031eae58354b9ac1c59bad69968cbe6) fix: Consider Shutdown when assesing DAG Phase for incomplete Retry node (#2966)
 * [8a511e10](https://github.com/argoproj/argo-workflows/commit/8a511e109dc55d9f9c7b69614f110290c2536858) fix: Nodes with pods deleted out-of-band should be Errored, not Failed (#2855)
 * [ca4e08f7](https://github.com/argoproj/argo-workflows/commit/ca4e08f7ed861cf4e1d0a17617d210287ed83730) build: Build dev images from cache (#2968)
 * [5f01c4a5](https://github.com/argoproj/argo-workflows/commit/5f01c4a5945a9d89d5194efbbaaf1d4d2c40532d) Upgraded to Node 14.0.0 (#2816)
 * [849d876c](https://github.com/argoproj/argo-workflows/commit/849d876c835982bbfa814714e713b4d19b35148d) Fixes error with unknown flag: --show-all (#2960)
 * [93bf6609](https://github.com/argoproj/argo-workflows/commit/93bf6609cf407d6cd374a6dd3bc137b1c82e88df) fix: Don't update backoff message to save operations (#2951)
 * [3413a5df](https://github.com/argoproj/argo-workflows/commit/3413a5dfa7c29711d9bf0d227437a10bf0de9d3b) fix(cli): Remove info logging from watches. Fixes #2955 (#2958)
 * [fe9f9019](https://github.com/argoproj/argo-workflows/commit/fe9f90191fac2fb7909c8e0b31c5f3b5a31236c4) fix: Display Workflow finish time in UI (#2896)
 * [f281199a](https://github.com/argoproj/argo-workflows/commit/f281199a1df65a6716d29a8e29ba756aa31f36dc) docs: Update README with new features (#2807)
 * [c8bd0bb8](https://github.com/argoproj/argo-workflows/commit/c8bd0bb82e174cca8d733e7b75748273172efa37) fix(ui): Change default pagination to all and sort workflows (#2943)
 * [e3ed686e](https://github.com/argoproj/argo-workflows/commit/e3ed686e13eacf0174b3e1088fe3cf2eb7706b39) fix(cli): Re-establish watch on EOF (#2944)
 * [67355372](https://github.com/argoproj/argo-workflows/commit/673553729e12d4ad83387eba68b3cbfb0aea8fe4) fix(swagger)!: Fixes invalid K8S definitions in `swagger.json`. Fixes #2888 (#2907)
 * [023f2338](https://github.com/argoproj/argo-workflows/commit/023f233896ac90fdf1529f747c56ab19028b6a9c) fix(argo-server)!: Implement missing instanceID code. Fixes #2780 (#2786)
 * [7b0739e0](https://github.com/argoproj/argo-workflows/commit/7b0739e0b846cff7d2bc3340e88859ab655d25ff) Fix typo (#2939)
 * [20d69c75](https://github.com/argoproj/argo-workflows/commit/20d69c75662653523dc6276e7e57084ec1c7334f) Detect ctrl key when a link is clicked (#2935)
 * [f32cec31](https://github.com/argoproj/argo-workflows/commit/f32cec31027b7112a9a51069c2ad7b1cfbedd960) fix default null value for timestamp column - MySQL 5.7 (#2933)
 * [9773cfeb](https://github.com/argoproj/argo-workflows/commit/9773cfebcdcba9a6ab199c7001711c500f6f69a3) docs: Add docs/scaling.md (#2918)
 * [99858ea5](https://github.com/argoproj/argo-workflows/commit/99858ea53d79e964530f4a3840936d5da79585d9) feat(controller): Remove the excessive logging of node data (#2925)
 * [03ad694c](https://github.com/argoproj/argo-workflows/commit/03ad694c42a782dc9f45f7ff0ba94b32cbbfa2f1) feat(cli): Refactor `argo list --chunk-size` and add `argo archive list --chunk-size`. Fixes #2820 (#2854)
 * [1c45d5ea](https://github.com/argoproj/argo-workflows/commit/1c45d5eafe1c44b6dc53aba80ab3ef978db04afa) test: Use argoproj/argosay:v1 (#2917)
 * [f311a5a7](https://github.com/argoproj/argo-workflows/commit/f311a5a70a8f299f05363175e27afffc6772457b) build: Fix Darwin build (#2920)
 * [a06cb5e0](https://github.com/argoproj/argo-workflows/commit/a06cb5e0e02d7b480d20713e9c67f83d09fa2b24) fix: remove doubled entry in server cluster role deployment (#2904)
 * [c71116dd](https://github.com/argoproj/argo-workflows/commit/c71116ddedafde0f2931fbd489b9b17b8bd81e65) feat: Windows Container Support. Fixes #1507 and #1383 (#2747)
 * [3afa7b2f](https://github.com/argoproj/argo-workflows/commit/3afa7b2f1b4ecb9e64b2c9dee1e91dcf548f82c3) fix(ui): Use LogsViewer for container logs (#2825)
 * [9ecd5226](https://github.com/argoproj/argo-workflows/commit/9ecd522618b390b27c784092c3dc83e84785dcbb) docs: Document node field selector. Closes #2860 (#2882)
 * [7d8818ca](https://github.com/argoproj/argo-workflows/commit/7d8818ca2a335f5cb200d9b088305d032cacd020) fix(controller): Workflow stop and resume by node didn't properly support offloaded nodes. Fixes #2543 (#2548)
 * [e013f29d](https://github.com/argoproj/argo-workflows/commit/e013f29dd224a91023b5fc4cc9fed2879994ddb1) ci: Remove context to stop unauthozied errors on test jobs (#2910)
 * [db52e7ba](https://github.com/argoproj/argo-workflows/commit/db52e7bac649a7b101f846e7f7354d10a45c9e62) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)
 * [9a33aa2d](https://github.com/argoproj/argo-workflows/commit/9a33aa2d3c0ffedf33625bd3339c2006937c0953) docs(users): Adding Habx to the users list (#2781)
 * [9e4ac9b3](https://github.com/argoproj/argo-workflows/commit/9e4ac9b3c8c7028c9759278931a76c5f26481e53) feat(cli): Tolerate deleted workflow when running `argo delete`. Fixes #2821 (#2877)
 * [a0035dd5](https://github.com/argoproj/argo-workflows/commit/a0035dd58609d744a6fa304e51d61474f25c817d) fix: ConfigMap syntax (#2889)
 * [c05c3859](https://github.com/argoproj/argo-workflows/commit/c05c3859cf911502597456f5ed374c8604af85f0) ci: Build less and therefore faster (#2839)
 * [56143eb1](https://github.com/argoproj/argo-workflows/commit/56143eb1e1e80275da2742135ef147e563cae737) feat(ui): Add pagination to workflow list. Fixes #1080 and #976 (#2863)
 * [e0ad7de9](https://github.com/argoproj/argo-workflows/commit/e0ad7de97a82b2e509bb4bc8bb5fcf5b9c26dea3) test: Fixes various tests (#2874)
 * [e378ca47](https://github.com/argoproj/argo-workflows/commit/e378ca470f1a97d624d3aceb3c53b55155fd02a9) fix: Cannot create WorkflowTemplate with un-supplied inputs (#2869)
 * [c3e30c50](https://github.com/argoproj/argo-workflows/commit/c3e30c5052b9544d363c4c73315be5136b593f9a) fix(swagger): Generate correct Swagger for inline objects. Fixes #2835 (#2837)
 * [c0143d34](https://github.com/argoproj/argo-workflows/commit/c0143d3478c6ff2ec5138f7c6b272fc8e36c6734) feat: Add metric retention policy (#2836)
 * [f03cda61](https://github.com/argoproj/argo-workflows/commit/f03cda61a73243eea225fe4d0a49f2ada0523d0d) Update getting-started.md (#2872)
 * [d66224e1](https://github.com/argoproj/argo-workflows/commit/d66224e12613c36f8fa91956509fad9fc450af74) fix: Don't error when deleting already-deleted WFs (#2866)
 * [e84acb50](https://github.com/argoproj/argo-workflows/commit/e84acb502cbbba88a700c511ffbf7feee609ccb8) chore: Display wf.Status.Conditions in CLI (#2858)
 * [3c7f3a07](https://github.com/argoproj/argo-workflows/commit/3c7f3a07d90ea6dcdf91673d4e5b4075216628f7) docs: Fix typo ".yam" -> ".yaml" (#2862)
 * [d7f8e0c4](https://github.com/argoproj/argo-workflows/commit/d7f8e0c4742b62d9271b6272a8f87c53a4fddea2) fix(CLI): Re-establish workflow watch on disconnect. Fixes #2796 (#2830)
 * [31358d6e](https://github.com/argoproj/argo-workflows/commit/31358d6e255e28f20803575f5ee0fdf2015ecb68) feat(CLI): Add -v and --verbose to Argo CLI (#2814)
 * [1d30f708](https://github.com/argoproj/argo-workflows/commit/1d30f70896b8b5f7ddc29e255c2dce0c6d01f4bd) ci: Don't configure Sonar on CI for release branches (#2811)
 * [d9c54075](https://github.com/argoproj/argo-workflows/commit/d9c54075b71baad2742829fe0874e4f07c67c67a) docs: Fix exit code example and docs (#2853)
 * [90743353](https://github.com/argoproj/argo-workflows/commit/90743353fcaf46dae04872935e95ce858e1792b3) feat: Expose workflow.serviceAccountName as global variable (#2838)
 * [f07f7bf6](https://github.com/argoproj/argo-workflows/commit/f07f7bf61147b3444255117c26bfd38261220e95) note that tar.gz'ing output artifacts is optional (#2797)
 * [3fd3fc6c](https://github.com/argoproj/argo-workflows/commit/3fd3fc6c3c789e7a3b357e16aacb02d0f880892b) docs: Document how to label creator (#2827)
 * [b956ec65](https://github.com/argoproj/argo-workflows/commit/b956ec65f372194e0f110e672a2ad50bd51a10d8) fix: Add Step node outputs to global scope (#2826)
 * [bac339af](https://github.com/argoproj/argo-workflows/commit/bac339afe10013a63bc1bb2fb83a883c07e19cb9) chore: Configure webpack dev server to proxy using HTTPS (#2812)
 * [cc136f9c](https://github.com/argoproj/argo-workflows/commit/cc136f9c3d76a5c50a9c03613233c62d118d3457) test: Skip TestStopBehavior. See #2833 (#2834)
 * [52ff43b5](https://github.com/argoproj/argo-workflows/commit/52ff43b54a76f934ae3b491c74e2350fbd2298f2) fix: Artifact panic on unknown artifact. Fixes #2824 (#2829)
 * [554fd06c](https://github.com/argoproj/argo-workflows/commit/554fd06c9daf7ce1147f949d397e489d508c58ba) fix: Enforce metric naming validation (#2819)
 * [dd223669](https://github.com/argoproj/argo-workflows/commit/dd223669a30acc58369a70288fee6ed6e006c189) docs: Add Microba as official Argo user (#2822)
 * [8151f0c4](https://github.com/argoproj/argo-workflows/commit/8151f0c49aea618a6dfcf92ec8388ccb7a5de985) docs: Update tls.md (#2813)
 * [0dbd78ff](https://github.com/argoproj/argo-workflows/commit/0dbd78ff223e592f8761f1334f952e97c9e6ac48) feat: Add TLS support. Closes #2764 (#2766)
 * [510e11b6](https://github.com/argoproj/argo-workflows/commit/510e11b639e0b797cc4253d84e96fb070691b7ab) fix: Allow empty strings in valueFrom.default (#2805)
 * [d7f41ac8](https://github.com/argoproj/argo-workflows/commit/d7f41ac8df15b8ed1e68b2e4f44d64418e4c4000) fix: Print correct version in logs. (#2806)
 * [e9c21120](https://github.com/argoproj/argo-workflows/commit/e9c2112064293b3a71e47b493666bdc9b311dfa6) chore: Add GCS native example for output artifact (#2789)
 * [e0f2697e](https://github.com/argoproj/argo-workflows/commit/e0f2697e252e7b62842af3b56f924f324f2c48ec) fix(controller): Include global params when using withParam (#2757)
 * [3441b11a](https://github.com/argoproj/argo-workflows/commit/3441b11aa5bde5fa5d0a6652fbb8fa05a4225686) docs: Fix typo in CronWorkflow doc (#2804)
 * [a2d2b848](https://github.com/argoproj/argo-workflows/commit/a2d2b848a9b6f3cf6fe5c0f0dd3b7b3084f83e37) docs: Add example of recursive for loop (#2801)
 * [29d39e29](https://github.com/argoproj/argo-workflows/commit/29d39e297c93355b68a9726aadeef4c67d4767b2) docs: Update the contributing docs  (#2791)
 * [1ea286eb](https://github.com/argoproj/argo-workflows/commit/1ea286eb237ed86bfde5a4c954927b335ab588f2) fix: ClusterWorkflowTemplate RBAC for  argo server (#2753)
 * [1f14f2a5](https://github.com/argoproj/argo-workflows/commit/1f14f2a5f6054a88f740c6799d443216f694f08f) feat(archive): Implement data retention. Closes #2273 (#2312)
 * [d0cc7764](https://github.com/argoproj/argo-workflows/commit/d0cc7764fe477465ac2c76de9cc406bbf2aac807) feat: Display argo-server version in `argo version` and in UI. (#2740)
 * [8de57281](https://github.com/argoproj/argo-workflows/commit/8de572813ee9f028cf8e06834f45a3592bc73f14) feat(controller): adds Kubernetes node name to workflow node detail in web UI and CLI output. Implements #2540 (#2732)
 * [52fa5fde](https://github.com/argoproj/argo-workflows/commit/52fa5fdee9f021b73eca30a199c65a3760462bd9) MySQL config fix (#2681)
 * [43d9eebb](https://github.com/argoproj/argo-workflows/commit/43d9eebb479242ef23e84135bbe4b9dd252dea46) fix: Rename Submittable API endpoint to `submit` (#2778)
 * [69333a87](https://github.com/argoproj/argo-workflows/commit/69333a87b0ae411972f7f25b196db989500bbe0c) Fix template scope tests (#2779)
 * [bb1abf7f](https://github.com/argoproj/argo-workflows/commit/bb1abf7f4c425494a0878d6cbc2d2cb677e88a97) chore: Add CODEOWNERS file (#2776)
 * [905e0b99](https://github.com/argoproj/argo-workflows/commit/905e0b99312e579dcd8aa8036c2ee57df6fa7a29) fix: Naming error in Makefile (#2774)
 * [7cb2fd17](https://github.com/argoproj/argo-workflows/commit/7cb2fd17765aad691eda25ca4c5acecb89f84394) fix: allow non path output params (#2680)
 * [af9f61ea](https://github.com/argoproj/argo-workflows/commit/af9f61ea7ce53f629a284a44f0106b9ed73f24e2) ci: Recurl (#2769)
 * [ef08e642](https://github.com/argoproj/argo-workflows/commit/ef08e642b5c92de0571998909b2b34ab3ac89fd4) build: Retry curl 3x (#2768)
 * [dedec906](https://github.com/argoproj/argo-workflows/commit/dedec906f0391b63b341c90e43a67047303c4728) test: Get tests running on release branches (#2767)
 * [1c8318eb](https://github.com/argoproj/argo-workflows/commit/1c8318eb92d17fa2263675cabce5134d3f1e37a2) fix: Add compatiblity mode to templateReference (#2765)
 * [7975952b](https://github.com/argoproj/argo-workflows/commit/7975952b0aa3ac84ea4559b302236598d1d47954) fix: Consider expanded tasks in getTaskFromNode (#2756)
 * [bc421380](https://github.com/argoproj/argo-workflows/commit/bc421380c9dfce1b8a25950d2bdc6a71b2e74a2d) fix: Fix template resolution in UI (#2754)
 * [391c0f78](https://github.com/argoproj/argo-workflows/commit/391c0f78a496dbe0334686dfcabde8c9af8a474f) Make phase and templateRef available for unsuspend and retry selectors (#2723)
 * [a6fa3f71](https://github.com/argoproj/argo-workflows/commit/a6fa3f71fa6bf742cb2fa90292180344f3744def) fix: Improve cookie security. Fixes #2759 (#2763)
 * [57f0183c](https://github.com/argoproj/argo-workflows/commit/57f0183cd194767af8f9bcb5fb84ab083c1661c3) Fix typo on the documentation. It causes error unmarshaling JSON: while (#2730)
 * [c6ef1ff1](https://github.com/argoproj/argo-workflows/commit/c6ef1ff19e1c3f74b4ef146be37e74bd0b748cd7) feat(manifests): add name on workflow-controller-metrics service port (#2744)
 * [af5cd1ae](https://github.com/argoproj/argo-workflows/commit/af5cd1ae0030b20f71ad345f21456100fec74639) docs: Update OWNERS (#2750)
 * [06c4bd60](https://github.com/argoproj/argo-workflows/commit/06c4bd60cf2dc85362b3370acd44e4bc3977dcbc) fix: Make ClusterWorkflowTemplate optional for namespaced Installation (#2670)
 * [25c62463](https://github.com/argoproj/argo-workflows/commit/25c624636d80605c08dd423528cb22b89cebf687) docs: Update README (#2752)
 * [908e1685](https://github.com/argoproj/argo-workflows/commit/908e1685d78d12c87fe955eec8ad0df964b3d98b) docs: Update README.md (#2751)
 * [4ea43e2d](https://github.com/argoproj/argo-workflows/commit/4ea43e2d63385211cc0a29c2aa1b237797a62f71) fix: Children of onExit nodes are also onExit nodes (#2722)
 * [3f1b6667](https://github.com/argoproj/argo-workflows/commit/3f1b6667282cf3d1b7944f7fdc075ef0f1b8ff36) feat: Add Kustomize as supported install option. Closes #2715 (#2724)
 * [691459ed](https://github.com/argoproj/argo-workflows/commit/691459ed3591f72251dc230982d7b03dc3d6f9db) fix: Error pending nodes w/o Pods unless resubmitPendingPods is set (#2721)
 * [874d8776](https://github.com/argoproj/argo-workflows/commit/874d8776c22f54ede8a07ef87b9d18c6ba8198ec) test: Longer timeout for deletion (#2737)
 * [3c8149fa](https://github.com/argoproj/argo-workflows/commit/3c8149fabfcb84bc57d1973c10fe6dbce96232a0) Fix typo (#2741)
 * [98f60e79](https://github.com/argoproj/argo-workflows/commit/98f60e7985ebd77d42ff99c6d6e1276048fb07f6) feat: Added Workflow SubmitFromResource API (#2544)
 * [6253997a](https://github.com/argoproj/argo-workflows/commit/6253997a7e25f3ad9fd3c322ea9ca9ad0b710c83) fix: Reset all conditions when resubmitting (#2702)
 * [e7c67de3](https://github.com/argoproj/argo-workflows/commit/e7c67de30df90ba7bbd649a2833dc6efed8a18de) fix: Maybe fix watch. Fixes #2678 (#2719)
 * [cef6dfb6](https://github.com/argoproj/argo-workflows/commit/cef6dfb6a25445624f864863da45c36380049e6d) fix: Print correct version string. (#2713)
 * [e9589d28](https://github.com/argoproj/argo-workflows/commit/e9589d28a5dbc7cb620f206bd1fee457a8b29dfe) feat: Increase pod workers and workflow workers both to 32 by default. (#2705)
 * [3a1990e0](https://github.com/argoproj/argo-workflows/commit/3a1990e09b353cd963b5dfbf50a702266d49b2fc) test: Fix Goroutine leak that was making controller unit tests slow. (#2701)
 * [9894c29f](https://github.com/argoproj/argo-workflows/commit/9894c29f4258fd40b604ee2c33bd877d03ff5b00) ci: Fix Sonar analysis on master. (#2709)
 * [54f5be36](https://github.com/argoproj/argo-workflows/commit/54f5be361f597d45c97469095a2e5cb5678436a8) style: Camelcase "clusterScope" (#2720)
 * [db6d1416](https://github.com/argoproj/argo-workflows/commit/db6d1416a11dbd9d963a2df6740908a1d8086ff6) fix: Flakey TestNestedClusterWorkflowTemplate testcase failure (#2613)
 * [b4fd4475](https://github.com/argoproj/argo-workflows/commit/b4fd4475c2661f12a92ba48a71b52067536044fe) feat(ui): Add a YAML panel to view the workflow manifest. (#2700)
 * [65d413e5](https://github.com/argoproj/argo-workflows/commit/65d413e5d68b2f1667ef09f3c5938a07c3442fe8) build(ui): Fix compression of UI package. (#2704)
 * [4129528d](https://github.com/argoproj/argo-workflows/commit/4129528d430be282099e94d7e98d61e40d9c78ba) fix: Don't use docker cache when building release images (#2707)
 * [8d0956c9](https://github.com/argoproj/argo-workflows/commit/8d0956c9eb8533d5a399246ffed68f6d343d47a1) test: Increase runCli timeout to 1m (#2703)
 * [9d93e971](https://github.com/argoproj/argo-workflows/commit/9d93e971a66d8f50ad92ff9e15175c6bbfe292c4) Update getting-started.md (#2697)
 * [ee644a35](https://github.com/argoproj/argo-workflows/commit/ee644a35ce4ec6a5565327fbf8cbae17a742603f) docs: Fix CONTRIBUTING.md and running-locally.md. Fixes #2682 (#2699)
 * [2737c0ab](https://github.com/argoproj/argo-workflows/commit/2737c0abf77f1555c9a9a59e564d0f1242d2656e) feat: Allow to pass optional flags to resource template (#1779)
 * [c1a2fc7c](https://github.com/argoproj/argo-workflows/commit/c1a2fc7ca8be7b9286ec01a12a185d8d4360b9f6) Update running-locally.md - fixing incorrect protoc install (#2689)
 * [a1226c46](https://github.com/argoproj/argo-workflows/commit/a1226c4616ad327400b37be19703e65a31919248) fix: Enhanced WorkflowTemplate and ClusterWorkflowTemplate validation to support Global Variables   (#2644)
 * [c21cc2f3](https://github.com/argoproj/argo-workflows/commit/c21cc2f31fead552cbab5f4664d20d56cf291619) fix a typo (#2669)
 * [9430a513](https://github.com/argoproj/argo-workflows/commit/9430a513fe7b5587048a5e74d3c9abc9e36e4304) fix: Namespace-related validation in UI (#2686)
 * [f3eeca6e](https://github.com/argoproj/argo-workflows/commit/f3eeca6e3b72f27f86678de840d1b6b7497e9473) feat: Add exit code as output variable (#2111)
 * [9f95e23a](https://github.com/argoproj/argo-workflows/commit/9f95e23a4dc9104da2218c66c66c4475285dfc3e) fix: Report metric emission errors via Conditions (#2676)
 * [c67f5ff5](https://github.com/argoproj/argo-workflows/commit/c67f5ff55b8e41b465e481d7a38d54d551c07ee4) fix: Leaf task with continueOn should not fail DAG (#2668)
 * [3c20d4c0](https://github.com/argoproj/argo-workflows/commit/3c20d4c072f1ec69954a3db8a9383bf312b495fd) ci: Migrate to use Sonar instead of CodeCov for analysis (#2666)
 * [9c6351fa](https://github.com/argoproj/argo-workflows/commit/9c6351fa643f76a7cf36eef3b80cff9bf5880463) feat: Allow step restart on workflow retry. Closes #2334 (#2431)
 * [cf277eb5](https://github.com/argoproj/argo-workflows/commit/cf277eb5114cd2db4f00d34e400a132d3344bf97) docs: Updates docs for CII. See #2641 (#2643)
 * [e2d0aa23](https://github.com/argoproj/argo-workflows/commit/e2d0aa23ab4ee9b91b018bb556959c60981586e2) fix: Consider offloaded and compressed node in retry and resume (#2645)
 * [a25c6a20](https://github.com/argoproj/argo-workflows/commit/a25c6a20d0ff7b7b7b211fcfe207200036ed5df8) build: Fix codegen for releases (#2662)
 * [4a3ca930](https://github.com/argoproj/argo-workflows/commit/4a3ca930ef1d944dfd8659d5886d8abc7f6ce42f) fix: Correctly emit events. Fixes #2626 (#2629)
 * [4a7d4bdb](https://github.com/argoproj/argo-workflows/commit/4a7d4bdba522870ab9883c4f6ccac7b244bc5bcb) test: Fix flakey DeleteCompleted test (#2659)
 * [41f91e18](https://github.com/argoproj/argo-workflows/commit/41f91e18a4f65d8a6626782ebc8920ca02b3cc86) fix: Add DAG as default in UI filter and reorder (#2661)
 * [f138ada6](https://github.com/argoproj/argo-workflows/commit/f138ada68ba0b3c46f546bfef574e212833759ac) fix: DAG should not fail if its tasks have continueOn (#2656)
 * [e5cbdf6a](https://github.com/argoproj/argo-workflows/commit/e5cbdf6a4be8f111f6353534079fa4a71384e401) ci: Only run CI jobs if needed (#2655)
 * [4c452d5f](https://github.com/argoproj/argo-workflows/commit/4c452d5f7287179b6a7967fc7d60fb0837bd36ca) fix: Don't attempt to resolve artifacts if task is going to be skipped (#2657)
 * [2caf570a](https://github.com/argoproj/argo-workflows/commit/2caf570a35565617ae9af04682883ab34e2692b6) chore: Add newline to fields.md (#2654)
 * [2cb596da](https://github.com/argoproj/argo-workflows/commit/2cb596da3dac3c5683ed44e7a363c014e73a38a5) Storage region should be specified (#2538)
 * [271e4551](https://github.com/argoproj/argo-workflows/commit/271e45512be56bb6187d7665e9b5b65eb2500ad6) chore: Fix-up Yarn deps (#2649)
 * [4c1b0777](https://github.com/argoproj/argo-workflows/commit/4c1b077725a22d183ecdb24f2f147fee0a6e320c) fix: Sort log entries. (#2647)
 * [268fc461](https://github.com/argoproj/argo-workflows/commit/268fc46197ac411339c78018f05d76e102447eef)  docs: Added doc generator code (#2632)
 * [d58b7fc3](https://github.com/argoproj/argo-workflows/commit/d58b7fc39620fb24e40bb4f55f69c4e0fb5fc017) fix: Add input paremeters to metric scope (#2646)
 * [cc3af0b8](https://github.com/argoproj/argo-workflows/commit/cc3af0b83381e2d4a8da1959c36fd0a466c414ff) fix: Validating Item Param in Steps Template (#2608)
 * [6c685c5b](https://github.com/argoproj/argo-workflows/commit/6c685c5baf281116340b7b0708f8a29764d72c47) fix: allow onExit to run if wf exceeds activeDeadlineSeconds. Fixes #2603 (#2605)
 * [ffc43ce9](https://github.com/argoproj/argo-workflows/commit/ffc43ce976973c7c20d6c58d7b27a28969ae206f) feat: Added Client validation on Workflow/WFT/CronWF/CWFT (#2612)
 * [24655cd9](https://github.com/argoproj/argo-workflows/commit/24655cd93246e2a25dc858238116f7acec45ea42) feat(UI): Move Workflow parameters to top of submit (#2640)
 * [0a3b159a](https://github.com/argoproj/argo-workflows/commit/0a3b159ab87bd313896174f8464ffd277b14264c) Use error equals (#2636)
 * [8c29e05c](https://github.com/argoproj/argo-workflows/commit/8c29e05cb5befe5f9f0263ff138eab66f75c54d0) ci: Fix codegen job (#2648)
 * [a78ecb7f](https://github.com/argoproj/argo-workflows/commit/a78ecb7fe040c0040fb12731997351a02e0808a0) docs(users): Add CoreWeave and ConciergeRender (#2641)
 * [14be4670](https://github.com/argoproj/argo-workflows/commit/14be46707f4051db71e9495472e842fbb1eb5ea0) fix: Fix logs part 2 (#2639)
 * [4da6f4f3](https://github.com/argoproj/argo-workflows/commit/4da6f4f3ee75b2e50206381dad1809d5a21c6cce) feat: Add 'outputs.result' to Container templates (#2584)
 * [51bc876d](https://github.com/argoproj/argo-workflows/commit/51bc876d576b6e61f508bb56ab9f2dfbf91b0e85) test: Fixes TestCreateWorkflowDryRun. Closes #2618 (#2628)
 * [212c6d75](https://github.com/argoproj/argo-workflows/commit/212c6d75fa7e5e8d568e80992d1924a2c51cd631) fix: Support minimal mysql version 5.7.8 (#2633)
 * [8facacee](https://github.com/argoproj/argo-workflows/commit/8facaceeb3515d804c3fd276b1802dbd6cf773e8) refactor: Refactor Template context interfaces (#2573)
 * [812813a2](https://github.com/argoproj/argo-workflows/commit/812813a288608e196006d4b8369702d020e61dc4) fix: fix test cases (#2631)
 * [ed028b25](https://github.com/argoproj/argo-workflows/commit/ed028b25f6c925a02596f90d722283856b003ff8) fix: Fix logging problems. See #2589 (#2595)
 * [d4e81238](https://github.com/argoproj/argo-workflows/commit/d4e8123816f3883d876ed715036c5d91d3fe0586) test: Fix teething problems (#2630)
 * [4aad6d55](https://github.com/argoproj/argo-workflows/commit/4aad6d55ed4e7a6c9eaa9a36b78e123655dd4ca4) chore: Add comments to issues (#2627)
 * [54f7a013](https://github.com/argoproj/argo-workflows/commit/54f7a0134ad9933608993bc09eda2032e7a16a80) test: Enhancements and repairs to e2e test framework (#2609)
 * [d95926fe](https://github.com/argoproj/argo-workflows/commit/d95926fe40e48932c25a0f70c671ad99f4149505) fix: Fix WorkflowTemplate icons to be more cohesive (#2607)
 * [0130e1fd](https://github.com/argoproj/argo-workflows/commit/0130e1fd85b7fa5b3b48b07b873858670e1a61a0) docs: Add fields and core concepts doc (#2610)
 * [5a1ac203](https://github.com/argoproj/argo-workflows/commit/5a1ac20352ab6042958f49a59d0f5227329f654c) fix: Fixes panic in toWorkflow method (#2604)
 * [51910292](https://github.com/argoproj/argo-workflows/commit/5191029247ac817dd6ce811e044459c45b2846ee) chore: Lint UI on CI, test diagnostics, skip bad test (#2587)
 * [232bb115](https://github.com/argoproj/argo-workflows/commit/232bb115eba8e2667653fdbdc9831bee112daa85) fix(error handling): use Errorf instead of New when throwing errors with formatted text (#2598)
 * [eeb2f97b](https://github.com/argoproj/argo-workflows/commit/eeb2f97be5c8787180af9f32f2d5e8baee63ed2f) fix(controller): dag continue on failed. Fixes #2596 (#2597)
 * [99c35129](https://github.com/argoproj/argo-workflows/commit/99c35129eae2d283c2e6d81b578d786b494aab11) docs: Fix inaccurate field name in docs (#2591)
 * [21c73779](https://github.com/argoproj/argo-workflows/commit/21c7377932825cd30f67a840d30853f4a48951fa) fix: Fixes lint errors (#2594)
 * [38aca5fa](https://github.com/argoproj/argo-workflows/commit/38aca5fa2a153393b3edb93be07ddce375ad13f4) chore: Added ClusterWorkflowTemplate RBAC on quick-start manifests (#2576)
 * [59f746e1](https://github.com/argoproj/argo-workflows/commit/59f746e1a551180d11e57676f8a2a384b3741599) feat: UI enhancement for Cluster Workflow Template (#2525)
 * [0801a428](https://github.com/argoproj/argo-workflows/commit/0801a4284a948bbeced83852af27a019e7b33535) fix(cli): Show lint errors of all files (#2552)
 * [c3535ba5](https://github.com/argoproj/argo-workflows/commit/c3535ba5ac85e1071a08ccbc930f2ff45cd2f295) docs: Fix wrong Configuring Your Artifact Repository document. (#2586)
 * [79217bc8](https://github.com/argoproj/argo-workflows/commit/79217bc89e892ee82bdd5018b2bba65425924d36) feat(archive): allow specifying a compression level (#2575)
 * [88d261d7](https://github.com/argoproj/argo-workflows/commit/88d261d7fa72faea19745de588c19de45e7fab88) fix: Use outputs of last child instead of retry node itslef (#2565)
 * [5c08292e](https://github.com/argoproj/argo-workflows/commit/5c08292e4ee388c1c5ca5291c601d50b2b3374e7) style: Correct the confused logic (#2577)
 * [3d146144](https://github.com/argoproj/argo-workflows/commit/3d14614459d50b96838fcfd83809ee29499e2917) fix: Fix bug in deleting pods. Fixes #2571 (#2572)
 * [cb739a68](https://github.com/argoproj/argo-workflows/commit/cb739a6897591969b959bd2feebd8ded97b9cb33) feat: Cluster scoped workflow template (#2451)
 * [c63e3d40](https://github.com/argoproj/argo-workflows/commit/c63e3d40be50479ca3c9a7325bfeb5fd9d31fa7c) feat: Show workflow duration in the index UI page (#2568)
 * [1520452a](https://github.com/argoproj/argo-workflows/commit/1520452a381319b414618d8429d6d7e0bb23790d) chore: Error -> Warn when Parent CronWf no longer exists (#2566)
 * [ffbb3b89](https://github.com/argoproj/argo-workflows/commit/ffbb3b899912f7af888d8216bd2ab55bc7106880) fix: Fixes empty/missing CM. Fixes #2285 (#2562)
 * [d0fba6f4](https://github.com/argoproj/argo-workflows/commit/d0fba6f443da013fd9ae8e48f658b337a0a18015) chore: fix typos in the workflow template docs (#2563)
 * [49801e32](https://github.com/argoproj/argo-workflows/commit/49801e32f1624ba20926f1b07a6ddafa2f162301) chore(docker): upgrade base image for executor image (#2561)
 * [c4efb8f8](https://github.com/argoproj/argo-workflows/commit/c4efb8f8b6e28a591794c018f5e61f55dd7d75e3) Add Riskified to the user list (#2558)
 * [8b92d33e](https://github.com/argoproj/argo-workflows/commit/8b92d33eb2f2de3b593459140576ea8eaff8fb4b) feat: Create K8S events on node completion. Closes #2274 (#2521)
 * [2902e144](https://github.com/argoproj/argo-workflows/commit/2902e144ddba2f8c5a93cdfc8e2437c04705065b) feat: Add node type and phase filter to UI (#2555)
 * [fb74ba1c](https://github.com/argoproj/argo-workflows/commit/fb74ba1ce27b96473411c2c5cfe9a86972af589e) fix: Separate global scope processing from local scope building (#2528)
 * [618b6dee](https://github.com/argoproj/argo-workflows/commit/618b6dee4de973b3f3ef1d1164a44b9cb176355e) fix: Fixes --kubeconfig flag. Fixes #2492 (#2553)
 * [79dc969f](https://github.com/argoproj/argo-workflows/commit/79dc969f73e0ec90bdc202e936afec970ff66fc6) test: Increase timeout for flaky test (#2543)
 * [15a3c990](https://github.com/argoproj/argo-workflows/commit/15a3c990359c40d791be64a34736e2a1ffa40178) feat: Report SpecWarnings in status.conditions (#2541)
 * [f142f30a](https://github.com/argoproj/argo-workflows/commit/f142f30a99aa9b12cdfbeed31129abb8d4266762) docs: Add example of template-level volume declaration. (#2542)
 * [93b6be61](https://github.com/argoproj/argo-workflows/commit/93b6be619523ec3d9d8c52c75d9fa540e0272c7f) fix(archive): Fix bug that prevents listing archive workflows. Fixes … (#2523)
 * [b4c9c54f](https://github.com/argoproj/argo-workflows/commit/b4c9c54f79d902f2372192f017192fa519800fd8) fix: Omit config key in configure artifact document. (#2539)
 * [864bf1e5](https://github.com/argoproj/argo-workflows/commit/864bf1e56812b0ea1434b3952073a3e15dd9f046) fix: Show template on its own field in CLI (#2535)
 * [555aaf06](https://github.com/argoproj/argo-workflows/commit/555aaf06306d066268c04e4dd50ec2fecadd22cc) test: fix master (#2534)
 * [94862b98](https://github.com/argoproj/argo-workflows/commit/94862b985ef97e39d01fcafc95109b1b3507b21e) chore: Remove deprecated example (#2533)
 * [5e1e7829](https://github.com/argoproj/argo-workflows/commit/5e1e78295df4df0205a47adcedde6f1d5915af95) fix: Validate CronWorkflow before creation (#2532)
 * [c9241339](https://github.com/argoproj/argo-workflows/commit/c92413393404bd4caeb00606b3ba8775eeadf231) fix: Fix wrong assertions (#2531)
 * [67fe04bb](https://github.com/argoproj/argo-workflows/commit/67fe04bb78ac7b402bb6ef5b58d5cca33ecd74db) Revert "fix: fix template scope tests (#2498)" (#2526)
 * [ddfa1ad0](https://github.com/argoproj/argo-workflows/commit/ddfa1ad03f2835b64efac96eb4fb10d14e3ed987) docs: couple of examples for REST API usage of argo-server (#2519)
 * [30542be7](https://github.com/argoproj/argo-workflows/commit/30542be7a121cf8774352bf987ee658b5d8b96c8) chore(docs): Update docs for useSDKCreds (#2518)
 * [e2cc6988](https://github.com/argoproj/argo-workflows/commit/e2cc6988018e50956c05ed20c665ead01766278d) feat: More control over resuming suspended nodes Fixes #1893 (#1904)
 * [b2771249](https://github.com/argoproj/argo-workflows/commit/b2771249b0be9c782ee2ae190dd76ec3bba2a562) chore: minor fix and refactory (#2517)
 * [b1ad163a](https://github.com/argoproj/argo-workflows/commit/b1ad163ac17312d103c03bf6a88069f1b055ea7d) fix: fix template scope tests (#2498)
 * [661d1b67](https://github.com/argoproj/argo-workflows/commit/661d1b6748b25488b288811dc5c0089b49b75a52) Increase client gRPC max size to match server (#2514)
 * [d8aa477f](https://github.com/argoproj/argo-workflows/commit/d8aa477f7f5089505df5fd26560f53f508f5b29f) fix: Fix potential panic (#2516)
 * [1afb692e](https://github.com/argoproj/argo-workflows/commit/1afb692eeb6a63cb0539cbc6762d8219b2b2dd00) fix: Allow runtime resolution for workflow parameter names (#2501)
 * [243ea338](https://github.com/argoproj/argo-workflows/commit/243ea338de767a39947f5fb4450321083a6f9c67) fix(controller): Ensure we copy any executor securityContext when creating wait containers; fixes #2512 (#2510)
 * [6e8c7bad](https://github.com/argoproj/argo-workflows/commit/6e8c7badcfa3f2eb7d5cb76f229e0570f3325f61) feat: Extend workflowDefaults to full Workflow and clean up docs and code (#2508)
 * [06cfc129](https://github.com/argoproj/argo-workflows/commit/06cfc1294a5a913a8b23bc4337ffa019717c4af2) feat: Native Google Cloud Storage support for artifact. Closes #1911 (#2484)
 * [999b1e1d](https://github.com/argoproj/argo-workflows/commit/999b1e1d9a6c9d69def35fd43d01b03c75748e62)  fix: Read ConfigMap before starting servers  (#2507)
 * [3d6e9b61](https://github.com/argoproj/argo-workflows/commit/3d6e9b61b3c7214ab5c62438e7d0ea750c3ae3f7) docs: Add separate ConfigMap doc for 2.7+ (#2505)
 * [e5bd6a7e](https://github.com/argoproj/argo-workflows/commit/e5bd6a7ed35a4d5ed75023719814541423affc48) fix(controller): Updates GetTaskAncestry to skip visited nod. Fixes #1907 (#1908)
 * [183a29e4](https://github.com/argoproj/argo-workflows/commit/183a29e40314ac97dfa6d7ff2e61f59ee6484279) docs: add official user (#2499)
 * [e636000b](https://github.com/argoproj/argo-workflows/commit/e636000bc457d654d487e065c1bcacd15ed75a74) feat: Updated arm64 support patch (#2491)
 * [559cb005](https://github.com/argoproj/argo-workflows/commit/559cb00596acbcc9a6a9cce001ca25fdcc561b2b) feat(ui): Report resources duration in UI. Closes #2460 (#2489)
 * [09291d9d](https://github.com/argoproj/argo-workflows/commit/09291d9d59e1fe51b1622b90ac18c6a5985b6a85) feat: Add default field in parameters.valueFrom (#2500)
 * [33cd4f2b](https://github.com/argoproj/argo-workflows/commit/33cd4f2b86e8b0993563d70c6b0d6f0f91b14535) feat(config): Make configuration mangement easier. Closes #2463 (#2464)
 * [f3df9660](https://github.com/argoproj/argo-workflows/commit/f3df9660be9f4d52975720e79bd01a6efe6fa18d) test: Fix test (#2490)
 * [bfaf1c21](https://github.com/argoproj/argo-workflows/commit/bfaf1c215f5491526edd020055ed8a15eb804a04) chore: Move quickstart Prometheus port to 9090 (#2487)
 * [487ed425](https://github.com/argoproj/argo-workflows/commit/487ed425840dc5698a4ef3a3c8f214b6c08949cc) feat: Logging the Pod Spec in controller log (#2476)
 * [96c80e3e](https://github.com/argoproj/argo-workflows/commit/96c80e3e2c6eb6867e360dde3dea97047b963c2f) fix(cli): Rearrange the order of chunk size argument in list command. Closes #2420 (#2485)
 * [47bd70a0](https://github.com/argoproj/argo-workflows/commit/47bd70a092debe980075195efd802e7bfb59c82f) chore: Fix Swagger for PDB to support Java client (#2483)
 * [53a10564](https://github.com/argoproj/argo-workflows/commit/53a10564aebc6ee17eb8e3e121b4c36b2a334b87) feat(usage): Report resource duration. Closes #1066 (#2219)
 * [063d9bc6](https://github.com/argoproj/argo-workflows/commit/063d9bc657b00e23ce7722d5d08ca69347fe7205) Revert "feat: Add support for arm64 platform (#2364)" (#2482)
 * [735d25e9](https://github.com/argoproj/argo-workflows/commit/735d25e9d719b409a7517685bcb4148278bef5a1) fix: Build image with SHA tag when a git tag is not available (#2479)
 * [c55bb3b2](https://github.com/argoproj/argo-workflows/commit/c55bb3b211be8ccc9680f8282f98f8a8bf647ca7) ci: Run lint on CI and fix GolangCI (#2470)
 * [e1c9f7af](https://github.com/argoproj/argo-workflows/commit/e1c9f7afcb4f685f615235ae1d0b6000add93635) fix ParallelSteps child type so replacements happen correctly; fixes argoproj-labs/argo-client-gen#5 (#2478)
 * [55c315db](https://github.com/argoproj/argo-workflows/commit/55c315db2e87fe28dcc26f49f4ee969bae9c7ea1) feat: Add support for IRSA and aws default provider chain. (#2468)
 * [c724c7c1](https://github.com/argoproj/argo-workflows/commit/c724c7c1afca646e09c0cb82acf8b59f8c413780) feat: Add support for arm64 platform (#2364)
 * [315dc164](https://github.com/argoproj/argo-workflows/commit/315dc164dcd24d0443b49ac95d49eb06b2c2a64f) feat: search archived wf by startat. Closes #2436 (#2473)
 * [23d230bd](https://github.com/argoproj/argo-workflows/commit/23d230bd54e04af264a0977545db365a2c0d6a6d) feat(ui): add Env to Node Container Info pane. Closes #2471 (#2472)
 * [10a0789b](https://github.com/argoproj/argo-workflows/commit/10a0789b9477b1b6c1b7adda71101925989d02de) fix: ParallelSteps swagger.json (#2459)
 * [a59428e7](https://github.com/argoproj/argo-workflows/commit/a59428e72c092e12b17c2bd8f22ee2e86eec043f) fix: Duration must be a string. Make it a string. (#2467)
 * [47bc6f3b](https://github.com/argoproj/argo-workflows/commit/47bc6f3b7450895aa35f9275b326077bb08453b5) feat: Add `argo stop` command (#2352)
 * [14478bc0](https://github.com/argoproj/argo-workflows/commit/14478bc07f42ae9ee362cc1531b1cf00d923211d) feat(ui): Add the ability to have links to logging facility in UI. Closes #2438 (#2443)
 * [2864c745](https://github.com/argoproj/argo-workflows/commit/2864c745877c9e44a5b14140f4317f8e2d45975a) chore: make codegen + make start (#2465)
 * [a85f62c5](https://github.com/argoproj/argo-workflows/commit/a85f62c5e8ee1a51f5fa8fd715ebdf4140d2483d) feat: Custom, step-level, and usage metrics (#2254)
 * [64ac0298](https://github.com/argoproj/argo-workflows/commit/64ac02980ea641d92f22328442e5a12893600d67) fix: Deprecate template.{template,templateRef,arguments} (#2447)
 * [6cb79e4e](https://github.com/argoproj/argo-workflows/commit/6cb79e4e5414277932e5cf755761cec4cda7e1b7) fix: Postgres persistence SSL Mode (#1866) (#1867)
 * [2205c0e1](https://github.com/argoproj/argo-workflows/commit/2205c0e162c93645a5ae1d883aec6ae33fec3c8f) fix(controller): Updates to add condition to workflow status. Fixes #2421 (#2453)
 * [9d96ab2f](https://github.com/argoproj/argo-workflows/commit/9d96ab2ffd6cec9fc65f0182234e103664ab9cd5) fix: make dir if needed (#2455)
 * [5346609e](https://github.com/argoproj/argo-workflows/commit/5346609e79de4fc4f6fc9d833f0f2a85790821aa) test: Maybe fix TestPendingRetryWorkflowWithRetryStrategy. Fixes #2446 (#2456)
 * [3448ccf9](https://github.com/argoproj/argo-workflows/commit/3448ccf91cbff2e3901a99e23e57a0e1ad97044c) fix: Delete PVCs unless WF Failed/Errored (#2449)
 * [782bc8e7](https://github.com/argoproj/argo-workflows/commit/782bc8e7c5d1fd102f1a16d07f209aed3bfdc689) fix: Don't error when optional artifacts are not found (#2445)
 * [fc18f3cf](https://github.com/argoproj/argo-workflows/commit/fc18f3cf27c525ff94a6b190a0aff0a9a3d45426) chore: Master needs codegen (#2448)
 * [32fc2f78](https://github.com/argoproj/argo-workflows/commit/32fc2f78212d031f99f1dfc5ad3a3642617ce7e7) feat: Support workflow templates submission. Closes #2007 (#2222)
 * [050a143d](https://github.com/argoproj/argo-workflows/commit/050a143d7639ad38dc01a685edce536917409a37) fix(archive): Fix edge-cast error for archiving. Fixes #2427 (#2434)
 * [9455c1b8](https://github.com/argoproj/argo-workflows/commit/9455c1b88d85f80091aa4fd2c8d4dc53b6cc73f8) doc: update CHANGELOG.md (#2425)
 * [1baa7ee4](https://github.com/argoproj/argo-workflows/commit/1baa7ee4ec7149afe789d73ed6e64abfe13387a7) feat(ui): cache namespace selection. Closes #2439 (#2441)
 * [91d29881](https://github.com/argoproj/argo-workflows/commit/91d29881f41642273fe0494bef70f2b9c41350e2) feat: Retry pending nodes (#2385)
 * [7094433e](https://github.com/argoproj/argo-workflows/commit/7094433e12b668236a87c034445daf88d659231f) test: Skip flakey tests in operator_template_scope_test.go. See #2432 (#2433)
 * [30332b14](https://github.com/argoproj/argo-workflows/commit/30332b14fb1043e22a66db594f1af252c5932853) fix: Allow numbers in steps.args.params.value (#2414)
 * [e9a06dde](https://github.com/argoproj/argo-workflows/commit/e9a06dde297e9f907d10ec88da93fbb90df5ebaf) feat: instanceID support for argo server. Closes #2004 (#2365)
 * [3f8be0cd](https://github.com/argoproj/argo-workflows/commit/3f8be0cd48963958c493e7669a1d03bb719b375a) fix "Unable to retry workflow" on argo-server (#2409)
 * [dd3029ab](https://github.com/argoproj/argo-workflows/commit/dd3029abdd13a6b4053934660ca1078e23780809) docs: Example showing how to use default settings for workflow spec. Related to ##2388 (#2411)
 * [13508828](https://github.com/argoproj/argo-workflows/commit/135088284acd1ced004374d20928c017fbf9cac7) fix: Check child node status before backoff in retry (#2407)
 * [b59419c9](https://github.com/argoproj/argo-workflows/commit/b59419c9f58422f60c7d5185c89b4d55ac278660) fix: Build with the correct version if you check out a specific version (#2423)
 * [6d834d54](https://github.com/argoproj/argo-workflows/commit/6d834d545bc816cde9b74b224116d9746db5b799) chore: document BASE_HREF (#2418)
 * [184c3653](https://github.com/argoproj/argo-workflows/commit/184c3653085bc8821bdcd65f5476fbe24f24b00e) fix: Remove lazy workflow template (#2417)
 * [918d0d17](https://github.com/argoproj/argo-workflows/commit/918d0d17c0455b6a0644c6d851dbea3f945db21c) docs: Added Survey Results (#2416)
 * [20d6e27b](https://github.com/argoproj/argo-workflows/commit/20d6e27bdf11389f23b2efe1be4ef737f333221d) Update CONTRIBUTING.md (#2410)
 * [f2ca045e](https://github.com/argoproj/argo-workflows/commit/f2ca045e1cad03d5ec7566ff7200fd8ca575ec5d) feat: Allow WF metadata spec on Cron WF (#2400)
 * [068a4336](https://github.com/argoproj/argo-workflows/commit/068a43362b2088f53d408623bc7ab078e0e7a9d0) fix: Correctly report version. Fixes #2374 (#2402)
 * [e19a398c](https://github.com/argoproj/argo-workflows/commit/e19a398c810fada879facd624a7663501306e1ef) Update pull_request_template.md (#2401)
 * [7c99c109](https://github.com/argoproj/argo-workflows/commit/7c99c109e3dd726f6453c94a594d69bca709ccf6) chore: Fix typo (#2405)
 * [175b164c](https://github.com/argoproj/argo-workflows/commit/175b164c33aee7fe2873df60915a881502ec9163) Change font family for class yaml (#2394)
 * [d1194755](https://github.com/argoproj/argo-workflows/commit/d11947558bc758e5102238162036650890731ec6) fix: Don't display Retry Nodes in UI if len(children) == 1 (#2390)
 * [b8623ec7](https://github.com/argoproj/argo-workflows/commit/b8623ec7b4a19713f5965cc0d628f26b81af39a2) docs: Create USERS.md (#2389)
 * [1d21d3f5](https://github.com/argoproj/argo-workflows/commit/1d21d3f5600feca4b63e3dc4b1d94d2830fa6e24) fix(doc strings): Fix bug related documentation/clean up of default configurations #2331 (#2388)
 * [77e11fc4](https://github.com/argoproj/argo-workflows/commit/77e11fc4838ff92de9d9cae91159fb88755dff0b) chore: add noindex meta tag to solve #2381; add kustomize to build docs (#2383)
 * [42200fad](https://github.com/argoproj/argo-workflows/commit/42200fad45b4925b8f4aac48a580e6e369de2ad4) fix(controller): Mount volumes defined in script templates. Closes #1722 (#2377)
 * [96af36d8](https://github.com/argoproj/argo-workflows/commit/96af36d85d70d4721b1ac3e6e0ef14db65e7aec3) fix: duration must be a string (#2380)
 * [7bf08192](https://github.com/argoproj/argo-workflows/commit/7bf0819267543808d80acaa5f39f40c1fdba511e) fix: Say no logs were outputted when pod is done (#2373)
 * [847c3507](https://github.com/argoproj/argo-workflows/commit/847c3507dafdd3ff2cd1acca4669c1a54a680ee2) fix(ui): Removed tailLines from EventSource (#2330)
 * [3890a124](https://github.com/argoproj/argo-workflows/commit/3890a12431bfacc83cc75d862f956ddfbc1d2a37) feat: Allow for setting default configurations for workflows, Fixes #1923, #2044 (#2331)
 * [81ab5385](https://github.com/argoproj/argo-workflows/commit/81ab538594ad0428a97e99f34b18041f31a1c753) Update readme (#2379)
 * [91810273](https://github.com/argoproj/argo-workflows/commit/91810273318ab3ea84ecf73b9d0a6f1ba7f43c2a) feat: Log version (structured) on component start-up (#2375)
 * [d0572a74](https://github.com/argoproj/argo-workflows/commit/d0572a74069a1a6c38fa860e1964fa0564fd28cd) docs: Make Getting Started agnostic to version (#2371)
 * [d3a3f6b1](https://github.com/argoproj/argo-workflows/commit/d3a3f6b195b984a97eb214e99f29498c0bd39c85) docs: Add Prudential to the users list (#2353)
 * [4714c880](https://github.com/argoproj/argo-workflows/commit/4714c88099f25a3ffe2db14574016b069f85335d) chore: Master needs codegen (#2369)
 * [5b6b8257](https://github.com/argoproj/argo-workflows/commit/5b6b8257890d3c7aa93d8e98b10090add08a22e1) fix(docker): fix streaming of combined stdout/stderr (#2368)
 * [97438313](https://github.com/argoproj/argo-workflows/commit/9743831306714cc85b762487ac070f77e25f85d6) fix: Restart server ConfigMap watch when closed (#2360)
 * [64d0cec0](https://github.com/argoproj/argo-workflows/commit/64d0cec080bb27e147632fb8993f75e16c92e4a7) chore: Master needs make lint (#2361)
 * [12386fc6](https://github.com/argoproj/argo-workflows/commit/12386fc6029f5533921c75797455efc62e4cc9ce) fix: rerun codegen after merging OSS artifact support (#2357)
 * [40586ed5](https://github.com/argoproj/argo-workflows/commit/40586ed5c3a539d2e13f8a34509a40367563874a) fix: Always validate templates (#2342)
 * [897db894](https://github.com/argoproj/argo-workflows/commit/897db89434079fa3b3b902253d1c624c39af1422) feat: Add support for Alibaba Cloud OSS artifact (#1919)
 * [7e2dba03](https://github.com/argoproj/argo-workflows/commit/7e2dba03674219ec35e88b2ce785fdf120f855fd) feat(ui): Circles for nodes (#2349)
 * [e85f6169](https://github.com/argoproj/argo-workflows/commit/e85f6169fadf503c220ecc2385334fc0f2073ca4) chore: update getting started guide to use 2.6.0 (#2350)
 * [7ae4ec78](https://github.com/argoproj/argo-workflows/commit/7ae4ec78f627b620197a323b190fa33c31ffcbcc) docker: remove NopCloser from the executor. (#2345)
 * [5895b364](https://github.com/argoproj/argo-workflows/commit/5895b3642a691629b6c8aa145cf17627a227665f) feat: Expose workflow.paramteres with JSON string of all params (#2341)
 * [a9850b43](https://github.com/argoproj/argo-workflows/commit/a9850b43b16e05d9f74f52c789a8475d493f4c92) Fix the default (#2346)
 * [c3763d34](https://github.com/argoproj/argo-workflows/commit/c3763d34ed02bc63d166e8ef4f2f724786a2cf7c) fix: Simplify completion detection logic in DAGs (#2344)
 * [d8a9ea09](https://github.com/argoproj/argo-workflows/commit/d8a9ea09be395241664d929e8dbca7d02aecb049) fix(auth): Fixed returning  expired  Auth token for GKE (#2327)
 * [6fef0454](https://github.com/argoproj/argo-workflows/commit/6fef0454073fb60b4dd6216accef07f5195ec7e9) fix: Add timezone support to startingDeadlineSeconds (#2335)
 * [c28731b9](https://github.com/argoproj/argo-workflows/commit/c28731b9f602b3ed79c76dd4e3383f39419e463f) chore: Add go mod tidy to codegen (#2332)
 * [a66c8802](https://github.com/argoproj/argo-workflows/commit/a66c8802c7d0dbec9b13d408b91655e41531a97a) feat: Allow Worfklows to be submitted as files from UI (#2340)
 * [a9c1d547](https://github.com/argoproj/argo-workflows/commit/a9c1d547e5b044d9d375ebf527c132b0545455b0) docs: Update Argo Rollouts description (#2336)
 * [8672b97f](https://github.com/argoproj/argo-workflows/commit/8672b97f134dacb553592c367399229891aaf5c8) fix(Dockerfile): Using `--no-install-recommends` (Optimization) (#2329)
 * [c3fe1ae1](https://github.com/argoproj/argo-workflows/commit/c3fe1ae1b3ad662bc94a4b46e72f20c957dd4475) fix(ui): fixed worflow UI refresh. Fixes ##2337 (#2338)
 * [d7690e32](https://github.com/argoproj/argo-workflows/commit/d7690e32faf2ac5842468831daf1443283703c25) feat(ui): Adds ability zoom and hide successful steps. POC (#2319)
 * [e9e13d4c](https://github.com/argoproj/argo-workflows/commit/e9e13d4cbbc0f456c2d1dafbb1a95739127f6ab4) feat: Allow retry strategy on non-leaf nodes, eg for step groups. Fixes #1891 (#1892)
 * [62e6db82](https://github.com/argoproj/argo-workflows/commit/62e6db826ea4e0a02ac839bc59ec5f70ce3b9b29) feat: Ability to include or exclude fields in the response (#2326)
 * [52ba89ad](https://github.com/argoproj/argo-workflows/commit/52ba89ad4911fd4c7b13fd6dbc7f019971354ea0) fix(swagger): Fix the broken swagger. (#2317)
 * [efb8a1ac](https://github.com/argoproj/argo-workflows/commit/efb8a1ac8fc9961f0caa00ec6df7cf006d25e87a) docs: Update CODE_OF_CONDUCT.md (#2323)
 * [1c77e864](https://github.com/argoproj/argo-workflows/commit/1c77e864ac004f9cc6aff0e204ea9fd4b056c84b) fix(swagger): Fix the broken swagger. (#2317)
 * [aa052346](https://github.com/argoproj/argo-workflows/commit/aa05234694bc79e649e02adcc9790778cef0154d) feat: Support workflow level poddisruptionbudge for workflow pods #1728 (#2286)
 * [8da88d7e](https://github.com/argoproj/argo-workflows/commit/8da88d7ed20d8e533252e610337c15737445a225) chore: update getting-started guide for 2.5.2 and apply other tweaks (#2311)
 * [2f97c261](https://github.com/argoproj/argo-workflows/commit/2f97c261a9eafa022b464e0aea5b5d34d6f99100) build: Improve reliability of release. (#2309)
 * [5dcb84bb](https://github.com/argoproj/argo-workflows/commit/5dcb84bb549429ba5f46a21873e873a2c1c5bf67) chore(cli): Clean-up code. Closes #2117 (#2303)
 * [e49dd8c4](https://github.com/argoproj/argo-workflows/commit/e49dd8c4f9f69551be7e31c2044fef043d2992b2) chore(cli): Migrate `argo logs` to use API client. See #2116 (#2177)
 * [5c3d9cf9](https://github.com/argoproj/argo-workflows/commit/5c3d9cf93079ecbbfb024ea273d6e57e56c2506d) chore(cli): Migrate `argo wait` to use API client. See #2116 (#2282)
 * [baf03f67](https://github.com/argoproj/argo-workflows/commit/baf03f672728a6ed8b2aeb986d84ce35e9d7717a) fix(ui): Provide a link to archived logs. Fixes #2300 (#2301)
 * [b5947165](https://github.com/argoproj/argo-workflows/commit/b5947165564246a3c55375500f3fc1aea4dc6966) feat: Create API clients (#2218)
 * [214c4515](https://github.com/argoproj/argo-workflows/commit/214c451535ebeb6e68f1599c2c0a4a4d174ade25) fix(controller): Get correct Step or DAG name. Fixes #2244 (#2304)
 * [c4d26466](https://github.com/argoproj/argo-workflows/commit/c4d2646612d190ec73f38ec840259110a9ce89e0) fix: Remove active wf from Cron when deleted (#2299)
 * [0eff938d](https://github.com/argoproj/argo-workflows/commit/0eff938d62764abffcfdc741dfaca5fd6c8ae53f) fix: Skip empty withParam steps (#2284)
 * [636ea443](https://github.com/argoproj/argo-workflows/commit/636ea443c38869beaccfff19f4b72dd23755b2ff) chore(cli): Migrate `argo terminate` to use API client. See #2116 (#2280)
 * [d0a9b528](https://github.com/argoproj/argo-workflows/commit/d0a9b528e383a1b9ea737e0f919c93969d3d393b) chore(cli): Migrate `argo template` to use API client. Closes #2115 (#2296)
 * [f69a6c5f](https://github.com/argoproj/argo-workflows/commit/f69a6c5fa487d3b6c2d5383aa588695d6dcdb6de) chore(cli): Migrate `argo cron` to use API client. Closes #2114 (#2295)
 * [80b9b590](https://github.com/argoproj/argo-workflows/commit/80b9b590ebca1dbe69c5c7df0dd1c2f1feae5eea) chore(cli): Migrate `argo retry` to use API client. See #2116 (#2277)
 * [cdbc6194](https://github.com/argoproj/argo-workflows/commit/cdbc61945e09ae4dab8a56a085d050a0c358b896) fix(sequence): broken in 2.5. Fixes #2248 (#2263)
 * [0d3955a7](https://github.com/argoproj/argo-workflows/commit/0d3955a7f617c58f74c2892894036dfbdebaa5aa) refactor(cli): 2x simplify migration to API client. See #2116 (#2290)
 * [df8493a1](https://github.com/argoproj/argo-workflows/commit/df8493a1c05d3bac19a8f95f608d5543ba96ac82) fix: Start Argo server with out Configmap #2285 (#2293)
 * [51cdf95b](https://github.com/argoproj/argo-workflows/commit/51cdf95b18c8532f0bdb72c7ca20d56bdafc3a60) doc: More detail for namespaced installation (#2292)
 * [a7302697](https://github.com/argoproj/argo-workflows/commit/a730269767bdd10c4a9c5901c7e73f6bb25429c2) build(swagger): Fix argo-server swagger so version does not change. (#2291)
 * [47b4fc28](https://github.com/argoproj/argo-workflows/commit/47b4fc284df3cff9dfb4ea6622a0236bf1613096) fix(cli): Reinstate `argo wait`. Fixes #2281 (#2283)
 * [1793887b](https://github.com/argoproj/argo-workflows/commit/1793887b95446d341102b81523931403e30ef0f7) chore(cli): Migrate `argo suspend` and `argo resume` to use API client. See #2116 (#2275)
 * [1f3d2f5a](https://github.com/argoproj/argo-workflows/commit/1f3d2f5a0c9d772d7b204b13529f56bc33703a45) chore(cli): Update `argo resubmit` to support client API. See #2116 (#2276)
 * [c33f6cda](https://github.com/argoproj/argo-workflows/commit/c33f6cda39a3be40cc2e829c4c8d0b4c54704896) fix(archive): Fix bug in migrating cluster name. Fixes #2272 (#2279)
 * [fb0acbbf](https://github.com/argoproj/argo-workflows/commit/fb0acbbffb0a7c754223e516f55a40b957277fe4) fix: Fixes double logging in UI. Fixes #2270 (#2271)
 * [acf37c2d](https://github.com/argoproj/argo-workflows/commit/acf37c2db0d69def2045a6fc0f37a2b9db0c41fe) fix: Correctly report version. Fixes #2264 (#2268)
 * [b30f1af6](https://github.com/argoproj/argo-workflows/commit/b30f1af6528046a3af29c82ac1e29d9d300eec22) fix: Removes Template.Arguments as this is never used. Fixes #2046 (#2267)
 * [79b09ed4](https://github.com/argoproj/argo-workflows/commit/79b09ed43550bbf958c631386f8514b2d474062c) fix: Removed duplicate Watch Command (#2262)
 * [b5c47266](https://github.com/argoproj/argo-workflows/commit/b5c47266c4e33ba8739277ea43fe4b8023542367) feat(ui): Add filters for archived workflows (#2257)
 * [d30aa335](https://github.com/argoproj/argo-workflows/commit/d30aa3357738a272e1864d9f352f3c160c1608fc) fix(archive): Return correct next page info. Fixes #2255 (#2256)
 * [8c97689e](https://github.com/argoproj/argo-workflows/commit/8c97689e5d9d956a0dd9493c4c53088a6e8a87fa) fix: Ignore bookmark events for restart. Fixes #2249 (#2253)
 * [63858eaa](https://github.com/argoproj/argo-workflows/commit/63858eaa919c430bf0683dc33d81c94d4237b45b) fix(offloading): Change offloaded nodes datatype to JSON to support 1GB. Fixes #2246 (#2250)
 * [4d88374b](https://github.com/argoproj/argo-workflows/commit/4d88374b70e272eb454395f066c371ad2977abef) Add Cartrack into officially using Argo (#2251)
 * [d309d5c1](https://github.com/argoproj/argo-workflows/commit/d309d5c1a134502a11040757ff85230f7199510f) feat(archive): Add support to filter list by labels. Closes #2171 (#2205)
 * [79f13373](https://github.com/argoproj/argo-workflows/commit/79f13373fd8c4d0e9c9ff56f2133fa6009d1ed07) feat: Add a new symbol for suspended nodes. Closes #1896 (#2240)
 * [82b48821](https://github.com/argoproj/argo-workflows/commit/82b48821a83e012ac7ea5740d45addb046e3c8ee) Fix presumed typo (#2243)
 * [af94352f](https://github.com/argoproj/argo-workflows/commit/af94352f6c93e4bdbb69a1fc92b5d596c647d1a0) feat: Reduce API calls when changing filters. Closes #2231 (#2232)
 * [a58cbc7d](https://github.com/argoproj/argo-workflows/commit/a58cbc7dd12fe919614768ca0fa4714853091b7f) BasisAI uses Argo (#2241)
 * [68e3c9fd](https://github.com/argoproj/argo-workflows/commit/68e3c9fd9f597b6b4599dc7e9dbc5d71252ac5cf) feat: Add Pod Name to UI (#2227)
 * [eef85072](https://github.com/argoproj/argo-workflows/commit/eef85072691a9302e4168a072cfdffed6908a5d6) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)
 * [4e4565cd](https://github.com/argoproj/argo-workflows/commit/4e4565cdbb5d2e5c215af1b8b2f03695b45c2bba) feat: Label workflow-created pvc with workflow name (#1890)
 * [8bd5ecbc](https://github.com/argoproj/argo-workflows/commit/8bd5ecbc16f1063ef332ca3445ed9a9b953efa4f) fix: display error message when deleting archived workflow fails. (#2235)
 * [ae381ae5](https://github.com/argoproj/argo-workflows/commit/ae381ae57e5d2d3226114c773264595b3d672c39) feat: This add support to enable debug logging for all CLI commands (#2212)
 * [1b1927fc](https://github.com/argoproj/argo-workflows/commit/1b1927fc6fa519b7bf277e4273f4c7cede16ed64) feat(swagger): Adds a make api/argo-server/swagger.json (#2216)
 * [5d7b4c8c](https://github.com/argoproj/argo-workflows/commit/5d7b4c8c2d5819116b060f1ee656571b77b873bd) Update README.md (#2226)
 * [170abfa5](https://github.com/argoproj/argo-workflows/commit/170abfa5875227a74381764de93aa345aa5cca19) chore: Run `go mod tidy` (#2225)
 * [2981e6ff](https://github.com/argoproj/argo-workflows/commit/2981e6ff4c053b898a425d366fa696c8530ffeb0) fix: Enforce UnknownField requirement in WorkflowStep (#2210)
 * [affc235c](https://github.com/argoproj/argo-workflows/commit/affc235cd07bb01ee0ef8bb226b7a4c6470dc1e7) feat: Add failed node info to exit handler (#2166)
 * [af1f6d60](https://github.com/argoproj/argo-workflows/commit/af1f6d60078c5562b2c9d538d2b104c277c82593) fix: UI Responsive design on filter box (#2221)
 * [a445049c](https://github.com/argoproj/argo-workflows/commit/a445049ca3f67b499b9bef95c9e43075c8e10250) fix: Fixed race condition in kill container method. Fixes #1884 (#2208)
 * [2672857f](https://github.com/argoproj/argo-workflows/commit/2672857f2fbaabf727e354b040b1af2431ea70e5) feat: upgrade to Go 1.13. Closes #1375 (#2097)
 * [7466efa9](https://github.com/argoproj/argo-workflows/commit/7466efa99adfeeb3833b02c5afa7a33cdf8f87bc) feat: ArtifactRepositoryRef ConfigMap is now taken from the workflow namespace (#1821)
 * [50f331d0](https://github.com/argoproj/argo-workflows/commit/50f331d0e686f603440500c026ffe9d1f5133c1c) build: Fix ARGO_TOKEN (#2215)
 * [7f090351](https://github.com/argoproj/argo-workflows/commit/7f09035156e5dce68af203df21e688476d05ce12) test: Correctly report diagnostics (#2214)
 * [f2bd74bc](https://github.com/argoproj/argo-workflows/commit/f2bd74bca116f1b1ad9990aef9dbad98e0068900) fix: Remove quotes from UI (#2213)
 * [62f46680](https://github.com/argoproj/argo-workflows/commit/62f4668064e71046532505a11c67a675aa29afcf) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [e30b77fc](https://github.com/argoproj/argo-workflows/commit/e30b77fcd5b140074065491988985779b800c4d7) feat(ui): Add label filter to workflow list page. Fixes #802 (#2196)
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)
 * [c4f49cf0](https://github.com/argoproj/argo-workflows/commit/c4f49cf074ad874996145674d635165f6256ca15) refactor: Move server code (cmd/server/ -> server/) (#2071)
 * [2542454c](https://github.com/argoproj/argo-workflows/commit/2542454c1daf61bc3826fa370c21799059904093) fix(controller): Do not crash if cm is empty. Fixes #2069 (#2070)
 * [85fa9aaf](https://github.com/argoproj/argo-workflows/commit/85fa9aafa70a98ce999157bb900971f24bd81101) fix: Do not expect workflowChange to always be defined (#2068)
 * [6f65bc2b](https://github.com/argoproj/argo-workflows/commit/6f65bc2b77ddcf4616c78d6db4955bf839a0c21a) fix: "base64 -d" not always available, using "base64 --decode" (#2067)
 * [6f2c8802](https://github.com/argoproj/argo-workflows/commit/6f2c880280d490ba746a86d828ade61d8b58c7a5) feat(ui): Use cookies in the UI. Closes #1949 (#2058)
 * [4592aec6](https://github.com/argoproj/argo-workflows/commit/4592aec6805ce1110edcb7dc4e3e7454a2042441) fix(api): Change `CronWorkflowName` to `Name`. Fixes #1982 (#2033)
 * [e26c11af](https://github.com/argoproj/argo-workflows/commit/e26c11af747651c6642cf0abd3cbc4ccac7b95de) fix: only run archived wf testing when persistence is enabled (#2059)
 * [b3cab5df](https://github.com/argoproj/argo-workflows/commit/b3cab5dfbb5e5973b1dc448946d16ee0cd690d6a) fix: Fix permission test cases (#2035)
 * [b408e7cd](https://github.com/argoproj/argo-workflows/commit/b408e7cd28b95a08498f6e30fcbef385d0ff89f5) fix: nil pointer in GC (#2055)
 * [4ac11560](https://github.com/argoproj/argo-workflows/commit/4ac115606bf6f0b3c5c837020efd41bf90789a00) fix: offload Node Status in Get and List api call (#2051)
 * [dfdde1d0](https://github.com/argoproj/argo-workflows/commit/dfdde1d08b2a39d074729f1d64053a6e37453b32) ci: Run using our own cowsay image (#2047)
 * [71ba8238](https://github.com/argoproj/argo-workflows/commit/71ba823822c190bfdb71073604bb987bb938cff4) Update README.md (#2045)
 * [c7953052](https://github.com/argoproj/argo-workflows/commit/c795305268d5793e6672252ae6ff7fb6a54f23fd) fix(persistence): Allow `argo server` to run without persistence (#2050)
 * [1db74e1a](https://github.com/argoproj/argo-workflows/commit/1db74e1a2658fa7de925cd4c81fbfd98f648cd99) fix(archive): upsert archive + ci: Pin images on CI, add readiness probes, clean-up logging and other tweaks (#2038)
 * [c46c6836](https://github.com/argoproj/argo-workflows/commit/c46c6836706dce54aea4a13deee864bd3c6cb906) feat: Allow workflow-level parameters to be modified in the UI when submitting a workflow (#2030)
 * [faa9dbb5](https://github.com/argoproj/argo-workflows/commit/faa9dbb59753a068c64a1aa5923e3e359c0866d8) fix(Makefile): Rename staticfiles make target. Fixes #2010 (#2040)
 * [79a42d48](https://github.com/argoproj/argo-workflows/commit/79a42d48cec9c41269fbe736a61f3975fe2a9aea) docs: Update link to configure-artifact-repository.md (#2041)
 * [1a96007f](https://github.com/argoproj/argo-workflows/commit/1a96007fed6a57d14a0e364000b54a364293438b) fix: Redirect to correct page when using managed namespace. Fixes #2015 (#2029)
 * [78726314](https://github.com/argoproj/argo-workflows/commit/787263142162b62085572660f5e6497279f82ab1) fix(api): Updates proto message naming (#2034)
 * [4a1307c8](https://github.com/argoproj/argo-workflows/commit/4a1307c89e58f554af8e0cdc44e5e66e4623dfb4) feat: Adds support for MySQL. Fixes #1945 (#2013)
 * [d843e608](https://github.com/argoproj/argo-workflows/commit/d843e6085d51f409d32aefe6b6cf18bf6fd6bbd1) chore: Smoke tests are timing out, give them more time (#2032)
 * [5c98a14e](https://github.com/argoproj/argo-workflows/commit/5c98a14ecdc78a5be48f34c455d90782157c4cbe) feat(controller): Add audit logs to workflows. Fixes #1769 (#1930)
 * [2982c1a8](https://github.com/argoproj/argo-workflows/commit/2982c1a82cd6f1e7fb755a948d7a165aa0aeebc0) fix(validate): Allow placeholder in values taken from inputs. Fixes #1984 (#2028)
 * [3293c83f](https://github.com/argoproj/argo-workflows/commit/3293c83f6170ad4dc022067bb37f12d07d2834c1) feat: Add version to offload nodes. Fixes #1944 and #1946 (#1974)
 * [283bbf8d](https://github.com/argoproj/argo-workflows/commit/283bbf8df50d615dee867becc21569be760fc59e) build: `make clean` now only deletes dist directories (#2019)
 * [72fa88c9](https://github.com/argoproj/argo-workflows/commit/72fa88c9daf9ae42a8a1feb297a0b118505b32b0) build: Enable linting for tests. Closes #1971 (#2025)
 * [f8569ae9](https://github.com/argoproj/argo-workflows/commit/f8569ae913053c8ba4cd9ca72c9c237dd83200c0) feat: Auth refactoring to support single version token (#1998)
 * [eb360d60](https://github.com/argoproj/argo-workflows/commit/eb360d60ea81e8deefbaf41bcb76921acd08b16f) Fix README (#2023)
 * [ef1bd3a3](https://github.com/argoproj/argo-workflows/commit/ef1bd3a32c434c565defc7b325463e8d831262f2) fix typo (#2021)
 * [f25a45de](https://github.com/argoproj/argo-workflows/commit/f25a45deb4a7179044034da890884432e750d98a) feat(controller): Exposes container runtime executor as CLI option. (#2014)
 * [3b26af7d](https://github.com/argoproj/argo-workflows/commit/3b26af7dd4cc3d08ee50f3bc2f389efd516b9248) Enable s3 trace support. Bump version to v2.5.0. Tweak proto id to match Workflow (#2009)
 * [5eb15bb5](https://github.com/argoproj/argo-workflows/commit/5eb15bb5409f54f1a4759dde2479b7569e5f81e4) fix: Fix workflow level timeouts (#1369)
 * [5868982b](https://github.com/argoproj/argo-workflows/commit/5868982bcddf3b9c9ddb98151bf458f6868dce81) fix: Fixes the `test` job on master (#2008)
 * [29c85072](https://github.com/argoproj/argo-workflows/commit/29c850728fa701d62078910e1641588c959c28c5) fix: Fixed grammar on TTLStrategy (#2006)
 * [2f58d202](https://github.com/argoproj/argo-workflows/commit/2f58d202c21910500ecc4abdb9e23270c9791d0a) fix: v2 token bug (#1991)
 * [ed36d92f](https://github.com/argoproj/argo-workflows/commit/ed36d92f99ea65e06dc78b82923d74c57130dfc3) feat: Add quick start manifests to Git. Change auth-mode to default to server. Fixes #1990 (#1993)
 * [d1965c93](https://github.com/argoproj/argo-workflows/commit/d1965c9352c43d486b2d7cf99b0141fdb17eac2b) docs: Encourage users to upvote issues relevant to them (#1996)
 * [91331a89](https://github.com/argoproj/argo-workflows/commit/91331a894d713f085207e30406e72b8f65ad0227) fix: No longer delete the argo ns as this is dangerous (#1995)
 * [1a777cc6](https://github.com/argoproj/argo-workflows/commit/1a777cc6662b0c95ccf3de12c1a328c4cb12bc78) feat(cron): Added timezone support to cron workflows. Closes #1931 (#1986)
 * [48b85e57](https://github.com/argoproj/argo-workflows/commit/48b85e5705a235257b5926d0714eeb173b4347cb) fix: WorkflowTempalteTest fix (#1992)
 * [51dab8a4](https://github.com/argoproj/argo-workflows/commit/51dab8a4a79e5180d795ef10586e31ecf4075214) feat: Adds `argo server` command. Fixes #1966 (#1972)
 * [732e03bb](https://github.com/argoproj/argo-workflows/commit/732e03bb6cdc94ecd264fa76ecf71c29114b7769) chore: Added WorkflowTemplate test (#1989)
 * [27387d4b](https://github.com/argoproj/argo-workflows/commit/27387d4b52e99f83fe1c6ac9a0e65add669463d9) chore: Fix UI TODOs (#1987)
 * [dd704dd6](https://github.com/argoproj/argo-workflows/commit/dd704dd6557e972c8dc3c9816996305a23c80f37) feat: Renders namespace in UI. Fixes #1952 and #1959 (#1965)
 * [14d58036](https://github.com/argoproj/argo-workflows/commit/14d58036faa444ee49a4905a632db7e0a5ab60ba) feat(server): Argo Server. Closes #1331 (#1882)
 * [f69655a0](https://github.com/argoproj/argo-workflows/commit/f69655a09c82236d91703fbce2ee1a07fc3641be) fix: Added decompress in retry, resubmit and resume. (#1934)
 * [1e7ccb53](https://github.com/argoproj/argo-workflows/commit/1e7ccb53e8604654c073f6578ae024fd341f048a) updated jq version to 1.6 (#1937)
 * [c51c1302](https://github.com/argoproj/argo-workflows/commit/c51c1302f48cec5b9c6009b9b7e50962d338c679) feat: Enhancement for namespace installation mode configuration (#1939)
 * [6af100d5](https://github.com/argoproj/argo-workflows/commit/6af100d5470137cc17c019546f3cad2acf5e4a31) feat: Add suspend and resume to CronWorkflows CLI (#1925)
 * [232a465d](https://github.com/argoproj/argo-workflows/commit/232a465d00b6104fe4801b773b0b3ceffdafb116) feat: Added onExit handlers to Step and DAG (#1716)
 * [071eb112](https://github.com/argoproj/argo-workflows/commit/071eb1126cae351c5059246d2c375dc47175a3d6) docs: Update PR template to demand tests. (#1929)
 * [ae58527e](https://github.com/argoproj/argo-workflows/commit/ae58527eed40947078a7cb71da1dc3ab9c052a56) docs: Add CyberAgent to the list of Argo users (#1926)
 * [02022e4b](https://github.com/argoproj/argo-workflows/commit/02022e4bb36977253ff2e362f844b9596e768102) docs: Minor formatting fix (#1922)
 * [e4107bb8](https://github.com/argoproj/argo-workflows/commit/e4107bb831af9eb4b99753f7e324ec33042cdc55) Updated Readme.md for companies using Argo: (#1916)
 * [7e9b2b58](https://github.com/argoproj/argo-workflows/commit/7e9b2b58915c5cb51276e21c81344e010472cbae) feat: Support for scheduled Workflows with CronWorkflow CRD (#1758)
 * [5d7e9185](https://github.com/argoproj/argo-workflows/commit/5d7e91852b09ca2f3f912a8f1efaa6c28e07b524) feat: Provide values of withItems maps as JSON in {{item}}. Fixes #1905 (#1906)
 * [de3ffd78](https://github.com/argoproj/argo-workflows/commit/de3ffd78b9c16ed09065aeb16e966904e964a572)  feat: Enhanced Different TTLSecondsAfterFinished depending on if job is in Succeeded, Failed or Error, Fixes (#1883)
 * [94449876](https://github.com/argoproj/argo-workflows/commit/94449876f4a571ab279802d5ca4d5e938ca3d44d) docs: Add question option to issue templates (#1910)
 * [83ae2df4](https://github.com/argoproj/argo-workflows/commit/83ae2df4130468a95b720ce33c9b9e27e7005b17) fix: Decrease docker build time by ignoring node_modules (#1909)
 * [59a19069](https://github.com/argoproj/argo-workflows/commit/59a190697286bf19ee4a5c398c1af590a2419003) feat: support iam roles for service accounts in artifact storage (#1899)
 * [6526b6cc](https://github.com/argoproj/argo-workflows/commit/6526b6cc5e4671317fa0bc8c62440364c37a9700) fix: Revert node creation logic (#1818)
 * [160a7940](https://github.com/argoproj/argo-workflows/commit/160a794046299c9d0420ae1710641814f30a9b7f) fix: Update Gopkg.lock with dep ensure -update (#1898)
 * [ce78227a](https://github.com/argoproj/argo-workflows/commit/ce78227abe5a3c901e5b7a7dd823fb2551dff584) fix: quick fail after pod termination (#1865)
 * [cd3bd235](https://github.com/argoproj/argo-workflows/commit/cd3bd235f550fbc24c31d1763fde045c9c321fbe) refactor: Format Argo UI using prettier (#1878)
 * [b48446e0](https://github.com/argoproj/argo-workflows/commit/b48446e09e29d4f18f6a0cf0e6ff1166770286b1) fix: Fix support for continueOn failed for DAG. Fixes #1817 (#1855)
 * [48256961](https://github.com/argoproj/argo-workflows/commit/482569615734d7cb5e24c90d399f3ec98fb2ed96) fix: Fix template scope (#1836)
 * [eb585ef7](https://github.com/argoproj/argo-workflows/commit/eb585ef7381c4c9547eb9c2e922e175c0556da03) fix: Use dynamically generated placeholders (#1844)
 * [c821cfcc](https://github.com/argoproj/argo-workflows/commit/c821cfcce488222bcd5a4514cd94c66582885f33) test: Adds 'test' and 'ui' jobs to CI (#1869)
 * [54f44909](https://github.com/argoproj/argo-workflows/commit/54f44909a0e68bc24209e9e83999421b814e80c9) feat: Always archive logs if in config. Closes #1790 (#1860)
 * [1e25d6cf](https://github.com/argoproj/argo-workflows/commit/1e25d6cfa9c4c2f805717f94bd67ec612746a862) docs: Fix e2e testing link (#1873)
 * [f5f40728](https://github.com/argoproj/argo-workflows/commit/f5f40728c4be2d852e8199a5754aee39ed72399f) fix: Minor comment fix (#1872)
 * [72fad7ec](https://github.com/argoproj/argo-workflows/commit/72fad7ec0cf3aa463bd9c2c8c8f961738408cf93) Update docs (#1870)
 * [90352865](https://github.com/argoproj/argo-workflows/commit/9035286554768119b83e00294ea7c0b400b5de83) docs: Update doc based on helm 3.x changes (#1843)
 * [78889895](https://github.com/argoproj/argo-workflows/commit/788898954f7eff5b096f7597e74fc68104d8bf78) Move Workflows UI from https://github.com/argoproj/argo-ui (#1859)
 * [4b96172f](https://github.com/argoproj/argo-workflows/commit/4b96172f71f3fb36a691499b11e52a0d5650448a) docs: Refactored and cleaned up docs (#1856)
 * [6ba4598f](https://github.com/argoproj/argo-workflows/commit/6ba4598fd19c4add40b66d32df18592194c4cf4c) test: Adds core e2e test infra. Fixes #678 (#1854)
 * [87f26c8d](https://github.com/argoproj/argo-workflows/commit/87f26c8de2adc9563a3811aacc1eb31475a84f0b) fix: Move ISSUE_TEMPLATE/ under .github/ (#1858)
 * [bd78d159](https://github.com/argoproj/argo-workflows/commit/bd78d1597e82bf2bf0193e4bf49b6386c68e8222) fix: Ensure timer channel is empty after stop (#1829)
 * [afc63024](https://github.com/argoproj/argo-workflows/commit/afc63024de79c2e211a1ed0e0ede87b99825c63f) Code duplication (#1482)
 * [5b136713](https://github.com/argoproj/argo-workflows/commit/5b1367137d2b511b0310ac322596ff5395ed148d) docs: biobox analytics (#1830)
 * [68b72a8f](https://github.com/argoproj/argo-workflows/commit/68b72a8fd1773ba5f1afb4ec6ba9bf8a4d2b7ad4) add CCRi to list of users in README (#1845)
 * [941f30aa](https://github.com/argoproj/argo-workflows/commit/941f30aaf4e51e1eec13e842a0b8d46767929cec) Add Sidecar Technologies to list of who uses Argo (#1850)
 * [a08048b6](https://github.com/argoproj/argo-workflows/commit/a08048b6de84ff7355728b85851aa84b08be0851) Adding Wavefront to the users list (#1852)
 * [1cb68c98](https://github.com/argoproj/argo-workflows/commit/1cb68c9829099eb5218995159fb11fb58a147032) docs: Updates issue and PR templates. (#1848)
 * [cb0598ea](https://github.com/argoproj/argo-workflows/commit/cb0598ea82bd676fefd98e2040752cfa06516a98) Fixed Panic if DB context has issue (#1851)
 * [e5fb8848](https://github.com/argoproj/argo-workflows/commit/e5fb884853d2ad0d1f32022723e211b902841945) fix: Fix a couple of nil derefs (#1847)
 * [b3d45850](https://github.com/argoproj/argo-workflows/commit/b3d458504b319b3b02b82a872a5e13c59cb3128f) Add HOVER to the list of who uses Argo (#1825)
 * [99db30d6](https://github.com/argoproj/argo-workflows/commit/99db30d67b42cbd9c7fa35bbdd35a57040c2f222) InsideBoard uses Argo (#1835)
 * [ac8efcf4](https://github.com/argoproj/argo-workflows/commit/ac8efcf40e45750ae3c78f696f160049ea85dc8e) Red Hat uses Argo (#1828)
 * [41ed3acf](https://github.com/argoproj/argo-workflows/commit/41ed3acfb68c1200ea5f03643120cac81f7d3df6) Adding Fairwinds to the list of companies that use Argo (#1820)
 * [5274afb9](https://github.com/argoproj/argo-workflows/commit/5274afb97686a4d2a58c50c3b23dd2b680b881e6) Add exponential back-off to retryStrategy (#1782)
 * [e522e30a](https://github.com/argoproj/argo-workflows/commit/e522e30acebc17793540ac4270d14747b2617b26) Handle operation level errors PVC in Retry (#1762)
 * [f2e6054e](https://github.com/argoproj/argo-workflows/commit/f2e6054e9376f2d2be1d928ee79746b8b49937df) Do not resolve remote templates in lint (#1787)
 * [3852bc3f](https://github.com/argoproj/argo-workflows/commit/3852bc3f3311e9ac174976e9a3e8f625b87888eb) SSL enabled database connection for workflow repository (#1712) (#1756)
 * [f2676c87](https://github.com/argoproj/argo-workflows/commit/f2676c875e0af8e43b8967c669a33871bc02995c) Fix retry node name issue on error (#1732)
 * [d38a107c](https://github.com/argoproj/argo-workflows/commit/d38a107c84b91ad476f4760d984450efda296fdc) Refactoring Template Resolution Logic (#1744)
 * [23e94604](https://github.com/argoproj/argo-workflows/commit/23e9460451566e04b14acd336fccf54b0623efc4) Error occurred on pod watch should result in an error on the wait container (#1776)
 * [57d051b5](https://github.com/argoproj/argo-workflows/commit/57d051b52de7c9b78d926f0be7b158adb08803c8) Added hint when using certain tokens in when expressions (#1810)
 * [0e79edff](https://github.com/argoproj/argo-workflows/commit/0e79edff4b879558a19132035446fca2fbe3f2ca) Make kubectl print status and start/finished time (#1766)
 * [723b3c15](https://github.com/argoproj/argo-workflows/commit/723b3c15e55d2f8dceb86f1ac0a6dc7d1a58f10b) Fix code-gen docs (#1811)
 * [711bb114](https://github.com/argoproj/argo-workflows/commit/711bb11483a0ccb46600795c636c98d9c3a7f16c) Fix withParam node naming issue (#1800)
 * [4351a336](https://github.com/argoproj/argo-workflows/commit/4351a3360f6b20298a28a06be545bc349b22b9e4) Minor doc fix (#1808)
 * [efb748fe](https://github.com/argoproj/argo-workflows/commit/efb748fe35c6f24c736db8e002078abd02b57141) Fix some issues in examples (#1804)
 * [a3e31289](https://github.com/argoproj/argo-workflows/commit/a3e31289915e4d129a743b9284442775ef41a15c) Add documentation for executors (#1778)
 * [1ac75b39](https://github.com/argoproj/argo-workflows/commit/1ac75b39040e6f292ee322122a157e05f55f1f73) Add  to linter (#1777)
 * [3bead0db](https://github.com/argoproj/argo-workflows/commit/3bead0db3d2777638992ba5e11a2de1c65be162c) Add ability to retry nodes after errors (#1696)
 * [b50845e2](https://github.com/argoproj/argo-workflows/commit/b50845e22e8910d27291bab30f0c3dbef1fe5dad) Support no-headers flag (#1760)
 * [7ea2b2f8](https://github.com/argoproj/argo-workflows/commit/7ea2b2f8c10c3004c3c13a49d200df704895f93c) Minor rework of suspened node (#1752)
 * [9ab1bc88](https://github.com/argoproj/argo-workflows/commit/9ab1bc88f58c551208ce5e76eea0c6fb83359710) Update README.md (#1768)
 * [e66fa328](https://github.com/argoproj/argo-workflows/commit/e66fa328e396fe35dfad8ab1e3088ab088aea8be) Fixed lint issues (#1739)
 * [63e12d09](https://github.com/argoproj/argo-workflows/commit/63e12d0986cb4b138715b8f2b9c483de5547f64e) binary up version (#1748)
 * [1b7f9bec](https://github.com/argoproj/argo-workflows/commit/1b7f9becdfc47688018e6d71ac417fb7278637ab) Minor typo fix (#1754)
 * [4c002677](https://github.com/argoproj/argo-workflows/commit/4c002677e360beb9d6e4398618bafdce025cda42) fix blank lines (#1753)
 * [fae73826](https://github.com/argoproj/argo-workflows/commit/fae7382686d917d78e3909d1f6db79c272a1aa11) Fail suspended steps after deadline (#1704)
 * [b2d7ee62](https://github.com/argoproj/argo-workflows/commit/b2d7ee62e903c062b62da35dc390e38c05ba1591) Fix typo in docs (#1745)
 * [f2592448](https://github.com/argoproj/argo-workflows/commit/f2592448636bc35b7f9ec0fdc48b92135ba9852f) Removed uneccessary debug Println (#1741)
 * [846d01ed](https://github.com/argoproj/argo-workflows/commit/846d01eddc271f330e00414d1ea2277ac390651b) Filter workflows in list  based on name prefix (#1721)
 * [8ae688c6](https://github.com/argoproj/argo-workflows/commit/8ae688c6cbcc9494195431be7754fe69eb33a9f4) Added ability to auto-resume from suspended state (#1715)
 * [fb617b63](https://github.com/argoproj/argo-workflows/commit/fb617b63a09679bb74427cd5d13192b1fd8f48cf) unquote strings from parameter-file (#1733)
 * [34120341](https://github.com/argoproj/argo-workflows/commit/34120341747e0261425b49a5600c42efbb1812a3) example for pod spec from output of previous step (#1724)
 * [12b983f4](https://github.com/argoproj/argo-workflows/commit/12b983f4c00bda3f9bedd14a316b0beade6158ed) Add gonum.org/v1/gonum/graph to Gopkg.toml (#1726)
 * [327fcb24](https://github.com/argoproj/argo-workflows/commit/327fcb242b20107c859142b3dd68745b3440e5eb) Added  Protobuf extension  (#1601)
 * [602e5ad8](https://github.com/argoproj/argo-workflows/commit/602e5ad8e4002f7df0bd02014505cbc7de3fd37c) Fix invitation link. (#1710)
 * [eb29ae4c](https://github.com/argoproj/argo-workflows/commit/eb29ae4c89b89d4d4192a5f8c08d44ad31fa4cd2) Fixes bugs in demo (#1700)
 * [ebb25b86](https://github.com/argoproj/argo-workflows/commit/ebb25b861b1b452207582b6dea0060bf418037ff) `restartPolicy` -> `retryStrategy` in examples (#1702)
 * [167d65b1](https://github.com/argoproj/argo-workflows/commit/167d65b15ac0d3483071e0506f3e98a92a034183) Fixed incorrect `pod.name` in retry pods (#1699)
 * [e0818029](https://github.com/argoproj/argo-workflows/commit/e0818029d190cfd616527cccf208b5a9866224e1) fixed broke metrics endpoint per #1634 (#1695)
 * [36fd09a1](https://github.com/argoproj/argo-workflows/commit/36fd09a1321fd145b36b4f9067b61fabad363926) Apply Strategic merge patch against the pod spec (#1687)
 * [d3546467](https://github.com/argoproj/argo-workflows/commit/d35464670439b660c7c9ab0bcd9d3686ffe08687) Fix retry node processing (#1694)
 * [dd517e4c](https://github.com/argoproj/argo-workflows/commit/dd517e4c2db59b4c704ed7aeaed8505a757a60f7) Print multiple workflows in one command (#1650)
 * [09a6cb4e](https://github.com/argoproj/argo-workflows/commit/09a6cb4e81c1d9f5c8c082c9e96ce783fa20796f) Added status of previous steps as variables (#1681)
 * [ad3dd4d4](https://github.com/argoproj/argo-workflows/commit/ad3dd4d4a41b58e30983e8a93f06c1526c8aa9a0) Fix issue that workflow.priority substitution didn't pass validation (#1690)
 * [095d67f8](https://github.com/argoproj/argo-workflows/commit/095d67f8d0f1d309529c8a400cb16d0a0e2765b9) Store locally referenced template properly (#1670)
 * [30a91ef0](https://github.com/argoproj/argo-workflows/commit/30a91ef002e7c8850f45e6fe7ac01a7966ff31b8) Handle retried node properly (#1669)
 * [263cb703](https://github.com/argoproj/argo-workflows/commit/263cb7038b927fabe0f67b4455e17534b51c2989) Update README.md  Argo Ansible role: Provisioning Argo Workflows on Kubernetes/OpenShift (#1673)
 * [867f5ff7](https://github.com/argoproj/argo-workflows/commit/867f5ff7e72bc8b5d9b6be5a5f8849ccd2a1108c) Handle sidecar killing properly (#1675)
 * [f0ab9df9](https://github.com/argoproj/argo-workflows/commit/f0ab9df9ef8090fc388c32adbe9180dbaee683f5) Fix typo (#1679)
 * [502db42d](https://github.com/argoproj/argo-workflows/commit/502db42db84f317af8660d862ddd48c28cbd3b8e) Don't provision VM for empty artifacts (#1660)
 * [b5dcac81](https://github.com/argoproj/argo-workflows/commit/b5dcac8114d6f4b5fe32bae049d2c70b4dea4d15) Resolve WorkflowTemplate lazily (#1655)
 * [d15994bb](https://github.com/argoproj/argo-workflows/commit/d15994bbbb0a1ca8fc60b452ae532b10510c4762) [User] Update Argo users list (#1661)
 * [4a654ca6](https://github.com/argoproj/argo-workflows/commit/4a654ca6914923656bd1dc21ca5b8c4aa75b9e25) Stop failing if artifact file exists, but empty (#1653)
 * [c6cddafe](https://github.com/argoproj/argo-workflows/commit/c6cddafe19854d91bff41f093f48ac444a781c0d) Bug fixes in getting started (#1656)
 * [ec788373](https://github.com/argoproj/argo-workflows/commit/ec7883735e20f87fe483b26c947bd891a695a2bd) Update workflow_level_host_aliases.yaml (#1657)
 * [7e5af474](https://github.com/argoproj/argo-workflows/commit/7e5af4748d406f244378da86fda339a0c9e74476) Fix child node template handling (#1654)
 * [7f385a6b](https://github.com/argoproj/argo-workflows/commit/7f385a6bbf67ab780ab86c941cbd426f9b003834) Use stored templates to raggregate step outputs (#1651)
 * [cd6f3627](https://github.com/argoproj/argo-workflows/commit/cd6f3627992b6947dd47c98420d0a0fec4de9112) Fix dag output aggregation correctly (#1649)
 * [706075a5](https://github.com/argoproj/argo-workflows/commit/706075a55f694f94cfe729efca8eacb31d14f7f0) Fix DAG output aggregation (#1648)
 * [fa32dabd](https://github.com/argoproj/argo-workflows/commit/fa32dabdc0a5a74469a0e86e04b9868508503a73) Fix missing merged changes in validate.go (#1647)
 * [45716027](https://github.com/argoproj/argo-workflows/commit/457160275cc42be4c5fa6c1050c6e61a614b9544) fixed example wrong comment (#1643)
 * [69fd8a58](https://github.com/argoproj/argo-workflows/commit/69fd8a58d4877d616f3b576a2e8c8cbd224e029a) Delay killing sidecars until artifacts are saved (#1645)
 * [ec5f9860](https://github.com/argoproj/argo-workflows/commit/ec5f98605429f8d757f3b92fe6b2a2e8a4cb235f) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [4b84f975](https://github.com/argoproj/argo-workflows/commit/4b84f975f14714cedad2dc9697c9a181075b04ea) Fix global lint issue (#1641)
 * [bb579138](https://github.com/argoproj/argo-workflows/commit/bb579138c6104baab70f859e8ed05954718c5ee8) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [cbf99682](https://github.com/argoproj/argo-workflows/commit/cbf99682c7a84306066b059834a625892b86d28c) Fix regression where parallelism could cause workflow to fail (#1639)
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)
 * [9fca1441](https://github.com/argoproj/argo-workflows/commit/9fca144128c97499d11f07a0ee008a9921e1f5f8) Update argo dependencies to kubernetes v1.14 (#1530)
 * [0246d184](https://github.com/argoproj/argo-workflows/commit/0246d184add04e44f77ffbe00e796b3adaf535d2) Use cache to retrieve WorkflowTemplates (#1534)
 * [4864c32f](https://github.com/argoproj/argo-workflows/commit/4864c32ffa40861c5ca066f67615da6d52eaa8b5) Update README.md (#1533)
 * [4df114fa](https://github.com/argoproj/argo-workflows/commit/4df114fae66e87727cfcb871731ec002af1515c7) Update CHANGELOG for v2.4 (#1531)
 * [c7e5cba1](https://github.com/argoproj/argo-workflows/commit/c7e5cba14a835fbfd0aba88b99197675ce1f0c66) Introduce podGC strategy for deleting completed/successful pods (#1234)
 * [bb0d14af](https://github.com/argoproj/argo-workflows/commit/bb0d14af9d320a141cb307b6a883c1eaafa498c3) Update ISSUE_TEMPLATE.md (#1528)
 * [b5702d8a](https://github.com/argoproj/argo-workflows/commit/b5702d8ae725c5caa4058d39f77e6d1e7e549da4) Format sources and order imports with the help of goimports (#1504)
 * [d3ff77bf](https://github.com/argoproj/argo-workflows/commit/d3ff77bf475095c73f034fb3b23c279c62f4269e) Added Architecture doc (#1515)
 * [fc1ec1a5](https://github.com/argoproj/argo-workflows/commit/fc1ec1a51462c9a114417db801e3a9715d3dc6b4) WorkflowTemplate CRD (#1312)
 * [f99d3266](https://github.com/argoproj/argo-workflows/commit/f99d3266d1879579338f124c56f1fc14867308a3) Expose all input parameters to template as JSON (#1488)
 * [bea60526](https://github.com/argoproj/argo-workflows/commit/bea605261be82d8bb91bf703ad68875f1093ebb8) Fix argo logs empty content when workflow run in virtual kubelet env (#1201)
 * [d82de881](https://github.com/argoproj/argo-workflows/commit/d82de8813910afaf9b3fb77d029faa7953bfee3a) Implemented support for WorkflowSpec.ArtifactRepositoryRef (#1350)
 * [0fa20c7b](https://github.com/argoproj/argo-workflows/commit/0fa20c7ba317d8c9a837bcc37d92f3fe79808499) Fix validation (#1508)
 * [87e2cb60](https://github.com/argoproj/argo-workflows/commit/87e2cb6043a305839ca37cc77c7611aaa7bdbd44) Add --dry-run option to `argo submit` (#1506)
 * [e7e50af6](https://github.com/argoproj/argo-workflows/commit/e7e50af6e56b1eeddccc82a2dbc8b421d1a63942) Support git shallow clones and additional ref fetches (#1521)
 * [605489cd](https://github.com/argoproj/argo-workflows/commit/605489cd5dd688527e60efee0aff239e3439c2dc) Allow overriding workflow labels in 'argo submit' (#1475)
 * [47eba519](https://github.com/argoproj/argo-workflows/commit/47eba519107c229edf61dbe024a6a5e0f1618a8d) Fix issue [Documentation] kubectl get service argo-artifacts -o wide (#1516)
 * [02f38262](https://github.com/argoproj/argo-workflows/commit/02f38262c40901346ddd622685bc6bfd344a2717) Fixed #1287 Executor kubectl version is obsolete (#1513)
 * [f62105e6](https://github.com/argoproj/argo-workflows/commit/f62105e659a22ccc0875151698eab540090885f6) Allow Makefile variables to be set from the command line (#1501)
 * [e62be65b](https://github.com/argoproj/argo-workflows/commit/e62be65ba25ae68a1bed10bddf33b4dae4991249) Fix a compiler error in a unit test (#1514)
 * [5c5c29af](https://github.com/argoproj/argo-workflows/commit/5c5c29af729b39f5f9b8a7fe6b8c1dede53eae3a) Fix the lint target (#1505)
 * [e03287bf](https://github.com/argoproj/argo-workflows/commit/e03287bfb7f97f639c8d81617808f709ca547eaa) Allow output parameters with .value, not only .valueFrom (#1336)
 * [781d3b8a](https://github.com/argoproj/argo-workflows/commit/781d3b8ae243b2c32ea3c4abd5b4a99fe9fc9cad) Implemented Conditionally annotate outputs of script template only when consumed #1359 (#1462)
 * [b028e61d](https://github.com/argoproj/argo-workflows/commit/b028e61db71e74b5730469a5f23a734937ddb8d9) change 'continue-on-fail' example to better reflect its description (#1494)
 * [97e824c9](https://github.com/argoproj/argo-workflows/commit/97e824c9a5b71baea658e8de6130bee089fb764d) Readme update to add argo and airflow comparison (#1502)
 * [414d6ce7](https://github.com/argoproj/argo-workflows/commit/414d6ce7b8aebcbd3b8822f407ec71ed465c103d) Fix a compiler error (#1500)
 * [ca1d5e67](https://github.com/argoproj/argo-workflows/commit/ca1d5e671519aaa9f38f5f2564eb70c138fadda7) Fix: Support the List within List type in withParam #1471 (#1473)
 * [75cb8b9c](https://github.com/argoproj/argo-workflows/commit/75cb8b9cd92cd7fcce4b921b88232bb05f2672b2) Fix #1366 unpredictable global artifact behavior (#1461)
 * [082e5c4f](https://github.com/argoproj/argo-workflows/commit/082e5c4f617c4120584ad601a8d85e0a3ce36a26) Exposed workflow priority as a variable (#1476)
 * [38c4def7](https://github.com/argoproj/argo-workflows/commit/38c4def7fb100e954757649553db8c04ea64f318) Fix: Argo CLI should show warning if there is no workflow definition in file #1486
 * [af7e496d](https://github.com/argoproj/argo-workflows/commit/af7e496db6ee8c10c9a2b6b51a27265bc6b0ee6d) Add Commodus Tech as official user (#1484)
 * [8c559642](https://github.com/argoproj/argo-workflows/commit/8c559642f2ec8abaea3204279fa3d6ff5ad40add) Update OWNERS (#1485)
 * [007d1f88](https://github.com/argoproj/argo-workflows/commit/007d1f8816736a758fa3720f0081e01dbc4200e3) Fix: 1008 `argo wait` and `argo submit --wait` should exit 1 if workflow fails  (#1467)
 * [3ab7bc94](https://github.com/argoproj/argo-workflows/commit/3ab7bc94c01d7a470bd05198b99c33e1a0221847) Document the insecureIgnoreHostKey git flag (#1483)
 * [7d9bb51a](https://github.com/argoproj/argo-workflows/commit/7d9bb51ae328f1a8cc7daf7d8ef108cf190df0ce) Fix failFast bug:   When a node in the middle fails, the entire workflow will hang (#1468)
 * [42adbf32](https://github.com/argoproj/argo-workflows/commit/42adbf32e8d4c626c544795c2fc1adb70676e968) Add --no-color flag to logs (#1479)
 * [67fc29c5](https://github.com/argoproj/argo-workflows/commit/67fc29c57db795a7020f355ab32cd883cfaf701e) fix typo: symboloic > symbolic (#1478)
 * [7c3e1901](https://github.com/argoproj/argo-workflows/commit/7c3e1901f49fe34cbe9d084274f6e64c48270635) Added Codec to the Argo community list (#1477)
 * [0a9cf9d3](https://github.com/argoproj/argo-workflows/commit/0a9cf9d3b06a3b304c0c690a298d8dc3d51c015b) Add doc about failFast feature (#1453)
 * [6a590300](https://github.com/argoproj/argo-workflows/commit/6a5903000fe8a7b3610c32435b2363cbf6334d1b) Support PodSecurityContext (#1463)
 * [e392d854](https://github.com/argoproj/argo-workflows/commit/e392d854bf78db89413782a23e62b0e38cf9c780) issue-1445: changing temp directory for output artifacts from root to tmp (#1458)
 * [7a21adfe](https://github.com/argoproj/argo-workflows/commit/7a21adfeb0af18c2452648a8bb3698a687f99b5e) New Feature:  provide failFast flag, allow a DAG to run all branches of the DAG (either success or failure) (#1443)
 * [b9b87b7f](https://github.com/argoproj/argo-workflows/commit/b9b87b7fa0cd3177c2b89cacff189f4893c5af95) Centralized Longterm workflow persistence storage  (#1344)
 * [cb09609b](https://github.com/argoproj/argo-workflows/commit/cb09609bd646a394c3a6f739dd447022a2bdb327) mention sidecar in failure message for sidecar containers (#1430)
 * [373bbe6e](https://github.com/argoproj/argo-workflows/commit/373bbe6ec9e819c39152292f79752792ce40b94d) Fix demo's doc issue of install minio chart (#1450)
 * [83552334](https://github.com/argoproj/argo-workflows/commit/835523341bcc96b6e9358be71e7432d0ac4058c5) Add threekit to user list (#1444)
 * [83f82ad1](https://github.com/argoproj/argo-workflows/commit/83f82ad172de0472643495d3ef3e0ce6d959900a) Improve bash completion (#1437)
 * [ee0ec78a](https://github.com/argoproj/argo-workflows/commit/ee0ec78ac98eaa112d343906a6e9b6490c39817f) Update documentation for workflow.outputs.artifacts (#1439)
 * [9e30c06e](https://github.com/argoproj/argo-workflows/commit/9e30c06e32b072b87e0d17095448d114175c713f) Revert "Update demo.md (#1396)" (#1433)
 * [c08de630](https://github.com/argoproj/argo-workflows/commit/c08de6300c3b394c34a5b3596455dcb50c29af48) Add paging function for list command (#1420)
 * [bba2f9cb](https://github.com/argoproj/argo-workflows/commit/bba2f9cbe9aa0eb053c19b03bc8fa7c002f579b0) Fixed:  Implemented Template level service account (#1354)
 * [d635c1de](https://github.com/argoproj/argo-workflows/commit/d635c1def74936869edbd8b9037ac81ea0af1772) Ability to configure hostPath mount for `/var/run/docker.sock` (#1419)
 * [d2f7162a](https://github.com/argoproj/argo-workflows/commit/d2f7162ac26550642ebe1792c65fb5e6ca9c0e7a) Terminate all containers within pod after main container completes (#1423)
 * [1607d74a](https://github.com/argoproj/argo-workflows/commit/1607d74a8de0704b82627364645a99b699d40cc0) PNS executor intermitently failed to capture entire log of script templates (#1406)
 * [5e47256c](https://github.com/argoproj/argo-workflows/commit/5e47256c7f86b56cfbf2ce53f73ed093eef2e3b6) Fix typo (#1431)
 * [5635c33a](https://github.com/argoproj/argo-workflows/commit/5635c33aa263080fe84e29a11a52f86fee583ca2) Update demo.md (#1396)
 * [83425455](https://github.com/argoproj/argo-workflows/commit/83425455bff34527e65ca1371347eed5203ae99a) Add OVH as official user (#1417)
 * [82e5f63d](https://github.com/argoproj/argo-workflows/commit/82e5f63d3680e7e4a22747803b0753b5ec31d2ad) Typo fix in ARTIFACT_REPO.md (#1425)
 * [15fa6f52](https://github.com/argoproj/argo-workflows/commit/15fa6f52d926ee5e839321900f613f6e546e6b6e) Update OWNERS (#1429)
 * [96b9a40e](https://github.com/argoproj/argo-workflows/commit/96b9a40e9aafe9c0132ce1b9f1eb01f05c3894ca) Orders uses alphabetically (#1411)
 * [6550e2cb](https://github.com/argoproj/argo-workflows/commit/6550e2cb10112ddf6435755958387ffa6ada0ef5) chore: add IBM to official users section in README.md (#1409)
 * [bc81fe28](https://github.com/argoproj/argo-workflows/commit/bc81fe288ebf9811774b36dd6eba9a851ac7717e) Fiixed: persistentvolumeclaims already exists #1130 (#1363)
 * [6a042d1f](https://github.com/argoproj/argo-workflows/commit/6a042d1f7eb01f1f369c2325aecebf71a3bea3a4) Update README.md (#1404)
 * [aa811fbd](https://github.com/argoproj/argo-workflows/commit/aa811fbdb914fe386cfbf3fa84a51bfd5104b5d0) Update README.md (#1402)
 * [abe3c99f](https://github.com/argoproj/argo-workflows/commit/abe3c99f19a1ec28775a276b50ad588a2dd660ca) Add Mirantis as an official user (#1401)
 * [18ab750a](https://github.com/argoproj/argo-workflows/commit/18ab750aea4de8f7dc67433f4e73505c80e13222) Added Argo Rollouts to README (#1388)
 * [67714f99](https://github.com/argoproj/argo-workflows/commit/67714f99b4bf664eb5e853b25ebf4b12bb98f733) Make locating kubeconfig in example os independent (#1393)
 * [672dc04f](https://github.com/argoproj/argo-workflows/commit/672dc04f737a3be099fe64c343587c35074b0938) Fixed: withParam parsing of JSON/YAML lists #1389 (#1397)
 * [b9aec5f9](https://github.com/argoproj/argo-workflows/commit/b9aec5f9833d5fa2055d06d1a71fdb75709eea21) Fixed: make verify-codegen is failing on the master branch (#1399) (#1400)
 * [270aabf1](https://github.com/argoproj/argo-workflows/commit/270aabf1d8cabd69b9851209ad5d9c874348e21d) Fixed:  failed to save outputs: verify serviceaccount default:default has necessary privileges (#1362)
 * [163f4a5d](https://github.com/argoproj/argo-workflows/commit/163f4a5d322352bd98f9a88ebd6089cf5e5b49ad) Fixed: Support hostAliases in WorkflowSpec #1265 (#1365)
 * [abb17478](https://github.com/argoproj/argo-workflows/commit/abb174788dce1bc6bed993a2967f7d8e112e44ca) Add Max Kelsen to USERS in README.md (#1374)
 * [dc549193](https://github.com/argoproj/argo-workflows/commit/dc5491930e09eebe700952e28359deeb8e0d2314) Update docs for the v2.3.0 release and to use the stable tag
 * [4001c964](https://github.com/argoproj/argo-workflows/commit/4001c964dbc70962e1cc1d80a4aff64cf8594ec3) Update README.md (#1372)
 * [6c18039b](https://github.com/argoproj/argo-workflows/commit/6c18039be962996d971145be8349d2ed3e396c80) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [d7e74fe3](https://github.com/argoproj/argo-workflows/commit/d7e74fe3a96277ba532e4a2f40303a92d2d0ce94) Validate action for resource templates (#1346)
 * [810949d5](https://github.com/argoproj/argo-workflows/commit/810949d5106b4d1d533b647d1d61559c208b590a) Fixed :  CLI Does Not Honor metadata.namespace #1288 (#1352)
 * [e58859d7](https://github.com/argoproj/argo-workflows/commit/e58859d79516508838fead8222f0e26a6c2a2861) [Fix #1242] Failed DAG nodes are now kept and set to running on RetryWorkflow. (#1250)
 * [d5fe5f98](https://github.com/argoproj/argo-workflows/commit/d5fe5f981fb112ba01ed77521ae688f8a15f67b9) Use golangci-lint instead of deprecated gometalinter (#1335)
 * [26744d10](https://github.com/argoproj/argo-workflows/commit/26744d100e91eb757f48bfedd539e7e4a044faf3) Support an easy way to set owner reference (#1333)
 * [8bf7578e](https://github.com/argoproj/argo-workflows/commit/8bf7578e1884c61128603bbfaa677fd79cc17ea8) Add --status filter for get command (#1325)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions
 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing
 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md
 * [40f9a875](https://github.com/argoproj/argo-workflows/commit/40f9a87593d312a46f7fa24aaf32e125458cc701) Reorganize manifests to kustomize 2 and update version to v2.3.0-rc1
 * [75b28a37](https://github.com/argoproj/argo-workflows/commit/75b28a37b923e278fc89fd647f78a42e7a3bf029) Implement support for PNS (Process Namespace Sharing) executor (#1214)
 * [b4edfd30](https://github.com/argoproj/argo-workflows/commit/b4edfd30b0e3034d98e938b491cf5bd054b36525) Fix SIGSEGV in watch/CheckAndDecompress. Consolidate duplicate code (resolves #1315)
 * [02550be3](https://github.com/argoproj/argo-workflows/commit/02550be31e53da79f1f4dbebda3ede7dc1052086) Archive location should conditionally be added to template only when needed
 * [c60010da](https://github.com/argoproj/argo-workflows/commit/c60010da29bd36c10c6e627802df6d6a06c1a59a) Fix nil pointer dereference with secret volumes (#1314)
 * [db89c477](https://github.com/argoproj/argo-workflows/commit/db89c477d65a29fc0a95ca55f68e1bd23d0170e0) Fix formatting issues in examples documentation (#1310)
 * [0d400f2c](https://github.com/argoproj/argo-workflows/commit/0d400f2ce6db9478b4eaa6fe24849a686c9d1d44) Refactor checkandEstimate to optimize podReconciliation (#1311)
 * [bbdf2e2c](https://github.com/argoproj/argo-workflows/commit/bbdf2e2c8f1b5a8dc83e88fedba9b1899f6bc78b) Add alibaba cloud to officially using argo list (#1313)
 * [abb77062](https://github.com/argoproj/argo-workflows/commit/abb77062fc06ae964ce7ccd1a534ec8bbdf3747c) CheckandEstimate implementation to optimize podReconciliation (#1308)
 * [1a028d54](https://github.com/argoproj/argo-workflows/commit/1a028d5458ffef240f8af31caeecda91f057c3ba) Secrets should be passed to pods using volumes instead of API calls (#1302)
 * [e34024a3](https://github.com/argoproj/argo-workflows/commit/e34024a3ca285d1af3b5ba3b3235dc7adc0472b7) Add support for init containers (#1183)
 * [4591e44f](https://github.com/argoproj/argo-workflows/commit/4591e44fe0e4de543f4c4339de0808346e0807e3) Added support for artifact path references (#1300)
 * [928e4df8](https://github.com/argoproj/argo-workflows/commit/928e4df81c4b33f0c0750f01b3aa3c4fc7ff256c) Add Karius to users in README.md (#1305)
 * [de779f36](https://github.com/argoproj/argo-workflows/commit/de779f36122205790915622f5ee91c9a9d5b9086) Add community meeting notes link (#1304)
 * [a8a55579](https://github.com/argoproj/argo-workflows/commit/a8a55579131605d4dc769cb599bc99c06350dfb7) Speed up podReconciliation using parallel goroutine (#1286)
 * [93451119](https://github.com/argoproj/argo-workflows/commit/934511192e4045b87be1675ff7e9dfa79faa9fcb) Add dns config support (#1301)
 * [850f3f15](https://github.com/argoproj/argo-workflows/commit/850f3f15dd1965e99cd636711a5e3306bc4bd0c0) Admiralty: add link to blog post, add user (#1295)
 * [d5f4b428](https://github.com/argoproj/argo-workflows/commit/d5f4b428ce02de34a37d5cb2fdba4dfa9fd16e75) Fix for Resource creation where template has same parameter templating (#1283)
 * [9b555cdb](https://github.com/argoproj/argo-workflows/commit/9b555cdb30f6092d5f53891f318fb74b8371c039) Issue#896 Workflow steps with non-existant output artifact path will succeed (#1277)
 * [adab9ed6](https://github.com/argoproj/argo-workflows/commit/adab9ed6bc4f8f337105182c56abad39bccb9676) Argo CI is current inactive (#1285)
 * [59fcc5cc](https://github.com/argoproj/argo-workflows/commit/59fcc5cc33ce67c057064dc37a463707501615e1) Add workflow labels and annotations global vars (#1280)
 * [1e111caa](https://github.com/argoproj/argo-workflows/commit/1e111caa1d2cc672b3b53c202b96a5f660a7e9b2) Fix bug with DockerExecutor's CopyFile (#1275)
 * [73a37f2b](https://github.com/argoproj/argo-workflows/commit/73a37f2b2a12d74ddf6a4b54e04b50fa1a7c68a1) Add the `mergeStrategy` option to resource patching (#1269)
 * [e6105243](https://github.com/argoproj/argo-workflows/commit/e6105243c785d9f53aef6fcfd344e855ad4f7d84) Reduce redundancy pod label action (#1271)
 * [4bfbb20b](https://github.com/argoproj/argo-workflows/commit/4bfbb20bc23f8bf4611a6314fb80f8138b17b9b9) Error running 1000s of tasks: "etcdserver: request is too large" #1186 (#1264)
 * [b2743f30](https://github.com/argoproj/argo-workflows/commit/b2743f30c411f5ad8f8c8b481a5d6b6ff83c33bd) Proxy Priority and PriorityClassName to pods (#1179)
 * [70c130ae](https://github.com/argoproj/argo-workflows/commit/70c130ae626f7c58d9e5ac0eed8977f51696fcbd) Update versions (#1218)
 * [b0384129](https://github.com/argoproj/argo-workflows/commit/b03841297e4b0dab0380b441cf41f5ed34db44bf) Git cloning via SSH was not verifying host public key (#1261)
 * [3f06385b](https://github.com/argoproj/argo-workflows/commit/3f06385b129c02e23ea283f7c66d347cb8899564) Issue#1165 fake outputs don't notify and task completes successfully (#1247)
 * [fa042aa2](https://github.com/argoproj/argo-workflows/commit/fa042aa285947c5fa365ef06a9565d0b4e20da0e) typo, executo -> executor (#1243)
 * [1cb88bae](https://github.com/argoproj/argo-workflows/commit/1cb88baee9ded1ede27a9d3f1e31f06f4369443d) Fixed Issue#1223 Kubernetes Resource action: patch is not supported (#1245)
 * [2b0b8f1c](https://github.com/argoproj/argo-workflows/commit/2b0b8f1c3f46aa41e4b4ddaf14ad1fdebccfaf8a) Fix the Prometheus address references (#1237)
 * [94cda3d5](https://github.com/argoproj/argo-workflows/commit/94cda3d53c6a72e3fc225ba08796bfd9420eccd6) Add feature to continue workflow on failed/error steps/tasks (#1205)
 * [3f1fb9d5](https://github.com/argoproj/argo-workflows/commit/3f1fb9d5e61d300c4922e48a748dc17285e07f07) Add Gardener to "Who uses Argo" (#1228)
 * [cde5cd32](https://github.com/argoproj/argo-workflows/commit/cde5cd320fa987ac6dd539a3126f29c73cd7277a) Include stderr when retrieving docker logs (#1225)
 * [2b1d56e7](https://github.com/argoproj/argo-workflows/commit/2b1d56e7d4e583e2e06b37904714b350faf03d97) Update README.md (#1224)
 * [eeac5a0e](https://github.com/argoproj/argo-workflows/commit/eeac5a0e11b4a6f4bc28757a3b0684598b8c4974) Remove extra quotes around output parameter value (#1232)
 * [8b67e1bf](https://github.com/argoproj/argo-workflows/commit/8b67e1bfdc7ed5ea153cb17f9a740afe2bd4efa8) Update README.md (#1236)
 * [baa3e622](https://github.com/argoproj/argo-workflows/commit/baa3e622121e66c9fec7c612c88027b7cacbd1b2) Update README with typo fixes (#1220)
 * [f6b0c8f2](https://github.com/argoproj/argo-workflows/commit/f6b0c8f285217fd0e6089b0cf03ca4926d1b4758) Executor can access the k8s apiserver with a out-of-cluster config file (#1134)
 * [0bda53c7](https://github.com/argoproj/argo-workflows/commit/0bda53c77c54b037e7d91b18554053362b1e4d35) fix dag retries (#1221)
 * [8aae2931](https://github.com/argoproj/argo-workflows/commit/8aae29317a8cfef2edc084a4c74a44c83d845936) Issue #1190 - Fix incorrect retry node handling (#1208)
 * [f1797f78](https://github.com/argoproj/argo-workflows/commit/f1797f78044504dbf2e1f7285cc9c18ac79f5e81) Add schedulerName to workflow and template spec (#1184)
 * [2ddae161](https://github.com/argoproj/argo-workflows/commit/2ddae161037f603d2a3c12ba6b495dc422547b58) Set executor image pull policy for resource template (#1174)
 * [edcb5629](https://github.com/argoproj/argo-workflows/commit/edcb56296255267a3c8fa639c3ad26a016caab80) Dockerfile: argoexec base image correction (fixes #1209) (#1213)
 * [f92284d7](https://github.com/argoproj/argo-workflows/commit/f92284d7108ebf92907008d8f12a0696ee467a43) Minor spelling, formatting, and style updates. (#1193)
 * [bd249a83](https://github.com/argoproj/argo-workflows/commit/bd249a83e119d6161fa1c593b09fb381db448a0d) Issue #1128 - Use polling instead of fs notify to get annotation changes (#1194)
 * [14a432e7](https://github.com/argoproj/argo-workflows/commit/14a432e75119e37d42715b7e83992789c6dac454) Update community/README (#1197)
 * [eda7e084](https://github.com/argoproj/argo-workflows/commit/eda7e08438d2314bb5eb178a1335a3c28555ab34) Updated OWNERS (#1198)
 * [73504a24](https://github.com/argoproj/argo-workflows/commit/73504a24e885c6df9d1cceb4aa123c79eca7b7cd) Fischerjulian adds ruby to rest docs (#1196)
 * [311ad86f](https://github.com/argoproj/argo-workflows/commit/311ad86f101c58a1de1cef313a1516b4c79e643f) Fix missing docker binary in argoexec image. Improve reuse of image layers
 * [831e2198](https://github.com/argoproj/argo-workflows/commit/831e2198e22503394acca1cce0dbcf8dcebb2931) Issue #988 - Submit should not print logs to stdout unless output is 'wide' (#1192)
 * [17250f3a](https://github.com/argoproj/argo-workflows/commit/17250f3a51d545c49114882d0da6ca29eda7c6f2) Add documentation how to use parameter-file's (#1191)
 * [01ce5c3b](https://github.com/argoproj/argo-workflows/commit/01ce5c3bcf0dde5536b596d48bd48a93b3f2eee0) Add Docker Hub build hooks
 * [93289b42](https://github.com/argoproj/argo-workflows/commit/93289b42f96cd49cdc048d84626cb28ef6932940) Refactor Makefile/Dockerfile to remove volume binding in favor of build stages (#1189)
 * [8eb4c666](https://github.com/argoproj/argo-workflows/commit/8eb4c66639c5fd1a607c73a4d765468a99c43da1) Issue #1123 - Fix 'kubectl get' failure if resource namespace is different from workflow namespace (#1171)
 * [eaaad7d4](https://github.com/argoproj/argo-workflows/commit/eaaad7d47257302f203bab24bce1b7d479453351) Increased S3 artifact retry time and added log (#1138)
 * [f07b5afe](https://github.com/argoproj/argo-workflows/commit/f07b5afeaf950f49f87cdffb5116e82c8b0d43a1) Issue #1113 - Wait for daemon pods completion to handle annotations (#1177)
 * [2b2651b0](https://github.com/argoproj/argo-workflows/commit/2b2651b0a7f5d6873c8470fad137d42f9b7d7240) Do not mount unnecessary docker socket (#1178)
 * [1fc03144](https://github.com/argoproj/argo-workflows/commit/1fc03144c55f987993c7777b190b1848fc3833cd) Argo users: Equinor (#1175)
 * [e381653b](https://github.com/argoproj/argo-workflows/commit/e381653b6d6d6a6babba2e8f05f6f103e81a191d) Update README. (#1173) (#1176)
 * [5a917140](https://github.com/argoproj/argo-workflows/commit/5a917140cb56a27e7b6f3b1d5068f4838863c273) Update README and preview notice in CLA.
 * [521eb25a](https://github.com/argoproj/argo-workflows/commit/521eb25aeb2b8351d72bad4a3d3aa2d1fa55eb23) Validate ArchiveLocation artifacts (#1167)
 * [528e8f80](https://github.com/argoproj/argo-workflows/commit/528e8f803683ee462ccc05fc9b00dc57858c0e93) Add missing patch in namespace kustomization.yaml (#1170)
 * [0b41ca0a](https://github.com/argoproj/argo-workflows/commit/0b41ca0a2410b01205712a2186dd12851eecb707) Add Preferred Networks to users in README.md (#1172)
 * [649d64d1](https://github.com/argoproj/argo-workflows/commit/649d64d1bd375f779cd150446bddce94582067d2) Add GitHub to users in README.md (#1151)
 * [864c7090](https://github.com/argoproj/argo-workflows/commit/864c7090a0bfcaa12237ff6e894a9d26ab463a7a) Update codegen for network config (#1168)
 * [c3cc51be](https://github.com/argoproj/argo-workflows/commit/c3cc51be2e14e931d6e212aa30842a2c514082d1) Support HDFS Artifact (#1159)
 * [8db00066](https://github.com/argoproj/argo-workflows/commit/8db0006667dec74c58cbab744b014c67fda55c65) add support for hostNetwork & dnsPolicy config (#1161)
 * [149d176f](https://github.com/argoproj/argo-workflows/commit/149d176fdf3560d74afa91fe91a0ee38bf7ec3bd) Replace exponential retry with poll (#1166)
 * [31e5f63c](https://github.com/argoproj/argo-workflows/commit/31e5f63cba89b06abc2cdce0d778c6b8d937a23e) Fix tests compilation error (#1157)
 * [6726d9a9](https://github.com/argoproj/argo-workflows/commit/6726d9a961a2c3ed5467430d3631a36cfbf361de) Fix failing TestAddGlobalArtifactToScope unit test
 * [4fd758c3](https://github.com/argoproj/argo-workflows/commit/4fd758c38fc232bf26bb5e1d4e7e23321ba91416) Add slack badge to README (#1164)
 * [3561bff7](https://github.com/argoproj/argo-workflows/commit/3561bff70ad6bfeca8967be6aa4ac24fbbc8ac27) Issue #1136 - Fix metadata for DAG with loops (#1149)
 * [c7fec9d4](https://github.com/argoproj/argo-workflows/commit/c7fec9d41c0e2d3369e111f8b1d0f1d0ca77edae) Reflect minio chart changes in documentation (#1147)
 * [f6ce7833](https://github.com/argoproj/argo-workflows/commit/f6ce78334762cbc3c6de1604c11ea4f5f618c275) add support for other archs (#1137)
 * [cb538489](https://github.com/argoproj/argo-workflows/commit/cb538489a187134577e2146afcf9367f45088ff7) Fix issue where steps with exhausted retires would not complete (#1148)
 * [e400b65c](https://github.com/argoproj/argo-workflows/commit/e400b65c5eca2de2aa891f8489dcd835ef0e161c) Fix global artifact overwriting in nested workflow (#1086)
 * [174eb20a](https://github.com/argoproj/argo-workflows/commit/174eb20a6a110c9bf647b040460df83b6ab031c4) Issue #1040 - Kill daemoned step if workflow consist of single daemoned step (#1144)
 * [e078032e](https://github.com/argoproj/argo-workflows/commit/e078032e469effdfc492c8eea97eb2701ceda0c2) Issue #1132 - Fix panic in ttl controller (#1143)
 * [e09d9ade](https://github.com/argoproj/argo-workflows/commit/e09d9ade25535ae7e78ca23636e4d158a98bba84) Issue #1104 - Remove container wait timeout from 'argo logs --follow' (#1142)
 * [0f84e514](https://github.com/argoproj/argo-workflows/commit/0f84e5148dd34c225a35eab7a1f5953afb45e724) Allow owner reference to be set in submit util (#1120)
 * [3484099c](https://github.com/argoproj/argo-workflows/commit/3484099c856716f6da5e02ad75a48b568f547695) Update generated swagger to fix verify-codegen (#1131)
 * [587ab1a0](https://github.com/argoproj/argo-workflows/commit/587ab1a02772cd9b7ae7cd94f91b815ac4774297) Fix output artifact and parameter conflict (#1125)
 * [6bb3adbc](https://github.com/argoproj/argo-workflows/commit/6bb3adbc596349100c4f19155cfe976f4ea0e6fb) Adding Quantibio in Who uses Argo (#1111)
 * [1ae3696c](https://github.com/argoproj/argo-workflows/commit/1ae3696c27f343c947d9225c5cc2294c8b7c45e5) Install mime-support in argoexec to set proper mime types for S3 artifacts (resolves #1119)
 * [515a9005](https://github.com/argoproj/argo-workflows/commit/515a9005057dfd260a8b60c4ba1ab8c3aa614f48) add support for ppc64le and s390x (#1102)
 * [78142837](https://github.com/argoproj/argo-workflows/commit/78142837836cb100f6858d246d84100b74794cc6) Remove docker_lib mount volume which is not needed anymore (#1115)
 * [e59398ad](https://github.com/argoproj/argo-workflows/commit/e59398adf39b8ef1d0ce273263e80d49e370c510) Fix examples docs of parameters. (#1110)
 * [ec20d94b](https://github.com/argoproj/argo-workflows/commit/ec20d94b6f1d0d88d579c8a27b964f6e9915ff55) Issue #1114 - Set FORCE_NAMESPACE_ISOLATION env variable in namespace install manifests (#1116)
 * [49c1fa4f](https://github.com/argoproj/argo-workflows/commit/49c1fa4f42e1c19ce3b8f4ac2c339894e1ed90d7) Update docs with examples using the K8s REST API
 * [bb8a6a58](https://github.com/argoproj/argo-workflows/commit/bb8a6a58fee8170d6db65c73a50c5fe640f3cb7d) Update ROADMAP.md
 * [46855dcd](https://github.com/argoproj/argo-workflows/commit/46855dcde1d9ba904a1c94a97e602d0510f5e0d4) adding logo to be used by the OS Site (#1099)
 * [438330c3](https://github.com/argoproj/argo-workflows/commit/438330c38da69a68d6b0b0b24f6aae0053fc35ee) #1081 added retry logic to s3 load and save function (#1082)
 * [cb8b036b](https://github.com/argoproj/argo-workflows/commit/cb8b036b8db3ebeb6ef73d9f2070a1ddaf0d2150) Initialize child node before marking phase. Fixes panic on invalid `When` (#1075)
 * [60b508dd](https://github.com/argoproj/argo-workflows/commit/60b508dd9ec36ef45013d72ec6166dd9a30d77fe) Drop reference to removed `argo install` command. (#1074)
 * [62b24368](https://github.com/argoproj/argo-workflows/commit/62b24368a93d57eb505bf226e042a8eb0bf72da4) Fix typo in demo.md (#1089)
 * [b5dfa021](https://github.com/argoproj/argo-workflows/commit/b5dfa0217470c97d8e83716a22cf3bd274c4a2d5) Use relative links on README file (#1087)
 * [95b72f38](https://github.com/argoproj/argo-workflows/commit/95b72f38c94d12735e79bb8bec1a46b10514603c) Update docs to outline bare minimum set of privileges for a workflow
 * [d4ef6e94](https://github.com/argoproj/argo-workflows/commit/d4ef6e944c302b5d2b75d4c49e1833c3a28c1f9a) Add new article and minor edits. (#1083)
 * [afdac9bb](https://github.com/argoproj/argo-workflows/commit/afdac9bb34fe8a01ad511323a00ccf6c07e41137) Issue #740 - System level workflow parallelism limits & priorities (#1065)
 * [a53a76e9](https://github.com/argoproj/argo-workflows/commit/a53a76e9401fab701eaa150307b21a28825c97ce) fix #1078 Azure AKS authentication issues (#1079)
 * [79b3e307](https://github.com/argoproj/argo-workflows/commit/79b3e30746f779e3cec3a28beaecb9c0df7024e1) Fix string format arguments in workflow utilities. (#1070)
 * [76b14f54](https://github.com/argoproj/argo-workflows/commit/76b14f54520a92b81ced78d4cae2632655f396fc) Auto-complete workflow names (#1061)
 * [f2914d63](https://github.com/argoproj/argo-workflows/commit/f2914d63e9c8b41a13b5932f7962f208b7e5a0da) Support nested steps workflow parallelism (#1046)
 * [eb48c23a](https://github.com/argoproj/argo-workflows/commit/eb48c23a2525a62bbc1b8b4c94e3d50fd91014bd) Raise not implemented error when artifact saving is unsupported (#1062)
 * [036969c0](https://github.com/argoproj/argo-workflows/commit/036969c0f4f6ce6a3c948b5d161c0367cf07176b) Add Cratejoy to list of users (#1063)
 * [a07bbe43](https://github.com/argoproj/argo-workflows/commit/a07bbe431cecbb1d50356f94111d3bd2dbc48bb6) Adding SAP Hybris in Who uses Argo (#1064)
 * [7ef1cea6](https://github.com/argoproj/argo-workflows/commit/7ef1cea68c94f7f0e1e2f8bd75bedc5a7df8af90) Update dependencies to K8s v1.12 and client-go 9.0
 * [23d733ba](https://github.com/argoproj/argo-workflows/commit/23d733bae386db44ec80639daf91b29dbf86b335) Add namespace explicitly to pod metadata (#1059)
 * [79ed7665](https://github.com/argoproj/argo-workflows/commit/79ed7665d7419e7fbfe8b120c4cbcd486bebee57) Parameter and Argument names should support snake case (#1048)
 * [6e6c59f1](https://github.com/argoproj/argo-workflows/commit/6e6c59f13ff84fd6b4f1e7f836c783941c434ce7) Submodules are dirty after checkout -- need to update (#1052)
 * [f18716b7](https://github.com/argoproj/argo-workflows/commit/f18716b74c6f52d0c8bf4d64c05eae9db75bfb1f) Support for K8s API based Executor (#1010)
 * [e297d195](https://github.com/argoproj/argo-workflows/commit/e297d19501a8116b5a18c925a3c72d7c7e106ea0) Updated examples/README.md (#1051)
 * [19d6cee8](https://github.com/argoproj/argo-workflows/commit/19d6cee8149917c994b737510d9c8dbfc6dbdd27) Updated ARTIFACT_REPO.md (#1049)
 * [0a928e93](https://github.com/argoproj/argo-workflows/commit/0a928e93dac6d8522682931a0a68c52add310cdb) Update installation manifests to use v2.2.1
 * [3b52b261](https://github.com/argoproj/argo-workflows/commit/3b52b26190163d1f72f3aef1a39f9f291378dafb) Fix linter warnings and update swagger
 * [7d0e77ba](https://github.com/argoproj/argo-workflows/commit/7d0e77ba74587d913b1f4aceb1443228a04d35de) Update changelog and bump version to 2.2.1
 * [b402e12f](https://github.com/argoproj/argo-workflows/commit/b402e12feefe5cd1380e9479b2cc9bae838357bf) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)
 * [3f2e986e](https://github.com/argoproj/argo-workflows/commit/3f2e986e130ca136514767fb1593d745ca418236) fix typo in examples/README.md (#1025)
 * [9c5e056a](https://github.com/argoproj/argo-workflows/commit/9c5e056a858a9b510cdacdbc5deb5857a97662f8) Replace tabs with spaces (#1027)
 * [091f1407](https://github.com/argoproj/argo-workflows/commit/091f1407180990c745e981b24169c3bb4868dbe3) Update README.md (#1030)
 * [159fe09c](https://github.com/argoproj/argo-workflows/commit/159fe09c99c16738c0897f9d74087ec1b264954d) Fix format issues to resolve build errors (#1023)
 * [363bd97b](https://github.com/argoproj/argo-workflows/commit/363bd97b72ae5cb7fc52a560b6f7939248cdb72d) Fix error in env syntax (#1014)
 * [ae7bf0a5](https://github.com/argoproj/argo-workflows/commit/ae7bf0a5f7ddb1e5211e724bef15951198610942) Issue #1018 - Workflow controller should save information about archived logs in step outputs (#1019)
 * [15d006c5](https://github.com/argoproj/argo-workflows/commit/15d006c54ee7149b0d86e6d60453ecc8c071c953) Add example of workflow using imagePullSecrets (resolves #1013)
 * [2388294f](https://github.com/argoproj/argo-workflows/commit/2388294fa412e153d8366910e4d47ba564f29856) Fix RBAC roles to include workflow delete for GC to work properly (resolves #1004)
 * [6f611cb9](https://github.com/argoproj/argo-workflows/commit/6f611cb9383610471f941b5cab4227ce8bfea7c5) Fix issue where resubmission of a terminated workflow creates a terminated workflow (issue #1011)
 * [4a7748f4](https://github.com/argoproj/argo-workflows/commit/4a7748f433f888fdc50b592db1002244ea466bdb) Disable Persistence in the demo example (#997)
 * [55ae0cb2](https://github.com/argoproj/argo-workflows/commit/55ae0cb242a9cf6b390822ca6c0aa0868f5b06e3) Fix example pod name (#1002)
 * [c275e7ac](https://github.com/argoproj/argo-workflows/commit/c275e7acb7b5e8f9820a09d8b0cb635f710b8674) Add imagePullPolicy config for executors (#995)
 * [b1eed124](https://github.com/argoproj/argo-workflows/commit/b1eed124e6d943c453d87a9b4291ba10198d0bc6) `tar -tf` will detect compressed tars correctly. (#998)
 * [03a7137c](https://github.com/argoproj/argo-workflows/commit/03a7137c9ca9459727b57fb0a0e95584c5305844) Add new organization using argo (#994)
 * [83884528](https://github.com/argoproj/argo-workflows/commit/8388452870ed9a2d2e348a2844d3d7d1c4d61b05) Update argoproj/pkg to trim leading/trailing whitespace in S3 credentials (resolves #981)
 * [978b4938](https://github.com/argoproj/argo-workflows/commit/978b49383d30cdbc7c9708eb281b7800ee5412df) Add syntax highlighting for all YAML snippets and most shell snippets (#980)
 * [60d5dc11](https://github.com/argoproj/argo-workflows/commit/60d5dc11c73e888898160b4cc329e87747cee4d2) Give control to decide whether or not to archive logs at a template level
 * [8fab73b1](https://github.com/argoproj/argo-workflows/commit/8fab73b142b96f943592c66932ae0c5183e8c3db) Detect and indicate when container was OOMKilled
 * [47a9e556](https://github.com/argoproj/argo-workflows/commit/47a9e5560229c789b70a6624f23fb4433412fbc4) Update config map doc with instructions to enable log archiving
 * [79dbbaa1](https://github.com/argoproj/argo-workflows/commit/79dbbaa1ed30cae6279eabd9a84650107f4387b3) Add instructions to match git URL format to auth type in git example (issue #979)
 * [429f03f5](https://github.com/argoproj/argo-workflows/commit/429f03f5b26db42f1857a93b7599b545642c2f0a) Add feature list to README.md. Tweaks to getting started.
 * [36fd1948](https://github.com/argoproj/argo-workflows/commit/36fd19482c6bebfb21076cba81b924deaff14f52) Update getting started guide with v2.2.0 instructions
 * [af636ddd](https://github.com/argoproj/argo-workflows/commit/af636ddd8455660f307d835814d3112b90815dfd) Update installation manifests to use v2.2.0
 * [7864ad36](https://github.com/argoproj/argo-workflows/commit/7864ad36788dc78d035d59ddb27ecd979f7216f4) Introduce `withSequence` to iterate a range of numbers in a loop (resolves #527)
 * [99e9977e](https://github.com/argoproj/argo-workflows/commit/99e9977e4ccf61171ca1e347f6a182ba1d8dba83) Introduce `argo terminate` to terminate a workflow without deleting it (resolves #527)
 * [f52c0450](https://github.com/argoproj/argo-workflows/commit/f52c045087abff478603db4817de1933bddce5e7) Reorganize codebase to make CLI functionality available as a library
 * [311169f7](https://github.com/argoproj/argo-workflows/commit/311169f7e71c58fe9bf879a94681ee274ddf623c) Fix issue where sidecars and daemons were not reliably killed (resolves #879)
 * [67ffb6eb](https://github.com/argoproj/argo-workflows/commit/67ffb6eb7519936e1149f36e11dc9fda0f70a242) Add a reason/message for Unschedulable Pending pods
 * [69c390f2](https://github.com/argoproj/argo-workflows/commit/69c390f288ccaaeefba1d5a7961acebfe2e7771a) Support for workflow level timeouts (resolves #848)
 * [f88732ec](https://github.com/argoproj/argo-workflows/commit/f88732ec09413716bf14927bef10355b21b88516) Update docs to use keyFormat field
 * [0df022e7](https://github.com/argoproj/argo-workflows/commit/0df022e777f35bf0ea39ebbacfe4e5f92f099a62) Rename keyPattern to keyFormat. Remove pending pod query during pod reconciliation
 * [75a9983b](https://github.com/argoproj/argo-workflows/commit/75a9983b17869b76a93621f108ee85c70b8d8533) Fix potential panic in `argo watch`
 * [9cb46449](https://github.com/argoproj/argo-workflows/commit/9cb4644975d16dbebc3607ffb91364c93bc14e30) Add TTLSecondsAfterFinished field and controller to garbage collect completed workflows (resolves #911)
 * [7540714a](https://github.com/argoproj/argo-workflows/commit/7540714a47f04f664362c7083c886058c62408f8) Add ability to archive container logs to the artifact repository (resolves #454)
 * [11e57f4d](https://github.com/argoproj/argo-workflows/commit/11e57f4dea93fde60b204a5e7675fec999c66f56) Introduce archive strategies with ability to disable tar.gz archiving (resolves #784)
 * [e180b547](https://github.com/argoproj/argo-workflows/commit/e180b547133aa461bd5cc282a59f8954485d5b8f) Update CHANGELOG.md
 * [5670bf5a](https://github.com/argoproj/argo-workflows/commit/5670bf5a65cbac898b298edd682e603666ed5cb6) Introduce `argo watch` command to watch live workflows from terminal (resolves #969)
 * [57394361](https://github.com/argoproj/argo-workflows/commit/5739436199980ec765b070f8e78669bc37115ad6) Support additional container runtimes through kubelet executor (#952)
 * [a9c84c97](https://github.com/argoproj/argo-workflows/commit/a9c84c97de8f088cd4ee91cd72cf75012fc70438) Error workflows which hit k8s/etcd 1M resource size limit (resolves #913)
 * [67792eb8](https://github.com/argoproj/argo-workflows/commit/67792eb89e5aa678ffc52540dbc232d8598ce43f) Add parameter-file support (#966)
 * [841832a3](https://github.com/argoproj/argo-workflows/commit/841832a3507be3b92e3b2a05fef1052b1cd6e20d) Aggregate workflow RBAC roles to built-in admin/edit/view clusterroles (resolves #960)
 * [35bb7093](https://github.com/argoproj/argo-workflows/commit/35bb70936cf1b76e53f7f6f0e6acaccb9c6d06bf) Allow scaling of workflow and pod workers via controller CLI flags (resolves #962)
 * [b479fa10](https://github.com/argoproj/argo-workflows/commit/b479fa10647bd1c1b86410b7837668c375b327be) Improve workflow configmap documentation for keyPattern
 * [f1802f91](https://github.com/argoproj/argo-workflows/commit/f1802f91d8934b2e4b9d1f64230230bc2a0b5baf) Introduce `keyPattern` workflow config to enable flexibility in archive location path (issue #953)
 * [a5648a96](https://github.com/argoproj/argo-workflows/commit/a5648a9644fcea5f498c24a573a038290b92016f) Fix kubectl proxy link for argo-ui Service (#963)
 * [09f05912](https://github.com/argoproj/argo-workflows/commit/09f0591205ec81b4ec03f0f5c534a13648346f41) Introduce Pending node state to highlight failures when start workflow pods
 * [a3ff464f](https://github.com/argoproj/argo-workflows/commit/a3ff464f67a862d4110848d94a46be39876ce57e) Speed up CI job
 * [88627e84](https://github.com/argoproj/argo-workflows/commit/88627e842c082ddc4d75d15a3e2dc6c7ab4f1db8) Update base images to debian:9.5-slim. Use stable metalinter
 * [753c5945](https://github.com/argoproj/argo-workflows/commit/753c5945b62be209f05025c2e415a0753f5e0b01) Update argo-ci-builder image with new dependencies
 * [674b61bb](https://github.com/argoproj/argo-workflows/commit/674b61bb473787a157e543c10dcf158fa35bb39a) Remove unnecessary dependency on argo-cd and obsolete RBAC constants
 * [60658de0](https://github.com/argoproj/argo-workflows/commit/60658de0cf7403c4be014e92b7a3bb4772f4ad5f) Refactor linting/validation into standalone package. Support linting of .json files
 * [f55d579a](https://github.com/argoproj/argo-workflows/commit/f55d579a9478ed33755874f24656faec04611777) Detect and fail upon unknown fields during argo submit & lint (resolves #892)
 * [edf6a574](https://github.com/argoproj/argo-workflows/commit/edf6a5741de8bdf3a20852a55581883f1ec80d9a) Migrate to using argoproj.io/pkg packages
 * [5ee1e0c7](https://github.com/argoproj/argo-workflows/commit/5ee1e0c7daed4e2c8dca5643a800292ece067fca) Update artifact config docs (#957)
 * [faca49c0](https://github.com/argoproj/argo-workflows/commit/faca49c009bead218ee974bfad2ccc36f84de1fb) Updated README
 * [936c6df7](https://github.com/argoproj/argo-workflows/commit/936c6df7eaae08082c1cc7ad750f664ff8a4c54c) Add table of content to examples (#956)
 * [d2c03f67](https://github.com/argoproj/argo-workflows/commit/d2c03f67c2fd45ff54c04db706c9ebf252fca6f2) Correct image used in install manifests
 * [ec3b7be0](https://github.com/argoproj/argo-workflows/commit/ec3b7be065aa65aae207bd34930001b593009b80) Remove CLI installer/uninstaller. Executor image configured via CLI argument (issue #928) Remove redundant/unused downward API metadata
 * [3a85e242](https://github.com/argoproj/argo-workflows/commit/3a85e2429154a4d97c8fc7c92f9e8f482de6639f) Rely on `git checkout` instead of go-git checkout for more reliable revision resolution
 * [ecef0e3d](https://github.com/argoproj/argo-workflows/commit/ecef0e3dd506eefc222c1ebed58ab81265ac9638) Rename Prometheus metrics (#948)
 * [b9cffe9c](https://github.com/argoproj/argo-workflows/commit/b9cffe9cd7b347905a42cf3e217cc3b039bdfb3f) Issue #896 - Prometheus metrics and telemetry (#935)
 * [290dee52](https://github.com/argoproj/argo-workflows/commit/290dee52bfb94679870cee94ca9560bbe8bd7813) Support parameter aggregation of map results in scripts
 * [fc20f5d7](https://github.com/argoproj/argo-workflows/commit/fc20f5d787ed11f03a24439c042b9ef45349eb95) Fix errors when submodules are from different URL (#939)
 * [b4f1a00a](https://github.com/argoproj/argo-workflows/commit/b4f1a00ad2862e6545dd4ad16279a49cd4585676) Add documentation about workflow variables
 * [4a242518](https://github.com/argoproj/argo-workflows/commit/4a242518c6ea81cd0d1e5aaab2822231d9b36d46) Update readme.md (#943)
 * [a5baca60](https://github.com/argoproj/argo-workflows/commit/a5baca60d1dfb8fb8c82a936ab383d49e075cff3) Support referencing of global workflow artifacts (issue #900)
 * [9b5c8563](https://github.com/argoproj/argo-workflows/commit/9b5c85631765285b4593b7707ede014178f77679) Support for sophisticated expressions in `when` conditionals (issue #860)
 * [ecc0f027](https://github.com/argoproj/argo-workflows/commit/ecc0f0272f2257600abab8f4779c478957644d7c) Resolve revision added ability to specify shorthand revision and other things like HEAD~2 etc (#936)
 * [11024318](https://github.com/argoproj/argo-workflows/commit/11024318c0e2a9106f8a8b4a719daba12adf9f36) Support conditions with DAG tasks. Support aggregated outputs from scripts (issue #921)
 * [d07c1d2f](https://github.com/argoproj/argo-workflows/commit/d07c1d2f3b7c916887185eea749db2278bf9d043) Support withItems/withParam and parameter aggregation with DAG templates (issue #801)
 * [94c195cb](https://github.com/argoproj/argo-workflows/commit/94c195cb014ba2e5c5943d96dc0a3cc3243edb6a) Bump VERSION to v2.2.0
 * [9168c59d](https://github.com/argoproj/argo-workflows/commit/9168c59dc486f840dc2b9713d92c14bdccebbaf8) Fix outbound node metadata with retry nodes causing disconnected nodes to be rendered in UI (issue #880)
 * [c6ce48d0](https://github.com/argoproj/argo-workflows/commit/c6ce48d086638168b9bd8b998d65a2e3a4801540) Fix outbound node metadata issue with steps template causing incorrect edges to be rendered in UI
 * [520b33d5](https://github.com/argoproj/argo-workflows/commit/520b33d5fc6e7e670c33015fd74c5a2f3bd74a21) Add ability to aggregate and reference output parameters expanded by loops (issue #861)
 * [ece1eef8](https://github.com/argoproj/argo-workflows/commit/ece1eef85ac1f92d2fad8a2fef8c657f04b4599a) Support submission of workflows as json, and from stdin (resolves #926)
 * [4c31d61d](https://github.com/argoproj/argo-workflows/commit/4c31d61da2891e92a3ae0d09b6924655a07fc59f) Add `argo delete --older` to delete completed workflows older than specified duration (resolves #930)
 * [c87cd33c](https://github.com/argoproj/argo-workflows/commit/c87cd33c1bc46c06314129c882fec80269af8133) Update golang version to v1.10.3
 * [618b7eb8](https://github.com/argoproj/argo-workflows/commit/618b7eb84678e177a38e5aa81fa59ed891459aa5) Proper fix for assessing overall DAG phase. Add some DAG unit tests (resolves #885)
 * [f223e5ad](https://github.com/argoproj/argo-workflows/commit/f223e5ad62115399cf1394db4e9e65f05ae6da8b) Fix issue where a DAG would fail even if retry was successful (resolves #885)
 * [143477f3](https://github.com/argoproj/argo-workflows/commit/143477f3d5e0ab0d65dd97774aabdcd736ae4fbe) Start use of argoproj/pkg shared libraries
 * [1220d080](https://github.com/argoproj/argo-workflows/commit/1220d0801b8aa78c5364a4586cd119553d96bca5) Update argo-cluster-role to work with OpenShift (resolves #922)
 * [4744f45a](https://github.com/argoproj/argo-workflows/commit/4744f45a9c110b11fa73070a52e4166406fa5da4) Added SSH clone and proper git clone using go-git (#919)
 * [d657abf4](https://github.com/argoproj/argo-workflows/commit/d657abf4a37c9f2987b5cc2ee337743c981c3e48) Regenerate code and address OpenAPI rule validation errors (resolves #923)
 * [c5ec4cf6](https://github.com/argoproj/argo-workflows/commit/c5ec4cf6194ab5f741eb2e1d4e387dcf32ba3ce7) Upgrade k8s dependencies to v1.10 (resolves #908)
 * [ba8061ab](https://github.com/argoproj/argo-workflows/commit/ba8061abd296895555ea3d1d6ca7418fcd07d633) Redundant verifyResolvedVariables check in controller precluded the ability to use {{ }} in other circumstances
 * [05a61449](https://github.com/argoproj/argo-workflows/commit/05a614496bb921b5fa081605227de1a8832260cd) Added link to community meetings (#912)
 * [f33624d6](https://github.com/argoproj/argo-workflows/commit/f33624d67d0cf348dcdece46832081346c26bf80) Add an example on how to submit and wait on a workflow
 * [aeed7f9d](https://github.com/argoproj/argo-workflows/commit/aeed7f9da490d8dc4ad40c00ac2272a19da4ff17) Added new members
 * [288e4fc8](https://github.com/argoproj/argo-workflows/commit/288e4fc8577890e7fa6cc546f92aef4c954ce18c) Added Argo Events link.
 * [3322506e](https://github.com/argoproj/argo-workflows/commit/3322506e5a1d07e198f69cadd210b0b6cc6cfbc9) Updated README
 * [3ce640a2](https://github.com/argoproj/argo-workflows/commit/3ce640a24509454302a5126c972fd5424673c00e) Issue #889 - Support retryStrategy for scripts (#890)
 * [91c6afb2](https://github.com/argoproj/argo-workflows/commit/91c6afb2cc07c113e4999f114279638aa6809fd6) adding BlackRock as corporate contributor/user (#886)
 * [c8667b5c](https://github.com/argoproj/argo-workflows/commit/c8667b5c81068326638a5e35c20336223b3894db) Fix issue where `argo lint` required spec level arguments to be supplied
 * [ed7dedde](https://github.com/argoproj/argo-workflows/commit/ed7dedde1f8be2a5f7be828a31ac9bb4025919e1) Update influx-ci example to choose a stable InfluxDB branch
 * [135813e1](https://github.com/argoproj/argo-workflows/commit/135813e10e932a2187d007284766a816d9aa4442) Add datadog to the argo users (#882)
 * [f1038948](https://github.com/argoproj/argo-workflows/commit/f103894843e9ed8cbaf4212e765c10311bec5989) Fix `make verify-codegen` build target when run in CI
 * [785f2cbd](https://github.com/argoproj/argo-workflows/commit/785f2cbd114e6d0097e21240d5cacece0b6d071e) Update references to v2.1.1. Add better checks in release Makefile target
 * [d65e1cd3](https://github.com/argoproj/argo-workflows/commit/d65e1cd3e77efbe6fc877ac689fd4cd19bc35093) readme: add Interline Technologies to user list (#867)
 * [c903168e](https://github.com/argoproj/argo-workflows/commit/c903168ee12f296f71f4953cda2163b8fa8cd409) Add documentation on global parameters (#871)

### Contributors

 * 0x1D-1983
 * Aaron Curtis
 * Adam Gilat
 * Adam Thornton
 * Aditya Sundaramurthy
 * Adrien Trouillaud
 * Aisuko
 * Akshay Chitneni
 * Alessandro Marrella
 * Alex Capras
 * Alex Collins
 * Alex Stein
 * Alexander Matyushentsev
 * Alexander Zigelski
 * Alexey Volkov
 * Anastasia Satonina
 * Andrei Miulescu
 * Andrew Suderman
 * Anes Benmerzoug
 * Ang Gao
 * Anna Winkler
 * Antoine Dao
 * Antonio Macías Ojeda
 * Appréderisse Benjamin
 * Avi Weit
 * Bastian Echterhölter
 * Ben Wells
 * Ben Ye
 * Brandon Steinman
 * Brian Mericle
 * CWen
 * Caden
 * Caglar Gulseni
 * Carlos Montemuino
 * Chen Zhiwei
 * Chris Chambers
 * Chris Hepner
 * Christian Muehlhaeuser
 * Clemens Lange
 * Cristian Pop
 * Daisuke Taniwaki
 * Dan Norris
 * Daniel Duvall
 * Daniel Moran
 * Daniel Sutton
 * David Bernard
 * David Seapy
 * David Van Loon
 * Deepen Mehta
 * Derek Wang
 * Dineshmohan Rajaveeran
 * Divya Vavili
 * Drew Dara-Abrams
 * Dustin Specker
 * EDGsheryl
 * Ed Lee
 * Edward Lee
 * Edwin Jacques
 * Ejiah
 * Elton
 * Erik Parmann
 * Fabio Rigato
 * Feynman Liang
 * Florent Clairambault
 * Fred Dubois
 * Gabriele Santomaggio
 * Galen Han
 * Grant Stephens
 * Greg Roodt
 * Guillaume Hormiere
 * Hamel Husain
 * Heikki Kesa
 * Hideto Inamura
 * Howie Benefiel
 * Huan-Cheng Chang
 * Ian Howell
 * Ilias K
 * Ilias Katsakioris
 * Ilya Sotkov
 * Ismail Alidzhikov
 * Jacob O'Farrell
 * Jaime
 * Jared Welch
 * Jean-Louis Queguiner
 * Jeff Uren
 * Jesse Suen
 * Jialu Zhu
 * Jie Zhang
 * Johannes 'fish' Ziemke
 * John Wass
 * Jonathan Steele
 * Jonathon Belotti
 * Jonny
 * Joshua Carp
 * Juan C. Muller
 * Julian Fahrer
 * Julian Fischer
 * Julian Mazzitelli
 * Julien Balestra
 * Kannappan Sirchabesan
 * Kaushik B
 * Konstantin Zadorozhny
 * Leonardo Luz
 * Lucas Theisen
 * Marcin Karkocha
 * Marco Sanvido
 * Marek Čermák
 * Markus Lippert
 * Matt Brant
 * Matt Hillsdon
 * Matthew Coleman
 * Matthew Magaldi
 * MengZeLee
 * Michael Crenshaw
 * Michael Weibel
 * Mike Seddon
 * Mingjie Tang
 * Miyamae Yuuya
 * Mostapha Sadeghipour Roudsari
 * Mukulikak
 * Naoto Migita
 * Naresh Kumar Amrutham
 * Nasrudin Bin Salim
 * Neutron Soutmun
 * Nick Groszewski
 * Nick Stott
 * Niklas Hansson
 * Niklas Vest
 * Nirav Patel
 * Noorain Panjwani
 * Nándor István Krácser
 * Omer Kahani
 * Orion Delwaterman
 * Pablo Osinaga
 * Pascal VanDerSwalmen
 * Patryk Jeziorowski
 * Paul Brit
 * Pavel Kravchenko
 * Peng Li
 * Pengfei Zhao
 * Per Buer
 * Peter Salanki
 * Pierre Houssin
 * Pradip Caulagi
 * Praneet Chandra
 * Pratik Raj
 * Premkumar Masilamani
 * Rafael Rodrigues
 * Rafał Bigaj
 * Remington Breeze
 * Rick Avendaño
 * Rocio Montes
 * Romain Di Giorgio
 * Romain GUICHARD
 * Roman Galeev
 * Saradhi Sreegiriraju
 * Saravanan Balasubramanian
 * Sascha Grunert
 * Sean Fern
 * Sebastian Ortan
 * Semjon Kopp
 * Shannon
 * Shubham Koli (FaultyCarry)
 * Simon Behar
 * Simon Frey
 * Snyk bot
 * Song Juchao
 * Stephen Steiner
 * StoneHuang
 * Takashi Abe
 * Takayuki Kasai
 * Tang Lee
 * Theodore Messinezis
 * Tim Schrodi
 * Tobias Bradtke
 * Tom Wieczorek
 * Tomas Valasek
 * Trevor Foster
 * Tristan Colgate-McFarlane
 * Val Sichkovskyi
 * Vardan Manucharyan
 * Vincent Boulineau
 * Vincent Smith
 * Vlad Losev
 * Wei Yan
 * WeiYan
 * Weston Platter
 * William
 * William Reed
 * Xianlu Bird
 * Xie.CS
 * Xin Wang
 * Youngjoon Lee
 * Yuan Tang
 * Yunhai Luo
 * Zach Aller
 * Zach Himsel
 * Zadjad Rezai
 * Zhipeng Wang
 * Ziyang Wang
 * alex weidner
 * almariah
 * candonov
 * commodus-sebastien
 * descrepes
 * dgiebert
 * dherman
 * dmayle
 * dthomson25
 * fsiegmund
 * gerardaus
 * gerdos82
 * haibingzhao
 * hidekuro
 * houz
 * ianCambrio
 * jacky
 * jdfalko
 * joe
 * juliusvonkohout
 * kshamajain99
 * lueenavarro
 * maguowei
 * mark9white
 * maryoush
 * mdvorakramboll
 * nglinh
 * sang
 * sh-tatsuno
 * shahin
 * shibataka000
 * tkilpela
 * tralexa
 * tunoat
 * vatine
 * vdinesh2461990
 * xubofei1983
 * yonirab
 * zhujl1991
 * モハメド

## v2.1.1 (2018-05-29)

 * [ac241c95](https://github.com/argoproj/argo-workflows/commit/ac241c95c13f08e868cd6f5ee32c9ce273e239ff) Update CHANGELOG for v2.1.1
 * [468e0760](https://github.com/argoproj/argo-workflows/commit/468e07600c5e124c8d2e0737f8c67a3265979952) Retrying failed steps templates could potentially result in disconnected children
 * [8d96ea7b](https://github.com/argoproj/argo-workflows/commit/8d96ea7b1b1ba843eb19a0632bc503d816ab9ef3) Switch to an UnstructuredInformer to guard against malformed workflow manifests (resolves #632)
 * [5bef6cae](https://github.com/argoproj/argo-workflows/commit/5bef6cae26dece96cadad855c9d54c5148f5e917) Suspend templates were not properly being connected to their children (resolves #869)
 * [543e9392](https://github.com/argoproj/argo-workflows/commit/543e9392f44873d1deb0a95fad3e00d67e8a7c70) Fix issue where a failed step in a template with parallelism would not complete (resolves #868)
 * [289000ca](https://github.com/argoproj/argo-workflows/commit/289000cac81b199c2fc9e50d04831e3ccfcc0659) Update argocli Dockerfile and make cli-image part of release
 * [d35a1e69](https://github.com/argoproj/argo-workflows/commit/d35a1e6949beca7cd032e5de5687e4e66869a916) Bump version to v2.1.1
 * [bbcff0c9](https://github.com/argoproj/argo-workflows/commit/bbcff0c94edf2b3270d7afc03b2538f47cb28492) Fix issue where `argo list` age column maxed out at 1d (resolves #857)
 * [d68cfb7e](https://github.com/argoproj/argo-workflows/commit/d68cfb7e585121e38e36c9d9dbd3e9cf8a1d9aac) Fix issue where volumes were not supported in script templates (resolves #852)
 * [fa72b6db](https://github.com/argoproj/argo-workflows/commit/fa72b6dbe4533ed9e2cc2c9f6bb574bcd85c6d16) Fix implementation of DAG task targets (resolves #865)
 * [dc003f43](https://github.com/argoproj/argo-workflows/commit/dc003f43baeba5509bfadfc825ced533715b93c6) Children of nested DAG templates were not correctly being connected to its parent
 * [b8065797](https://github.com/argoproj/argo-workflows/commit/b8065797712a29b0adefa5769cc6ffd2c6c7edd7) Simplify some examples for readability and clarity
 * [7b02c050](https://github.com/argoproj/argo-workflows/commit/7b02c050e86138983b20a38ee9efab52180141d5) Add CoreFiling to "Who uses Argo?" section. (#864)
 * [4f2fde50](https://github.com/argoproj/argo-workflows/commit/4f2fde505d221783bec889f3c9339361f5e8be73) Add windows support for argo-cli (#856)
 * [703241e6](https://github.com/argoproj/argo-workflows/commit/703241e60c7203550ac9f7947284e5d6fde3dc74) Updated ROADMAP.md for v2.2
 * [54f2138e](https://github.com/argoproj/argo-workflows/commit/54f2138ef83f92d2038ebf7b925bd102bc5a7b8d) Spell check the examples README (#855)
 * [f23feff5](https://github.com/argoproj/argo-workflows/commit/f23feff5e9353b4796ad4f0afa33efcb1b9f0d95) Mkbranch (#851)
 * [628b5408](https://github.com/argoproj/argo-workflows/commit/628b540891d1999c708accf064356d4dad22c7e0) DAG docs. (#850)
 * [22f62439](https://github.com/argoproj/argo-workflows/commit/22f624396c3c8cacd288040935feb7da4e4a869d) Small edit to README
 * [edc09afc](https://github.com/argoproj/argo-workflows/commit/edc09afc332c6e2707688a050060548940eca852) Added OWNERS file
 * [530e7244](https://github.com/argoproj/argo-workflows/commit/530e72444e2ced0c3c050e3238431dc32c1645c5) Update release notes and documentation for v2.1.0
 * [93796381](https://github.com/argoproj/argo-workflows/commit/9379638189cc194f1b34ff7295f0832eac1c1651) Avoid `println` which outputs to stderr. (#844)
 * [30e472e9](https://github.com/argoproj/argo-workflows/commit/30e472e9495f264676c00875e4ba5ddfcc23e15f) Add gladly as an official argo user (#843)
 * [cb4c1a13](https://github.com/argoproj/argo-workflows/commit/cb4c1a13b8c92d2bbfb73c2f1d7c8fcc5697ec6b) Add ability to override metadata.name and/or metadata.generateName during submission (resolves #836)
 * [834468a5](https://github.com/argoproj/argo-workflows/commit/834468a5d12598062b870c073f9a0230028c71b0) Command print the logs for a container in a workflow
 * [1cf13f9b](https://github.com/argoproj/argo-workflows/commit/1cf13f9b008ae41bbb23af6b55bf8e982723292f) Issue #825 - fix locating outbound nodes for skipped node (#842)
 * [30034d42](https://github.com/argoproj/argo-workflows/commit/30034d42b4f35729dd4575153c268565efef47be) Bump from debian:9.1 to debian:9.4. (#841)
 * [f3c41717](https://github.com/argoproj/argo-workflows/commit/f3c41717b21339157b6519b86e22a5e20feb2b97) Owner reference example (#839)
 * [191f7aff](https://github.com/argoproj/argo-workflows/commit/191f7aff4b619bc6796c18c39e58ed9636865cf5) Minor edit to README
 * [c8a2e25f](https://github.com/argoproj/argo-workflows/commit/c8a2e25fa6085587018f65a0fc4ec31f012c2653) Fixed typo (#835)
 * [cf13bf0b](https://github.com/argoproj/argo-workflows/commit/cf13bf0b35ebbcefce1138fa77f04b268ccde394) Added users section to README
 * [e4d76329](https://github.com/argoproj/argo-workflows/commit/e4d76329bf13e72f09433a9ab219f9c025d232a9) Updated News in README
 * [b631d0af](https://github.com/argoproj/argo-workflows/commit/b631d0af4dee5ecbe6e70e39ad31b9f708efb6b9) added community meeting (#834)
 * [e34728c6](https://github.com/argoproj/argo-workflows/commit/e34728c66bf37b76cb92f03552a2f2a200f09644) Fix issue where daemoned steps were not terminated properly in DAG templates (resolves #832)
 * [2e9e113f](https://github.com/argoproj/argo-workflows/commit/2e9e113fb3f2b86f75df9669f4bf11fca181a348) Update docs to work with latest minio chart
 * [ea95f191](https://github.com/argoproj/argo-workflows/commit/ea95f191047dd17bbcab8573541d25fbd51829c0) Use octal syntax for mode values (#833)
 * [5fc67d2b](https://github.com/argoproj/argo-workflows/commit/5fc67d2b785ac582a03e7dcdc83fc212839863d1) Updated community docs
 * [8fa4f006](https://github.com/argoproj/argo-workflows/commit/8fa4f0063893d8c419e4a9466abbc608c5c97811) Added community docs
 * [423c8d14](https://github.com/argoproj/argo-workflows/commit/423c8d144eab054acf682127c1ca04c216199db0) Issue #830 - retain Step node children references
 * [73990c78](https://github.com/argoproj/argo-workflows/commit/73990c787b08f2ce72f65b8169e9f1653b5b6877) Moved cricket gifs to a different s3 bucket
 * [ca1858ca](https://github.com/argoproj/argo-workflows/commit/ca1858caade6385f5424e16f53da5d38f2fcb3b2) edit Argo license info so that GitHub recognizes it (#823)
 * [206451f0](https://github.com/argoproj/argo-workflows/commit/206451f066924abf3b4b6756606234150bf10fc9) Fix influxdb-ci.yml example
 * [da582a51](https://github.com/argoproj/argo-workflows/commit/da582a5194056a08d5eef95c2441b562cde08740) Avoid nil pointer for 2.0 workflows. (#820)
 * [0f225cef](https://github.com/argoproj/argo-workflows/commit/0f225cef91f4b276e24270a827c37dcd5292a4f0) ClusterRoleBinding was using incorrect service account namespace reference when overriding install namespace (resolves #814)
 * [66ea711a](https://github.com/argoproj/argo-workflows/commit/66ea711a1c7cc805282fd4065e029287f4617d57) Issue #816 - fix updating outboundNodes field of failed step group node (#817)
 * [00ceef6a](https://github.com/argoproj/argo-workflows/commit/00ceef6aa002199186475350b95ebc2d32debf14) install & uninstall commands use --namespace flag (#813)

### Contributors

 * Adam Pearse
 * Alexander Matyushentsev
 * Andrea Kao
 * Edward Lee
 * Eric
 * Javier Castellanos
 * Jesse Suen
 * Jonas Fonseca
 * Lukasz Lempart
 * Matt Hillsdon
 * Mukulikak
 * Sean Fitzgerald
 * Sebastien Doido

## v2.1.0-beta2 (2018-03-29)

 * [fe23c2f6](https://github.com/argoproj/argo-workflows/commit/fe23c2f651a61a2d7aa877a86edff9802d7b5b47) Issue #810 - `argo install`does not install argo ui (#811)
 * [28673ed2](https://github.com/argoproj/argo-workflows/commit/28673ed2f85ca39f5d9b136382ea9a87da0ca716) Update release date in change log

### Contributors

 * Alexander Matyushentsev

## v2.1.0-beta1 (2018-03-29)

 * [05e8a983](https://github.com/argoproj/argo-workflows/commit/05e8a98386ccc73a02f39357f6faed69f7d11a17) Update change log for 2.1.0-beta1 release
 * [bf38b6b5](https://github.com/argoproj/argo-workflows/commit/bf38b6b509ae3fb123e47da2570906d0262ccf67) Use socket type for hostPath to mount docker.sock (#804) (#809)
 * [37680ef2](https://github.com/argoproj/argo-workflows/commit/37680ef26585f412930694cc809d9870d655bd13) Minimal shell completion support (#807)
 * [c83ad24a](https://github.com/argoproj/argo-workflows/commit/c83ad24a6fb5eb7054af16ae2c4f95de8df3965b) Omit empty status fields. (#806)
 * [d7291a3e](https://github.com/argoproj/argo-workflows/commit/d7291a3ee3b5375f8a079b60c568380e1bb91de9) Issue #660 - Support rendering logs from all steps using 'argo logs' command (#792)
 * [7d3f1e83](https://github.com/argoproj/argo-workflows/commit/7d3f1e83d3e08b13eb705ddd74244ea29e019c1a) Minor edits to README
 * [7a4c9c1f](https://github.com/argoproj/argo-workflows/commit/7a4c9c1f9c4fbd5282c57011c0bdcd48fe10137b) Added a review to README
 * [383276f3](https://github.com/argoproj/argo-workflows/commit/383276f300e666bf133a0355f2da493997ddd6cc) Inlined LICENSE file. Renamed old license to COPYRIGHT
 * [91d0f47f](https://github.com/argoproj/argo-workflows/commit/91d0f47fec82c7cef156ac05287622adc0b0a53b) Build argo cli image (#800)
 * [3b2c426e](https://github.com/argoproj/argo-workflows/commit/3b2c426ee5ba6249fec0d0a59353bfe77cb0966c) Add ability to pass pod annotations and labels at the template level (#798)
 * [d8be0287](https://github.com/argoproj/argo-workflows/commit/d8be0287f04f1d0d3bdee60243e0742594009bc8) Add ability to use IAM role from EC2 instance for AWS S3 credentials
 * [624f0f48](https://github.com/argoproj/argo-workflows/commit/624f0f48306183da33e2ef3aecf9566bb0ad8ad3) Update CHANGELOG.md for v2.1.0-beta1 release
 * [e96a09a3](https://github.com/argoproj/argo-workflows/commit/e96a09a3911f039038ea3038bed3a8cd8d63e269) Allow spec.arguments to be not supplied during linting. Global parameters were not referencable from artifact arguments (resolves #791)
 * [018e663a](https://github.com/argoproj/argo-workflows/commit/018e663a53aeda35149ec9b8de28f26391eb688e) Fix for https://github.com/argoproj/argo/issues/739 Nested stepgroups render correctly (#790)
 * [5c5b35ba](https://github.com/argoproj/argo-workflows/commit/5c5b35ba271fb48c38bf65e386e3d8b574f49373) Fix install issue where service account was not being created
 * [88e9e5ec](https://github.com/argoproj/argo-workflows/commit/88e9e5ecb5fc9e5215033a11abf6f6ddf50db253) packr needs to run compiled in order to cross compile darwin binaries
 * [dcdf9acf](https://github.com/argoproj/argo-workflows/commit/dcdf9acf9c7c3f58b3adfbf1994a5d3e7574dd9c) Fix install tests and build failure
 * [06c0d324](https://github.com/argoproj/argo-workflows/commit/06c0d324bf93a037010186fe54e40590ea39d92c) Rewrite the installer such that manifests are maintainable
 * [a45bf1b7](https://github.com/argoproj/argo-workflows/commit/a45bf1b7558b3eb60ec65d02c166c306e7797a79) Introduce support for exported global output parameters and artifacts
 * [60c48a9a](https://github.com/argoproj/argo-workflows/commit/60c48a9aa4b4dbf4c229e273faa945e0f5982539) Introduce `argo retry` to retry a failed workflow with the same name (resolves #762) onExit and related nodes should never be executed during resubmit/retry (resolves #780)
 * [90c08bff](https://github.com/argoproj/argo-workflows/commit/90c08bffc1b12b4c7941daccbf417772f17e3704) Refactor command structure
 * [101509d6](https://github.com/argoproj/argo-workflows/commit/101509d6b5ebeb957bb7ad6e819a961a26812a0e) Abstract the container runtime as an interface to support mocking and future runtimes Trim a trailing newline from path-based output parameters (resolves #758)
 * [a3441d38](https://github.com/argoproj/argo-workflows/commit/a3441d38b9be1f75506ab91dfbac7d6546d2b900) Add ability to reference global parameters in spec level fields (resolves #749)
 * [cd73a9ce](https://github.com/argoproj/argo-workflows/commit/cd73a9ce18aae35beee5012c68f553ab0c46030d) Fix template.parallelism limiting parallelism of entire workflow (resolves #772) Refactor operator to make template execution method signatures consistent
 * [7d7b74fa](https://github.com/argoproj/argo-workflows/commit/7d7b74fa8a62c43f8891a9af1dcae71f6efdc7e0) Make {{pod.name}} available as a parameter in pod templates (resolves #744)
 * [3cf4bb13](https://github.com/argoproj/argo-workflows/commit/3cf4bb136a9857ea17921a2ec6cfd95b4b95a0d7) parse the artifactory URL before appending the artifact to the path (#774)
 * [ea1257f7](https://github.com/argoproj/argo-workflows/commit/ea1257f717676997f0efcac9086ed348613a28c7) examples: use alpine python image
 * [2114078c](https://github.com/argoproj/argo-workflows/commit/2114078c533db0ab34b2f76fe481f03eba046cc1) fix typo
 * [9f605589](https://github.com/argoproj/argo-workflows/commit/9f6055899fff0b3161bb573159b13fd337e2e35f) Fix retry-container-to-completion example
 * [07422f26](https://github.com/argoproj/argo-workflows/commit/07422f264ed62a428622505e1880d2d5787d50ae) Update CHANGELOG release date. Remove ui-image from release target

### Contributors

 * Alexander Matyushentsev
 * Dmitry Monakhov
 * Edward Lee
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Lukasz Lempart
 * Matt Hillsdon
 * Yang Pan
 * dougsc
 * gaganapplatix

## v2.1.0-alpha1 (2018-02-21)


### Contributors


## v2.10.2 (2020-09-14)

 * [ed79a540](https://github.com/argoproj/argo-workflows/commit/ed79a5401162db7a3060111aff1b0fae5e8c2117) Update manifests to v2.10.2
 * [d27bf2d2](https://github.com/argoproj/argo-workflows/commit/d27bf2d29afaaad608943f238c821d94952a8b85) fix: Fix UI selection issues (#3928)
 * [51220389](https://github.com/argoproj/argo-workflows/commit/51220389ac2a0f109b5411851f29f9ee2ff3d968) fix: Create global scope before workflow-level realtime metrics (#3979)
 * [857ef750](https://github.com/argoproj/argo-workflows/commit/857ef750f595f292775bace1129d9c01b08a8ddd) fix: Custom metrics are not recorded for DAG tasks Fixes #3872 (#3886)
 * [b9a0bb00](https://github.com/argoproj/argo-workflows/commit/b9a0bb00b03344c720485c8103f21b90beffc78e) fix: Consider WorkflowTemplate metadata during validation (#3988)
 * [089e1862](https://github.com/argoproj/argo-workflows/commit/089e1862ab1e6c34ff33b7f453ca2f7bad021eb4) fix(server): Remove XSS vulnerability. Fixes #3942 (#3975)
 * [1215d9e1](https://github.com/argoproj/argo-workflows/commit/1215d9e1e3250ec482363430d50c6ea4e5ca05ab) fix(cli): Allow `argo version` without KUBECONFIG. Fixes #3943 (#3945)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.10.1 (2020-09-02)

 * [854444e4](https://github.com/argoproj/argo-workflows/commit/854444e47ac00d146cb83d174049bfbb2066bfb2) Update manifests to v2.10.1
 * [69861fc9](https://github.com/argoproj/argo-workflows/commit/69861fc919495b4215fe24f549ce1a55bf0674db) fix: Workflow should fail on Pod failure before container starts Fixes #3879 (#3890)
 * [670fc618](https://github.com/argoproj/argo-workflows/commit/670fc618c52f8672a99d1159f4c922a7f1b1f1f5) fix(controller): Cron re-apply update (#3883)
 * [4b30fa4e](https://github.com/argoproj/argo-workflows/commit/4b30fa4ef82acba373b9e0d33809f63aa3c2632b) fix(executor): Replace default retry in executor with an increased value retryer (#3891)
 * [ae537cd7](https://github.com/argoproj/argo-workflows/commit/ae537cd769ca57842fe92a463e78a0f9f3b74d32) fix(ui): use absolute URL to redirect from autocomplete list. Closes #3903 (#3906)
 * [0e4b3902](https://github.com/argoproj/argo-workflows/commit/0e4b39027f9fefe4ea0c000b5514c055a61e1b4c) chore: Added unittest for PVC exceed quota Closes #3561 (#3860)
 * [56dc9f7a](https://github.com/argoproj/argo-workflows/commit/56dc9f7a77ce68880a8c95c43b380d6167d5f4c9) fix: Consider all children of TaskGroups in DAGs (#3740)
 * [8ac7369b](https://github.com/argoproj/argo-workflows/commit/8ac7369bf66af992a23d23eb6713000b95101e52) fix(controller): Support exit handler on workflow templates.  Fixes #3737 (#3782)
 * [ee848921](https://github.com/argoproj/argo-workflows/commit/ee848921348676718a8ab4cef8e8c2f52b86d124) fix(controller): Failure tolerant workflow archiving and offloading. Fixes #3786 and #3837 (#3787)
 * [c367d93e](https://github.com/argoproj/argo-workflows/commit/c367d93e9b12263d53792d419ff0148afb755057) build: Copy Dockerfile lines from master
 * [f491bbc6](https://github.com/argoproj/argo-workflows/commit/f491bbc676a18e2d930440056ba16c5c7c253ef7) chore: Merge .gitignore from master to prevent dirty
 * [195c6d83](https://github.com/argoproj/argo-workflows/commit/195c6d8310a70b07043b9df5c988d5a62dafe00d) Update manifests to v2.10.0
 * [08117f0c](https://github.com/argoproj/argo-workflows/commit/08117f0cd1206647644f1f14580046268d1c8639) fix: Increase the requeue duration on checkForbiddenErrorAndResubmitAllowed (#3794)
 * [5ea2ed0d](https://github.com/argoproj/argo-workflows/commit/5ea2ed0dbdb4003fc457b7cd76cf5cec9edc6799) fix(server): Trucate creator label at 63 chars. Fixes #3756 (#3758)

### Contributors

 * Alex Collins
 * Ang Gao
 * Nirav Patel
 * Saravanan Balasubramanian
 * Simon Behar

## v2.10.0-rc7 (2020-08-13)

 * [267da535](https://github.com/argoproj/argo-workflows/commit/267da535b66ed1dab8bcc90410260b7cf4b80e2c) Update manifests to v2.10.0-rc7
 * [baeb0fed](https://github.com/argoproj/argo-workflows/commit/baeb0fed2b3ab53f35297a764f983059600d4b44) fix: Revert merge error
 * [66bae22f](https://github.com/argoproj/argo-workflows/commit/66bae22f147cd248f1a88f913eaeac13ec873bcd) fix(executor): Add retry on pods watch to handle timeout. (#3675)
 * [971f1153](https://github.com/argoproj/argo-workflows/commit/971f115373c8f01f0e21991b14fc3b27876f3cbf) removed unused test-report files
 * [8c0b9f0a](https://github.com/argoproj/argo-workflows/commit/8c0b9f0a52922485a1bdf6a8954cdc09060dbc29) fix: Couldn't Terminate/Stop the ResourceTemplate Workflow (#3679)
 * [a04d72f9](https://github.com/argoproj/argo-workflows/commit/a04d72f95a433eaa37202418809e1877eb167a1a) fix(controller): Tolerate PDB delete race. Fixes #3706 (#3717)
 * [a7635763](https://github.com/argoproj/argo-workflows/commit/a76357638598174812bb749ea539ca4061284d89) fix: Fix bug with 'argo delete --older' (#3699)
 * [fe8129cf](https://github.com/argoproj/argo-workflows/commit/fe8129cfc766f875985f0f09d37dc351a1e5f933) fix(controller): Carry-over labels for re-submitted workflows. Fixes #3622 (#3638)
 * [e12d26e5](https://github.com/argoproj/argo-workflows/commit/e12d26e52a42d91ec4d2dbc3d188cf3b1a623a26) fix(controller): Treat TooManyError same as Forbidden (i.e. try again). Fixes #3606 (#3607)
 * [9a5febec](https://github.com/argoproj/argo-workflows/commit/9a5febec11d231ed1cd5e085a841069b9106dafe) fix: Ensure target task's onExit handlers are run (#3716)
 * [c3a58e36](https://github.com/argoproj/argo-workflows/commit/c3a58e36d18e3c3cbb7bffcd3a6ae4c5c08a66ea) fix: Enforce metric Help must be the same for each metric Name (#3613)

### Contributors

 * Alex Collins
 * Guillaume Hormiere
 * Saravanan Balasubramanian
 * Simon Behar

## v2.10.0-rc6 (2020-08-06)

 * [cb3536f9](https://github.com/argoproj/argo-workflows/commit/cb3536f9d1dd64258c1c3d737bb115bdab923e58) Update manifests to v2.10.0-rc6
 * [6e004ace](https://github.com/argoproj/argo-workflows/commit/6e004ace2710e17ed2a282c6570a97b567946e58) lint
 * [b31fc1f8](https://github.com/argoproj/argo-workflows/commit/b31fc1f8612a93c907b375de2e9a3c9326dca34b) fix(controller): Adds ALL_POD_CHANGES_SIGNIFICANT (#3689)
 * [0b7cd5b3](https://github.com/argoproj/argo-workflows/commit/0b7cd5b3181eece7636b99d4761e96c61c17c453) fix: Fixed workflow queue duration if PVC creation is forbidden (#3691)
 * [03b84162](https://github.com/argoproj/argo-workflows/commit/03b8416271002bfc88c11dd27d86fa08f95b33e9) fix: Re-introduce 1 second sleep to reconcile informer (#3684)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.10.0-rc5 (2020-08-03)

 * [e9ca55ec](https://github.com/argoproj/argo-workflows/commit/e9ca55ec1cdbf37a43ee68da756ac91abb4edf73) Update manifests to v2.10.0-rc5
 * [85ddda05](https://github.com/argoproj/argo-workflows/commit/85ddda0533d7b60614bee5a93d60bbfe0209ea83) lint
 * [fb367f5e](https://github.com/argoproj/argo-workflows/commit/fb367f5e8f2faff6eeba751dc13c73336c112236) fix(controller): Fix nested maps. Fixes #3653 (#3661)
 * [2385cca5](https://github.com/argoproj/argo-workflows/commit/2385cca59396eb53c03eac5bd87611b57f2a47a2) fix: interface{} values should be expanded with '%v' (#3659)
 * [263e4bad](https://github.com/argoproj/argo-workflows/commit/263e4bad78092310ad405919b607e2ef696c8bf9) fix(server): Report v1.Status errors. Fixes #3608 (#3652)
 * [718f802b](https://github.com/argoproj/argo-workflows/commit/718f802b8ed1533da2d2a0b666d2a80b51f476b2) fix: Avoid overriding the Workflow parameter when it is merging with WorkflowTemplate parameter (#3651)
 * [9735df32](https://github.com/argoproj/argo-workflows/commit/9735df3275d456a868028b51a2386241f0d207ef) fix: Fixed flaky unit test TestFailSuspendedAndPendingNodesAfterDeadline (#3640)
 * [662d22e4](https://github.com/argoproj/argo-workflows/commit/662d22e4f10566a4ce34c3080ba38788d58fd681) fix: Don't panic on invalid template creation (#3643)
 * [854aaefa](https://github.com/argoproj/argo-workflows/commit/854aaefaa9713155a62deaaf041a36527d7f1718) fix: Fix 'malformed request: field selector' error (#3636)
 * [9d56eb29](https://github.com/argoproj/argo-workflows/commit/9d56eb29c268c7a1f73068e17edf10b6affc51a8) fix: DAG level Output Artifacts on K8S and Kubelet executor (#3624)
 * [c7512b6c](https://github.com/argoproj/argo-workflows/commit/c7512b6ce53e9b3fc5f7792a6c7c6d016aa66734) fix: Simplify the WorkflowTemplateRef field validation to support all fields in WorkflowSpec except `Templates` (#3632)

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian
 * Simon Behar

## v2.10.0-rc4 (2020-07-28)

 * [8d6dae61](https://github.com/argoproj/argo-workflows/commit/8d6dae6128074445d9bd0222c449643053568db8) Update manifests to v2.10.0-rc4
 * [a4b1dde5](https://github.com/argoproj/argo-workflows/commit/a4b1dde573754556db1e635491189960721920a8) build(cli)!: Zip binaries binaries. Closes #3576 (#3614)
 * [dea03a9c](https://github.com/argoproj/argo-workflows/commit/dea03a9c7f1016cfb0b47e1b5152cb07c111b436) fix(server): Re-establish watch on v1.Status errors. Fixes #3608 (#3609)
 * [c063f9f1](https://github.com/argoproj/argo-workflows/commit/c063f9f1c3a5d1ce0fd5fb9dd5ce3938de18edce) fix: Fix panic and provide better error message on watch endpoint (#3605)
 * [35a00498](https://github.com/argoproj/argo-workflows/commit/35a00498dcc62ebecb9dd476c90fddb2800fdeb7) fix: Argo Workflows does not honour global timeout if step/pod is not able to schedule (#3581)
 * [3879827c](https://github.com/argoproj/argo-workflows/commit/3879827cb6bfa3f9e29e81dbd3bdbf0ffeeec233) fix(controller): Fix bug in util/RecoverWorkflowNameFromSelectorString. Add error handling (#3596)
 * [5f4dec75](https://github.com/argoproj/argo-workflows/commit/5f4dec750a3be0d1ed8808d90535e90ee532f111) fix(ui): Fix multiple UI issues (#3573)
 * [e94cf8a2](https://github.com/argoproj/argo-workflows/commit/e94cf8a21cd1c97f1a415d015038145a241a7b23) fix(ui): cannot push to nil when filtering by label (#3555)
 * [61b5bd93](https://github.com/argoproj/argo-workflows/commit/61b5bd931045a2e423f1126300ab332f606cff9c) fix: Fix flakey TestRetryOmitted (#3552)
 * [d53c883b](https://github.com/argoproj/argo-workflows/commit/d53c883b713ad281b33603567a92d4dbe61a5b47) fix: Fix links in fields doc (#3539)
 * [d2bd5879](https://github.com/argoproj/argo-workflows/commit/d2bd5879f47badbd9dddef8308e20c3434caa95e) fix(artifacts): support optional input artifacts, Fixes #3491 (#3512)
 * [652956e0](https://github.com/argoproj/argo-workflows/commit/652956e04c88c347d018367c8f11398ae2ced9dc) fix: Fix when retrying Workflows with Omitted nodes (#3528)
 * [32c36d78](https://github.com/argoproj/argo-workflows/commit/32c36d785be4394b96615fbb4c716ae74177ed20) fix(controller): Backoff exponent is off by one. Fixes #3513 (#3514)
 * [75d29574](https://github.com/argoproj/argo-workflows/commit/75d2957473c4783a6db18fda08907f62375c002e) fix: String interpreted as boolean in labels (#3518)

### Contributors

 * Alex Collins
 * Jie Zhang
 * Jonny
 * Remington Breeze
 * Saravanan Balasubramanian
 * Simon Behar
 * haibingzhao

## v2.10.0-rc3 (2020-07-23)

 * [37f4f9da](https://github.com/argoproj/argo-workflows/commit/37f4f9da2b921c96f4d8919a17d4303e588e86c9) Update manifests to v2.10.0-rc3
 * [37297af7](https://github.com/argoproj/argo-workflows/commit/37297af7ddf7d9fcebfed0dff5f76d9c4cc3199f) Update manifests to v2.10.0-rc2
 * [cbf27edf](https://github.com/argoproj/argo-workflows/commit/cbf27edf17e84c86b9c969ed19f67774c27c50bd) fix: Panic on CLI Watch command (#3532)
 * [a3666482](https://github.com/argoproj/argo-workflows/commit/a366648233e5fb7e992188034e0bc0e250279feb) fix: Skip TestStorageQuotaLimit (#3566)
 * [802c18ed](https://github.com/argoproj/argo-workflows/commit/802c18ed6ea8b1e481ef2feb6d0552eac7dab67d) fix: Exceeding quota with volumeClaimTemplates (#3490)
 * [94b20124](https://github.com/argoproj/argo-workflows/commit/94b201241a88aac9a4ffa28a4fc8e4e0032e79be) ci: Make builds marginally faster. Fixes #3515 (#3519)
 * [38caab7c](https://github.com/argoproj/argo-workflows/commit/38caab7cbb5b6e474d6e1df887741019667aa1de) chore: `make lint`
 * [bbee82a0](https://github.com/argoproj/argo-workflows/commit/bbee82a086d32e721e60880139a91064c0b3abb6) fix(server): Ignore not-JWT server tokens. Fixes #3562 (#3579)
 * [f72ae881](https://github.com/argoproj/argo-workflows/commit/f72ae8813aa570eb13769de606b07dd72d991db8) fix(controller): Do not panic on nil output value. Fixes #3505 (#3509)
 * [18c7440f](https://github.com/argoproj/argo-workflows/commit/18c7440f5693410678f5f1e407d5e86dff12a4a8) build: Fix version and do not push images. Fixes #3515
 * [66d6f964](https://github.com/argoproj/argo-workflows/commit/66d6f964553e6d5f908a2fe67f694cc806cfce7f) build: Fix version and do not push images. Fixes #3515

### Contributors

 * Alex Collins
 * Saravanan Balasubramanian

## v2.10.0-rc2 (2020-07-18)

 * [4bba17f3](https://github.com/argoproj/argo-workflows/commit/4bba17f3956708c4e50b54d932b516201f368b8b) Update manifests to v2.10.0-rc2
 * [953f50e4](https://github.com/argoproj/argo-workflows/commit/953f50e498a09692d37864650d4ced4af8a6693e) build: Fix version and do not push images. Fixes #3515
 * [616c79df](https://github.com/argoproj/argo-workflows/commit/616c79df09c435fa7659bf7e5194529d948ee93b) Update manifests to v2.10.0-rc1

### Contributors

 * Alex Collins

## v2.10.0-rc1 (2020-07-17)


### Contributors


## v2.10.0 (2020-08-18)

 * [195c6d83](https://github.com/argoproj/argo-workflows/commit/195c6d8310a70b07043b9df5c988d5a62dafe00d) Update manifests to v2.10.0
 * [08117f0c](https://github.com/argoproj/argo-workflows/commit/08117f0cd1206647644f1f14580046268d1c8639) fix: Increase the requeue duration on checkForbiddenErrorAndResubmitAllowed (#3794)
 * [5ea2ed0d](https://github.com/argoproj/argo-workflows/commit/5ea2ed0dbdb4003fc457b7cd76cf5cec9edc6799) fix(server): Trucate creator label at 63 chars. Fixes #3756 (#3758)
 * [267da535](https://github.com/argoproj/argo-workflows/commit/267da535b66ed1dab8bcc90410260b7cf4b80e2c) Update manifests to v2.10.0-rc7
 * [baeb0fed](https://github.com/argoproj/argo-workflows/commit/baeb0fed2b3ab53f35297a764f983059600d4b44) fix: Revert merge error
 * [66bae22f](https://github.com/argoproj/argo-workflows/commit/66bae22f147cd248f1a88f913eaeac13ec873bcd) fix(executor): Add retry on pods watch to handle timeout. (#3675)
 * [971f1153](https://github.com/argoproj/argo-workflows/commit/971f115373c8f01f0e21991b14fc3b27876f3cbf) removed unused test-report files
 * [8c0b9f0a](https://github.com/argoproj/argo-workflows/commit/8c0b9f0a52922485a1bdf6a8954cdc09060dbc29) fix: Couldn't Terminate/Stop the ResourceTemplate Workflow (#3679)
 * [a04d72f9](https://github.com/argoproj/argo-workflows/commit/a04d72f95a433eaa37202418809e1877eb167a1a) fix(controller): Tolerate PDB delete race. Fixes #3706 (#3717)
 * [a7635763](https://github.com/argoproj/argo-workflows/commit/a76357638598174812bb749ea539ca4061284d89) fix: Fix bug with 'argo delete --older' (#3699)
 * [fe8129cf](https://github.com/argoproj/argo-workflows/commit/fe8129cfc766f875985f0f09d37dc351a1e5f933) fix(controller): Carry-over labels for re-submitted workflows. Fixes #3622 (#3638)
 * [e12d26e5](https://github.com/argoproj/argo-workflows/commit/e12d26e52a42d91ec4d2dbc3d188cf3b1a623a26) fix(controller): Treat TooManyError same as Forbidden (i.e. try again). Fixes #3606 (#3607)
 * [9a5febec](https://github.com/argoproj/argo-workflows/commit/9a5febec11d231ed1cd5e085a841069b9106dafe) fix: Ensure target task's onExit handlers are run (#3716)
 * [c3a58e36](https://github.com/argoproj/argo-workflows/commit/c3a58e36d18e3c3cbb7bffcd3a6ae4c5c08a66ea) fix: Enforce metric Help must be the same for each metric Name (#3613)
 * [cb3536f9](https://github.com/argoproj/argo-workflows/commit/cb3536f9d1dd64258c1c3d737bb115bdab923e58) Update manifests to v2.10.0-rc6
 * [6e004ace](https://github.com/argoproj/argo-workflows/commit/6e004ace2710e17ed2a282c6570a97b567946e58) lint
 * [b31fc1f8](https://github.com/argoproj/argo-workflows/commit/b31fc1f8612a93c907b375de2e9a3c9326dca34b) fix(controller): Adds ALL_POD_CHANGES_SIGNIFICANT (#3689)
 * [0b7cd5b3](https://github.com/argoproj/argo-workflows/commit/0b7cd5b3181eece7636b99d4761e96c61c17c453) fix: Fixed workflow queue duration if PVC creation is forbidden (#3691)
 * [03b84162](https://github.com/argoproj/argo-workflows/commit/03b8416271002bfc88c11dd27d86fa08f95b33e9) fix: Re-introduce 1 second sleep to reconcile informer (#3684)
 * [e9ca55ec](https://github.com/argoproj/argo-workflows/commit/e9ca55ec1cdbf37a43ee68da756ac91abb4edf73) Update manifests to v2.10.0-rc5
 * [85ddda05](https://github.com/argoproj/argo-workflows/commit/85ddda0533d7b60614bee5a93d60bbfe0209ea83) lint
 * [fb367f5e](https://github.com/argoproj/argo-workflows/commit/fb367f5e8f2faff6eeba751dc13c73336c112236) fix(controller): Fix nested maps. Fixes #3653 (#3661)
 * [2385cca5](https://github.com/argoproj/argo-workflows/commit/2385cca59396eb53c03eac5bd87611b57f2a47a2) fix: interface{} values should be expanded with '%v' (#3659)
 * [263e4bad](https://github.com/argoproj/argo-workflows/commit/263e4bad78092310ad405919b607e2ef696c8bf9) fix(server): Report v1.Status errors. Fixes #3608 (#3652)
 * [718f802b](https://github.com/argoproj/argo-workflows/commit/718f802b8ed1533da2d2a0b666d2a80b51f476b2) fix: Avoid overriding the Workflow parameter when it is merging with WorkflowTemplate parameter (#3651)
 * [9735df32](https://github.com/argoproj/argo-workflows/commit/9735df3275d456a868028b51a2386241f0d207ef) fix: Fixed flaky unit test TestFailSuspendedAndPendingNodesAfterDeadline (#3640)
 * [662d22e4](https://github.com/argoproj/argo-workflows/commit/662d22e4f10566a4ce34c3080ba38788d58fd681) fix: Don't panic on invalid template creation (#3643)
 * [854aaefa](https://github.com/argoproj/argo-workflows/commit/854aaefaa9713155a62deaaf041a36527d7f1718) fix: Fix 'malformed request: field selector' error (#3636)
 * [9d56eb29](https://github.com/argoproj/argo-workflows/commit/9d56eb29c268c7a1f73068e17edf10b6affc51a8) fix: DAG level Output Artifacts on K8S and Kubelet executor (#3624)
 * [c7512b6c](https://github.com/argoproj/argo-workflows/commit/c7512b6ce53e9b3fc5f7792a6c7c6d016aa66734) fix: Simplify the WorkflowTemplateRef field validation to support all fields in WorkflowSpec except `Templates` (#3632)
 * [8d6dae61](https://github.com/argoproj/argo-workflows/commit/8d6dae6128074445d9bd0222c449643053568db8) Update manifests to v2.10.0-rc4
 * [a4b1dde5](https://github.com/argoproj/argo-workflows/commit/a4b1dde573754556db1e635491189960721920a8) build(cli)!: Zip binaries binaries. Closes #3576 (#3614)
 * [dea03a9c](https://github.com/argoproj/argo-workflows/commit/dea03a9c7f1016cfb0b47e1b5152cb07c111b436) fix(server): Re-establish watch on v1.Status errors. Fixes #3608 (#3609)
 * [c063f9f1](https://github.com/argoproj/argo-workflows/commit/c063f9f1c3a5d1ce0fd5fb9dd5ce3938de18edce) fix: Fix panic and provide better error message on watch endpoint (#3605)
 * [35a00498](https://github.com/argoproj/argo-workflows/commit/35a00498dcc62ebecb9dd476c90fddb2800fdeb7) fix: Argo Workflows does not honour global timeout if step/pod is not able to schedule (#3581)
 * [3879827c](https://github.com/argoproj/argo-workflows/commit/3879827cb6bfa3f9e29e81dbd3bdbf0ffeeec233) fix(controller): Fix bug in util/RecoverWorkflowNameFromSelectorString. Add error handling (#3596)
 * [5f4dec75](https://github.com/argoproj/argo-workflows/commit/5f4dec750a3be0d1ed8808d90535e90ee532f111) fix(ui): Fix multiple UI issues (#3573)
 * [e94cf8a2](https://github.com/argoproj/argo-workflows/commit/e94cf8a21cd1c97f1a415d015038145a241a7b23) fix(ui): cannot push to nil when filtering by label (#3555)
 * [61b5bd93](https://github.com/argoproj/argo-workflows/commit/61b5bd931045a2e423f1126300ab332f606cff9c) fix: Fix flakey TestRetryOmitted (#3552)
 * [d53c883b](https://github.com/argoproj/argo-workflows/commit/d53c883b713ad281b33603567a92d4dbe61a5b47) fix: Fix links in fields doc (#3539)
 * [d2bd5879](https://github.com/argoproj/argo-workflows/commit/d2bd5879f47badbd9dddef8308e20c3434caa95e) fix(artifacts): support optional input artifacts, Fixes #3491 (#3512)
 * [652956e0](https://github.com/argoproj/argo-workflows/commit/652956e04c88c347d018367c8f11398ae2ced9dc) fix: Fix when retrying Workflows with Omitted nodes (#3528)
 * [32c36d78](https://github.com/argoproj/argo-workflows/commit/32c36d785be4394b96615fbb4c716ae74177ed20) fix(controller): Backoff exponent is off by one. Fixes #3513 (#3514)
 * [75d29574](https://github.com/argoproj/argo-workflows/commit/75d2957473c4783a6db18fda08907f62375c002e) fix: String interpreted as boolean in labels (#3518)
 * [37f4f9da](https://github.com/argoproj/argo-workflows/commit/37f4f9da2b921c96f4d8919a17d4303e588e86c9) Update manifests to v2.10.0-rc3
 * [37297af7](https://github.com/argoproj/argo-workflows/commit/37297af7ddf7d9fcebfed0dff5f76d9c4cc3199f) Update manifests to v2.10.0-rc2
 * [cbf27edf](https://github.com/argoproj/argo-workflows/commit/cbf27edf17e84c86b9c969ed19f67774c27c50bd) fix: Panic on CLI Watch command (#3532)
 * [a3666482](https://github.com/argoproj/argo-workflows/commit/a366648233e5fb7e992188034e0bc0e250279feb) fix: Skip TestStorageQuotaLimit (#3566)
 * [802c18ed](https://github.com/argoproj/argo-workflows/commit/802c18ed6ea8b1e481ef2feb6d0552eac7dab67d) fix: Exceeding quota with volumeClaimTemplates (#3490)
 * [94b20124](https://github.com/argoproj/argo-workflows/commit/94b201241a88aac9a4ffa28a4fc8e4e0032e79be) ci: Make builds marginally faster. Fixes #3515 (#3519)
 * [38caab7c](https://github.com/argoproj/argo-workflows/commit/38caab7cbb5b6e474d6e1df887741019667aa1de) chore: `make lint`
 * [bbee82a0](https://github.com/argoproj/argo-workflows/commit/bbee82a086d32e721e60880139a91064c0b3abb6) fix(server): Ignore not-JWT server tokens. Fixes #3562 (#3579)
 * [f72ae881](https://github.com/argoproj/argo-workflows/commit/f72ae8813aa570eb13769de606b07dd72d991db8) fix(controller): Do not panic on nil output value. Fixes #3505 (#3509)
 * [18c7440f](https://github.com/argoproj/argo-workflows/commit/18c7440f5693410678f5f1e407d5e86dff12a4a8) build: Fix version and do not push images. Fixes #3515
 * [66d6f964](https://github.com/argoproj/argo-workflows/commit/66d6f964553e6d5f908a2fe67f694cc806cfce7f) build: Fix version and do not push images. Fixes #3515
 * [4bba17f3](https://github.com/argoproj/argo-workflows/commit/4bba17f3956708c4e50b54d932b516201f368b8b) Update manifests to v2.10.0-rc2
 * [953f50e4](https://github.com/argoproj/argo-workflows/commit/953f50e498a09692d37864650d4ced4af8a6693e) build: Fix version and do not push images. Fixes #3515
 * [616c79df](https://github.com/argoproj/argo-workflows/commit/616c79df09c435fa7659bf7e5194529d948ee93b) Update manifests to v2.10.0-rc1
 * [19e700a3](https://github.com/argoproj/argo-workflows/commit/19e700a3388552d9440ae75dd259efcbeb0a3657) fix(cli): Check mutual exclusivity for argo CLI flags (#3493)
 * [7d45ff7f](https://github.com/argoproj/argo-workflows/commit/7d45ff7f014d011ef895b9c808da781000ea32a5) fix: Panic on releaseAllWorkflowLocks if Object is not Unstructured type (#3504)
 * [1b68a5a1](https://github.com/argoproj/argo-workflows/commit/1b68a5a15af12fb0866f4d5a4dcd9fb5da3f2ab4) fix: ui/package.json & ui/yarn.lock to reduce vulnerabilities (#3501)
 * [7f262fd8](https://github.com/argoproj/argo-workflows/commit/7f262fd81bae1f8b9bc7707d8bf02f10174cc87d) fix(cli)!: Enable CLI to work without kube config. Closes #3383, #2793 (#3385)
 * [2976e7ac](https://github.com/argoproj/argo-workflows/commit/2976e7ac517ec680b1077e64aa499d92c5d39a0d) build: Clear cmd docs before generating them (#3499)
 * [27528ba3](https://github.com/argoproj/argo-workflows/commit/27528ba34538b764db9254d41761a4edeba6694c) feat: Support completions for more resources (#3494)
 * [5bd2ad7a](https://github.com/argoproj/argo-workflows/commit/5bd2ad7a9d0ad5437fb7d1b7955e0b8e0c9b52ca) fix: Merge WorkflowTemplateRef with defaults workflow spec (#3480)
 * [e244337b](https://github.com/argoproj/argo-workflows/commit/e244337be239e462086a2bcad46f71ffb57a7a62) chore: Added examples for exit handler for step and dag level (#3495)
 * [bcb32547](https://github.com/argoproj/argo-workflows/commit/bcb325476ba49877df6b2dd9622bc64dfe9ad5f4) build: Use `git rev-parse` to accomodate older gits (#3497)
 * [3eb6e2f9](https://github.com/argoproj/argo-workflows/commit/3eb6e2f90c700070c4f1d2730a727aea7746c776) docs: Add link to GitHub Actions in the badge (#3492)
 * [69179e72](https://github.com/argoproj/argo-workflows/commit/69179e72c0872cde9131cc9d68192d5c472d64c9) fix: link to server auth mode docs, adds Tulip as official user (#3486)
 * [7a8e2b34](https://github.com/argoproj/argo-workflows/commit/7a8e2b34631aa8ae7037059deb5c2108a2ca2cb4) docs: Add comments to NodePhase definition. Closes #1117. (#3467)
 * [24d1e529](https://github.com/argoproj/argo-workflows/commit/24d1e52996d8af27909cf4477a5a14950a9a6da7) build: Simplify builds (#3478)
 * [acf56f9f](https://github.com/argoproj/argo-workflows/commit/acf56f9f0d2da426eab9cacc03b7ebadb4aa9ea3) feat(server): Label workflows with creator. Closes #2437 (#3440)
 * [3b8ac065](https://github.com/argoproj/argo-workflows/commit/3b8ac065a1db8ebe629d7cf02c1a8585b34ea2b7) fix: Pass resolved arguments to onExit handler (#3477)
 * [58097a9e](https://github.com/argoproj/argo-workflows/commit/58097a9ec2a9203dfebce9c75fdddc84ac48885e) docs: Add controller-level metrics (#3464)
 * [f6f1844b](https://github.com/argoproj/argo-workflows/commit/f6f1844b73d4e643614f575075401946b9aa7a7c) feat: Attempt to resolve nested tags (#3339)
 * [48e15d6f](https://github.com/argoproj/argo-workflows/commit/48e15d6fce2f980ae5dd5b5d2ff405f496b8f644) feat(cli): List only resubmitted workflows option (#3357)
 * [25e9c0cd](https://github.com/argoproj/argo-workflows/commit/25e9c0cdf73a3c9fa712fc3b544f1f8f33980515) docs, quick-start. Use http, not https for link (#3476)
 * [7a2d7642](https://github.com/argoproj/argo-workflows/commit/7a2d76427da0ae6440f91adbb2f97e62b28355e6) fix: Metric emission with retryStrategy (#3470)
 * [f5876e04](https://github.com/argoproj/argo-workflows/commit/f5876e041a2d87c8d48983751d2c3b4959fb1d93) test(controller): Ensure resubmitted workflows have correct labels (#3473)
 * [aa92ec03](https://github.com/argoproj/argo-workflows/commit/aa92ec03885b2c58c537b33161809f9966faf968) fix(controller): Correct fail workflow when pod is deleted with --force. Fixes #3097 (#3469)
 * [a1945d63](https://github.com/argoproj/argo-workflows/commit/a1945d635b24963af7f52bd73b19a7da52d647e3) fix(controller): Respect the volumes of a workflowTemplateRef. Fixes … (#3451)
 * [847ba530](https://github.com/argoproj/argo-workflows/commit/847ba5305273a16a65333c278e705dc157b9c723) test(controller): Add memoization tests. See #3214 (#3455) (#3466)
 * [f5183aed](https://github.com/argoproj/argo-workflows/commit/f5183aed8bb42b5c267b838c7b31b0f38fec28e8) docs: Fix CLI docs (#3465)
 * [1e42813a](https://github.com/argoproj/argo-workflows/commit/1e42813aaaaee55b9e4483338f7a8554ba9f9eab) test(controller): Add memoization tests. See #3214 (#3455)
 * [abe768c4](https://github.com/argoproj/argo-workflows/commit/abe768c4ba5433fe72f9e6d5a1dde09d37d4d20d) feat(cli): Allow to view previously terminated container logs (#3423)
 * [7581025f](https://github.com/argoproj/argo-workflows/commit/7581025ffac0da6a4c9b125dac3173d0c84aef4f) fix: Allow ints for sequence start/end/count. Fixes #3420 (#3425)
 * [b82f900a](https://github.com/argoproj/argo-workflows/commit/b82f900ae5e446d14a9899302c143c8e32447eab) Fixed typos (#3456)
 * [23760119](https://github.com/argoproj/argo-workflows/commit/23760119d4664f0825536d368b65cdde356e0ff3) feat: Workflow Semaphore Support (#3141)
 * [81cba832](https://github.com/argoproj/argo-workflows/commit/81cba832ed1d4f5b116dc9e43f1f3ad79c190c44) feat: Support WorkflowMetadata in WorkflowTemplate and ClusterWorkflowTemplate (#3364)
 * [568c032b](https://github.com/argoproj/argo-workflows/commit/568c032b3b86c39b39ae38d772b33bc1cbb757de) chore: update aws-sdk-go version (#3376)
 * [bd27d9f3](https://github.com/argoproj/argo-workflows/commit/bd27d9f3216bae609de2cb482a89af3783f0d132) chore: Upgrade node-sass (#3450)
 * [b1e601e5](https://github.com/argoproj/argo-workflows/commit/b1e601e586d376ef3b022acf684cf5de648dc3dc) docs: typo in argo stop --help (#3439)
 * [308c7083](https://github.com/argoproj/argo-workflows/commit/308c7083bded1b6a1fb91bcd963e1e9b8d0b4152) fix(controller): Prevent panic on nil node. Fixes #3436 (#3437)
 * [8ab06f53](https://github.com/argoproj/argo-workflows/commit/8ab06f532b24944e5e9c3ed33c4adc249203cad4) feat(controller): Add log message count as metrics. (#3362)
 * [5d0c436d](https://github.com/argoproj/argo-workflows/commit/5d0c436d3d148d70fd766fa50f97be6b2fef0d45) chore: Fix GitHub Actions Docker Image build  (#3442)
 * [e54b4ab5](https://github.com/argoproj/argo-workflows/commit/e54b4ab5cfaddec4e5f3e3cdecd6ea931501f6fb) docs: Add Sohu as official Argo user (#3430)
 * [ee6c8760](https://github.com/argoproj/argo-workflows/commit/ee6c8760e3d46dfdab0f8d3a63dbf1995322ad4b) fix: Ensure task dependencies run after onExit handler is fulfilled (#3435)
 * [6dc04b39](https://github.com/argoproj/argo-workflows/commit/6dc04b39c7986046c2be1535d2a933e4cba25e03) chore: Use GitHub Actions to build Docker Images to allow publishing Windows Images (#3291)
 * [05b3590b](https://github.com/argoproj/argo-workflows/commit/05b3590b5dc70963700b4a7a5cef4afd76b4943d) feat(controller): Add support for Docker workflow executor for Windows nodes (#3301)
 * [676868f3](https://github.com/argoproj/argo-workflows/commit/676868f31da1bce361e89bebfa1eea81471784ac) fix(docs): Update kubectl proxy URL (#3433)
 * [3507c3e6](https://github.com/argoproj/argo-workflows/commit/3507c3e6e8e9c420a6028a43b930a3ef6b221705) docs: Make https://argoproj.github.io/argo/  (#3369)
 * [733e95f7](https://github.com/argoproj/argo-workflows/commit/733e95f742ff14fb7c303d8b1dbf30403e9e8983) fix: Add struct-wide RWMutext to metrics (#3421)
 * [0463f241](https://github.com/argoproj/argo-workflows/commit/0463f24165e360344b5ff743915d16a12fef0ba0) fix: Use a unique queue to visit nodes (#3418)
 * [eddcac63](https://github.com/argoproj/argo-workflows/commit/eddcac6398e674aa24b59aea2e449492cf2c0c02) fix: Script steps fail with exceededQuota (#3407)
 * [c631a545](https://github.com/argoproj/argo-workflows/commit/c631a545e824682652569e49eb764844a7f5cb05) feat(ui): Add Swagger UI (#3358)
 * [910f636d](https://github.com/argoproj/argo-workflows/commit/910f636dcfad66c999aa859e11a31a9a772ccc79) fix: No panic on watch. Fixes #3411 (#3426)
 * [b4da1bcc](https://github.com/argoproj/argo-workflows/commit/b4da1bccc7f961200b8fe8551e4b286d1d5d5a9f) fix(sso): Remove unused `groups` claim. Fixes #3411 (#3427)
 * [330d4a0a](https://github.com/argoproj/argo-workflows/commit/330d4a0a2085b986855f9d3f4c5e27fbbe261ca9) fix: panic on wait command if event is null (#3424)
 * [7c439424](https://github.com/argoproj/argo-workflows/commit/7c4394245437d36245a4c9246a51ceb92edeaf42) docs: Include timezone name reference (#3414)
 * [03cbb8cf](https://github.com/argoproj/argo-workflows/commit/03cbb8cf2c75f5b241ae543259ea9db02e9339fd) fix(ui): Render DAG with exit node (#3408)
 * [3d50f985](https://github.com/argoproj/argo-workflows/commit/3d50f9852b481692235a3f075c4c0966e6404104) feat: Expose certain queue metrics (#3371)
 * [c7b35e05](https://github.com/argoproj/argo-workflows/commit/c7b35e054e3eee38f750c0eaf4a5431a56f80c49) fix: Ensure non-leaf DAG tasks have their onExit handler's run (#3403)
 * [70111600](https://github.com/argoproj/argo-workflows/commit/70111600d464bd7dd99014aa88b5f2cbab64a573) fix: Fix concurrency issues with metrics (#3401)
 * [d307f96f](https://github.com/argoproj/argo-workflows/commit/d307f96f2307da4897685b96ef54251b064de239) docs: Update config example to include useSDKCreds (#3398)
 * [637d50bc](https://github.com/argoproj/argo-workflows/commit/637d50bc132c346885caa4e70eee47ad5c96648e) chore: maybe -> may be (#3392)
 * [e70a8863](https://github.com/argoproj/argo-workflows/commit/e70a8863582e6fab7e2c5ea7c95a7fc0b4ab374d) chore: Added CWFT WorkflowTemplateRef example (#3386)
 * [bc4faf5f](https://github.com/argoproj/argo-workflows/commit/bc4faf5f739e9172b7968e198dc595f27d506f7b) fix: Fix bug parsing parmeters (#3372)
 * [4934ad22](https://github.com/argoproj/argo-workflows/commit/4934ad227f043a5554c9a4f717f09f70d2c18cbf) fix: Running pods are garaged in PodGC onSuccess
 * [0541cfda](https://github.com/argoproj/argo-workflows/commit/0541cfda611a656ab16dbfcd7bed858b7c8b2f3c) chore(ui): Remove unused interfaces for artifacts (#3377)
 * [20382cab](https://github.com/argoproj/argo-workflows/commit/20382cab7bbbbd5646a3dbfac6ee18586a6eada5) docs: Fix incorrect example of global parameter (#3375)
 * [1db93c06](https://github.com/argoproj/argo-workflows/commit/1db93c062c4f7e417bf74afe253e9a44e5381802) perf: Optimize time-based filtering on large number of workflows (#3340)
 * [2ab9495f](https://github.com/argoproj/argo-workflows/commit/2ab9495f0f3d944243d845411bafe7ebe496642b) fix: Don't double-count metric events (#3350)
 * [7bd3e720](https://github.com/argoproj/argo-workflows/commit/7bd3e7209018d0d7716ca0dbd0ffb1863165892d) fix(ui): Confirmation of workflow actions (#3370)
 * [488790b2](https://github.com/argoproj/argo-workflows/commit/488790b247191dd22babadd9592efae11f4fd245) Wellcome is using Argo in our Data Labs division (#3365)
 * [63e71192](https://github.com/argoproj/argo-workflows/commit/63e71192852138685d68156a0f6b1133ecfdaf74) chore: Remove unused code (#3367)
 * [a64ceb03](https://github.com/argoproj/argo-workflows/commit/a64ceb03f165513e30e5c9614d1bb64273219140) build: Enable Stale Bot (#3363)
 * [e4b08abb](https://github.com/argoproj/argo-workflows/commit/e4b08abbcfe6f3886e0cd28e8ea8c1860ef8c9e1) fix(server): Remove `context cancelled` error. Fixes #3073 (#3359)
 * [74ba5162](https://github.com/argoproj/argo-workflows/commit/74ba516220423cae5960b7dd51c4a8d5a37012b5) fix: Fix UI bug in DAGs (#3368)
 * [5e60decf](https://github.com/argoproj/argo-workflows/commit/5e60decf96e85a4077cd70d1d4e8da299d1d963d) feat(crds)!: Adds CRD generation and enhanced UI resource editor. Closes #859 (#3075)
 * [c2347f35](https://github.com/argoproj/argo-workflows/commit/c2347f3542d48467e8a0bede67db17ecce890f56) chore: Simplify deps by removing YAML (#3353)
 * [1323f9f4](https://github.com/argoproj/argo-workflows/commit/1323f9f418a407d7cbb92e7bb67e00faefe17e51) test: Add e2e tags (#3354)
 * [731a1b4a](https://github.com/argoproj/argo-workflows/commit/731a1b4a670078b8ba8e2f36bdd433afe22f2631) fix(controller): Allow events to be sent to non-argo namespace. Fixes #3342 (#3345)
 * [916e0db2](https://github.com/argoproj/argo-workflows/commit/916e0db25880cef3058e4c3c3f6d118e14312be1) Adding InVision to Users (#3352)
 * [6caf10fa](https://github.com/argoproj/argo-workflows/commit/6caf10fad7b116f9e3a6aaee4eb02243e37f2779) fix: Ensure child pods respect maxDuration (#3280)
 * [8f4945f5](https://github.com/argoproj/argo-workflows/commit/8f4945f5e6f7a6d503f400079b607715151a2a41) docs: Field fix (ParallelSteps -> WorkflowStep) (#3338)
 * [2b4b7340](https://github.com/argoproj/argo-workflows/commit/2b4b7340a6afb8317e27e3d58c46fba3c3db8ff0) fix: Remove broken SSO from quick-starts (#3327)
 * [26570fd5](https://github.com/argoproj/argo-workflows/commit/26570fd51ec2eebe86cd0f3bc05ab43272f957c5) fix(controller)!: Support nested items. Fixes #3288 (#3290)
 * [c3d85716](https://github.com/argoproj/argo-workflows/commit/c3d85716420048dd0567ccc5cda894a9717598ae) chore: Avoid variable name collision with imported package name (#3335)
 * [ca822af0](https://github.com/argoproj/argo-workflows/commit/ca822af0c4353bb30a51f0a4edfccdd4226c7043) build: Fix path to go-to-protobuf binary (#3308)
 * [769a964f](https://github.com/argoproj/argo-workflows/commit/769a964fcf51f58c76f2d4900c736f4dd945bd7f) feat(controller): Label workflows with their source workflow template (#3328)
 * [0785be24](https://github.com/argoproj/argo-workflows/commit/0785be24caaf93d62f5b77b2ee142a0691992b86) fix(ui): runtime error from null savedOptions props (#3330)
 * [200be0e1](https://github.com/argoproj/argo-workflows/commit/200be0e1e34f9cf6689e9739e3e4aea7f5bf7fde) feat: Save pagination limit and selected phases/labels to local storage (#3322)
 * [b5ed90fe](https://github.com/argoproj/argo-workflows/commit/b5ed90fe8611a10df7982e3fb2e6670400acf2d2) feat: Allow to change priority when resubmitting workflows (#3293)
 * [60c86c84](https://github.com/argoproj/argo-workflows/commit/60c86c84c60ac38c5a876d8df5362b5896700d73) fix(ui): Compiler error from workflows toolbar (#3317)
 * [3fe6ecc4](https://github.com/argoproj/argo-workflows/commit/3fe6ecc424fe1474b2ce765e47f1dc69ec9ef98e) docs: Document access token creation and usage (#3316)
 * [ab3c081e](https://github.com/argoproj/argo-workflows/commit/ab3c081e310835f7f2e7a3424042944adde39afd) docs: Rename Ant Financial to Ant Group (#3304)
 * [baad42ea](https://github.com/argoproj/argo-workflows/commit/baad42ea8fed83b2158721766e518b203664ebe1) feat(ui): Add ability to select multiple workflows from list and perform actions on them. Fixes #3185 (#3234)
 * [b6118939](https://github.com/argoproj/argo-workflows/commit/b6118939bf0948e856bb20955f6911743106af4d) fix(controller): Fix panic logging. (#3315)
 * [633ea71e](https://github.com/argoproj/argo-workflows/commit/633ea71ebf624530c75b1f9aeb713a92510cf62a) build: Pin `goimports` to working version (#3311)
 * [436c1259](https://github.com/argoproj/argo-workflows/commit/436c12590d80010e300a63be3acb3bd24ac3bf93) ci: Remove CircleCI (#3302)
 * [8e340229](https://github.com/argoproj/argo-workflows/commit/8e340229cfd3fb976b1261dbf32d038bfd2f7706) build: Remove generated Swagger files. (#3297)
 * [e021d7c5](https://github.com/argoproj/argo-workflows/commit/e021d7c512f01721e2f25d39836829752226c290) Clean up unused constants (#3298)
 * [48d86f03](https://github.com/argoproj/argo-workflows/commit/48d86f03ce9ac49f5099c46dd7995305eb59eb11) build: Upload E2E diagnostics after failure (#3294)
 * [8b12f433](https://github.com/argoproj/argo-workflows/commit/8b12f433a2e32cc69714ee456ee0d83e904ff31c) feat(cli): Add --logs to `argo [submit|resubmit|retry]. Closes #3183 (#3279)
 * [07b450e8](https://github.com/argoproj/argo-workflows/commit/07b450e8134e1afe0b58c45b21dc0c13d91ecdb5) fix: Reapply Update if CronWorkflow resource changed (#3272)
 * [8af01491](https://github.com/argoproj/argo-workflows/commit/8af014911901678ee24bea9b2ab652fb0af5bc48) docs: ArchiveLabelSelector document (#3284)
 * [38c908a2](https://github.com/argoproj/argo-workflows/commit/38c908a272e8a59b2843ad5514c6334ba1c7a693) docs: Add example for handling large output resutls (#3276)
 * [d44d264c](https://github.com/argoproj/argo-workflows/commit/d44d264c72649c540204ccb54e9a57550f48d1fc) Fixes validation of overridden ref template parameters. (#3286)
 * [62e54fb6](https://github.com/argoproj/argo-workflows/commit/62e54fb68778030245bed87f0675694ef3c58b57) fix: Fix delete --complete (#3278)
 * [a3c379bb](https://github.com/argoproj/argo-workflows/commit/a3c379bb5df171d635a200b9dec7a9ca89c3295d) docs: Updated WorkflowTemplateRef  on WFT and CWFT (#3137)
 * [824de95b](https://github.com/argoproj/argo-workflows/commit/824de95bfb2de0e325f92c0544f42267242486e4) fix(git): Fixes Git when using auth or fetch. Fixes #2343 (#3248)
 * [018fcc23](https://github.com/argoproj/argo-workflows/commit/018fcc23dc9fad051d15db2f9a83c2710d50c828) Update releasing.md (#3283)
 * [acee573b](https://github.com/argoproj/argo-workflows/commit/acee573b88bf96160b69d18bcc8031caf119c647) docs: Update CI Badges (#3282)
 * [9eb182c0](https://github.com/argoproj/argo-workflows/commit/9eb182c04957f2ca587ff1de84b79fc274f91788) build: Allow to change k8s namespace for installation (#3281)
 * [2bcfafb5](https://github.com/argoproj/argo-workflows/commit/2bcfafb56230194fd2d23adcfa5a1294066ec91e) fix: Add {{workflow.status}} to workflow-metrics (#3271)
 * [e6aab605](https://github.com/argoproj/argo-workflows/commit/e6aab605122356a10cb21df3a08e1ddeac6d2593) fix(jqFilter)!: remove extra quotes around output parameter value (#3251)
 * [f4580163](https://github.com/argoproj/argo-workflows/commit/f4580163f4187f798f93b8d778415e8bec001dda) fix(ui): Allow render of templates without entrypoint. Fixes #2891 (#3274)
 * [f30c05c7](https://github.com/argoproj/argo-workflows/commit/f30c05c74f598b6400b66bb20a752d78eca05e45) build: Add warning to ensure 'v' is present on release versions (#3273)
 * [d1cb1992](https://github.com/argoproj/argo-workflows/commit/d1cb1992cd22e9f69894532f214fa0e00312ff36) fixed archiveLabelSelector nil (#3270)
 * [c7e4c180](https://github.com/argoproj/argo-workflows/commit/c7e4c1808cf097857b8ee89d326ef9f32384fc1b) fix(ui): Update workflow drawer with new duration format (#3256)
 * [f2381a54](https://github.com/argoproj/argo-workflows/commit/f2381a5448e9d49a7b6ed0c9583ac8cf9b257938) fix(controller): More structured logging. Fixes #3260 (#3262)
 * [acba084a](https://github.com/argoproj/argo-workflows/commit/acba084abb01b967c239952d49e8e3d7775cbf2c) fix: Avoid unnecessary nil check for annotations of resubmitted workflow (#3268)
 * [55e13705](https://github.com/argoproj/argo-workflows/commit/55e13705ae57f86ca6c5846eb5de3e80370bc1d4) feat: Append previous workflow name as label to resubmitted workflow (#3261)
 * [2dae7244](https://github.com/argoproj/argo-workflows/commit/2dae724496a96ce2e0993daea0a3b6a473f784da) feat: Add mode to require Workflows to use workflowTemplateRef (#3149)
 * [56694abe](https://github.com/argoproj/argo-workflows/commit/56694abe27267c1cb855064b44bc7c32d61ca66c) Fixed onexit on workflowtempalteRef (#3263)
 * [54dd72c2](https://github.com/argoproj/argo-workflows/commit/54dd72c2439b5a6ef389eab4cb39bd412db9fd42) update mysql yaml port (#3258)
 * [fb502632](https://github.com/argoproj/argo-workflows/commit/fb502632419409e528e23f1ef70e7f610812d175) feat: Configure ArchiveLabelSelector for Workflow Archive (#3249)
 * [5467c899](https://github.com/argoproj/argo-workflows/commit/5467c8995e07e5501d685384e44585fc1b02c6b8) fix(controller): set pod finish timestamp when it is deleted (#3230)
 * [04bc5492](https://github.com/argoproj/argo-workflows/commit/04bc5492d582d45633a4a18ec691a10d913a73a3) build: Disable Circle CI and Sonar (#3253)
 * [23ca07a7](https://github.com/argoproj/argo-workflows/commit/23ca07a790714ad8c97ecab71ffa439843a7ad6c) chore: Covered steps.<STEPNAME>.outputs.parameters in variables document (#3245)
 * [4bd33c6c](https://github.com/argoproj/argo-workflows/commit/4bd33c6c6ce6dcb9f0c85dab40f162608d5f67a6) chore(cli): Add examples of @latest alias for relevant commands. Fixes #3225 (#3242)
 * [17108df1](https://github.com/argoproj/argo-workflows/commit/17108df1cea937f49f099ec26b7a25bd376b16a5) fix: Ensure subscription is closed in log viewer (#3247)
 * [495dc89b](https://github.com/argoproj/argo-workflows/commit/495dc89b5cfb2419b0438c4a53cfb3b13cb5785a) docs: Correct available fields in {{workflow.failures}} (#3238)
 * [4db1c4c8](https://github.com/argoproj/argo-workflows/commit/4db1c4c8495d0b8e13c718207175273fe98555a2) fix: Support the TTLStrategy for WorkflowTemplateRef (#3239)
 * [47f50693](https://github.com/argoproj/argo-workflows/commit/47f5069376f3c61b09ff02ff5729e5c3e6e58e45) feat(logging): Made more controller err/warn logging structured (#3240)
 * [c25e2880](https://github.com/argoproj/argo-workflows/commit/c25e28809863435d718d7e5ab303591d8039c724) build: Migrate to Github Actions (#3233)
 * [ef159f9a](https://github.com/argoproj/argo-workflows/commit/ef159f9ad6be552de1abf58c3dc4dc6911c49733) feat: Tick CLI Workflow watch even if there are no new events (#3219)
 * [ff1627b7](https://github.com/argoproj/argo-workflows/commit/ff1627b71789c42f604c0f83a9a3328d7e6b8248) fix(events): Adds config flag. Reduce number of dupe events emitted. (#3205)
 * [eae8f681](https://github.com/argoproj/argo-workflows/commit/eae8f68144acaf5c2ec0145ef0d136097cca7fcc) feat: Validate CronWorkflows before execution (#3223)
 * [4470a8a2](https://github.com/argoproj/argo-workflows/commit/4470a8a29bca9e16ac7e5d7d8c8a2310d0200efa) fix(ui/server): Fix broken label filter functionality on UI due to bug on server. Fix #3226 (#3228)
 * [e5e6456b](https://github.com/argoproj/argo-workflows/commit/e5e6456be37b52856205c4f7600a05ffef6daab1) feat(cli): Add --latest flag for argo get command as per #3128 (#3179)
 * [34608594](https://github.com/argoproj/argo-workflows/commit/34608594b98257c4ae47a280831d462bab7c53b4) fix(ui): Correctly update workflow list when workflow are modified/deleted (#3220)
 * [a7d8546c](https://github.com/argoproj/argo-workflows/commit/a7d8546cf9515ea70d686b8c669bf0a1d9b7538d) feat(controller): Improve throughput of many workflows. Fixes #2908 (#2921)
 * [a37d0a72](https://github.com/argoproj/argo-workflows/commit/a37d0a729c206040463d41e88e09814c1bf622dd) build: Change "DB=..." to "PROFILE=..." (#3216)
 * [15885d3e](https://github.com/argoproj/argo-workflows/commit/15885d3edc6d4754bc66f950251450eea8f29170) feat(sso): Allow reading SSO clientID from a secret. (#3207)
 * [723e9d5f](https://github.com/argoproj/argo-workflows/commit/723e9d5f40448ae425631fac8af2863a1f1ff1f5) fix: Ensrue image name is present in containers (#3215)
 * [0ee5e112](https://github.com/argoproj/argo-workflows/commit/0ee5e11253282eb5c36a5163086c20306cc09019) feat: Only process significant pod changes (#3181)
 * [c89a81f3](https://github.com/argoproj/argo-workflows/commit/c89a81f3ad3a76e22b98570a6045fd8eb358dbdb) feat: Add '--schedule' flag to 'argo cron create' (#3199)
 * [591f649a](https://github.com/argoproj/argo-workflows/commit/591f649a306edf826b667d0069ee04cb345dcd26) refactor: Refactor assesDAGPhase logic (#3035)
 * [285eda6b](https://github.com/argoproj/argo-workflows/commit/285eda6bbe9008ffa394edbc4b510e88119a1fd0) chore: Remove unused pod in addArchiveLocation() (#3200)
 * [8e1d56cb](https://github.com/argoproj/argo-workflows/commit/8e1d56cb78f8e039f4dbeea991bdaa1935738130) feat(controller): Add default name for artifact repository ref. (#3060)
 * [f1cdba18](https://github.com/argoproj/argo-workflows/commit/f1cdba18b3ef476e11f02e50a69fc33924158be7) feat(controller): Add `--qps` and `--burst` flags to controller (#3180)
 * [b86949f0](https://github.com/argoproj/argo-workflows/commit/b86949f0e9523e10c69e0f6b10b0f35413a20520) fix: Ensure stable desc/hash for metrics (#3196)
 * [e26d2f08](https://github.com/argoproj/argo-workflows/commit/e26d2f08c2d08dd83413b91a35e38ea6ed0d3839) docs: Update Getting Started (#3099)
 * [47bfea5d](https://github.com/argoproj/argo-workflows/commit/47bfea5d4e23d506c616fa8726c6bc751104bc94) docs: Add Graviti as official Argo user (#3187)
 * [04c77f49](https://github.com/argoproj/argo-workflows/commit/04c77f490b00ffc05f74a941f1c9ccf76a5bf789) fix(server): Allow field selection for workflow-event endpoint (fixes #3163) (#3165)
 * [0c38e66e](https://github.com/argoproj/argo-workflows/commit/0c38e66e619e243a5344f0f11a5e01194c7c5cb6) chore: Update Community Meeting link and specify Go@v1.13 (#3178)
 * [81846d41](https://github.com/argoproj/argo-workflows/commit/81846d416ecc84241ae8423d91280d6a39d9b4c2) build: Only check Dex in hosts file when SSO is enabled (#3177)
 * [a130d488](https://github.com/argoproj/argo-workflows/commit/a130d488ab69cf4d4d543c7348a45e4cd34f972e) feat(ui): Add drawer with more details for each workflow in Workflow List (#3151)
 * [fa84e203](https://github.com/argoproj/argo-workflows/commit/fa84e203239b35976210a441387d6480d951f034) fix: Do not use alphabetical order if index exists (#3174)
 * [138af597](https://github.com/argoproj/argo-workflows/commit/138af5977b81e619681eb2cfa20fd3891c752510) fix(cli): Sort expanded nodes by index. Closes #3145 (#3146)
 * [a9ec4d08](https://github.com/argoproj/argo-workflows/commit/a9ec4d08bf1e3a4b4ae55055011d5c64a1197bc0) docs: Fix api swagger file path in docs (#3167)
 * [c42e4d3a](https://github.com/argoproj/argo-workflows/commit/c42e4d3aeaf4093581d0a5d92b4d7750be205225) feat(metrics): Add node-level resources duration as Argo variable for metrics. Closes #3110 (#3161)
 * [e36fe66e](https://github.com/argoproj/argo-workflows/commit/e36fe66ee795fcde237360e593c34879873f0e36) docs: Add instructions on using Minikube as an alternative to K3D (#3162)
 * [edfa5b93](https://github.com/argoproj/argo-workflows/commit/edfa5b93fb58c0b243e1f019b92f02e846f7b83d) feat(metrics): Report controller error counters via metrics. Closes #3034 (#3144)
 * [8831e4ea](https://github.com/argoproj/argo-workflows/commit/8831e4ead39acfe3d49801271a95907a3b737d49) feat(argo-server): Add support for SSO. See #1813 (#2745)
 * [b62184c2](https://github.com/argoproj/argo-workflows/commit/b62184c2e3715fd7ddd9077e11513db25a512c93) feat(cli): More `argo list` and `argo delete` options (#3117)
 * [c6565d7c](https://github.com/argoproj/argo-workflows/commit/c6565d7c3c8c4b40c6725a1f682186e04e0a8f36) fix(controller): Maybe bug with nil woc.wfSpec. Fixes #3121 (#3160)
 * [06ca71d7](https://github.com/argoproj/argo-workflows/commit/06ca71d7a8b5f9ecc448006d3fae73baf88f9d18) build: Fix path to staticfiles and goreman binaries (#3159)
 * [cad84cab](https://github.com/argoproj/argo-workflows/commit/cad84cab7817141d259785f7565f82fd3c3dc540) chore: Remove unused nodeType in initializeNodeOrMarkError() (#3153)
 * [be425513](https://github.com/argoproj/argo-workflows/commit/be42551364ec9a792171588a662489ff32347ec1) chore: Master needs lint (#3152)
 * [70b56f25](https://github.com/argoproj/argo-workflows/commit/70b56f25baf78d67253a2f29bd4057279b0e9558) enhancement(ui): Add workflow labels column to workflow list. Fixes #2782 (#3143)
 * [3318c115](https://github.com/argoproj/argo-workflows/commit/3318c1152ac0654816e36c0b4eb8679c45b6250b) chore: Move default metrics server port/path to consts (#3135)
 * [a0062adf](https://github.com/argoproj/argo-workflows/commit/a0062adfe895ee39572db3aa6f259913279c6db3) feat(ui): Add Alibaba Cloud OSS related models in UI (#3140)
 * [1469991c](https://github.com/argoproj/argo-workflows/commit/1469991ce34333697df07ca750adb247b21cc3a9) fix: Update container delete grace period to match Kubernetes default (#3064)
 * [df725bbd](https://github.com/argoproj/argo-workflows/commit/df725bbddac2f3a216010b069363f0344a2f5a80) fix(ui): Input artifacts labelled in UI. Fixes #3098 (#3131)
 * [c0d59cc2](https://github.com/argoproj/argo-workflows/commit/c0d59cc283a62f111123728f70c24df5954d98e4) feat: Persist DAG rendering options in local storage (#3126)
 * [8715050b](https://github.com/argoproj/argo-workflows/commit/8715050b441f0fb5c84ae0a0a19695c89bf2e7b9) fix(ui): Fix label error (#3130)
 * [1814ea2e](https://github.com/argoproj/argo-workflows/commit/1814ea2e4a6702eacd567aefd1194bd6aec212ed) fix(item): Support ItemValue.Type == List. Fixes #2660 (#3129)
 * [12b72546](https://github.com/argoproj/argo-workflows/commit/12b72546eb49b8af5b4374577107f30484a6e975) fix: Panic on invalid WorkflowTemplateRef (#3127)
 * [09092147](https://github.com/argoproj/argo-workflows/commit/09092147cf26939e775848d75f687d5c8fc15aa9) fix(ui): Display error message instead of DAG when DAG cannot be rendered. Fixes #3091 (#3125)
 * [2d9a74de](https://github.com/argoproj/argo-workflows/commit/2d9a74de9b2ad28318dfb6bfdbc1db6f4db716db) docs: Document cost optimizations. Fixes #1139 (#2972)
 * [69c9e5f0](https://github.com/argoproj/argo-workflows/commit/69c9e5f053195e46871176c6a31d646144532c3a) fix: Remove unnecessary panic (#3123)
 * [2f3aca89](https://github.com/argoproj/argo-workflows/commit/2f3aca8988cee483f5fac116a8e99cdec7fd89cc) add AppDirect to the list of users (#3124)
 * [257355e4](https://github.com/argoproj/argo-workflows/commit/257355e4c54b8ca37e056e73718a112441faddb4) feat: Add 'submit --from' to CronWorkflow and WorkflowTemplate in UI. Closes #3112 (#3116)
 * [6e5dd2e1](https://github.com/argoproj/argo-workflows/commit/6e5dd2e19a3094f88e6f927f786f866eccc5f500) Add Alibaba OSS to the list of supported artifacts (#3108)
 * [1967b45b](https://github.com/argoproj/argo-workflows/commit/1967b45b1465693b71e3a0ccac9563886641694c) support sso (#3079)
 * [9229165f](https://github.com/argoproj/argo-workflows/commit/9229165f83011b3d5b867ac511793f8934bdcfab) feat(ui): Add cost optimisation nudges. (#3089)
 * [e88124db](https://github.com/argoproj/argo-workflows/commit/e88124dbf64128388cf0e6fa6d30b2f756e57d23) fix(controller): Do not panic of woc.orig in not hydrated. Fixes #3118 (#3119)
 * [132b947a](https://github.com/argoproj/argo-workflows/commit/132b947ad6ba5a5b81e281c469f08cb97748e42d) fix: Differentiate between Fulfilled and Completed (#3083)
 * [a93968ff](https://github.com/argoproj/argo-workflows/commit/a93968ff36a1472402ec9655458e6ad7b04401a8) docs: Document how to backfill a cron workflow (#3094)
 * [4de99746](https://github.com/argoproj/argo-workflows/commit/4de9974681034d7bb7223d2131eba1cd0e5d254d) feat: Added Label selector and Field selector in Argo list  (#3088)
 * [6229353b](https://github.com/argoproj/argo-workflows/commit/6229353b2355c9425f42509e3504e64ee7c7ae92) chore: goimports (#3107)
 * [8491e00f](https://github.com/argoproj/argo-workflows/commit/8491e00f31f1f744ee1af729e5598a7e8894ff5f) docs: Add link to USERS.md in PR template (#3086)
 * [bb2ce9f7](https://github.com/argoproj/argo-workflows/commit/bb2ce9f77894982f5bcae4e772795d0e679bf405) fix: Graceful error handling of malformatted log lines in watch (#3071)
 * [4fd27c31](https://github.com/argoproj/argo-workflows/commit/4fd27c314810ae43b39a5c2d36cef2dbbf5691af) build(swagger): Fix Swagger build problems (#3084)
 * [e4e0dfb6](https://github.com/argoproj/argo-workflows/commit/e4e0dfb6c66fd2c0dbbba240b1cfe8c12dcb93c2) test: fix TestContinueOnFailDag (#3101)
 * [fa69c1bb](https://github.com/argoproj/argo-workflows/commit/fa69c1bb7157e19755eea669bf44434e2bedd157) feat: Add CronWorkflowConditions to report errors (#3055)
 * [50ad3cec](https://github.com/argoproj/argo-workflows/commit/50ad3cec2b002b81e30a5d6975e7dc044a83b301) adds millisecond-level timestamps to argoexec (#2950)
 * [6464bd19](https://github.com/argoproj/argo-workflows/commit/6464bd199eff845da66d59d263f2d04479663020) fix(controller): Implement offloading for workflow updates that are re-applied. Fixes #2856 (#2941)
 * [6c369e61](https://github.com/argoproj/argo-workflows/commit/6c369e614281df0342d5cc46871551282da71ea9) chore: Rename files that include 'top-level' terminology (#3076)
 * [bd40b80b](https://github.com/argoproj/argo-workflows/commit/bd40b80bc0c6b81a824da04cbb892a5e93deeebb) docs: Document work avoidance. (#3066)
 * [6df0b2d3](https://github.com/argoproj/argo-workflows/commit/6df0b2d3538cd1525223c8d85581662ece172cf9) feat: Support Top level workflow template reference  (#2912)
 * [0709ad28](https://github.com/argoproj/argo-workflows/commit/0709ad28c3dbd4696404aa942478a7505e9e9a67) feat: Enhanced filters for argo {watch,get,submit} (#2450)
 * [784c1385](https://github.com/argoproj/argo-workflows/commit/784c1385f3bec1bacdc1ef80e223a33476696ed0) build: Use goreman for starting locally. (#3074)
 * [5b5bae9a](https://github.com/argoproj/argo-workflows/commit/5b5bae9a6e46a82f5830f68f87598ee0c7dc2ff7) docs: Add Isbank to users.md (#3068)
 * [2b038ed2](https://github.com/argoproj/argo-workflows/commit/2b038ed2e61781e5c4b8a796aba4c4afe4850305) feat: Enhanced depends logic (#2673)
 * [4c3387b2](https://github.com/argoproj/argo-workflows/commit/4c3387b273d802419a1552345dfb95dd05b8555b) fix: Linters should error if nothing was validated (#3011)
 * [51dd05b5](https://github.com/argoproj/argo-workflows/commit/51dd05b5f16e0554bdd33511f8332f3198604690) fix(artifacts): Explicit archive strategy. Fixes #2140 (#3052)
 * [ada2209e](https://github.com/argoproj/argo-workflows/commit/ada2209ef94e2380c4415cf19a8e321324650405) Revert "fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)" (#3047)
 * [b7ff9f09](https://github.com/argoproj/argo-workflows/commit/b7ff9f09c46c8f313378f7f6091260be4f6363e5) chore: Add ability to configure maximum DB connection lifetime (#3032)
 * [38a995b7](https://github.com/argoproj/argo-workflows/commit/38a995b749b83a76b5f1f2542df959898489210b) fix(executor): Properly handle empty resource results, like for a missing get (#3037)
 * [a1ac8bcf](https://github.com/argoproj/argo-workflows/commit/a1ac8bcf548c4f8fcff6b7df25aa61ad9e4c15ed) fix(artifacts): Allow tar check to be ignored. Fixes #2140 (#3024)
 * [f12d79ca](https://github.com/argoproj/argo-workflows/commit/f12d79cad9d4a9b2169f634183b6c7837c9e4615) fix(controller)!: Correctly format workflow.creationTimepstamp as RFC3339. Fixes #2974 (#3023)
 * [d10e949a](https://github.com/argoproj/argo-workflows/commit/d10e949a061de541f5312645dfa19c5732a302ff) fix: Consider metric nodes that were created and completed in the same operation (#3033)
 * [202d4ab3](https://github.com/argoproj/argo-workflows/commit/202d4ab31a2883d4f2448c309c30404f67761727) fix(executor): Optional input artifacts. Fixes #2990 (#3019)
 * [f17e946c](https://github.com/argoproj/argo-workflows/commit/f17e946c4d006cda4e161380fb5a0ba52dcebfd1) fix(executor): Save script results before artifacts in case of error. Fixes #1472 (#3025)
 * [3d216ae6](https://github.com/argoproj/argo-workflows/commit/3d216ae6d5ad96b996ce40c42793a2031a392bb1) fix: Consider missing optional input/output artifacts with same name (#3029)
 * [3717dd63](https://github.com/argoproj/argo-workflows/commit/3717dd636949e4a78e8a6ddee4320e6a98cc3c81) fix: Improve robustness of releases. Fixes #3004 (#3009)
 * [9f86a4e9](https://github.com/argoproj/argo-workflows/commit/9f86a4e941ecca4399267f7780fbb2e7ddcd2199) feat(ui): Enable CSP, HSTS, X-Frame-Options. Fixes #2760, #1376, #2761 (#2971)
 * [cb71d585](https://github.com/argoproj/argo-workflows/commit/cb71d585c73c72513aead057d570c279ba46e74b) refactor(metrics)!: Refactor Metric interface (#2979)
 * [c0ee1eb2](https://github.com/argoproj/argo-workflows/commit/c0ee1eb2293f268f6c56f343e77ff64480562f4a) docs: Add Ravelin as a user of Argo (#3020)
 * [052e6c51](https://github.com/argoproj/argo-workflows/commit/052e6c5197a6e8b4dfb14d18c2b923ca93fcb84c) Fix isTarball to handle the small gzipped file (#3014)
 * [cdcba3c4](https://github.com/argoproj/argo-workflows/commit/cdcba3c4d6849668238180903e59f37affdff01d) fix(ui): Displays command args correctl pre-formatted. (#3018)
 * [b5160988](https://github.com/argoproj/argo-workflows/commit/b516098804443b6741e9253cc211ddbf208898ab) build: Mockery v1.1.1 (#3015)
 * [a04d8f28](https://github.com/argoproj/argo-workflows/commit/a04d8f28b3028ebb3c9dacd525c563c448b19215) docs: Add StatefulSet and Service doc (#3008)
 * [8412526c](https://github.com/argoproj/argo-workflows/commit/8412526cb2d3675b4e9df5c0d4abb369eaf16380) docs: Fix Deprecated formatting (#3010)
 * [cc0fe433](https://github.com/argoproj/argo-workflows/commit/cc0fe433aebc0397c648ff4ddc8c1f99df042568) fix(events): Correct event API Version. Fixes #2994 (#2999)
 * [d5d6f750](https://github.com/argoproj/argo-workflows/commit/d5d6f750bf9324e8277fc0f05d8214b5dee255cd) feat(controller)!: Updates the resource duration calculation. Fixes #2934 (#2937)
 * [fa3801a5](https://github.com/argoproj/argo-workflows/commit/fa3801a5d89d58208f07977b73a8686e3aa2c3c9) feat(ui): Render 2000+ nodes DAG acceptably. (#2959)
 * [f952df51](https://github.com/argoproj/argo-workflows/commit/f952df517bae1f423063d61e7542c4f0c4c667e1) fix(executor/pns): remove sleep before sigkill (#2995)
 * [2a9ee21f](https://github.com/argoproj/argo-workflows/commit/2a9ee21f47dbd36ba1d2020d0939c73fc198b333) feat(ui): Add Suspend and Resume to CronWorkflows in UI (#2982)
 * [eefe120f](https://github.com/argoproj/argo-workflows/commit/eefe120f9f1e0fe5eb4876a24b00b1eb5147cebb) test: Upgrade to argosay:v2 (#3001)
 * [47472f73](https://github.com/argoproj/argo-workflows/commit/47472f73d9cec8ac601814a41388064185d2eae7) chore: Update Mockery (#3000)
 * [46b11e1e](https://github.com/argoproj/argo-workflows/commit/46b11e1eca9d25ab3dc936e959316ec587a86f52) docs: Use keyFormat instead of keyPrefix in docs (#2997)
 * [60d5fdc7](https://github.com/argoproj/argo-workflows/commit/60d5fdc7f91b675055ab0b1c7f450fa6feb0fac5) fix: Begin counting maxDuration from first child start (#2976)
 * [76aca493](https://github.com/argoproj/argo-workflows/commit/76aca4936290823c5fd0da0be8429e6d4d92efee) build: Fix Docker build. Fixes #2983 (#2984)
 * [d8cb66e7](https://github.com/argoproj/argo-workflows/commit/d8cb66e785c170030bd503ca4626ab4e6e4f8c6c) feat: Add Argo variable {{retries}} to track retry attempt (#2911)
 * [14b7a459](https://github.com/argoproj/argo-workflows/commit/14b7a459ec4ad58a3ae77c74c293a283cafdc33b) docs: Fix typo with WorkflowTemplates link (#2977)
 * [3c442232](https://github.com/argoproj/argo-workflows/commit/3c4422326dceea456df94a71270df80e9cbf7177) fix: Remove duplicate node event. Fixes #2961 (#2964)
 * [d8ab13f2](https://github.com/argoproj/argo-workflows/commit/d8ab13f24031eae58354b9ac1c59bad69968cbe6) fix: Consider Shutdown when assesing DAG Phase for incomplete Retry node (#2966)
 * [8a511e10](https://github.com/argoproj/argo-workflows/commit/8a511e109dc55d9f9c7b69614f110290c2536858) fix: Nodes with pods deleted out-of-band should be Errored, not Failed (#2855)
 * [ca4e08f7](https://github.com/argoproj/argo-workflows/commit/ca4e08f7ed861cf4e1d0a17617d210287ed83730) build: Build dev images from cache (#2968)
 * [5f01c4a5](https://github.com/argoproj/argo-workflows/commit/5f01c4a5945a9d89d5194efbbaaf1d4d2c40532d) Upgraded to Node 14.0.0 (#2816)
 * [849d876c](https://github.com/argoproj/argo-workflows/commit/849d876c835982bbfa814714e713b4d19b35148d) Fixes error with unknown flag: --show-all (#2960)
 * [93bf6609](https://github.com/argoproj/argo-workflows/commit/93bf6609cf407d6cd374a6dd3bc137b1c82e88df) fix: Don't update backoff message to save operations (#2951)
 * [3413a5df](https://github.com/argoproj/argo-workflows/commit/3413a5dfa7c29711d9bf0d227437a10bf0de9d3b) fix(cli): Remove info logging from watches. Fixes #2955 (#2958)
 * [fe9f9019](https://github.com/argoproj/argo-workflows/commit/fe9f90191fac2fb7909c8e0b31c5f3b5a31236c4) fix: Display Workflow finish time in UI (#2896)
 * [f281199a](https://github.com/argoproj/argo-workflows/commit/f281199a1df65a6716d29a8e29ba756aa31f36dc) docs: Update README with new features (#2807)
 * [c8bd0bb8](https://github.com/argoproj/argo-workflows/commit/c8bd0bb82e174cca8d733e7b75748273172efa37) fix(ui): Change default pagination to all and sort workflows (#2943)
 * [e3ed686e](https://github.com/argoproj/argo-workflows/commit/e3ed686e13eacf0174b3e1088fe3cf2eb7706b39) fix(cli): Re-establish watch on EOF (#2944)
 * [67355372](https://github.com/argoproj/argo-workflows/commit/673553729e12d4ad83387eba68b3cbfb0aea8fe4) fix(swagger)!: Fixes invalid K8S definitions in `swagger.json`. Fixes #2888 (#2907)
 * [023f2338](https://github.com/argoproj/argo-workflows/commit/023f233896ac90fdf1529f747c56ab19028b6a9c) fix(argo-server)!: Implement missing instanceID code. Fixes #2780 (#2786)
 * [7b0739e0](https://github.com/argoproj/argo-workflows/commit/7b0739e0b846cff7d2bc3340e88859ab655d25ff) Fix typo (#2939)
 * [20d69c75](https://github.com/argoproj/argo-workflows/commit/20d69c75662653523dc6276e7e57084ec1c7334f) Detect ctrl key when a link is clicked (#2935)
 * [f32cec31](https://github.com/argoproj/argo-workflows/commit/f32cec31027b7112a9a51069c2ad7b1cfbedd960) fix default null value for timestamp column - MySQL 5.7 (#2933)
 * [9773cfeb](https://github.com/argoproj/argo-workflows/commit/9773cfebcdcba9a6ab199c7001711c500f6f69a3) docs: Add docs/scaling.md (#2918)
 * [99858ea5](https://github.com/argoproj/argo-workflows/commit/99858ea53d79e964530f4a3840936d5da79585d9) feat(controller): Remove the excessive logging of node data (#2925)
 * [03ad694c](https://github.com/argoproj/argo-workflows/commit/03ad694c42a782dc9f45f7ff0ba94b32cbbfa2f1) feat(cli): Refactor `argo list --chunk-size` and add `argo archive list --chunk-size`. Fixes #2820 (#2854)
 * [1c45d5ea](https://github.com/argoproj/argo-workflows/commit/1c45d5eafe1c44b6dc53aba80ab3ef978db04afa) test: Use argoproj/argosay:v1 (#2917)
 * [f311a5a7](https://github.com/argoproj/argo-workflows/commit/f311a5a70a8f299f05363175e27afffc6772457b) build: Fix Darwin build (#2920)
 * [a06cb5e0](https://github.com/argoproj/argo-workflows/commit/a06cb5e0e02d7b480d20713e9c67f83d09fa2b24) fix: remove doubled entry in server cluster role deployment (#2904)
 * [c71116dd](https://github.com/argoproj/argo-workflows/commit/c71116ddedafde0f2931fbd489b9b17b8bd81e65) feat: Windows Container Support. Fixes #1507 and #1383 (#2747)
 * [3afa7b2f](https://github.com/argoproj/argo-workflows/commit/3afa7b2f1b4ecb9e64b2c9dee1e91dcf548f82c3) fix(ui): Use LogsViewer for container logs (#2825)
 * [9ecd5226](https://github.com/argoproj/argo-workflows/commit/9ecd522618b390b27c784092c3dc83e84785dcbb) docs: Document node field selector. Closes #2860 (#2882)
 * [7d8818ca](https://github.com/argoproj/argo-workflows/commit/7d8818ca2a335f5cb200d9b088305d032cacd020) fix(controller): Workflow stop and resume by node didn't properly support offloaded nodes. Fixes #2543 (#2548)
 * [e013f29d](https://github.com/argoproj/argo-workflows/commit/e013f29dd224a91023b5fc4cc9fed2879994ddb1) ci: Remove context to stop unauthozied errors on test jobs (#2910)
 * [db52e7ba](https://github.com/argoproj/argo-workflows/commit/db52e7bac649a7b101f846e7f7354d10a45c9e62) fix(controller): Add mutex to nameEntryIDMap in cron controller. Fix #2638 (#2851)
 * [9a33aa2d](https://github.com/argoproj/argo-workflows/commit/9a33aa2d3c0ffedf33625bd3339c2006937c0953) docs(users): Adding Habx to the users list (#2781)
 * [9e4ac9b3](https://github.com/argoproj/argo-workflows/commit/9e4ac9b3c8c7028c9759278931a76c5f26481e53) feat(cli): Tolerate deleted workflow when running `argo delete`. Fixes #2821 (#2877)
 * [a0035dd5](https://github.com/argoproj/argo-workflows/commit/a0035dd58609d744a6fa304e51d61474f25c817d) fix: ConfigMap syntax (#2889)
 * [c05c3859](https://github.com/argoproj/argo-workflows/commit/c05c3859cf911502597456f5ed374c8604af85f0) ci: Build less and therefore faster (#2839)
 * [56143eb1](https://github.com/argoproj/argo-workflows/commit/56143eb1e1e80275da2742135ef147e563cae737) feat(ui): Add pagination to workflow list. Fixes #1080 and #976 (#2863)
 * [e0ad7de9](https://github.com/argoproj/argo-workflows/commit/e0ad7de97a82b2e509bb4bc8bb5fcf5b9c26dea3) test: Fixes various tests (#2874)
 * [e378ca47](https://github.com/argoproj/argo-workflows/commit/e378ca470f1a97d624d3aceb3c53b55155fd02a9) fix: Cannot create WorkflowTemplate with un-supplied inputs (#2869)
 * [c3e30c50](https://github.com/argoproj/argo-workflows/commit/c3e30c5052b9544d363c4c73315be5136b593f9a) fix(swagger): Generate correct Swagger for inline objects. Fixes #2835 (#2837)
 * [c0143d34](https://github.com/argoproj/argo-workflows/commit/c0143d3478c6ff2ec5138f7c6b272fc8e36c6734) feat: Add metric retention policy (#2836)
 * [f03cda61](https://github.com/argoproj/argo-workflows/commit/f03cda61a73243eea225fe4d0a49f2ada0523d0d) Update getting-started.md (#2872)
 * [d66224e1](https://github.com/argoproj/argo-workflows/commit/d66224e12613c36f8fa91956509fad9fc450af74) fix: Don't error when deleting already-deleted WFs (#2866)
 * [e84acb50](https://github.com/argoproj/argo-workflows/commit/e84acb502cbbba88a700c511ffbf7feee609ccb8) chore: Display wf.Status.Conditions in CLI (#2858)
 * [3c7f3a07](https://github.com/argoproj/argo-workflows/commit/3c7f3a07d90ea6dcdf91673d4e5b4075216628f7) docs: Fix typo ".yam" -> ".yaml" (#2862)
 * [d7f8e0c4](https://github.com/argoproj/argo-workflows/commit/d7f8e0c4742b62d9271b6272a8f87c53a4fddea2) fix(CLI): Re-establish workflow watch on disconnect. Fixes #2796 (#2830)
 * [31358d6e](https://github.com/argoproj/argo-workflows/commit/31358d6e255e28f20803575f5ee0fdf2015ecb68) feat(CLI): Add -v and --verbose to Argo CLI (#2814)
 * [1d30f708](https://github.com/argoproj/argo-workflows/commit/1d30f70896b8b5f7ddc29e255c2dce0c6d01f4bd) ci: Don't configure Sonar on CI for release branches (#2811)
 * [d9c54075](https://github.com/argoproj/argo-workflows/commit/d9c54075b71baad2742829fe0874e4f07c67c67a) docs: Fix exit code example and docs (#2853)
 * [90743353](https://github.com/argoproj/argo-workflows/commit/90743353fcaf46dae04872935e95ce858e1792b3) feat: Expose workflow.serviceAccountName as global variable (#2838)
 * [f07f7bf6](https://github.com/argoproj/argo-workflows/commit/f07f7bf61147b3444255117c26bfd38261220e95) note that tar.gz'ing output artifacts is optional (#2797)
 * [3fd3fc6c](https://github.com/argoproj/argo-workflows/commit/3fd3fc6c3c789e7a3b357e16aacb02d0f880892b) docs: Document how to label creator (#2827)
 * [b956ec65](https://github.com/argoproj/argo-workflows/commit/b956ec65f372194e0f110e672a2ad50bd51a10d8) fix: Add Step node outputs to global scope (#2826)
 * [bac339af](https://github.com/argoproj/argo-workflows/commit/bac339afe10013a63bc1bb2fb83a883c07e19cb9) chore: Configure webpack dev server to proxy using HTTPS (#2812)
 * [cc136f9c](https://github.com/argoproj/argo-workflows/commit/cc136f9c3d76a5c50a9c03613233c62d118d3457) test: Skip TestStopBehavior. See #2833 (#2834)
 * [52ff43b5](https://github.com/argoproj/argo-workflows/commit/52ff43b54a76f934ae3b491c74e2350fbd2298f2) fix: Artifact panic on unknown artifact. Fixes #2824 (#2829)
 * [554fd06c](https://github.com/argoproj/argo-workflows/commit/554fd06c9daf7ce1147f949d397e489d508c58ba) fix: Enforce metric naming validation (#2819)
 * [dd223669](https://github.com/argoproj/argo-workflows/commit/dd223669a30acc58369a70288fee6ed6e006c189) docs: Add Microba as official Argo user (#2822)
 * [8151f0c4](https://github.com/argoproj/argo-workflows/commit/8151f0c49aea618a6dfcf92ec8388ccb7a5de985) docs: Update tls.md (#2813)
 * [0dbd78ff](https://github.com/argoproj/argo-workflows/commit/0dbd78ff223e592f8761f1334f952e97c9e6ac48) feat: Add TLS support. Closes #2764 (#2766)
 * [510e11b6](https://github.com/argoproj/argo-workflows/commit/510e11b639e0b797cc4253d84e96fb070691b7ab) fix: Allow empty strings in valueFrom.default (#2805)
 * [d7f41ac8](https://github.com/argoproj/argo-workflows/commit/d7f41ac8df15b8ed1e68b2e4f44d64418e4c4000) fix: Print correct version in logs. (#2806)
 * [e9c21120](https://github.com/argoproj/argo-workflows/commit/e9c2112064293b3a71e47b493666bdc9b311dfa6) chore: Add GCS native example for output artifact (#2789)
 * [e0f2697e](https://github.com/argoproj/argo-workflows/commit/e0f2697e252e7b62842af3b56f924f324f2c48ec) fix(controller): Include global params when using withParam (#2757)
 * [3441b11a](https://github.com/argoproj/argo-workflows/commit/3441b11aa5bde5fa5d0a6652fbb8fa05a4225686) docs: Fix typo in CronWorkflow doc (#2804)
 * [a2d2b848](https://github.com/argoproj/argo-workflows/commit/a2d2b848a9b6f3cf6fe5c0f0dd3b7b3084f83e37) docs: Add example of recursive for loop (#2801)
 * [29d39e29](https://github.com/argoproj/argo-workflows/commit/29d39e297c93355b68a9726aadeef4c67d4767b2) docs: Update the contributing docs  (#2791)
 * [1ea286eb](https://github.com/argoproj/argo-workflows/commit/1ea286eb237ed86bfde5a4c954927b335ab588f2) fix: ClusterWorkflowTemplate RBAC for  argo server (#2753)
 * [1f14f2a5](https://github.com/argoproj/argo-workflows/commit/1f14f2a5f6054a88f740c6799d443216f694f08f) feat(archive): Implement data retention. Closes #2273 (#2312)
 * [d0cc7764](https://github.com/argoproj/argo-workflows/commit/d0cc7764fe477465ac2c76de9cc406bbf2aac807) feat: Display argo-server version in `argo version` and in UI. (#2740)
 * [8de57281](https://github.com/argoproj/argo-workflows/commit/8de572813ee9f028cf8e06834f45a3592bc73f14) feat(controller): adds Kubernetes node name to workflow node detail in web UI and CLI output. Implements #2540 (#2732)
 * [52fa5fde](https://github.com/argoproj/argo-workflows/commit/52fa5fdee9f021b73eca30a199c65a3760462bd9) MySQL config fix (#2681)
 * [43d9eebb](https://github.com/argoproj/argo-workflows/commit/43d9eebb479242ef23e84135bbe4b9dd252dea46) fix: Rename Submittable API endpoint to `submit` (#2778)
 * [69333a87](https://github.com/argoproj/argo-workflows/commit/69333a87b0ae411972f7f25b196db989500bbe0c) Fix template scope tests (#2779)
 * [bb1abf7f](https://github.com/argoproj/argo-workflows/commit/bb1abf7f4c425494a0878d6cbc2d2cb677e88a97) chore: Add CODEOWNERS file (#2776)
 * [905e0b99](https://github.com/argoproj/argo-workflows/commit/905e0b99312e579dcd8aa8036c2ee57df6fa7a29) fix: Naming error in Makefile (#2774)
 * [7cb2fd17](https://github.com/argoproj/argo-workflows/commit/7cb2fd17765aad691eda25ca4c5acecb89f84394) fix: allow non path output params (#2680)
 * [af9f61ea](https://github.com/argoproj/argo-workflows/commit/af9f61ea7ce53f629a284a44f0106b9ed73f24e2) ci: Recurl (#2769)
 * [ef08e642](https://github.com/argoproj/argo-workflows/commit/ef08e642b5c92de0571998909b2b34ab3ac89fd4) build: Retry curl 3x (#2768)
 * [dedec906](https://github.com/argoproj/argo-workflows/commit/dedec906f0391b63b341c90e43a67047303c4728) test: Get tests running on release branches (#2767)
 * [1c8318eb](https://github.com/argoproj/argo-workflows/commit/1c8318eb92d17fa2263675cabce5134d3f1e37a2) fix: Add compatiblity mode to templateReference (#2765)
 * [7975952b](https://github.com/argoproj/argo-workflows/commit/7975952b0aa3ac84ea4559b302236598d1d47954) fix: Consider expanded tasks in getTaskFromNode (#2756)
 * [bc421380](https://github.com/argoproj/argo-workflows/commit/bc421380c9dfce1b8a25950d2bdc6a71b2e74a2d) fix: Fix template resolution in UI (#2754)
 * [391c0f78](https://github.com/argoproj/argo-workflows/commit/391c0f78a496dbe0334686dfcabde8c9af8a474f) Make phase and templateRef available for unsuspend and retry selectors (#2723)
 * [a6fa3f71](https://github.com/argoproj/argo-workflows/commit/a6fa3f71fa6bf742cb2fa90292180344f3744def) fix: Improve cookie security. Fixes #2759 (#2763)
 * [57f0183c](https://github.com/argoproj/argo-workflows/commit/57f0183cd194767af8f9bcb5fb84ab083c1661c3) Fix typo on the documentation. It causes error unmarshaling JSON: while (#2730)
 * [c6ef1ff1](https://github.com/argoproj/argo-workflows/commit/c6ef1ff19e1c3f74b4ef146be37e74bd0b748cd7) feat(manifests): add name on workflow-controller-metrics service port (#2744)
 * [af5cd1ae](https://github.com/argoproj/argo-workflows/commit/af5cd1ae0030b20f71ad345f21456100fec74639) docs: Update OWNERS (#2750)
 * [06c4bd60](https://github.com/argoproj/argo-workflows/commit/06c4bd60cf2dc85362b3370acd44e4bc3977dcbc) fix: Make ClusterWorkflowTemplate optional for namespaced Installation (#2670)
 * [25c62463](https://github.com/argoproj/argo-workflows/commit/25c624636d80605c08dd423528cb22b89cebf687) docs: Update README (#2752)
 * [908e1685](https://github.com/argoproj/argo-workflows/commit/908e1685d78d12c87fe955eec8ad0df964b3d98b) docs: Update README.md (#2751)
 * [4ea43e2d](https://github.com/argoproj/argo-workflows/commit/4ea43e2d63385211cc0a29c2aa1b237797a62f71) fix: Children of onExit nodes are also onExit nodes (#2722)
 * [3f1b6667](https://github.com/argoproj/argo-workflows/commit/3f1b6667282cf3d1b7944f7fdc075ef0f1b8ff36) feat: Add Kustomize as supported install option. Closes #2715 (#2724)
 * [691459ed](https://github.com/argoproj/argo-workflows/commit/691459ed3591f72251dc230982d7b03dc3d6f9db) fix: Error pending nodes w/o Pods unless resubmitPendingPods is set (#2721)
 * [874d8776](https://github.com/argoproj/argo-workflows/commit/874d8776c22f54ede8a07ef87b9d18c6ba8198ec) test: Longer timeout for deletion (#2737)
 * [3c8149fa](https://github.com/argoproj/argo-workflows/commit/3c8149fabfcb84bc57d1973c10fe6dbce96232a0) Fix typo (#2741)
 * [98f60e79](https://github.com/argoproj/argo-workflows/commit/98f60e7985ebd77d42ff99c6d6e1276048fb07f6) feat: Added Workflow SubmitFromResource API (#2544)
 * [6253997a](https://github.com/argoproj/argo-workflows/commit/6253997a7e25f3ad9fd3c322ea9ca9ad0b710c83) fix: Reset all conditions when resubmitting (#2702)
 * [e7c67de3](https://github.com/argoproj/argo-workflows/commit/e7c67de30df90ba7bbd649a2833dc6efed8a18de) fix: Maybe fix watch. Fixes #2678 (#2719)
 * [cef6dfb6](https://github.com/argoproj/argo-workflows/commit/cef6dfb6a25445624f864863da45c36380049e6d) fix: Print correct version string. (#2713)
 * [e9589d28](https://github.com/argoproj/argo-workflows/commit/e9589d28a5dbc7cb620f206bd1fee457a8b29dfe) feat: Increase pod workers and workflow workers both to 32 by default. (#2705)
 * [3a1990e0](https://github.com/argoproj/argo-workflows/commit/3a1990e09b353cd963b5dfbf50a702266d49b2fc) test: Fix Goroutine leak that was making controller unit tests slow. (#2701)
 * [9894c29f](https://github.com/argoproj/argo-workflows/commit/9894c29f4258fd40b604ee2c33bd877d03ff5b00) ci: Fix Sonar analysis on master. (#2709)
 * [54f5be36](https://github.com/argoproj/argo-workflows/commit/54f5be361f597d45c97469095a2e5cb5678436a8) style: Camelcase "clusterScope" (#2720)
 * [db6d1416](https://github.com/argoproj/argo-workflows/commit/db6d1416a11dbd9d963a2df6740908a1d8086ff6) fix: Flakey TestNestedClusterWorkflowTemplate testcase failure (#2613)
 * [b4fd4475](https://github.com/argoproj/argo-workflows/commit/b4fd4475c2661f12a92ba48a71b52067536044fe) feat(ui): Add a YAML panel to view the workflow manifest. (#2700)
 * [65d413e5](https://github.com/argoproj/argo-workflows/commit/65d413e5d68b2f1667ef09f3c5938a07c3442fe8) build(ui): Fix compression of UI package. (#2704)
 * [4129528d](https://github.com/argoproj/argo-workflows/commit/4129528d430be282099e94d7e98d61e40d9c78ba) fix: Don't use docker cache when building release images (#2707)
 * [8d0956c9](https://github.com/argoproj/argo-workflows/commit/8d0956c9eb8533d5a399246ffed68f6d343d47a1) test: Increase runCli timeout to 1m (#2703)
 * [9d93e971](https://github.com/argoproj/argo-workflows/commit/9d93e971a66d8f50ad92ff9e15175c6bbfe292c4) Update getting-started.md (#2697)
 * [ee644a35](https://github.com/argoproj/argo-workflows/commit/ee644a35ce4ec6a5565327fbf8cbae17a742603f) docs: Fix CONTRIBUTING.md and running-locally.md. Fixes #2682 (#2699)
 * [2737c0ab](https://github.com/argoproj/argo-workflows/commit/2737c0abf77f1555c9a9a59e564d0f1242d2656e) feat: Allow to pass optional flags to resource template (#1779)
 * [c1a2fc7c](https://github.com/argoproj/argo-workflows/commit/c1a2fc7ca8be7b9286ec01a12a185d8d4360b9f6) Update running-locally.md - fixing incorrect protoc install (#2689)
 * [a1226c46](https://github.com/argoproj/argo-workflows/commit/a1226c4616ad327400b37be19703e65a31919248) fix: Enhanced WorkflowTemplate and ClusterWorkflowTemplate validation to support Global Variables   (#2644)
 * [c21cc2f3](https://github.com/argoproj/argo-workflows/commit/c21cc2f31fead552cbab5f4664d20d56cf291619) fix a typo (#2669)
 * [9430a513](https://github.com/argoproj/argo-workflows/commit/9430a513fe7b5587048a5e74d3c9abc9e36e4304) fix: Namespace-related validation in UI (#2686)
 * [f3eeca6e](https://github.com/argoproj/argo-workflows/commit/f3eeca6e3b72f27f86678de840d1b6b7497e9473) feat: Add exit code as output variable (#2111)
 * [9f95e23a](https://github.com/argoproj/argo-workflows/commit/9f95e23a4dc9104da2218c66c66c4475285dfc3e) fix: Report metric emission errors via Conditions (#2676)
 * [c67f5ff5](https://github.com/argoproj/argo-workflows/commit/c67f5ff55b8e41b465e481d7a38d54d551c07ee4) fix: Leaf task with continueOn should not fail DAG (#2668)
 * [3c20d4c0](https://github.com/argoproj/argo-workflows/commit/3c20d4c072f1ec69954a3db8a9383bf312b495fd) ci: Migrate to use Sonar instead of CodeCov for analysis (#2666)
 * [9c6351fa](https://github.com/argoproj/argo-workflows/commit/9c6351fa643f76a7cf36eef3b80cff9bf5880463) feat: Allow step restart on workflow retry. Closes #2334 (#2431)
 * [cf277eb5](https://github.com/argoproj/argo-workflows/commit/cf277eb5114cd2db4f00d34e400a132d3344bf97) docs: Updates docs for CII. See #2641 (#2643)
 * [e2d0aa23](https://github.com/argoproj/argo-workflows/commit/e2d0aa23ab4ee9b91b018bb556959c60981586e2) fix: Consider offloaded and compressed node in retry and resume (#2645)
 * [a25c6a20](https://github.com/argoproj/argo-workflows/commit/a25c6a20d0ff7b7b7b211fcfe207200036ed5df8) build: Fix codegen for releases (#2662)
 * [4a3ca930](https://github.com/argoproj/argo-workflows/commit/4a3ca930ef1d944dfd8659d5886d8abc7f6ce42f) fix: Correctly emit events. Fixes #2626 (#2629)
 * [4a7d4bdb](https://github.com/argoproj/argo-workflows/commit/4a7d4bdba522870ab9883c4f6ccac7b244bc5bcb) test: Fix flakey DeleteCompleted test (#2659)
 * [41f91e18](https://github.com/argoproj/argo-workflows/commit/41f91e18a4f65d8a6626782ebc8920ca02b3cc86) fix: Add DAG as default in UI filter and reorder (#2661)
 * [f138ada6](https://github.com/argoproj/argo-workflows/commit/f138ada68ba0b3c46f546bfef574e212833759ac) fix: DAG should not fail if its tasks have continueOn (#2656)
 * [e5cbdf6a](https://github.com/argoproj/argo-workflows/commit/e5cbdf6a4be8f111f6353534079fa4a71384e401) ci: Only run CI jobs if needed (#2655)
 * [4c452d5f](https://github.com/argoproj/argo-workflows/commit/4c452d5f7287179b6a7967fc7d60fb0837bd36ca) fix: Don't attempt to resolve artifacts if task is going to be skipped (#2657)
 * [2caf570a](https://github.com/argoproj/argo-workflows/commit/2caf570a35565617ae9af04682883ab34e2692b6) chore: Add newline to fields.md (#2654)
 * [2cb596da](https://github.com/argoproj/argo-workflows/commit/2cb596da3dac3c5683ed44e7a363c014e73a38a5) Storage region should be specified (#2538)
 * [271e4551](https://github.com/argoproj/argo-workflows/commit/271e45512be56bb6187d7665e9b5b65eb2500ad6) chore: Fix-up Yarn deps (#2649)
 * [4c1b0777](https://github.com/argoproj/argo-workflows/commit/4c1b077725a22d183ecdb24f2f147fee0a6e320c) fix: Sort log entries. (#2647)
 * [268fc461](https://github.com/argoproj/argo-workflows/commit/268fc46197ac411339c78018f05d76e102447eef)  docs: Added doc generator code (#2632)
 * [d58b7fc3](https://github.com/argoproj/argo-workflows/commit/d58b7fc39620fb24e40bb4f55f69c4e0fb5fc017) fix: Add input paremeters to metric scope (#2646)
 * [cc3af0b8](https://github.com/argoproj/argo-workflows/commit/cc3af0b83381e2d4a8da1959c36fd0a466c414ff) fix: Validating Item Param in Steps Template (#2608)
 * [6c685c5b](https://github.com/argoproj/argo-workflows/commit/6c685c5baf281116340b7b0708f8a29764d72c47) fix: allow onExit to run if wf exceeds activeDeadlineSeconds. Fixes #2603 (#2605)
 * [ffc43ce9](https://github.com/argoproj/argo-workflows/commit/ffc43ce976973c7c20d6c58d7b27a28969ae206f) feat: Added Client validation on Workflow/WFT/CronWF/CWFT (#2612)
 * [24655cd9](https://github.com/argoproj/argo-workflows/commit/24655cd93246e2a25dc858238116f7acec45ea42) feat(UI): Move Workflow parameters to top of submit (#2640)
 * [0a3b159a](https://github.com/argoproj/argo-workflows/commit/0a3b159ab87bd313896174f8464ffd277b14264c) Use error equals (#2636)
 * [8c29e05c](https://github.com/argoproj/argo-workflows/commit/8c29e05cb5befe5f9f0263ff138eab66f75c54d0) ci: Fix codegen job (#2648)
 * [a78ecb7f](https://github.com/argoproj/argo-workflows/commit/a78ecb7fe040c0040fb12731997351a02e0808a0) docs(users): Add CoreWeave and ConciergeRender (#2641)
 * [14be4670](https://github.com/argoproj/argo-workflows/commit/14be46707f4051db71e9495472e842fbb1eb5ea0) fix: Fix logs part 2 (#2639)
 * [4da6f4f3](https://github.com/argoproj/argo-workflows/commit/4da6f4f3ee75b2e50206381dad1809d5a21c6cce) feat: Add 'outputs.result' to Container templates (#2584)
 * [51bc876d](https://github.com/argoproj/argo-workflows/commit/51bc876d576b6e61f508bb56ab9f2dfbf91b0e85) test: Fixes TestCreateWorkflowDryRun. Closes #2618 (#2628)
 * [212c6d75](https://github.com/argoproj/argo-workflows/commit/212c6d75fa7e5e8d568e80992d1924a2c51cd631) fix: Support minimal mysql version 5.7.8 (#2633)
 * [8facacee](https://github.com/argoproj/argo-workflows/commit/8facaceeb3515d804c3fd276b1802dbd6cf773e8) refactor: Refactor Template context interfaces (#2573)
 * [812813a2](https://github.com/argoproj/argo-workflows/commit/812813a288608e196006d4b8369702d020e61dc4) fix: fix test cases (#2631)
 * [ed028b25](https://github.com/argoproj/argo-workflows/commit/ed028b25f6c925a02596f90d722283856b003ff8) fix: Fix logging problems. See #2589 (#2595)
 * [d4e81238](https://github.com/argoproj/argo-workflows/commit/d4e8123816f3883d876ed715036c5d91d3fe0586) test: Fix teething problems (#2630)
 * [4aad6d55](https://github.com/argoproj/argo-workflows/commit/4aad6d55ed4e7a6c9eaa9a36b78e123655dd4ca4) chore: Add comments to issues (#2627)
 * [54f7a013](https://github.com/argoproj/argo-workflows/commit/54f7a0134ad9933608993bc09eda2032e7a16a80) test: Enhancements and repairs to e2e test framework (#2609)
 * [d95926fe](https://github.com/argoproj/argo-workflows/commit/d95926fe40e48932c25a0f70c671ad99f4149505) fix: Fix WorkflowTemplate icons to be more cohesive (#2607)
 * [0130e1fd](https://github.com/argoproj/argo-workflows/commit/0130e1fd85b7fa5b3b48b07b873858670e1a61a0) docs: Add fields and core concepts doc (#2610)
 * [5a1ac203](https://github.com/argoproj/argo-workflows/commit/5a1ac20352ab6042958f49a59d0f5227329f654c) fix: Fixes panic in toWorkflow method (#2604)
 * [51910292](https://github.com/argoproj/argo-workflows/commit/5191029247ac817dd6ce811e044459c45b2846ee) chore: Lint UI on CI, test diagnostics, skip bad test (#2587)
 * [232bb115](https://github.com/argoproj/argo-workflows/commit/232bb115eba8e2667653fdbdc9831bee112daa85) fix(error handling): use Errorf instead of New when throwing errors with formatted text (#2598)
 * [eeb2f97b](https://github.com/argoproj/argo-workflows/commit/eeb2f97be5c8787180af9f32f2d5e8baee63ed2f) fix(controller): dag continue on failed. Fixes #2596 (#2597)
 * [99c35129](https://github.com/argoproj/argo-workflows/commit/99c35129eae2d283c2e6d81b578d786b494aab11) docs: Fix inaccurate field name in docs (#2591)
 * [21c73779](https://github.com/argoproj/argo-workflows/commit/21c7377932825cd30f67a840d30853f4a48951fa) fix: Fixes lint errors (#2594)
 * [38aca5fa](https://github.com/argoproj/argo-workflows/commit/38aca5fa2a153393b3edb93be07ddce375ad13f4) chore: Added ClusterWorkflowTemplate RBAC on quick-start manifests (#2576)
 * [59f746e1](https://github.com/argoproj/argo-workflows/commit/59f746e1a551180d11e57676f8a2a384b3741599) feat: UI enhancement for Cluster Workflow Template (#2525)
 * [0801a428](https://github.com/argoproj/argo-workflows/commit/0801a4284a948bbeced83852af27a019e7b33535) fix(cli): Show lint errors of all files (#2552)
 * [c3535ba5](https://github.com/argoproj/argo-workflows/commit/c3535ba5ac85e1071a08ccbc930f2ff45cd2f295) docs: Fix wrong Configuring Your Artifact Repository document. (#2586)
 * [79217bc8](https://github.com/argoproj/argo-workflows/commit/79217bc89e892ee82bdd5018b2bba65425924d36) feat(archive): allow specifying a compression level (#2575)
 * [88d261d7](https://github.com/argoproj/argo-workflows/commit/88d261d7fa72faea19745de588c19de45e7fab88) fix: Use outputs of last child instead of retry node itslef (#2565)
 * [5c08292e](https://github.com/argoproj/argo-workflows/commit/5c08292e4ee388c1c5ca5291c601d50b2b3374e7) style: Correct the confused logic (#2577)
 * [3d146144](https://github.com/argoproj/argo-workflows/commit/3d14614459d50b96838fcfd83809ee29499e2917) fix: Fix bug in deleting pods. Fixes #2571 (#2572)
 * [cb739a68](https://github.com/argoproj/argo-workflows/commit/cb739a6897591969b959bd2feebd8ded97b9cb33) feat: Cluster scoped workflow template (#2451)
 * [c63e3d40](https://github.com/argoproj/argo-workflows/commit/c63e3d40be50479ca3c9a7325bfeb5fd9d31fa7c) feat: Show workflow duration in the index UI page (#2568)
 * [1520452a](https://github.com/argoproj/argo-workflows/commit/1520452a381319b414618d8429d6d7e0bb23790d) chore: Error -> Warn when Parent CronWf no longer exists (#2566)
 * [ffbb3b89](https://github.com/argoproj/argo-workflows/commit/ffbb3b899912f7af888d8216bd2ab55bc7106880) fix: Fixes empty/missing CM. Fixes #2285 (#2562)
 * [d0fba6f4](https://github.com/argoproj/argo-workflows/commit/d0fba6f443da013fd9ae8e48f658b337a0a18015) chore: fix typos in the workflow template docs (#2563)
 * [49801e32](https://github.com/argoproj/argo-workflows/commit/49801e32f1624ba20926f1b07a6ddafa2f162301) chore(docker): upgrade base image for executor image (#2561)
 * [c4efb8f8](https://github.com/argoproj/argo-workflows/commit/c4efb8f8b6e28a591794c018f5e61f55dd7d75e3) Add Riskified to the user list (#2558)
 * [8b92d33e](https://github.com/argoproj/argo-workflows/commit/8b92d33eb2f2de3b593459140576ea8eaff8fb4b) feat: Create K8S events on node completion. Closes #2274 (#2521)
 * [2902e144](https://github.com/argoproj/argo-workflows/commit/2902e144ddba2f8c5a93cdfc8e2437c04705065b) feat: Add node type and phase filter to UI (#2555)
 * [fb74ba1c](https://github.com/argoproj/argo-workflows/commit/fb74ba1ce27b96473411c2c5cfe9a86972af589e) fix: Separate global scope processing from local scope building (#2528)
 * [618b6dee](https://github.com/argoproj/argo-workflows/commit/618b6dee4de973b3f3ef1d1164a44b9cb176355e) fix: Fixes --kubeconfig flag. Fixes #2492 (#2553)
 * [79dc969f](https://github.com/argoproj/argo-workflows/commit/79dc969f73e0ec90bdc202e936afec970ff66fc6) test: Increase timeout for flaky test (#2543)
 * [15a3c990](https://github.com/argoproj/argo-workflows/commit/15a3c990359c40d791be64a34736e2a1ffa40178) feat: Report SpecWarnings in status.conditions (#2541)
 * [f142f30a](https://github.com/argoproj/argo-workflows/commit/f142f30a99aa9b12cdfbeed31129abb8d4266762) docs: Add example of template-level volume declaration. (#2542)
 * [93b6be61](https://github.com/argoproj/argo-workflows/commit/93b6be619523ec3d9d8c52c75d9fa540e0272c7f) fix(archive): Fix bug that prevents listing archive workflows. Fixes … (#2523)
 * [b4c9c54f](https://github.com/argoproj/argo-workflows/commit/b4c9c54f79d902f2372192f017192fa519800fd8) fix: Omit config key in configure artifact document. (#2539)
 * [864bf1e5](https://github.com/argoproj/argo-workflows/commit/864bf1e56812b0ea1434b3952073a3e15dd9f046) fix: Show template on its own field in CLI (#2535)
 * [555aaf06](https://github.com/argoproj/argo-workflows/commit/555aaf06306d066268c04e4dd50ec2fecadd22cc) test: fix master (#2534)
 * [94862b98](https://github.com/argoproj/argo-workflows/commit/94862b985ef97e39d01fcafc95109b1b3507b21e) chore: Remove deprecated example (#2533)
 * [5e1e7829](https://github.com/argoproj/argo-workflows/commit/5e1e78295df4df0205a47adcedde6f1d5915af95) fix: Validate CronWorkflow before creation (#2532)
 * [c9241339](https://github.com/argoproj/argo-workflows/commit/c92413393404bd4caeb00606b3ba8775eeadf231) fix: Fix wrong assertions (#2531)
 * [67fe04bb](https://github.com/argoproj/argo-workflows/commit/67fe04bb78ac7b402bb6ef5b58d5cca33ecd74db) Revert "fix: fix template scope tests (#2498)" (#2526)
 * [ddfa1ad0](https://github.com/argoproj/argo-workflows/commit/ddfa1ad03f2835b64efac96eb4fb10d14e3ed987) docs: couple of examples for REST API usage of argo-server (#2519)
 * [30542be7](https://github.com/argoproj/argo-workflows/commit/30542be7a121cf8774352bf987ee658b5d8b96c8) chore(docs): Update docs for useSDKCreds (#2518)
 * [e2cc6988](https://github.com/argoproj/argo-workflows/commit/e2cc6988018e50956c05ed20c665ead01766278d) feat: More control over resuming suspended nodes Fixes #1893 (#1904)
 * [b2771249](https://github.com/argoproj/argo-workflows/commit/b2771249b0be9c782ee2ae190dd76ec3bba2a562) chore: minor fix and refactory (#2517)
 * [b1ad163a](https://github.com/argoproj/argo-workflows/commit/b1ad163ac17312d103c03bf6a88069f1b055ea7d) fix: fix template scope tests (#2498)
 * [661d1b67](https://github.com/argoproj/argo-workflows/commit/661d1b6748b25488b288811dc5c0089b49b75a52) Increase client gRPC max size to match server (#2514)
 * [d8aa477f](https://github.com/argoproj/argo-workflows/commit/d8aa477f7f5089505df5fd26560f53f508f5b29f) fix: Fix potential panic (#2516)
 * [1afb692e](https://github.com/argoproj/argo-workflows/commit/1afb692eeb6a63cb0539cbc6762d8219b2b2dd00) fix: Allow runtime resolution for workflow parameter names (#2501)
 * [243ea338](https://github.com/argoproj/argo-workflows/commit/243ea338de767a39947f5fb4450321083a6f9c67) fix(controller): Ensure we copy any executor securityContext when creating wait containers; fixes #2512 (#2510)
 * [6e8c7bad](https://github.com/argoproj/argo-workflows/commit/6e8c7badcfa3f2eb7d5cb76f229e0570f3325f61) feat: Extend workflowDefaults to full Workflow and clean up docs and code (#2508)
 * [06cfc129](https://github.com/argoproj/argo-workflows/commit/06cfc1294a5a913a8b23bc4337ffa019717c4af2) feat: Native Google Cloud Storage support for artifact. Closes #1911 (#2484)
 * [999b1e1d](https://github.com/argoproj/argo-workflows/commit/999b1e1d9a6c9d69def35fd43d01b03c75748e62)  fix: Read ConfigMap before starting servers  (#2507)
 * [3d6e9b61](https://github.com/argoproj/argo-workflows/commit/3d6e9b61b3c7214ab5c62438e7d0ea750c3ae3f7) docs: Add separate ConfigMap doc for 2.7+ (#2505)
 * [e5bd6a7e](https://github.com/argoproj/argo-workflows/commit/e5bd6a7ed35a4d5ed75023719814541423affc48) fix(controller): Updates GetTaskAncestry to skip visited nod. Fixes #1907 (#1908)
 * [183a29e4](https://github.com/argoproj/argo-workflows/commit/183a29e40314ac97dfa6d7ff2e61f59ee6484279) docs: add official user (#2499)
 * [e636000b](https://github.com/argoproj/argo-workflows/commit/e636000bc457d654d487e065c1bcacd15ed75a74) feat: Updated arm64 support patch (#2491)
 * [559cb005](https://github.com/argoproj/argo-workflows/commit/559cb00596acbcc9a6a9cce001ca25fdcc561b2b) feat(ui): Report resources duration in UI. Closes #2460 (#2489)
 * [09291d9d](https://github.com/argoproj/argo-workflows/commit/09291d9d59e1fe51b1622b90ac18c6a5985b6a85) feat: Add default field in parameters.valueFrom (#2500)
 * [33cd4f2b](https://github.com/argoproj/argo-workflows/commit/33cd4f2b86e8b0993563d70c6b0d6f0f91b14535) feat(config): Make configuration mangement easier. Closes #2463 (#2464)
 * [f3df9660](https://github.com/argoproj/argo-workflows/commit/f3df9660be9f4d52975720e79bd01a6efe6fa18d) test: Fix test (#2490)
 * [bfaf1c21](https://github.com/argoproj/argo-workflows/commit/bfaf1c215f5491526edd020055ed8a15eb804a04) chore: Move quickstart Prometheus port to 9090 (#2487)
 * [487ed425](https://github.com/argoproj/argo-workflows/commit/487ed425840dc5698a4ef3a3c8f214b6c08949cc) feat: Logging the Pod Spec in controller log (#2476)
 * [96c80e3e](https://github.com/argoproj/argo-workflows/commit/96c80e3e2c6eb6867e360dde3dea97047b963c2f) fix(cli): Rearrange the order of chunk size argument in list command. Closes #2420 (#2485)
 * [47bd70a0](https://github.com/argoproj/argo-workflows/commit/47bd70a092debe980075195efd802e7bfb59c82f) chore: Fix Swagger for PDB to support Java client (#2483)
 * [53a10564](https://github.com/argoproj/argo-workflows/commit/53a10564aebc6ee17eb8e3e121b4c36b2a334b87) feat(usage): Report resource duration. Closes #1066 (#2219)
 * [063d9bc6](https://github.com/argoproj/argo-workflows/commit/063d9bc657b00e23ce7722d5d08ca69347fe7205) Revert "feat: Add support for arm64 platform (#2364)" (#2482)
 * [735d25e9](https://github.com/argoproj/argo-workflows/commit/735d25e9d719b409a7517685bcb4148278bef5a1) fix: Build image with SHA tag when a git tag is not available (#2479)
 * [c55bb3b2](https://github.com/argoproj/argo-workflows/commit/c55bb3b211be8ccc9680f8282f98f8a8bf647ca7) ci: Run lint on CI and fix GolangCI (#2470)
 * [e1c9f7af](https://github.com/argoproj/argo-workflows/commit/e1c9f7afcb4f685f615235ae1d0b6000add93635) fix ParallelSteps child type so replacements happen correctly; fixes argoproj-labs/argo-client-gen#5 (#2478)
 * [55c315db](https://github.com/argoproj/argo-workflows/commit/55c315db2e87fe28dcc26f49f4ee969bae9c7ea1) feat: Add support for IRSA and aws default provider chain. (#2468)
 * [c724c7c1](https://github.com/argoproj/argo-workflows/commit/c724c7c1afca646e09c0cb82acf8b59f8c413780) feat: Add support for arm64 platform (#2364)
 * [315dc164](https://github.com/argoproj/argo-workflows/commit/315dc164dcd24d0443b49ac95d49eb06b2c2a64f) feat: search archived wf by startat. Closes #2436 (#2473)
 * [23d230bd](https://github.com/argoproj/argo-workflows/commit/23d230bd54e04af264a0977545db365a2c0d6a6d) feat(ui): add Env to Node Container Info pane. Closes #2471 (#2472)
 * [10a0789b](https://github.com/argoproj/argo-workflows/commit/10a0789b9477b1b6c1b7adda71101925989d02de) fix: ParallelSteps swagger.json (#2459)
 * [a59428e7](https://github.com/argoproj/argo-workflows/commit/a59428e72c092e12b17c2bd8f22ee2e86eec043f) fix: Duration must be a string. Make it a string. (#2467)
 * [47bc6f3b](https://github.com/argoproj/argo-workflows/commit/47bc6f3b7450895aa35f9275b326077bb08453b5) feat: Add `argo stop` command (#2352)
 * [14478bc0](https://github.com/argoproj/argo-workflows/commit/14478bc07f42ae9ee362cc1531b1cf00d923211d) feat(ui): Add the ability to have links to logging facility in UI. Closes #2438 (#2443)
 * [2864c745](https://github.com/argoproj/argo-workflows/commit/2864c745877c9e44a5b14140f4317f8e2d45975a) chore: make codegen + make start (#2465)
 * [a85f62c5](https://github.com/argoproj/argo-workflows/commit/a85f62c5e8ee1a51f5fa8fd715ebdf4140d2483d) feat: Custom, step-level, and usage metrics (#2254)
 * [64ac0298](https://github.com/argoproj/argo-workflows/commit/64ac02980ea641d92f22328442e5a12893600d67) fix: Deprecate template.{template,templateRef,arguments} (#2447)
 * [6cb79e4e](https://github.com/argoproj/argo-workflows/commit/6cb79e4e5414277932e5cf755761cec4cda7e1b7) fix: Postgres persistence SSL Mode (#1866) (#1867)
 * [2205c0e1](https://github.com/argoproj/argo-workflows/commit/2205c0e162c93645a5ae1d883aec6ae33fec3c8f) fix(controller): Updates to add condition to workflow status. Fixes #2421 (#2453)
 * [9d96ab2f](https://github.com/argoproj/argo-workflows/commit/9d96ab2ffd6cec9fc65f0182234e103664ab9cd5) fix: make dir if needed (#2455)
 * [5346609e](https://github.com/argoproj/argo-workflows/commit/5346609e79de4fc4f6fc9d833f0f2a85790821aa) test: Maybe fix TestPendingRetryWorkflowWithRetryStrategy. Fixes #2446 (#2456)
 * [3448ccf9](https://github.com/argoproj/argo-workflows/commit/3448ccf91cbff2e3901a99e23e57a0e1ad97044c) fix: Delete PVCs unless WF Failed/Errored (#2449)
 * [782bc8e7](https://github.com/argoproj/argo-workflows/commit/782bc8e7c5d1fd102f1a16d07f209aed3bfdc689) fix: Don't error when optional artifacts are not found (#2445)
 * [fc18f3cf](https://github.com/argoproj/argo-workflows/commit/fc18f3cf27c525ff94a6b190a0aff0a9a3d45426) chore: Master needs codegen (#2448)
 * [32fc2f78](https://github.com/argoproj/argo-workflows/commit/32fc2f78212d031f99f1dfc5ad3a3642617ce7e7) feat: Support workflow templates submission. Closes #2007 (#2222)
 * [050a143d](https://github.com/argoproj/argo-workflows/commit/050a143d7639ad38dc01a685edce536917409a37) fix(archive): Fix edge-cast error for archiving. Fixes #2427 (#2434)
 * [9455c1b8](https://github.com/argoproj/argo-workflows/commit/9455c1b88d85f80091aa4fd2c8d4dc53b6cc73f8) doc: update CHANGELOG.md (#2425)
 * [1baa7ee4](https://github.com/argoproj/argo-workflows/commit/1baa7ee4ec7149afe789d73ed6e64abfe13387a7) feat(ui): cache namespace selection. Closes #2439 (#2441)
 * [91d29881](https://github.com/argoproj/argo-workflows/commit/91d29881f41642273fe0494bef70f2b9c41350e2) feat: Retry pending nodes (#2385)
 * [7094433e](https://github.com/argoproj/argo-workflows/commit/7094433e12b668236a87c034445daf88d659231f) test: Skip flakey tests in operator_template_scope_test.go. See #2432 (#2433)
 * [30332b14](https://github.com/argoproj/argo-workflows/commit/30332b14fb1043e22a66db594f1af252c5932853) fix: Allow numbers in steps.args.params.value (#2414)
 * [e9a06dde](https://github.com/argoproj/argo-workflows/commit/e9a06dde297e9f907d10ec88da93fbb90df5ebaf) feat: instanceID support for argo server. Closes #2004 (#2365)
 * [3f8be0cd](https://github.com/argoproj/argo-workflows/commit/3f8be0cd48963958c493e7669a1d03bb719b375a) fix "Unable to retry workflow" on argo-server (#2409)
 * [dd3029ab](https://github.com/argoproj/argo-workflows/commit/dd3029abdd13a6b4053934660ca1078e23780809) docs: Example showing how to use default settings for workflow spec. Related to ##2388 (#2411)
 * [13508828](https://github.com/argoproj/argo-workflows/commit/135088284acd1ced004374d20928c017fbf9cac7) fix: Check child node status before backoff in retry (#2407)
 * [b59419c9](https://github.com/argoproj/argo-workflows/commit/b59419c9f58422f60c7d5185c89b4d55ac278660) fix: Build with the correct version if you check out a specific version (#2423)
 * [6d834d54](https://github.com/argoproj/argo-workflows/commit/6d834d545bc816cde9b74b224116d9746db5b799) chore: document BASE_HREF (#2418)
 * [184c3653](https://github.com/argoproj/argo-workflows/commit/184c3653085bc8821bdcd65f5476fbe24f24b00e) fix: Remove lazy workflow template (#2417)
 * [918d0d17](https://github.com/argoproj/argo-workflows/commit/918d0d17c0455b6a0644c6d851dbea3f945db21c) docs: Added Survey Results (#2416)
 * [20d6e27b](https://github.com/argoproj/argo-workflows/commit/20d6e27bdf11389f23b2efe1be4ef737f333221d) Update CONTRIBUTING.md (#2410)
 * [f2ca045e](https://github.com/argoproj/argo-workflows/commit/f2ca045e1cad03d5ec7566ff7200fd8ca575ec5d) feat: Allow WF metadata spec on Cron WF (#2400)
 * [068a4336](https://github.com/argoproj/argo-workflows/commit/068a43362b2088f53d408623bc7ab078e0e7a9d0) fix: Correctly report version. Fixes #2374 (#2402)
 * [e19a398c](https://github.com/argoproj/argo-workflows/commit/e19a398c810fada879facd624a7663501306e1ef) Update pull_request_template.md (#2401)
 * [7c99c109](https://github.com/argoproj/argo-workflows/commit/7c99c109e3dd726f6453c94a594d69bca709ccf6) chore: Fix typo (#2405)
 * [175b164c](https://github.com/argoproj/argo-workflows/commit/175b164c33aee7fe2873df60915a881502ec9163) Change font family for class yaml (#2394)
 * [d1194755](https://github.com/argoproj/argo-workflows/commit/d11947558bc758e5102238162036650890731ec6) fix: Don't display Retry Nodes in UI if len(children) == 1 (#2390)
 * [b8623ec7](https://github.com/argoproj/argo-workflows/commit/b8623ec7b4a19713f5965cc0d628f26b81af39a2) docs: Create USERS.md (#2389)
 * [1d21d3f5](https://github.com/argoproj/argo-workflows/commit/1d21d3f5600feca4b63e3dc4b1d94d2830fa6e24) fix(doc strings): Fix bug related documentation/clean up of default configurations #2331 (#2388)
 * [77e11fc4](https://github.com/argoproj/argo-workflows/commit/77e11fc4838ff92de9d9cae91159fb88755dff0b) chore: add noindex meta tag to solve #2381; add kustomize to build docs (#2383)
 * [42200fad](https://github.com/argoproj/argo-workflows/commit/42200fad45b4925b8f4aac48a580e6e369de2ad4) fix(controller): Mount volumes defined in script templates. Closes #1722 (#2377)
 * [96af36d8](https://github.com/argoproj/argo-workflows/commit/96af36d85d70d4721b1ac3e6e0ef14db65e7aec3) fix: duration must be a string (#2380)
 * [7bf08192](https://github.com/argoproj/argo-workflows/commit/7bf0819267543808d80acaa5f39f40c1fdba511e) fix: Say no logs were outputted when pod is done (#2373)
 * [847c3507](https://github.com/argoproj/argo-workflows/commit/847c3507dafdd3ff2cd1acca4669c1a54a680ee2) fix(ui): Removed tailLines from EventSource (#2330)
 * [3890a124](https://github.com/argoproj/argo-workflows/commit/3890a12431bfacc83cc75d862f956ddfbc1d2a37) feat: Allow for setting default configurations for workflows, Fixes #1923, #2044 (#2331)
 * [81ab5385](https://github.com/argoproj/argo-workflows/commit/81ab538594ad0428a97e99f34b18041f31a1c753) Update readme (#2379)
 * [91810273](https://github.com/argoproj/argo-workflows/commit/91810273318ab3ea84ecf73b9d0a6f1ba7f43c2a) feat: Log version (structured) on component start-up (#2375)
 * [d0572a74](https://github.com/argoproj/argo-workflows/commit/d0572a74069a1a6c38fa860e1964fa0564fd28cd) docs: Make Getting Started agnostic to version (#2371)
 * [d3a3f6b1](https://github.com/argoproj/argo-workflows/commit/d3a3f6b195b984a97eb214e99f29498c0bd39c85) docs: Add Prudential to the users list (#2353)
 * [4714c880](https://github.com/argoproj/argo-workflows/commit/4714c88099f25a3ffe2db14574016b069f85335d) chore: Master needs codegen (#2369)
 * [5b6b8257](https://github.com/argoproj/argo-workflows/commit/5b6b8257890d3c7aa93d8e98b10090add08a22e1) fix(docker): fix streaming of combined stdout/stderr (#2368)
 * [97438313](https://github.com/argoproj/argo-workflows/commit/9743831306714cc85b762487ac070f77e25f85d6) fix: Restart server ConfigMap watch when closed (#2360)
 * [64d0cec0](https://github.com/argoproj/argo-workflows/commit/64d0cec080bb27e147632fb8993f75e16c92e4a7) chore: Master needs make lint (#2361)
 * [12386fc6](https://github.com/argoproj/argo-workflows/commit/12386fc6029f5533921c75797455efc62e4cc9ce) fix: rerun codegen after merging OSS artifact support (#2357)
 * [40586ed5](https://github.com/argoproj/argo-workflows/commit/40586ed5c3a539d2e13f8a34509a40367563874a) fix: Always validate templates (#2342)
 * [897db894](https://github.com/argoproj/argo-workflows/commit/897db89434079fa3b3b902253d1c624c39af1422) feat: Add support for Alibaba Cloud OSS artifact (#1919)
 * [7e2dba03](https://github.com/argoproj/argo-workflows/commit/7e2dba03674219ec35e88b2ce785fdf120f855fd) feat(ui): Circles for nodes (#2349)
 * [e85f6169](https://github.com/argoproj/argo-workflows/commit/e85f6169fadf503c220ecc2385334fc0f2073ca4) chore: update getting started guide to use 2.6.0 (#2350)
 * [7ae4ec78](https://github.com/argoproj/argo-workflows/commit/7ae4ec78f627b620197a323b190fa33c31ffcbcc) docker: remove NopCloser from the executor. (#2345)
 * [5895b364](https://github.com/argoproj/argo-workflows/commit/5895b3642a691629b6c8aa145cf17627a227665f) feat: Expose workflow.paramteres with JSON string of all params (#2341)
 * [a9850b43](https://github.com/argoproj/argo-workflows/commit/a9850b43b16e05d9f74f52c789a8475d493f4c92) Fix the default (#2346)
 * [c3763d34](https://github.com/argoproj/argo-workflows/commit/c3763d34ed02bc63d166e8ef4f2f724786a2cf7c) fix: Simplify completion detection logic in DAGs (#2344)
 * [d8a9ea09](https://github.com/argoproj/argo-workflows/commit/d8a9ea09be395241664d929e8dbca7d02aecb049) fix(auth): Fixed returning  expired  Auth token for GKE (#2327)
 * [6fef0454](https://github.com/argoproj/argo-workflows/commit/6fef0454073fb60b4dd6216accef07f5195ec7e9) fix: Add timezone support to startingDeadlineSeconds (#2335)
 * [c28731b9](https://github.com/argoproj/argo-workflows/commit/c28731b9f602b3ed79c76dd4e3383f39419e463f) chore: Add go mod tidy to codegen (#2332)
 * [a66c8802](https://github.com/argoproj/argo-workflows/commit/a66c8802c7d0dbec9b13d408b91655e41531a97a) feat: Allow Worfklows to be submitted as files from UI (#2340)
 * [a9c1d547](https://github.com/argoproj/argo-workflows/commit/a9c1d547e5b044d9d375ebf527c132b0545455b0) docs: Update Argo Rollouts description (#2336)
 * [8672b97f](https://github.com/argoproj/argo-workflows/commit/8672b97f134dacb553592c367399229891aaf5c8) fix(Dockerfile): Using `--no-install-recommends` (Optimization) (#2329)
 * [c3fe1ae1](https://github.com/argoproj/argo-workflows/commit/c3fe1ae1b3ad662bc94a4b46e72f20c957dd4475) fix(ui): fixed worflow UI refresh. Fixes ##2337 (#2338)
 * [d7690e32](https://github.com/argoproj/argo-workflows/commit/d7690e32faf2ac5842468831daf1443283703c25) feat(ui): Adds ability zoom and hide successful steps. POC (#2319)
 * [e9e13d4c](https://github.com/argoproj/argo-workflows/commit/e9e13d4cbbc0f456c2d1dafbb1a95739127f6ab4) feat: Allow retry strategy on non-leaf nodes, eg for step groups. Fixes #1891 (#1892)
 * [62e6db82](https://github.com/argoproj/argo-workflows/commit/62e6db826ea4e0a02ac839bc59ec5f70ce3b9b29) feat: Ability to include or exclude fields in the response (#2326)
 * [52ba89ad](https://github.com/argoproj/argo-workflows/commit/52ba89ad4911fd4c7b13fd6dbc7f019971354ea0) fix(swagger): Fix the broken swagger. (#2317)
 * [efb8a1ac](https://github.com/argoproj/argo-workflows/commit/efb8a1ac8fc9961f0caa00ec6df7cf006d25e87a) docs: Update CODE_OF_CONDUCT.md (#2323)
 * [1c77e864](https://github.com/argoproj/argo-workflows/commit/1c77e864ac004f9cc6aff0e204ea9fd4b056c84b) fix(swagger): Fix the broken swagger. (#2317)
 * [aa052346](https://github.com/argoproj/argo-workflows/commit/aa05234694bc79e649e02adcc9790778cef0154d) feat: Support workflow level poddisruptionbudge for workflow pods #1728 (#2286)
 * [8da88d7e](https://github.com/argoproj/argo-workflows/commit/8da88d7ed20d8e533252e610337c15737445a225) chore: update getting-started guide for 2.5.2 and apply other tweaks (#2311)
 * [2f97c261](https://github.com/argoproj/argo-workflows/commit/2f97c261a9eafa022b464e0aea5b5d34d6f99100) build: Improve reliability of release. (#2309)
 * [5dcb84bb](https://github.com/argoproj/argo-workflows/commit/5dcb84bb549429ba5f46a21873e873a2c1c5bf67) chore(cli): Clean-up code. Closes #2117 (#2303)
 * [e49dd8c4](https://github.com/argoproj/argo-workflows/commit/e49dd8c4f9f69551be7e31c2044fef043d2992b2) chore(cli): Migrate `argo logs` to use API client. See #2116 (#2177)
 * [5c3d9cf9](https://github.com/argoproj/argo-workflows/commit/5c3d9cf93079ecbbfb024ea273d6e57e56c2506d) chore(cli): Migrate `argo wait` to use API client. See #2116 (#2282)
 * [baf03f67](https://github.com/argoproj/argo-workflows/commit/baf03f672728a6ed8b2aeb986d84ce35e9d7717a) fix(ui): Provide a link to archived logs. Fixes #2300 (#2301)
 * [b5947165](https://github.com/argoproj/argo-workflows/commit/b5947165564246a3c55375500f3fc1aea4dc6966) feat: Create API clients (#2218)
 * [214c4515](https://github.com/argoproj/argo-workflows/commit/214c451535ebeb6e68f1599c2c0a4a4d174ade25) fix(controller): Get correct Step or DAG name. Fixes #2244 (#2304)
 * [c4d26466](https://github.com/argoproj/argo-workflows/commit/c4d2646612d190ec73f38ec840259110a9ce89e0) fix: Remove active wf from Cron when deleted (#2299)
 * [0eff938d](https://github.com/argoproj/argo-workflows/commit/0eff938d62764abffcfdc741dfaca5fd6c8ae53f) fix: Skip empty withParam steps (#2284)
 * [636ea443](https://github.com/argoproj/argo-workflows/commit/636ea443c38869beaccfff19f4b72dd23755b2ff) chore(cli): Migrate `argo terminate` to use API client. See #2116 (#2280)
 * [d0a9b528](https://github.com/argoproj/argo-workflows/commit/d0a9b528e383a1b9ea737e0f919c93969d3d393b) chore(cli): Migrate `argo template` to use API client. Closes #2115 (#2296)
 * [f69a6c5f](https://github.com/argoproj/argo-workflows/commit/f69a6c5fa487d3b6c2d5383aa588695d6dcdb6de) chore(cli): Migrate `argo cron` to use API client. Closes #2114 (#2295)
 * [80b9b590](https://github.com/argoproj/argo-workflows/commit/80b9b590ebca1dbe69c5c7df0dd1c2f1feae5eea) chore(cli): Migrate `argo retry` to use API client. See #2116 (#2277)
 * [cdbc6194](https://github.com/argoproj/argo-workflows/commit/cdbc61945e09ae4dab8a56a085d050a0c358b896) fix(sequence): broken in 2.5. Fixes #2248 (#2263)
 * [0d3955a7](https://github.com/argoproj/argo-workflows/commit/0d3955a7f617c58f74c2892894036dfbdebaa5aa) refactor(cli): 2x simplify migration to API client. See #2116 (#2290)
 * [df8493a1](https://github.com/argoproj/argo-workflows/commit/df8493a1c05d3bac19a8f95f608d5543ba96ac82) fix: Start Argo server with out Configmap #2285 (#2293)
 * [51cdf95b](https://github.com/argoproj/argo-workflows/commit/51cdf95b18c8532f0bdb72c7ca20d56bdafc3a60) doc: More detail for namespaced installation (#2292)
 * [a7302697](https://github.com/argoproj/argo-workflows/commit/a730269767bdd10c4a9c5901c7e73f6bb25429c2) build(swagger): Fix argo-server swagger so version does not change. (#2291)
 * [47b4fc28](https://github.com/argoproj/argo-workflows/commit/47b4fc284df3cff9dfb4ea6622a0236bf1613096) fix(cli): Reinstate `argo wait`. Fixes #2281 (#2283)
 * [1793887b](https://github.com/argoproj/argo-workflows/commit/1793887b95446d341102b81523931403e30ef0f7) chore(cli): Migrate `argo suspend` and `argo resume` to use API client. See #2116 (#2275)
 * [1f3d2f5a](https://github.com/argoproj/argo-workflows/commit/1f3d2f5a0c9d772d7b204b13529f56bc33703a45) chore(cli): Update `argo resubmit` to support client API. See #2116 (#2276)
 * [c33f6cda](https://github.com/argoproj/argo-workflows/commit/c33f6cda39a3be40cc2e829c4c8d0b4c54704896) fix(archive): Fix bug in migrating cluster name. Fixes #2272 (#2279)
 * [fb0acbbf](https://github.com/argoproj/argo-workflows/commit/fb0acbbffb0a7c754223e516f55a40b957277fe4) fix: Fixes double logging in UI. Fixes #2270 (#2271)
 * [acf37c2d](https://github.com/argoproj/argo-workflows/commit/acf37c2db0d69def2045a6fc0f37a2b9db0c41fe) fix: Correctly report version. Fixes #2264 (#2268)
 * [b30f1af6](https://github.com/argoproj/argo-workflows/commit/b30f1af6528046a3af29c82ac1e29d9d300eec22) fix: Removes Template.Arguments as this is never used. Fixes #2046 (#2267)
 * [79b09ed4](https://github.com/argoproj/argo-workflows/commit/79b09ed43550bbf958c631386f8514b2d474062c) fix: Removed duplicate Watch Command (#2262)
 * [b5c47266](https://github.com/argoproj/argo-workflows/commit/b5c47266c4e33ba8739277ea43fe4b8023542367) feat(ui): Add filters for archived workflows (#2257)
 * [d30aa335](https://github.com/argoproj/argo-workflows/commit/d30aa3357738a272e1864d9f352f3c160c1608fc) fix(archive): Return correct next page info. Fixes #2255 (#2256)
 * [8c97689e](https://github.com/argoproj/argo-workflows/commit/8c97689e5d9d956a0dd9493c4c53088a6e8a87fa) fix: Ignore bookmark events for restart. Fixes #2249 (#2253)
 * [63858eaa](https://github.com/argoproj/argo-workflows/commit/63858eaa919c430bf0683dc33d81c94d4237b45b) fix(offloading): Change offloaded nodes datatype to JSON to support 1GB. Fixes #2246 (#2250)
 * [4d88374b](https://github.com/argoproj/argo-workflows/commit/4d88374b70e272eb454395f066c371ad2977abef) Add Cartrack into officially using Argo (#2251)
 * [d309d5c1](https://github.com/argoproj/argo-workflows/commit/d309d5c1a134502a11040757ff85230f7199510f) feat(archive): Add support to filter list by labels. Closes #2171 (#2205)
 * [79f13373](https://github.com/argoproj/argo-workflows/commit/79f13373fd8c4d0e9c9ff56f2133fa6009d1ed07) feat: Add a new symbol for suspended nodes. Closes #1896 (#2240)
 * [82b48821](https://github.com/argoproj/argo-workflows/commit/82b48821a83e012ac7ea5740d45addb046e3c8ee) Fix presumed typo (#2243)
 * [af94352f](https://github.com/argoproj/argo-workflows/commit/af94352f6c93e4bdbb69a1fc92b5d596c647d1a0) feat: Reduce API calls when changing filters. Closes #2231 (#2232)
 * [a58cbc7d](https://github.com/argoproj/argo-workflows/commit/a58cbc7dd12fe919614768ca0fa4714853091b7f) BasisAI uses Argo (#2241)
 * [68e3c9fd](https://github.com/argoproj/argo-workflows/commit/68e3c9fd9f597b6b4599dc7e9dbc5d71252ac5cf) feat: Add Pod Name to UI (#2227)
 * [eef85072](https://github.com/argoproj/argo-workflows/commit/eef85072691a9302e4168a072cfdffed6908a5d6) fix(offload): Fix bug which deleted completed workflows. Fixes #2233 (#2234)
 * [4e4565cd](https://github.com/argoproj/argo-workflows/commit/4e4565cdbb5d2e5c215af1b8b2f03695b45c2bba) feat: Label workflow-created pvc with workflow name (#1890)
 * [8bd5ecbc](https://github.com/argoproj/argo-workflows/commit/8bd5ecbc16f1063ef332ca3445ed9a9b953efa4f) fix: display error message when deleting archived workflow fails. (#2235)
 * [ae381ae5](https://github.com/argoproj/argo-workflows/commit/ae381ae57e5d2d3226114c773264595b3d672c39) feat: This add support to enable debug logging for all CLI commands (#2212)
 * [1b1927fc](https://github.com/argoproj/argo-workflows/commit/1b1927fc6fa519b7bf277e4273f4c7cede16ed64) feat(swagger): Adds a make api/argo-server/swagger.json (#2216)
 * [5d7b4c8c](https://github.com/argoproj/argo-workflows/commit/5d7b4c8c2d5819116b060f1ee656571b77b873bd) Update README.md (#2226)
 * [170abfa5](https://github.com/argoproj/argo-workflows/commit/170abfa5875227a74381764de93aa345aa5cca19) chore: Run `go mod tidy` (#2225)
 * [2981e6ff](https://github.com/argoproj/argo-workflows/commit/2981e6ff4c053b898a425d366fa696c8530ffeb0) fix: Enforce UnknownField requirement in WorkflowStep (#2210)
 * [affc235c](https://github.com/argoproj/argo-workflows/commit/affc235cd07bb01ee0ef8bb226b7a4c6470dc1e7) feat: Add failed node info to exit handler (#2166)
 * [af1f6d60](https://github.com/argoproj/argo-workflows/commit/af1f6d60078c5562b2c9d538d2b104c277c82593) fix: UI Responsive design on filter box (#2221)
 * [a445049c](https://github.com/argoproj/argo-workflows/commit/a445049ca3f67b499b9bef95c9e43075c8e10250) fix: Fixed race condition in kill container method. Fixes #1884 (#2208)
 * [2672857f](https://github.com/argoproj/argo-workflows/commit/2672857f2fbaabf727e354b040b1af2431ea70e5) feat: upgrade to Go 1.13. Closes #1375 (#2097)
 * [7466efa9](https://github.com/argoproj/argo-workflows/commit/7466efa99adfeeb3833b02c5afa7a33cdf8f87bc) feat: ArtifactRepositoryRef ConfigMap is now taken from the workflow namespace (#1821)
 * [50f331d0](https://github.com/argoproj/argo-workflows/commit/50f331d0e686f603440500c026ffe9d1f5133c1c) build: Fix ARGO_TOKEN (#2215)
 * [7f090351](https://github.com/argoproj/argo-workflows/commit/7f09035156e5dce68af203df21e688476d05ce12) test: Correctly report diagnostics (#2214)
 * [f2bd74bc](https://github.com/argoproj/argo-workflows/commit/f2bd74bca116f1b1ad9990aef9dbad98e0068900) fix: Remove quotes from UI (#2213)
 * [62f46680](https://github.com/argoproj/argo-workflows/commit/62f4668064e71046532505a11c67a675aa29afcf) fix(offloading): Correctly deleted offloaded data. Fixes #2206 (#2207)
 * [e30b77fc](https://github.com/argoproj/argo-workflows/commit/e30b77fcd5b140074065491988985779b800c4d7) feat(ui): Add label filter to workflow list page. Fixes #802 (#2196)
 * [930ced39](https://github.com/argoproj/argo-workflows/commit/930ced39241b427a521b609c403e7a39f6cc8c48) fix(ui): fixed workflow filtering and ordering. Fixes #2201 (#2202)
 * [88112312](https://github.com/argoproj/argo-workflows/commit/8811231299434e89ee9279e400db3445d83fec39) fix: Correct login instructions. (#2198)
 * [d6f5953d](https://github.com/argoproj/argo-workflows/commit/d6f5953d73d3940e0151011b7c32446c4c1c0ec4) Update ReadMe for EBSCO (#2195)
 * [b024c46c](https://github.com/argoproj/argo-workflows/commit/b024c46c8fec8a682802c1d6667a79fede959ae4) feat: Add ability to submit CronWorkflow from CLI (#2003)
 * [c97527ce](https://github.com/argoproj/argo-workflows/commit/c97527cee961b00472ce566226e1c6824b6e9793) test: Invoke tests using s.T() (#2194)
 * [72a54fe1](https://github.com/argoproj/argo-workflows/commit/72a54fe1628ff7a1daeb69875356607829d595ed) chore: Move info.proto et al to correct package (#2193)
 * [f6600fa4](https://github.com/argoproj/argo-workflows/commit/f6600fa499470ea7bd9fe68303759257c329d7ae) fix: Namespace and phase selection in UI (#2191)
 * [c4a24dca](https://github.com/argoproj/argo-workflows/commit/c4a24dcab016e82a4f1dc764dc67e0d8d324ded3) fix(k8sapi-executor): Fix KillContainer impl (#2160)
 * [d22a5fe6](https://github.com/argoproj/argo-workflows/commit/d22a5fe69c2d5a1fd4c268822cf5e2cd76893a18) Update cli_with_server_test.go (#2189)
 * [ff18180f](https://github.com/argoproj/argo-workflows/commit/ff18180f838b8f0d56bae95a2cab57d939e2a353) test: Remove podGC (#2187)
 * [78245305](https://github.com/argoproj/argo-workflows/commit/78245305d369fe9e4ba4c15e4acff7fcee07d62a) chore: Improved error handling and refactor (#2184)
 * [b9c828ad](https://github.com/argoproj/argo-workflows/commit/b9c828ad3a8fe6e92263aafd5eb14f21a284f3fc) fix(archive): Only delete offloaded data we do not need. Fixes #2170 and #2156 (#2172)
 * [73cb5418](https://github.com/argoproj/argo-workflows/commit/73cb5418f13e359612bb6844ef1747c9e7e6522c) feat: Allow CronWorkflows to have instanceId (#2081)
 * [9efea660](https://github.com/argoproj/argo-workflows/commit/9efea660b611f02a1eeaa5dc5be857686ed82de2) Sort list and add Greenhouse (#2182)
 * [cae399ba](https://github.com/argoproj/argo-workflows/commit/cae399bae466266bef0351efae77162615f9790f) fix: Fixed the Exec Provider token bug (#2181)
 * [fc476b2a](https://github.com/argoproj/argo-workflows/commit/fc476b2a4f09c12c0eb4a669b5cc1a18adca206e) fix(ui): Retry workflow event stream on connection loss. Fixes #2179 (#2180)
 * [65058a27](https://github.com/argoproj/argo-workflows/commit/65058a2798fd31ebd4fb99afc41da6a9171ca5be) fix: Correctly create code from changed protos. (#2178)
 * [585d1eef](https://github.com/argoproj/argo-workflows/commit/585d1eefd71062f42f8d80c85722fc7c262a08cf) chore: Update lint command to use apiclient. See #2116 (#2131)
 * [299d467c](https://github.com/argoproj/argo-workflows/commit/299d467c17cd89e9f33e48e464eb26ec8a3e413a) build: Update release process and docs (#2128)
 * [fcfe1d43](https://github.com/argoproj/argo-workflows/commit/fcfe1d43693c98f0e6c5fe3e2b02ac6a4a9836e6) feat: Implemented open default browser in local mode (#2122)
 * [f6cee552](https://github.com/argoproj/argo-workflows/commit/f6cee552532702089e62e5fece4dae77e4c99336) fix: Specify download .tgz extension (#2164)
 * [8a1e611a](https://github.com/argoproj/argo-workflows/commit/8a1e611a03da8374567c9654f8baf29b66c83c6e) feat: Update archived workdflow column to be JSON. Closes #2133 (#2152)
 * [f591c471](https://github.com/argoproj/argo-workflows/commit/f591c471c336e99c206094d21567fe01c978bf3c) fix!: Change `argo token` to `argo auth token`. Closes #2149 (#2150)
 * [519c9434](https://github.com/argoproj/argo-workflows/commit/519c94344a91c86d60ce27b383fa50846432cc9f) chore: Add Mock gen to make codegen (#2148)
 * [409a5154](https://github.com/argoproj/argo-workflows/commit/409a5154726dd16475b3aaf97f05f191cdb65808) fix: Add certs to argocli image. Fixes #2129 (#2143)
 * [b094802a](https://github.com/argoproj/argo-workflows/commit/b094802a03406328699bffad6deeceb5bdb61777) fix: Allow download of artifacs in server auth-mode. Fixes #2129 (#2147)
 * [520fa540](https://github.com/argoproj/argo-workflows/commit/520fa54073ab20a9bcd2f115f65f50d9761dc230) fix: Correct SQL syntax. (#2141)
 * [059cb9b1](https://github.com/argoproj/argo-workflows/commit/059cb9b1879361b77a293b3156bc9dfab2cefe71) fix: logs UI should fall back to archive (#2139)
 * [4cda9a05](https://github.com/argoproj/argo-workflows/commit/4cda9a05bf8cee20027132e4b3428ca9654bed5a) fix: route all unknown web content requests to index.html (#2134)
 * [14d8b5d3](https://github.com/argoproj/argo-workflows/commit/14d8b5d3913c2a6b320c564d6fc11c1d90769a97) fix: archiveLogs needs to copy stderr (#2136)
 * [91319ee4](https://github.com/argoproj/argo-workflows/commit/91319ee49f1fefec13233cb843b46f42cf5a9830) fixed ui navigation issues with basehref (#2130)
 * [7881b980](https://github.com/argoproj/argo-workflows/commit/7881b980bfdc6319d229956866e9131f95be412f) docs: Add CronWorkflow usage docs (#2124)
 * [badfd183](https://github.com/argoproj/argo-workflows/commit/badfd18335ec1b26d395ece0ad65d12aeb11beec) feat: Add support to delete by using labels. Depended on by #2116 (#2123)
 * [706d0f23](https://github.com/argoproj/argo-workflows/commit/706d0f231542e80156f93e39d28cd8e28f5d7042) test: Try and make e2e more robust. Fixes #2125 (#2127)
 * [a75ac1b4](https://github.com/argoproj/argo-workflows/commit/a75ac1b487a50bad19b3c58262fb3b170640ab4a) fix: mark CLI common.go vars and funcs as DEPRECATED (#2119)
 * [be21a0f1](https://github.com/argoproj/argo-workflows/commit/be21a0f17ed851032a16cfa90934a04662da6d2d) feat(server): Restart server when config changes. Fixes #2090 (#2092)
 * [b5cd72b0](https://github.com/argoproj/argo-workflows/commit/b5cd72b083fd173fe2552be9ea83e342cf395ceb) test: Parallelize Cron tests (#2118)
 * [b2bd25bc](https://github.com/argoproj/argo-workflows/commit/b2bd25bc2ba15f1ffa39bade75b09af5e3bb81a4) fix: Disable webpack dot rule (#2112)
 * [865b4f3a](https://github.com/argoproj/argo-workflows/commit/865b4f3a2b51cc08cf4a80423933a97f876af4a2) addcompany (#2109)
 * [213e3a9d](https://github.com/argoproj/argo-workflows/commit/213e3a9d9ec43b9f05fe7c5cf11d3f704a8649dd) fix: Fix Resource Deletion Bug (#2084)
 * [ab1de233](https://github.com/argoproj/argo-workflows/commit/ab1de233b47ec7c284fd20705b9efa00626877f7) refactor(cli): Introduce v1.Interface for CLI. Closes #2107 (#2048)
 * [7a19f85c](https://github.com/argoproj/argo-workflows/commit/7a19f85caa8760f28ffae6227a529823a0867218) feat: Implemented Basic Auth scheme (#2093)
 * [7611b9f6](https://github.com/argoproj/argo-workflows/commit/7611b9f6c6359680a4d450116ee893e4dc174811) fix(ui): Add support for bash href. Fixes ##2100 (#2105)
 * [516d05f8](https://github.com/argoproj/argo-workflows/commit/516d05f81a86c586bc19aad7836f35bb85130025)  fix: Namespace redirects no longer error and are snappier (#2106)
 * [16aed5c8](https://github.com/argoproj/argo-workflows/commit/16aed5c8ec0256fc78d95149435c37dac1db087a) fix: Skip running --token testing if it is not on CI (#2104)
 * [aece7e6e](https://github.com/argoproj/argo-workflows/commit/aece7e6ebdf2478dd7efa5706490c5c7abe858e6) Parse container ID in correct way on CRI-O. Fixes #2095 (#2096)
 * [b6a2be89](https://github.com/argoproj/argo-workflows/commit/b6a2be89689222470288339570aa0a719e775002) feat: support arg --token when talking to argo-server (#2027) (#2089)
 * [01d8cae1](https://github.com/argoproj/argo-workflows/commit/01d8cae1f49da35c135463ff45dc1a4d13ab1af7) build: adds `make env` to make testing easier (#2087)
 * [492842aa](https://github.com/argoproj/argo-workflows/commit/492842aa17cc447d68f1181c02990bfa7a78913a) docs(README): Add Capital One to user list (#2094)
 * [d56a0e12](https://github.com/argoproj/argo-workflows/commit/d56a0e12a283aaa5398e03fe423fed83d60ca370) fix(controller): Fix template resolution for step groups. Fixes #1868  (#1920)
 * [b97044d2](https://github.com/argoproj/argo-workflows/commit/b97044d2a47a79fab26fb0e3142c82e88a582f64) fix(security): Fixes an issue that allowed you to list archived workf… (#2079)
 * [c4f49cf0](https://github.com/argoproj/argo-workflows/commit/c4f49cf074ad874996145674d635165f6256ca15) refactor: Move server code (cmd/server/ -> server/) (#2071)
 * [2542454c](https://github.com/argoproj/argo-workflows/commit/2542454c1daf61bc3826fa370c21799059904093) fix(controller): Do not crash if cm is empty. Fixes #2069 (#2070)
 * [85fa9aaf](https://github.com/argoproj/argo-workflows/commit/85fa9aafa70a98ce999157bb900971f24bd81101) fix: Do not expect workflowChange to always be defined (#2068)
 * [6f65bc2b](https://github.com/argoproj/argo-workflows/commit/6f65bc2b77ddcf4616c78d6db4955bf839a0c21a) fix: "base64 -d" not always available, using "base64 --decode" (#2067)
 * [6f2c8802](https://github.com/argoproj/argo-workflows/commit/6f2c880280d490ba746a86d828ade61d8b58c7a5) feat(ui): Use cookies in the UI. Closes #1949 (#2058)
 * [4592aec6](https://github.com/argoproj/argo-workflows/commit/4592aec6805ce1110edcb7dc4e3e7454a2042441) fix(api): Change `CronWorkflowName` to `Name`. Fixes #1982 (#2033)
 * [e26c11af](https://github.com/argoproj/argo-workflows/commit/e26c11af747651c6642cf0abd3cbc4ccac7b95de) fix: only run archived wf testing when persistence is enabled (#2059)
 * [b3cab5df](https://github.com/argoproj/argo-workflows/commit/b3cab5dfbb5e5973b1dc448946d16ee0cd690d6a) fix: Fix permission test cases (#2035)
 * [b408e7cd](https://github.com/argoproj/argo-workflows/commit/b408e7cd28b95a08498f6e30fcbef385d0ff89f5) fix: nil pointer in GC (#2055)
 * [4ac11560](https://github.com/argoproj/argo-workflows/commit/4ac115606bf6f0b3c5c837020efd41bf90789a00) fix: offload Node Status in Get and List api call (#2051)
 * [dfdde1d0](https://github.com/argoproj/argo-workflows/commit/dfdde1d08b2a39d074729f1d64053a6e37453b32) ci: Run using our own cowsay image (#2047)
 * [71ba8238](https://github.com/argoproj/argo-workflows/commit/71ba823822c190bfdb71073604bb987bb938cff4) Update README.md (#2045)
 * [c7953052](https://github.com/argoproj/argo-workflows/commit/c795305268d5793e6672252ae6ff7fb6a54f23fd) fix(persistence): Allow `argo server` to run without persistence (#2050)
 * [1db74e1a](https://github.com/argoproj/argo-workflows/commit/1db74e1a2658fa7de925cd4c81fbfd98f648cd99) fix(archive): upsert archive + ci: Pin images on CI, add readiness probes, clean-up logging and other tweaks (#2038)
 * [c46c6836](https://github.com/argoproj/argo-workflows/commit/c46c6836706dce54aea4a13deee864bd3c6cb906) feat: Allow workflow-level parameters to be modified in the UI when submitting a workflow (#2030)
 * [faa9dbb5](https://github.com/argoproj/argo-workflows/commit/faa9dbb59753a068c64a1aa5923e3e359c0866d8) fix(Makefile): Rename staticfiles make target. Fixes #2010 (#2040)
 * [79a42d48](https://github.com/argoproj/argo-workflows/commit/79a42d48cec9c41269fbe736a61f3975fe2a9aea) docs: Update link to configure-artifact-repository.md (#2041)
 * [1a96007f](https://github.com/argoproj/argo-workflows/commit/1a96007fed6a57d14a0e364000b54a364293438b) fix: Redirect to correct page when using managed namespace. Fixes #2015 (#2029)
 * [78726314](https://github.com/argoproj/argo-workflows/commit/787263142162b62085572660f5e6497279f82ab1) fix(api): Updates proto message naming (#2034)
 * [4a1307c8](https://github.com/argoproj/argo-workflows/commit/4a1307c89e58f554af8e0cdc44e5e66e4623dfb4) feat: Adds support for MySQL. Fixes #1945 (#2013)
 * [d843e608](https://github.com/argoproj/argo-workflows/commit/d843e6085d51f409d32aefe6b6cf18bf6fd6bbd1) chore: Smoke tests are timing out, give them more time (#2032)
 * [5c98a14e](https://github.com/argoproj/argo-workflows/commit/5c98a14ecdc78a5be48f34c455d90782157c4cbe) feat(controller): Add audit logs to workflows. Fixes #1769 (#1930)
 * [2982c1a8](https://github.com/argoproj/argo-workflows/commit/2982c1a82cd6f1e7fb755a948d7a165aa0aeebc0) fix(validate): Allow placeholder in values taken from inputs. Fixes #1984 (#2028)
 * [3293c83f](https://github.com/argoproj/argo-workflows/commit/3293c83f6170ad4dc022067bb37f12d07d2834c1) feat: Add version to offload nodes. Fixes #1944 and #1946 (#1974)
 * [283bbf8d](https://github.com/argoproj/argo-workflows/commit/283bbf8df50d615dee867becc21569be760fc59e) build: `make clean` now only deletes dist directories (#2019)
 * [72fa88c9](https://github.com/argoproj/argo-workflows/commit/72fa88c9daf9ae42a8a1feb297a0b118505b32b0) build: Enable linting for tests. Closes #1971 (#2025)
 * [f8569ae9](https://github.com/argoproj/argo-workflows/commit/f8569ae913053c8ba4cd9ca72c9c237dd83200c0) feat: Auth refactoring to support single version token (#1998)
 * [eb360d60](https://github.com/argoproj/argo-workflows/commit/eb360d60ea81e8deefbaf41bcb76921acd08b16f) Fix README (#2023)
 * [ef1bd3a3](https://github.com/argoproj/argo-workflows/commit/ef1bd3a32c434c565defc7b325463e8d831262f2) fix typo (#2021)
 * [f25a45de](https://github.com/argoproj/argo-workflows/commit/f25a45deb4a7179044034da890884432e750d98a) feat(controller): Exposes container runtime executor as CLI option. (#2014)
 * [3b26af7d](https://github.com/argoproj/argo-workflows/commit/3b26af7dd4cc3d08ee50f3bc2f389efd516b9248) Enable s3 trace support. Bump version to v2.5.0. Tweak proto id to match Workflow (#2009)
 * [5eb15bb5](https://github.com/argoproj/argo-workflows/commit/5eb15bb5409f54f1a4759dde2479b7569e5f81e4) fix: Fix workflow level timeouts (#1369)
 * [5868982b](https://github.com/argoproj/argo-workflows/commit/5868982bcddf3b9c9ddb98151bf458f6868dce81) fix: Fixes the `test` job on master (#2008)
 * [29c85072](https://github.com/argoproj/argo-workflows/commit/29c850728fa701d62078910e1641588c959c28c5) fix: Fixed grammar on TTLStrategy (#2006)
 * [2f58d202](https://github.com/argoproj/argo-workflows/commit/2f58d202c21910500ecc4abdb9e23270c9791d0a) fix: v2 token bug (#1991)
 * [ed36d92f](https://github.com/argoproj/argo-workflows/commit/ed36d92f99ea65e06dc78b82923d74c57130dfc3) feat: Add quick start manifests to Git. Change auth-mode to default to server. Fixes #1990 (#1993)
 * [d1965c93](https://github.com/argoproj/argo-workflows/commit/d1965c9352c43d486b2d7cf99b0141fdb17eac2b) docs: Encourage users to upvote issues relevant to them (#1996)
 * [91331a89](https://github.com/argoproj/argo-workflows/commit/91331a894d713f085207e30406e72b8f65ad0227) fix: No longer delete the argo ns as this is dangerous (#1995)
 * [1a777cc6](https://github.com/argoproj/argo-workflows/commit/1a777cc6662b0c95ccf3de12c1a328c4cb12bc78) feat(cron): Added timezone support to cron workflows. Closes #1931 (#1986)
 * [48b85e57](https://github.com/argoproj/argo-workflows/commit/48b85e5705a235257b5926d0714eeb173b4347cb) fix: WorkflowTempalteTest fix (#1992)
 * [51dab8a4](https://github.com/argoproj/argo-workflows/commit/51dab8a4a79e5180d795ef10586e31ecf4075214) feat: Adds `argo server` command. Fixes #1966 (#1972)
 * [732e03bb](https://github.com/argoproj/argo-workflows/commit/732e03bb6cdc94ecd264fa76ecf71c29114b7769) chore: Added WorkflowTemplate test (#1989)
 * [27387d4b](https://github.com/argoproj/argo-workflows/commit/27387d4b52e99f83fe1c6ac9a0e65add669463d9) chore: Fix UI TODOs (#1987)
 * [dd704dd6](https://github.com/argoproj/argo-workflows/commit/dd704dd6557e972c8dc3c9816996305a23c80f37) feat: Renders namespace in UI. Fixes #1952 and #1959 (#1965)
 * [14d58036](https://github.com/argoproj/argo-workflows/commit/14d58036faa444ee49a4905a632db7e0a5ab60ba) feat(server): Argo Server. Closes #1331 (#1882)
 * [f69655a0](https://github.com/argoproj/argo-workflows/commit/f69655a09c82236d91703fbce2ee1a07fc3641be) fix: Added decompress in retry, resubmit and resume. (#1934)
 * [1e7ccb53](https://github.com/argoproj/argo-workflows/commit/1e7ccb53e8604654c073f6578ae024fd341f048a) updated jq version to 1.6 (#1937)
 * [c51c1302](https://github.com/argoproj/argo-workflows/commit/c51c1302f48cec5b9c6009b9b7e50962d338c679) feat: Enhancement for namespace installation mode configuration (#1939)
 * [6af100d5](https://github.com/argoproj/argo-workflows/commit/6af100d5470137cc17c019546f3cad2acf5e4a31) feat: Add suspend and resume to CronWorkflows CLI (#1925)
 * [232a465d](https://github.com/argoproj/argo-workflows/commit/232a465d00b6104fe4801b773b0b3ceffdafb116) feat: Added onExit handlers to Step and DAG (#1716)
 * [071eb112](https://github.com/argoproj/argo-workflows/commit/071eb1126cae351c5059246d2c375dc47175a3d6) docs: Update PR template to demand tests. (#1929)
 * [ae58527e](https://github.com/argoproj/argo-workflows/commit/ae58527eed40947078a7cb71da1dc3ab9c052a56) docs: Add CyberAgent to the list of Argo users (#1926)
 * [02022e4b](https://github.com/argoproj/argo-workflows/commit/02022e4bb36977253ff2e362f844b9596e768102) docs: Minor formatting fix (#1922)
 * [e4107bb8](https://github.com/argoproj/argo-workflows/commit/e4107bb831af9eb4b99753f7e324ec33042cdc55) Updated Readme.md for companies using Argo: (#1916)
 * [7e9b2b58](https://github.com/argoproj/argo-workflows/commit/7e9b2b58915c5cb51276e21c81344e010472cbae) feat: Support for scheduled Workflows with CronWorkflow CRD (#1758)
 * [5d7e9185](https://github.com/argoproj/argo-workflows/commit/5d7e91852b09ca2f3f912a8f1efaa6c28e07b524) feat: Provide values of withItems maps as JSON in {{item}}. Fixes #1905 (#1906)
 * [de3ffd78](https://github.com/argoproj/argo-workflows/commit/de3ffd78b9c16ed09065aeb16e966904e964a572)  feat: Enhanced Different TTLSecondsAfterFinished depending on if job is in Succeeded, Failed or Error, Fixes (#1883)
 * [94449876](https://github.com/argoproj/argo-workflows/commit/94449876f4a571ab279802d5ca4d5e938ca3d44d) docs: Add question option to issue templates (#1910)
 * [83ae2df4](https://github.com/argoproj/argo-workflows/commit/83ae2df4130468a95b720ce33c9b9e27e7005b17) fix: Decrease docker build time by ignoring node_modules (#1909)
 * [59a19069](https://github.com/argoproj/argo-workflows/commit/59a190697286bf19ee4a5c398c1af590a2419003) feat: support iam roles for service accounts in artifact storage (#1899)
 * [6526b6cc](https://github.com/argoproj/argo-workflows/commit/6526b6cc5e4671317fa0bc8c62440364c37a9700) fix: Revert node creation logic (#1818)
 * [160a7940](https://github.com/argoproj/argo-workflows/commit/160a794046299c9d0420ae1710641814f30a9b7f) fix: Update Gopkg.lock with dep ensure -update (#1898)
 * [ce78227a](https://github.com/argoproj/argo-workflows/commit/ce78227abe5a3c901e5b7a7dd823fb2551dff584) fix: quick fail after pod termination (#1865)
 * [cd3bd235](https://github.com/argoproj/argo-workflows/commit/cd3bd235f550fbc24c31d1763fde045c9c321fbe) refactor: Format Argo UI using prettier (#1878)
 * [b48446e0](https://github.com/argoproj/argo-workflows/commit/b48446e09e29d4f18f6a0cf0e6ff1166770286b1) fix: Fix support for continueOn failed for DAG. Fixes #1817 (#1855)
 * [48256961](https://github.com/argoproj/argo-workflows/commit/482569615734d7cb5e24c90d399f3ec98fb2ed96) fix: Fix template scope (#1836)
 * [eb585ef7](https://github.com/argoproj/argo-workflows/commit/eb585ef7381c4c9547eb9c2e922e175c0556da03) fix: Use dynamically generated placeholders (#1844)
 * [c821cfcc](https://github.com/argoproj/argo-workflows/commit/c821cfcce488222bcd5a4514cd94c66582885f33) test: Adds 'test' and 'ui' jobs to CI (#1869)
 * [54f44909](https://github.com/argoproj/argo-workflows/commit/54f44909a0e68bc24209e9e83999421b814e80c9) feat: Always archive logs if in config. Closes #1790 (#1860)
 * [1e25d6cf](https://github.com/argoproj/argo-workflows/commit/1e25d6cfa9c4c2f805717f94bd67ec612746a862) docs: Fix e2e testing link (#1873)
 * [f5f40728](https://github.com/argoproj/argo-workflows/commit/f5f40728c4be2d852e8199a5754aee39ed72399f) fix: Minor comment fix (#1872)
 * [72fad7ec](https://github.com/argoproj/argo-workflows/commit/72fad7ec0cf3aa463bd9c2c8c8f961738408cf93) Update docs (#1870)
 * [90352865](https://github.com/argoproj/argo-workflows/commit/9035286554768119b83e00294ea7c0b400b5de83) docs: Update doc based on helm 3.x changes (#1843)
 * [78889895](https://github.com/argoproj/argo-workflows/commit/788898954f7eff5b096f7597e74fc68104d8bf78) Move Workflows UI from https://github.com/argoproj/argo-ui (#1859)
 * [4b96172f](https://github.com/argoproj/argo-workflows/commit/4b96172f71f3fb36a691499b11e52a0d5650448a) docs: Refactored and cleaned up docs (#1856)
 * [6ba4598f](https://github.com/argoproj/argo-workflows/commit/6ba4598fd19c4add40b66d32df18592194c4cf4c) test: Adds core e2e test infra. Fixes #678 (#1854)
 * [87f26c8d](https://github.com/argoproj/argo-workflows/commit/87f26c8de2adc9563a3811aacc1eb31475a84f0b) fix: Move ISSUE_TEMPLATE/ under .github/ (#1858)
 * [bd78d159](https://github.com/argoproj/argo-workflows/commit/bd78d1597e82bf2bf0193e4bf49b6386c68e8222) fix: Ensure timer channel is empty after stop (#1829)
 * [afc63024](https://github.com/argoproj/argo-workflows/commit/afc63024de79c2e211a1ed0e0ede87b99825c63f) Code duplication (#1482)
 * [5b136713](https://github.com/argoproj/argo-workflows/commit/5b1367137d2b511b0310ac322596ff5395ed148d) docs: biobox analytics (#1830)
 * [68b72a8f](https://github.com/argoproj/argo-workflows/commit/68b72a8fd1773ba5f1afb4ec6ba9bf8a4d2b7ad4) add CCRi to list of users in README (#1845)
 * [941f30aa](https://github.com/argoproj/argo-workflows/commit/941f30aaf4e51e1eec13e842a0b8d46767929cec) Add Sidecar Technologies to list of who uses Argo (#1850)
 * [a08048b6](https://github.com/argoproj/argo-workflows/commit/a08048b6de84ff7355728b85851aa84b08be0851) Adding Wavefront to the users list (#1852)
 * [1cb68c98](https://github.com/argoproj/argo-workflows/commit/1cb68c9829099eb5218995159fb11fb58a147032) docs: Updates issue and PR templates. (#1848)
 * [cb0598ea](https://github.com/argoproj/argo-workflows/commit/cb0598ea82bd676fefd98e2040752cfa06516a98) Fixed Panic if DB context has issue (#1851)
 * [e5fb8848](https://github.com/argoproj/argo-workflows/commit/e5fb884853d2ad0d1f32022723e211b902841945) fix: Fix a couple of nil derefs (#1847)
 * [b3d45850](https://github.com/argoproj/argo-workflows/commit/b3d458504b319b3b02b82a872a5e13c59cb3128f) Add HOVER to the list of who uses Argo (#1825)
 * [99db30d6](https://github.com/argoproj/argo-workflows/commit/99db30d67b42cbd9c7fa35bbdd35a57040c2f222) InsideBoard uses Argo (#1835)
 * [ac8efcf4](https://github.com/argoproj/argo-workflows/commit/ac8efcf40e45750ae3c78f696f160049ea85dc8e) Red Hat uses Argo (#1828)
 * [41ed3acf](https://github.com/argoproj/argo-workflows/commit/41ed3acfb68c1200ea5f03643120cac81f7d3df6) Adding Fairwinds to the list of companies that use Argo (#1820)
 * [5274afb9](https://github.com/argoproj/argo-workflows/commit/5274afb97686a4d2a58c50c3b23dd2b680b881e6) Add exponential back-off to retryStrategy (#1782)
 * [e522e30a](https://github.com/argoproj/argo-workflows/commit/e522e30acebc17793540ac4270d14747b2617b26) Handle operation level errors PVC in Retry (#1762)
 * [f2e6054e](https://github.com/argoproj/argo-workflows/commit/f2e6054e9376f2d2be1d928ee79746b8b49937df) Do not resolve remote templates in lint (#1787)
 * [3852bc3f](https://github.com/argoproj/argo-workflows/commit/3852bc3f3311e9ac174976e9a3e8f625b87888eb) SSL enabled database connection for workflow repository (#1712) (#1756)
 * [f2676c87](https://github.com/argoproj/argo-workflows/commit/f2676c875e0af8e43b8967c669a33871bc02995c) Fix retry node name issue on error (#1732)
 * [d38a107c](https://github.com/argoproj/argo-workflows/commit/d38a107c84b91ad476f4760d984450efda296fdc) Refactoring Template Resolution Logic (#1744)
 * [23e94604](https://github.com/argoproj/argo-workflows/commit/23e9460451566e04b14acd336fccf54b0623efc4) Error occurred on pod watch should result in an error on the wait container (#1776)
 * [57d051b5](https://github.com/argoproj/argo-workflows/commit/57d051b52de7c9b78d926f0be7b158adb08803c8) Added hint when using certain tokens in when expressions (#1810)
 * [0e79edff](https://github.com/argoproj/argo-workflows/commit/0e79edff4b879558a19132035446fca2fbe3f2ca) Make kubectl print status and start/finished time (#1766)
 * [723b3c15](https://github.com/argoproj/argo-workflows/commit/723b3c15e55d2f8dceb86f1ac0a6dc7d1a58f10b) Fix code-gen docs (#1811)
 * [711bb114](https://github.com/argoproj/argo-workflows/commit/711bb11483a0ccb46600795c636c98d9c3a7f16c) Fix withParam node naming issue (#1800)
 * [4351a336](https://github.com/argoproj/argo-workflows/commit/4351a3360f6b20298a28a06be545bc349b22b9e4) Minor doc fix (#1808)
 * [efb748fe](https://github.com/argoproj/argo-workflows/commit/efb748fe35c6f24c736db8e002078abd02b57141) Fix some issues in examples (#1804)
 * [a3e31289](https://github.com/argoproj/argo-workflows/commit/a3e31289915e4d129a743b9284442775ef41a15c) Add documentation for executors (#1778)
 * [1ac75b39](https://github.com/argoproj/argo-workflows/commit/1ac75b39040e6f292ee322122a157e05f55f1f73) Add  to linter (#1777)
 * [3bead0db](https://github.com/argoproj/argo-workflows/commit/3bead0db3d2777638992ba5e11a2de1c65be162c) Add ability to retry nodes after errors (#1696)
 * [b50845e2](https://github.com/argoproj/argo-workflows/commit/b50845e22e8910d27291bab30f0c3dbef1fe5dad) Support no-headers flag (#1760)
 * [7ea2b2f8](https://github.com/argoproj/argo-workflows/commit/7ea2b2f8c10c3004c3c13a49d200df704895f93c) Minor rework of suspened node (#1752)
 * [9ab1bc88](https://github.com/argoproj/argo-workflows/commit/9ab1bc88f58c551208ce5e76eea0c6fb83359710) Update README.md (#1768)
 * [e66fa328](https://github.com/argoproj/argo-workflows/commit/e66fa328e396fe35dfad8ab1e3088ab088aea8be) Fixed lint issues (#1739)
 * [63e12d09](https://github.com/argoproj/argo-workflows/commit/63e12d0986cb4b138715b8f2b9c483de5547f64e) binary up version (#1748)
 * [1b7f9bec](https://github.com/argoproj/argo-workflows/commit/1b7f9becdfc47688018e6d71ac417fb7278637ab) Minor typo fix (#1754)
 * [4c002677](https://github.com/argoproj/argo-workflows/commit/4c002677e360beb9d6e4398618bafdce025cda42) fix blank lines (#1753)
 * [fae73826](https://github.com/argoproj/argo-workflows/commit/fae7382686d917d78e3909d1f6db79c272a1aa11) Fail suspended steps after deadline (#1704)
 * [b2d7ee62](https://github.com/argoproj/argo-workflows/commit/b2d7ee62e903c062b62da35dc390e38c05ba1591) Fix typo in docs (#1745)
 * [f2592448](https://github.com/argoproj/argo-workflows/commit/f2592448636bc35b7f9ec0fdc48b92135ba9852f) Removed uneccessary debug Println (#1741)
 * [846d01ed](https://github.com/argoproj/argo-workflows/commit/846d01eddc271f330e00414d1ea2277ac390651b) Filter workflows in list  based on name prefix (#1721)
 * [8ae688c6](https://github.com/argoproj/argo-workflows/commit/8ae688c6cbcc9494195431be7754fe69eb33a9f4) Added ability to auto-resume from suspended state (#1715)
 * [fb617b63](https://github.com/argoproj/argo-workflows/commit/fb617b63a09679bb74427cd5d13192b1fd8f48cf) unquote strings from parameter-file (#1733)
 * [34120341](https://github.com/argoproj/argo-workflows/commit/34120341747e0261425b49a5600c42efbb1812a3) example for pod spec from output of previous step (#1724)
 * [12b983f4](https://github.com/argoproj/argo-workflows/commit/12b983f4c00bda3f9bedd14a316b0beade6158ed) Add gonum.org/v1/gonum/graph to Gopkg.toml (#1726)
 * [327fcb24](https://github.com/argoproj/argo-workflows/commit/327fcb242b20107c859142b3dd68745b3440e5eb) Added  Protobuf extension  (#1601)
 * [602e5ad8](https://github.com/argoproj/argo-workflows/commit/602e5ad8e4002f7df0bd02014505cbc7de3fd37c) Fix invitation link. (#1710)
 * [eb29ae4c](https://github.com/argoproj/argo-workflows/commit/eb29ae4c89b89d4d4192a5f8c08d44ad31fa4cd2) Fixes bugs in demo (#1700)
 * [ebb25b86](https://github.com/argoproj/argo-workflows/commit/ebb25b861b1b452207582b6dea0060bf418037ff) `restartPolicy` -> `retryStrategy` in examples (#1702)
 * [167d65b1](https://github.com/argoproj/argo-workflows/commit/167d65b15ac0d3483071e0506f3e98a92a034183) Fixed incorrect `pod.name` in retry pods (#1699)
 * [e0818029](https://github.com/argoproj/argo-workflows/commit/e0818029d190cfd616527cccf208b5a9866224e1) fixed broke metrics endpoint per #1634 (#1695)
 * [36fd09a1](https://github.com/argoproj/argo-workflows/commit/36fd09a1321fd145b36b4f9067b61fabad363926) Apply Strategic merge patch against the pod spec (#1687)
 * [d3546467](https://github.com/argoproj/argo-workflows/commit/d35464670439b660c7c9ab0bcd9d3686ffe08687) Fix retry node processing (#1694)
 * [dd517e4c](https://github.com/argoproj/argo-workflows/commit/dd517e4c2db59b4c704ed7aeaed8505a757a60f7) Print multiple workflows in one command (#1650)
 * [09a6cb4e](https://github.com/argoproj/argo-workflows/commit/09a6cb4e81c1d9f5c8c082c9e96ce783fa20796f) Added status of previous steps as variables (#1681)
 * [ad3dd4d4](https://github.com/argoproj/argo-workflows/commit/ad3dd4d4a41b58e30983e8a93f06c1526c8aa9a0) Fix issue that workflow.priority substitution didn't pass validation (#1690)
 * [095d67f8](https://github.com/argoproj/argo-workflows/commit/095d67f8d0f1d309529c8a400cb16d0a0e2765b9) Store locally referenced template properly (#1670)
 * [30a91ef0](https://github.com/argoproj/argo-workflows/commit/30a91ef002e7c8850f45e6fe7ac01a7966ff31b8) Handle retried node properly (#1669)
 * [263cb703](https://github.com/argoproj/argo-workflows/commit/263cb7038b927fabe0f67b4455e17534b51c2989) Update README.md  Argo Ansible role: Provisioning Argo Workflows on Kubernetes/OpenShift (#1673)
 * [867f5ff7](https://github.com/argoproj/argo-workflows/commit/867f5ff7e72bc8b5d9b6be5a5f8849ccd2a1108c) Handle sidecar killing properly (#1675)
 * [f0ab9df9](https://github.com/argoproj/argo-workflows/commit/f0ab9df9ef8090fc388c32adbe9180dbaee683f5) Fix typo (#1679)
 * [502db42d](https://github.com/argoproj/argo-workflows/commit/502db42db84f317af8660d862ddd48c28cbd3b8e) Don't provision VM for empty artifacts (#1660)
 * [b5dcac81](https://github.com/argoproj/argo-workflows/commit/b5dcac8114d6f4b5fe32bae049d2c70b4dea4d15) Resolve WorkflowTemplate lazily (#1655)
 * [d15994bb](https://github.com/argoproj/argo-workflows/commit/d15994bbbb0a1ca8fc60b452ae532b10510c4762) [User] Update Argo users list (#1661)
 * [4a654ca6](https://github.com/argoproj/argo-workflows/commit/4a654ca6914923656bd1dc21ca5b8c4aa75b9e25) Stop failing if artifact file exists, but empty (#1653)
 * [c6cddafe](https://github.com/argoproj/argo-workflows/commit/c6cddafe19854d91bff41f093f48ac444a781c0d) Bug fixes in getting started (#1656)
 * [ec788373](https://github.com/argoproj/argo-workflows/commit/ec7883735e20f87fe483b26c947bd891a695a2bd) Update workflow_level_host_aliases.yaml (#1657)
 * [7e5af474](https://github.com/argoproj/argo-workflows/commit/7e5af4748d406f244378da86fda339a0c9e74476) Fix child node template handling (#1654)
 * [7f385a6b](https://github.com/argoproj/argo-workflows/commit/7f385a6bbf67ab780ab86c941cbd426f9b003834) Use stored templates to raggregate step outputs (#1651)
 * [cd6f3627](https://github.com/argoproj/argo-workflows/commit/cd6f3627992b6947dd47c98420d0a0fec4de9112) Fix dag output aggregation correctly (#1649)
 * [706075a5](https://github.com/argoproj/argo-workflows/commit/706075a55f694f94cfe729efca8eacb31d14f7f0) Fix DAG output aggregation (#1648)
 * [fa32dabd](https://github.com/argoproj/argo-workflows/commit/fa32dabdc0a5a74469a0e86e04b9868508503a73) Fix missing merged changes in validate.go (#1647)
 * [45716027](https://github.com/argoproj/argo-workflows/commit/457160275cc42be4c5fa6c1050c6e61a614b9544) fixed example wrong comment (#1643)
 * [69fd8a58](https://github.com/argoproj/argo-workflows/commit/69fd8a58d4877d616f3b576a2e8c8cbd224e029a) Delay killing sidecars until artifacts are saved (#1645)
 * [ec5f9860](https://github.com/argoproj/argo-workflows/commit/ec5f98605429f8d757f3b92fe6b2a2e8a4cb235f) pin colinmarc/hdfs to the next commit, which no longer has vendored deps (#1622)
 * [4b84f975](https://github.com/argoproj/argo-workflows/commit/4b84f975f14714cedad2dc9697c9a181075b04ea) Fix global lint issue (#1641)
 * [bb579138](https://github.com/argoproj/argo-workflows/commit/bb579138c6104baab70f859e8ed05954718c5ee8) Fix regression where global outputs were unresolveable in DAGs (#1640)
 * [cbf99682](https://github.com/argoproj/argo-workflows/commit/cbf99682c7a84306066b059834a625892b86d28c) Fix regression where parallelism could cause workflow to fail (#1639)
 * [76461f92](https://github.com/argoproj/argo-workflows/commit/76461f925e4e53cdf65b362115d09aa5325dea6b) Update CHANGELOG for v2.4.0 (#1636)
 * [c75a0861](https://github.com/argoproj/argo-workflows/commit/c75a08616e8e6bd1aeb37fc9fc824197491aec9c) Regenerate installation manifests (#1638)
 * [e20cb28c](https://github.com/argoproj/argo-workflows/commit/e20cb28cf8a4f331316535dcfd793ea91c281feb) Grant get secret role to controller to support persistence (#1615)
 * [644946e4](https://github.com/argoproj/argo-workflows/commit/644946e4e07672051f9be0f71ca0d2ca7641648e) Save stored template ID in nodes (#1631)
 * [5d530bec](https://github.com/argoproj/argo-workflows/commit/5d530becae49e1e235d72dd5ac29cc40282bc401) Fix retry workflow state (#1632)
 * [2f0af522](https://github.com/argoproj/argo-workflows/commit/2f0af5221030858e6a5306545ca3577aad17ac1a) Update operator.go (#1630)
 * [6acea0c1](https://github.com/argoproj/argo-workflows/commit/6acea0c1c21a17e14dc95632e80655f7fff09e2e) Store resolved templates (#1552)
 * [df8260d6](https://github.com/argoproj/argo-workflows/commit/df8260d6f64fcacc24c13cf5cc4a3fc3f0a6db18) Increase timeout of golangci-lint (#1623)
 * [138f89f6](https://github.com/argoproj/argo-workflows/commit/138f89f684cec5a8b237584e46199815922f98c3) updated invite link (#1621)
 * [d027188d](https://github.com/argoproj/argo-workflows/commit/d027188d0fce8e44bb0cefb2d46c1e55b9f112a2) Updated the API Rule Violations list (#1618)
 * [a317fbf1](https://github.com/argoproj/argo-workflows/commit/a317fbf1412c4636066def42cd6b7adc732319f3) Prevent controller from crashing due to glog writing to /tmp (#1613)
 * [20e91ea5](https://github.com/argoproj/argo-workflows/commit/20e91ea580e532b9c62f3bd16c5f6f8ed0838fdd) Added WorkflowStatus and NodeStatus types to the Open API Spec. (#1614)
 * [ffb281a5](https://github.com/argoproj/argo-workflows/commit/ffb281a5567666db68a5acab03ba7a0188954bf8) Small code cleanup and add tests (#1562)
 * [1cb8345d](https://github.com/argoproj/argo-workflows/commit/1cb8345de0694cffc30882eac59a05cb8eb06bc4) Add merge keys to Workflow objects to allow for StrategicMergePatches (#1611)
 * [c855a66a](https://github.com/argoproj/argo-workflows/commit/c855a66a6a9e3239fe5d585f5b5f36a07d48c5ed) Increased Lint timeout (#1612)
 * [4bf83fc3](https://github.com/argoproj/argo-workflows/commit/4bf83fc3d0d6b1e1d2c85f7b9b10a051134f7b0a) Fix DAG enable failFast will hang in some case (#1595)
 * [e9f3d9cb](https://github.com/argoproj/argo-workflows/commit/e9f3d9cbc029a9d55cf35ea51c2486078110bb2d) Do not relocate the mounted docker.sock (#1607)
 * [1bd50fa2](https://github.com/argoproj/argo-workflows/commit/1bd50fa2dfd828a04ff012868c98ba33bac41136) Added retry around RuntimeExecutor.Wait call when waiting for main container completion (#1597)
 * [0393427b](https://github.com/argoproj/argo-workflows/commit/0393427b54f397237152f5b74f6d09d0c20c1618) Issue1571  Support ability to assume IAM roles in S3 Artifacts  (#1587)
 * [ffc0c84f](https://github.com/argoproj/argo-workflows/commit/ffc0c84f509226f02d47cb2d5280faa7e2b92841) Update Gopkg.toml and Gopkg.lock (#1596)
 * [aa3a8f1c](https://github.com/argoproj/argo-workflows/commit/aa3a8f1c99fcb70bb199750644f74b17812cc586) Update from github.com/ghodss/yaml to sigs.k8s.io/yaml (#1572)
 * [07a26f16](https://github.com/argoproj/argo-workflows/commit/07a26f16747e3c71e76ba83b43336fd7a49622fb) Regard resource templates as leaf nodes (#1593)
 * [89e959e7](https://github.com/argoproj/argo-workflows/commit/89e959e7aaf396bc09cc012014e425ece2b5d644) Fix workflow template in namespaced controller (#1580)
 * [cd04ab8b](https://github.com/argoproj/argo-workflows/commit/cd04ab8bb923012182f2dc2b35dbf14726f7b1a4) remove redundant codes (#1582)
 * [5bba8449](https://github.com/argoproj/argo-workflows/commit/5bba8449ac7f3c563282eec1cb1f0dfc28d0d7c8) Add entrypoint label to workflow default labels (#1550)
 * [9685d7b6](https://github.com/argoproj/argo-workflows/commit/9685d7b67be91bf81059c1c96120a4fe6288399e) Fix inputs and arguments during template resolution (#1545)
 * [19210ba6](https://github.com/argoproj/argo-workflows/commit/19210ba635a4288f51eb2dd827f03715aea72750) added DataStax as an organization that uses Argo (#1576)
 * [b5f2fdef](https://github.com/argoproj/argo-workflows/commit/b5f2fdef097fe0fd69c60c6ada893547fd944d22) Support AutomountServiceAccountToken and executor specific service account(#1480)
 * [8808726c](https://github.com/argoproj/argo-workflows/commit/8808726cf3d0bc3aa71e3f1653262685dbfa0acf) Fix issue saving outputs which overlap paths with inputs (#1567)
 * [ba7a1ed6](https://github.com/argoproj/argo-workflows/commit/ba7a1ed650e7251dfadf5e9ae1fc2cdda7e9eaa2) Add coverage make target (#1557)
 * [ced0ee96](https://github.com/argoproj/argo-workflows/commit/ced0ee96ced59d9b070a1e81a9c148f78a69bfb9) Document workflow controller dockerSockPath config (#1555)
 * [3e95f2da](https://github.com/argoproj/argo-workflows/commit/3e95f2da6af78cc482009692b65cdc565a0ff412) Optimize argo binary install documentation (#1563)
 * [e2ebb166](https://github.com/argoproj/argo-workflows/commit/e2ebb166683d8a6c96502ce6e72f1a3ae48f0b4b) docs(readme): fix workflow types link (#1560)
 * [6d150a15](https://github.com/argoproj/argo-workflows/commit/6d150a15eb96183fb21faf6a49b0997e6150880b) Initialize the wfClientset before using it (#1548)
 * [5331fc02](https://github.com/argoproj/argo-workflows/commit/5331fc02e257266a4a5887dfe6277e5a0b42e7fc) Remove GLog config from argo executor (#1537)
 * [ed4ac6d0](https://github.com/argoproj/argo-workflows/commit/ed4ac6d0697401da6dec3989ecd63dd7567f0750) Update main.go (#1536)
 * [9fca1441](https://github.com/argoproj/argo-workflows/commit/9fca144128c97499d11f07a0ee008a9921e1f5f8) Update argo dependencies to kubernetes v1.14 (#1530)
 * [0246d184](https://github.com/argoproj/argo-workflows/commit/0246d184add04e44f77ffbe00e796b3adaf535d2) Use cache to retrieve WorkflowTemplates (#1534)
 * [4864c32f](https://github.com/argoproj/argo-workflows/commit/4864c32ffa40861c5ca066f67615da6d52eaa8b5) Update README.md (#1533)
 * [4df114fa](https://github.com/argoproj/argo-workflows/commit/4df114fae66e87727cfcb871731ec002af1515c7) Update CHANGELOG for v2.4 (#1531)
 * [c7e5cba1](https://github.com/argoproj/argo-workflows/commit/c7e5cba14a835fbfd0aba88b99197675ce1f0c66) Introduce podGC strategy for deleting completed/successful pods (#1234)
 * [bb0d14af](https://github.com/argoproj/argo-workflows/commit/bb0d14af9d320a141cb307b6a883c1eaafa498c3) Update ISSUE_TEMPLATE.md (#1528)
 * [b5702d8a](https://github.com/argoproj/argo-workflows/commit/b5702d8ae725c5caa4058d39f77e6d1e7e549da4) Format sources and order imports with the help of goimports (#1504)
 * [d3ff77bf](https://github.com/argoproj/argo-workflows/commit/d3ff77bf475095c73f034fb3b23c279c62f4269e) Added Architecture doc (#1515)
 * [fc1ec1a5](https://github.com/argoproj/argo-workflows/commit/fc1ec1a51462c9a114417db801e3a9715d3dc6b4) WorkflowTemplate CRD (#1312)
 * [f99d3266](https://github.com/argoproj/argo-workflows/commit/f99d3266d1879579338f124c56f1fc14867308a3) Expose all input parameters to template as JSON (#1488)
 * [bea60526](https://github.com/argoproj/argo-workflows/commit/bea605261be82d8bb91bf703ad68875f1093ebb8) Fix argo logs empty content when workflow run in virtual kubelet env (#1201)
 * [d82de881](https://github.com/argoproj/argo-workflows/commit/d82de8813910afaf9b3fb77d029faa7953bfee3a) Implemented support for WorkflowSpec.ArtifactRepositoryRef (#1350)
 * [0fa20c7b](https://github.com/argoproj/argo-workflows/commit/0fa20c7ba317d8c9a837bcc37d92f3fe79808499) Fix validation (#1508)
 * [87e2cb60](https://github.com/argoproj/argo-workflows/commit/87e2cb6043a305839ca37cc77c7611aaa7bdbd44) Add --dry-run option to `argo submit` (#1506)
 * [e7e50af6](https://github.com/argoproj/argo-workflows/commit/e7e50af6e56b1eeddccc82a2dbc8b421d1a63942) Support git shallow clones and additional ref fetches (#1521)
 * [605489cd](https://github.com/argoproj/argo-workflows/commit/605489cd5dd688527e60efee0aff239e3439c2dc) Allow overriding workflow labels in 'argo submit' (#1475)
 * [47eba519](https://github.com/argoproj/argo-workflows/commit/47eba519107c229edf61dbe024a6a5e0f1618a8d) Fix issue [Documentation] kubectl get service argo-artifacts -o wide (#1516)
 * [02f38262](https://github.com/argoproj/argo-workflows/commit/02f38262c40901346ddd622685bc6bfd344a2717) Fixed #1287 Executor kubectl version is obsolete (#1513)
 * [f62105e6](https://github.com/argoproj/argo-workflows/commit/f62105e659a22ccc0875151698eab540090885f6) Allow Makefile variables to be set from the command line (#1501)
 * [e62be65b](https://github.com/argoproj/argo-workflows/commit/e62be65ba25ae68a1bed10bddf33b4dae4991249) Fix a compiler error in a unit test (#1514)
 * [5c5c29af](https://github.com/argoproj/argo-workflows/commit/5c5c29af729b39f5f9b8a7fe6b8c1dede53eae3a) Fix the lint target (#1505)
 * [e03287bf](https://github.com/argoproj/argo-workflows/commit/e03287bfb7f97f639c8d81617808f709ca547eaa) Allow output parameters with .value, not only .valueFrom (#1336)
 * [781d3b8a](https://github.com/argoproj/argo-workflows/commit/781d3b8ae243b2c32ea3c4abd5b4a99fe9fc9cad) Implemented Conditionally annotate outputs of script template only when consumed #1359 (#1462)
 * [b028e61d](https://github.com/argoproj/argo-workflows/commit/b028e61db71e74b5730469a5f23a734937ddb8d9) change 'continue-on-fail' example to better reflect its description (#1494)
 * [97e824c9](https://github.com/argoproj/argo-workflows/commit/97e824c9a5b71baea658e8de6130bee089fb764d) Readme update to add argo and airflow comparison (#1502)
 * [414d6ce7](https://github.com/argoproj/argo-workflows/commit/414d6ce7b8aebcbd3b8822f407ec71ed465c103d) Fix a compiler error (#1500)
 * [ca1d5e67](https://github.com/argoproj/argo-workflows/commit/ca1d5e671519aaa9f38f5f2564eb70c138fadda7) Fix: Support the List within List type in withParam #1471 (#1473)
 * [75cb8b9c](https://github.com/argoproj/argo-workflows/commit/75cb8b9cd92cd7fcce4b921b88232bb05f2672b2) Fix #1366 unpredictable global artifact behavior (#1461)
 * [082e5c4f](https://github.com/argoproj/argo-workflows/commit/082e5c4f617c4120584ad601a8d85e0a3ce36a26) Exposed workflow priority as a variable (#1476)
 * [38c4def7](https://github.com/argoproj/argo-workflows/commit/38c4def7fb100e954757649553db8c04ea64f318) Fix: Argo CLI should show warning if there is no workflow definition in file #1486
 * [af7e496d](https://github.com/argoproj/argo-workflows/commit/af7e496db6ee8c10c9a2b6b51a27265bc6b0ee6d) Add Commodus Tech as official user (#1484)
 * [8c559642](https://github.com/argoproj/argo-workflows/commit/8c559642f2ec8abaea3204279fa3d6ff5ad40add) Update OWNERS (#1485)
 * [007d1f88](https://github.com/argoproj/argo-workflows/commit/007d1f8816736a758fa3720f0081e01dbc4200e3) Fix: 1008 `argo wait` and `argo submit --wait` should exit 1 if workflow fails  (#1467)
 * [3ab7bc94](https://github.com/argoproj/argo-workflows/commit/3ab7bc94c01d7a470bd05198b99c33e1a0221847) Document the insecureIgnoreHostKey git flag (#1483)
 * [7d9bb51a](https://github.com/argoproj/argo-workflows/commit/7d9bb51ae328f1a8cc7daf7d8ef108cf190df0ce) Fix failFast bug:   When a node in the middle fails, the entire workflow will hang (#1468)
 * [42adbf32](https://github.com/argoproj/argo-workflows/commit/42adbf32e8d4c626c544795c2fc1adb70676e968) Add --no-color flag to logs (#1479)
 * [67fc29c5](https://github.com/argoproj/argo-workflows/commit/67fc29c57db795a7020f355ab32cd883cfaf701e) fix typo: symboloic > symbolic (#1478)
 * [7c3e1901](https://github.com/argoproj/argo-workflows/commit/7c3e1901f49fe34cbe9d084274f6e64c48270635) Added Codec to the Argo community list (#1477)
 * [0a9cf9d3](https://github.com/argoproj/argo-workflows/commit/0a9cf9d3b06a3b304c0c690a298d8dc3d51c015b) Add doc about failFast feature (#1453)
 * [6a590300](https://github.com/argoproj/argo-workflows/commit/6a5903000fe8a7b3610c32435b2363cbf6334d1b) Support PodSecurityContext (#1463)
 * [e392d854](https://github.com/argoproj/argo-workflows/commit/e392d854bf78db89413782a23e62b0e38cf9c780) issue-1445: changing temp directory for output artifacts from root to tmp (#1458)
 * [7a21adfe](https://github.com/argoproj/argo-workflows/commit/7a21adfeb0af18c2452648a8bb3698a687f99b5e) New Feature:  provide failFast flag, allow a DAG to run all branches of the DAG (either success or failure) (#1443)
 * [b9b87b7f](https://github.com/argoproj/argo-workflows/commit/b9b87b7fa0cd3177c2b89cacff189f4893c5af95) Centralized Longterm workflow persistence storage  (#1344)
 * [cb09609b](https://github.com/argoproj/argo-workflows/commit/cb09609bd646a394c3a6f739dd447022a2bdb327) mention sidecar in failure message for sidecar containers (#1430)
 * [373bbe6e](https://github.com/argoproj/argo-workflows/commit/373bbe6ec9e819c39152292f79752792ce40b94d) Fix demo's doc issue of install minio chart (#1450)
 * [83552334](https://github.com/argoproj/argo-workflows/commit/835523341bcc96b6e9358be71e7432d0ac4058c5) Add threekit to user list (#1444)
 * [83f82ad1](https://github.com/argoproj/argo-workflows/commit/83f82ad172de0472643495d3ef3e0ce6d959900a) Improve bash completion (#1437)
 * [ee0ec78a](https://github.com/argoproj/argo-workflows/commit/ee0ec78ac98eaa112d343906a6e9b6490c39817f) Update documentation for workflow.outputs.artifacts (#1439)
 * [9e30c06e](https://github.com/argoproj/argo-workflows/commit/9e30c06e32b072b87e0d17095448d114175c713f) Revert "Update demo.md (#1396)" (#1433)
 * [c08de630](https://github.com/argoproj/argo-workflows/commit/c08de6300c3b394c34a5b3596455dcb50c29af48) Add paging function for list command (#1420)
 * [bba2f9cb](https://github.com/argoproj/argo-workflows/commit/bba2f9cbe9aa0eb053c19b03bc8fa7c002f579b0) Fixed:  Implemented Template level service account (#1354)
 * [d635c1de](https://github.com/argoproj/argo-workflows/commit/d635c1def74936869edbd8b9037ac81ea0af1772) Ability to configure hostPath mount for `/var/run/docker.sock` (#1419)
 * [d2f7162a](https://github.com/argoproj/argo-workflows/commit/d2f7162ac26550642ebe1792c65fb5e6ca9c0e7a) Terminate all containers within pod after main container completes (#1423)
 * [1607d74a](https://github.com/argoproj/argo-workflows/commit/1607d74a8de0704b82627364645a99b699d40cc0) PNS executor intermitently failed to capture entire log of script templates (#1406)
 * [5e47256c](https://github.com/argoproj/argo-workflows/commit/5e47256c7f86b56cfbf2ce53f73ed093eef2e3b6) Fix typo (#1431)
 * [5635c33a](https://github.com/argoproj/argo-workflows/commit/5635c33aa263080fe84e29a11a52f86fee583ca2) Update demo.md (#1396)
 * [83425455](https://github.com/argoproj/argo-workflows/commit/83425455bff34527e65ca1371347eed5203ae99a) Add OVH as official user (#1417)
 * [82e5f63d](https://github.com/argoproj/argo-workflows/commit/82e5f63d3680e7e4a22747803b0753b5ec31d2ad) Typo fix in ARTIFACT_REPO.md (#1425)
 * [15fa6f52](https://github.com/argoproj/argo-workflows/commit/15fa6f52d926ee5e839321900f613f6e546e6b6e) Update OWNERS (#1429)
 * [96b9a40e](https://github.com/argoproj/argo-workflows/commit/96b9a40e9aafe9c0132ce1b9f1eb01f05c3894ca) Orders uses alphabetically (#1411)
 * [6550e2cb](https://github.com/argoproj/argo-workflows/commit/6550e2cb10112ddf6435755958387ffa6ada0ef5) chore: add IBM to official users section in README.md (#1409)
 * [bc81fe28](https://github.com/argoproj/argo-workflows/commit/bc81fe288ebf9811774b36dd6eba9a851ac7717e) Fiixed: persistentvolumeclaims already exists #1130 (#1363)
 * [6a042d1f](https://github.com/argoproj/argo-workflows/commit/6a042d1f7eb01f1f369c2325aecebf71a3bea3a4) Update README.md (#1404)
 * [aa811fbd](https://github.com/argoproj/argo-workflows/commit/aa811fbdb914fe386cfbf3fa84a51bfd5104b5d0) Update README.md (#1402)
 * [abe3c99f](https://github.com/argoproj/argo-workflows/commit/abe3c99f19a1ec28775a276b50ad588a2dd660ca) Add Mirantis as an official user (#1401)
 * [18ab750a](https://github.com/argoproj/argo-workflows/commit/18ab750aea4de8f7dc67433f4e73505c80e13222) Added Argo Rollouts to README (#1388)
 * [67714f99](https://github.com/argoproj/argo-workflows/commit/67714f99b4bf664eb5e853b25ebf4b12bb98f733) Make locating kubeconfig in example os independent (#1393)
 * [672dc04f](https://github.com/argoproj/argo-workflows/commit/672dc04f737a3be099fe64c343587c35074b0938) Fixed: withParam parsing of JSON/YAML lists #1389 (#1397)
 * [b9aec5f9](https://github.com/argoproj/argo-workflows/commit/b9aec5f9833d5fa2055d06d1a71fdb75709eea21) Fixed: make verify-codegen is failing on the master branch (#1399) (#1400)
 * [270aabf1](https://github.com/argoproj/argo-workflows/commit/270aabf1d8cabd69b9851209ad5d9c874348e21d) Fixed:  failed to save outputs: verify serviceaccount default:default has necessary privileges (#1362)
 * [163f4a5d](https://github.com/argoproj/argo-workflows/commit/163f4a5d322352bd98f9a88ebd6089cf5e5b49ad) Fixed: Support hostAliases in WorkflowSpec #1265 (#1365)
 * [abb17478](https://github.com/argoproj/argo-workflows/commit/abb174788dce1bc6bed993a2967f7d8e112e44ca) Add Max Kelsen to USERS in README.md (#1374)
 * [dc549193](https://github.com/argoproj/argo-workflows/commit/dc5491930e09eebe700952e28359deeb8e0d2314) Update docs for the v2.3.0 release and to use the stable tag
 * [4001c964](https://github.com/argoproj/argo-workflows/commit/4001c964dbc70962e1cc1d80a4aff64cf8594ec3) Update README.md (#1372)
 * [6c18039b](https://github.com/argoproj/argo-workflows/commit/6c18039be962996d971145be8349d2ed3e396c80) Fix issue where a DAG with exhausted retries would get stuck Running (#1364)
 * [d7e74fe3](https://github.com/argoproj/argo-workflows/commit/d7e74fe3a96277ba532e4a2f40303a92d2d0ce94) Validate action for resource templates (#1346)
 * [810949d5](https://github.com/argoproj/argo-workflows/commit/810949d5106b4d1d533b647d1d61559c208b590a) Fixed :  CLI Does Not Honor metadata.namespace #1288 (#1352)
 * [e58859d7](https://github.com/argoproj/argo-workflows/commit/e58859d79516508838fead8222f0e26a6c2a2861) [Fix #1242] Failed DAG nodes are now kept and set to running on RetryWorkflow. (#1250)
 * [d5fe5f98](https://github.com/argoproj/argo-workflows/commit/d5fe5f981fb112ba01ed77521ae688f8a15f67b9) Use golangci-lint instead of deprecated gometalinter (#1335)
 * [26744d10](https://github.com/argoproj/argo-workflows/commit/26744d100e91eb757f48bfedd539e7e4a044faf3) Support an easy way to set owner reference (#1333)
 * [8bf7578e](https://github.com/argoproj/argo-workflows/commit/8bf7578e1884c61128603bbfaa677fd79cc17ea8) Add --status filter for get command (#1325)
 * [3f6ac9c9](https://github.com/argoproj/argo-workflows/commit/3f6ac9c9f1ccd92d4dabf52e964a1dd52b1622f6) Update release instructions
 * [2274130d](https://github.com/argoproj/argo-workflows/commit/2274130dc55de0b019ac9fd5232c192364f275c9) Update version to v2.3.0-rc3
 * [b024b3d8](https://github.com/argoproj/argo-workflows/commit/b024b3d83a4bfd46bd6b4a5075e9f8f968457309) Fix: # 1328 argo submit --wait and argo wait quits while workflow is running (#1347)
 * [24680b7f](https://github.com/argoproj/argo-workflows/commit/24680b7fc8a1fd573b39d61ba7bdce5b143eb686) Fixed : Validate the secret credentials name and key (#1358)
 * [f641d84e](https://github.com/argoproj/argo-workflows/commit/f641d84eb5cd489c98b39b41b69dbea9a3312e01) Fix input artifacts with multiple ssh keys (#1338)
 * [e680bd21](https://github.com/argoproj/argo-workflows/commit/e680bd219a2478835d5d8cefcbfb96bd11acc40b) add / test (#1240)
 * [ee788a8a](https://github.com/argoproj/argo-workflows/commit/ee788a8a6c70c5c64f535b6a901e837a9b4d5797) Fix #1340 parameter substitution bug (#1345)
 * [60b65190](https://github.com/argoproj/argo-workflows/commit/60b65190a22e176429e586afe58a86a14b390c66) Fix missing template local volumes, Handle volumes only used in init containers (#1342)
 * [4e37a444](https://github.com/argoproj/argo-workflows/commit/4e37a444bde2a034885d0db35f7b38684505063e) Add documentation on releasing
 * [bb1bfdd9](https://github.com/argoproj/argo-workflows/commit/bb1bfdd9106d9b64aa2dccf8d3554bdd31513cf8) Update version to v2.3.0-rc2. Update changelog
 * [49a6b6d7](https://github.com/argoproj/argo-workflows/commit/49a6b6d7ac1bb5f6b390eff1b218205d995142cb) wait will conditionally become privileged if main/sidecar privileged (resolves #1323)
 * [34af5a06](https://github.com/argoproj/argo-workflows/commit/34af5a065e42230148b48603fc81f57fb2b4c22c) Fix regression where argoexec wait would not return when podname was too long
 * [bd8d5cb4](https://github.com/argoproj/argo-workflows/commit/bd8d5cb4b7510afb7bd43bd75e5c5d26ccc85ca4) `argo list` was not displaying non-zero priorities correctly
 * [64370a2d](https://github.com/argoproj/argo-workflows/commit/64370a2d185db66a8d2188d986c52a3b73aaf92b) Support parameter substitution in the volumes attribute (#1238)
 * [6607dca9](https://github.com/argoproj/argo-workflows/commit/6607dca93db6255a2abc30ae76b5f935fce5735d) Issue1316 Pod creation with secret volumemount  (#1318)
 * [a5a2bcf2](https://github.com/argoproj/argo-workflows/commit/a5a2bcf21900019d979328250009af4137f7ff2a) Update README.md (#1321)
 * [950de1b9](https://github.com/argoproj/argo-workflows/commit/950de1b94efc18473a85e1f23c9ed5e6ff75ba93) Export the methods of `KubernetesClientInterface` (#1294)
 * [1c729a72](https://github.com/argoproj/argo-workflows/commit/1c729a72a2ae431623332b65646c97cb689eab01) Update v2.3.0 CHANGELOG.md
 * [40f9a875](https://github.com/argoproj/argo-workflows/commit/40f9a87593d312a46f7fa24aaf32e125458cc701) Reorganize manifests to kustomize 2 and update version to v2.3.0-rc1
 * [75b28a37](https://github.com/argoproj/argo-workflows/commit/75b28a37b923e278fc89fd647f78a42e7a3bf029) Implement support for PNS (Process Namespace Sharing) executor (#1214)
 * [b4edfd30](https://github.com/argoproj/argo-workflows/commit/b4edfd30b0e3034d98e938b491cf5bd054b36525) Fix SIGSEGV in watch/CheckAndDecompress. Consolidate duplicate code (resolves #1315)
 * [02550be3](https://github.com/argoproj/argo-workflows/commit/02550be31e53da79f1f4dbebda3ede7dc1052086) Archive location should conditionally be added to template only when needed
 * [c60010da](https://github.com/argoproj/argo-workflows/commit/c60010da29bd36c10c6e627802df6d6a06c1a59a) Fix nil pointer dereference with secret volumes (#1314)
 * [db89c477](https://github.com/argoproj/argo-workflows/commit/db89c477d65a29fc0a95ca55f68e1bd23d0170e0) Fix formatting issues in examples documentation (#1310)
 * [0d400f2c](https://github.com/argoproj/argo-workflows/commit/0d400f2ce6db9478b4eaa6fe24849a686c9d1d44) Refactor checkandEstimate to optimize podReconciliation (#1311)
 * [bbdf2e2c](https://github.com/argoproj/argo-workflows/commit/bbdf2e2c8f1b5a8dc83e88fedba9b1899f6bc78b) Add alibaba cloud to officially using argo list (#1313)
 * [abb77062](https://github.com/argoproj/argo-workflows/commit/abb77062fc06ae964ce7ccd1a534ec8bbdf3747c) CheckandEstimate implementation to optimize podReconciliation (#1308)
 * [1a028d54](https://github.com/argoproj/argo-workflows/commit/1a028d5458ffef240f8af31caeecda91f057c3ba) Secrets should be passed to pods using volumes instead of API calls (#1302)
 * [e34024a3](https://github.com/argoproj/argo-workflows/commit/e34024a3ca285d1af3b5ba3b3235dc7adc0472b7) Add support for init containers (#1183)
 * [4591e44f](https://github.com/argoproj/argo-workflows/commit/4591e44fe0e4de543f4c4339de0808346e0807e3) Added support for artifact path references (#1300)
 * [928e4df8](https://github.com/argoproj/argo-workflows/commit/928e4df81c4b33f0c0750f01b3aa3c4fc7ff256c) Add Karius to users in README.md (#1305)
 * [de779f36](https://github.com/argoproj/argo-workflows/commit/de779f36122205790915622f5ee91c9a9d5b9086) Add community meeting notes link (#1304)
 * [a8a55579](https://github.com/argoproj/argo-workflows/commit/a8a55579131605d4dc769cb599bc99c06350dfb7) Speed up podReconciliation using parallel goroutine (#1286)
 * [93451119](https://github.com/argoproj/argo-workflows/commit/934511192e4045b87be1675ff7e9dfa79faa9fcb) Add dns config support (#1301)
 * [850f3f15](https://github.com/argoproj/argo-workflows/commit/850f3f15dd1965e99cd636711a5e3306bc4bd0c0) Admiralty: add link to blog post, add user (#1295)
 * [d5f4b428](https://github.com/argoproj/argo-workflows/commit/d5f4b428ce02de34a37d5cb2fdba4dfa9fd16e75) Fix for Resource creation where template has same parameter templating (#1283)
 * [9b555cdb](https://github.com/argoproj/argo-workflows/commit/9b555cdb30f6092d5f53891f318fb74b8371c039) Issue#896 Workflow steps with non-existant output artifact path will succeed (#1277)
 * [adab9ed6](https://github.com/argoproj/argo-workflows/commit/adab9ed6bc4f8f337105182c56abad39bccb9676) Argo CI is current inactive (#1285)
 * [59fcc5cc](https://github.com/argoproj/argo-workflows/commit/59fcc5cc33ce67c057064dc37a463707501615e1) Add workflow labels and annotations global vars (#1280)
 * [1e111caa](https://github.com/argoproj/argo-workflows/commit/1e111caa1d2cc672b3b53c202b96a5f660a7e9b2) Fix bug with DockerExecutor's CopyFile (#1275)
 * [73a37f2b](https://github.com/argoproj/argo-workflows/commit/73a37f2b2a12d74ddf6a4b54e04b50fa1a7c68a1) Add the `mergeStrategy` option to resource patching (#1269)
 * [e6105243](https://github.com/argoproj/argo-workflows/commit/e6105243c785d9f53aef6fcfd344e855ad4f7d84) Reduce redundancy pod label action (#1271)
 * [4bfbb20b](https://github.com/argoproj/argo-workflows/commit/4bfbb20bc23f8bf4611a6314fb80f8138b17b9b9) Error running 1000s of tasks: "etcdserver: request is too large" #1186 (#1264)
 * [b2743f30](https://github.com/argoproj/argo-workflows/commit/b2743f30c411f5ad8f8c8b481a5d6b6ff83c33bd) Proxy Priority and PriorityClassName to pods (#1179)
 * [70c130ae](https://github.com/argoproj/argo-workflows/commit/70c130ae626f7c58d9e5ac0eed8977f51696fcbd) Update versions (#1218)
 * [b0384129](https://github.com/argoproj/argo-workflows/commit/b03841297e4b0dab0380b441cf41f5ed34db44bf) Git cloning via SSH was not verifying host public key (#1261)
 * [3f06385b](https://github.com/argoproj/argo-workflows/commit/3f06385b129c02e23ea283f7c66d347cb8899564) Issue#1165 fake outputs don't notify and task completes successfully (#1247)
 * [fa042aa2](https://github.com/argoproj/argo-workflows/commit/fa042aa285947c5fa365ef06a9565d0b4e20da0e) typo, executo -> executor (#1243)
 * [1cb88bae](https://github.com/argoproj/argo-workflows/commit/1cb88baee9ded1ede27a9d3f1e31f06f4369443d) Fixed Issue#1223 Kubernetes Resource action: patch is not supported (#1245)
 * [2b0b8f1c](https://github.com/argoproj/argo-workflows/commit/2b0b8f1c3f46aa41e4b4ddaf14ad1fdebccfaf8a) Fix the Prometheus address references (#1237)
 * [94cda3d5](https://github.com/argoproj/argo-workflows/commit/94cda3d53c6a72e3fc225ba08796bfd9420eccd6) Add feature to continue workflow on failed/error steps/tasks (#1205)
 * [3f1fb9d5](https://github.com/argoproj/argo-workflows/commit/3f1fb9d5e61d300c4922e48a748dc17285e07f07) Add Gardener to "Who uses Argo" (#1228)
 * [cde5cd32](https://github.com/argoproj/argo-workflows/commit/cde5cd320fa987ac6dd539a3126f29c73cd7277a) Include stderr when retrieving docker logs (#1225)
 * [2b1d56e7](https://github.com/argoproj/argo-workflows/commit/2b1d56e7d4e583e2e06b37904714b350faf03d97) Update README.md (#1224)
 * [eeac5a0e](https://github.com/argoproj/argo-workflows/commit/eeac5a0e11b4a6f4bc28757a3b0684598b8c4974) Remove extra quotes around output parameter value (#1232)
 * [8b67e1bf](https://github.com/argoproj/argo-workflows/commit/8b67e1bfdc7ed5ea153cb17f9a740afe2bd4efa8) Update README.md (#1236)
 * [baa3e622](https://github.com/argoproj/argo-workflows/commit/baa3e622121e66c9fec7c612c88027b7cacbd1b2) Update README with typo fixes (#1220)
 * [f6b0c8f2](https://github.com/argoproj/argo-workflows/commit/f6b0c8f285217fd0e6089b0cf03ca4926d1b4758) Executor can access the k8s apiserver with a out-of-cluster config file (#1134)
 * [0bda53c7](https://github.com/argoproj/argo-workflows/commit/0bda53c77c54b037e7d91b18554053362b1e4d35) fix dag retries (#1221)
 * [8aae2931](https://github.com/argoproj/argo-workflows/commit/8aae29317a8cfef2edc084a4c74a44c83d845936) Issue #1190 - Fix incorrect retry node handling (#1208)
 * [f1797f78](https://github.com/argoproj/argo-workflows/commit/f1797f78044504dbf2e1f7285cc9c18ac79f5e81) Add schedulerName to workflow and template spec (#1184)
 * [2ddae161](https://github.com/argoproj/argo-workflows/commit/2ddae161037f603d2a3c12ba6b495dc422547b58) Set executor image pull policy for resource template (#1174)
 * [edcb5629](https://github.com/argoproj/argo-workflows/commit/edcb56296255267a3c8fa639c3ad26a016caab80) Dockerfile: argoexec base image correction (fixes #1209) (#1213)
 * [f92284d7](https://github.com/argoproj/argo-workflows/commit/f92284d7108ebf92907008d8f12a0696ee467a43) Minor spelling, formatting, and style updates. (#1193)
 * [bd249a83](https://github.com/argoproj/argo-workflows/commit/bd249a83e119d6161fa1c593b09fb381db448a0d) Issue #1128 - Use polling instead of fs notify to get annotation changes (#1194)
 * [14a432e7](https://github.com/argoproj/argo-workflows/commit/14a432e75119e37d42715b7e83992789c6dac454) Update community/README (#1197)
 * [eda7e084](https://github.com/argoproj/argo-workflows/commit/eda7e08438d2314bb5eb178a1335a3c28555ab34) Updated OWNERS (#1198)
 * [73504a24](https://github.com/argoproj/argo-workflows/commit/73504a24e885c6df9d1cceb4aa123c79eca7b7cd) Fischerjulian adds ruby to rest docs (#1196)
 * [311ad86f](https://github.com/argoproj/argo-workflows/commit/311ad86f101c58a1de1cef313a1516b4c79e643f) Fix missing docker binary in argoexec image. Improve reuse of image layers
 * [831e2198](https://github.com/argoproj/argo-workflows/commit/831e2198e22503394acca1cce0dbcf8dcebb2931) Issue #988 - Submit should not print logs to stdout unless output is 'wide' (#1192)
 * [17250f3a](https://github.com/argoproj/argo-workflows/commit/17250f3a51d545c49114882d0da6ca29eda7c6f2) Add documentation how to use parameter-file's (#1191)
 * [01ce5c3b](https://github.com/argoproj/argo-workflows/commit/01ce5c3bcf0dde5536b596d48bd48a93b3f2eee0) Add Docker Hub build hooks
 * [93289b42](https://github.com/argoproj/argo-workflows/commit/93289b42f96cd49cdc048d84626cb28ef6932940) Refactor Makefile/Dockerfile to remove volume binding in favor of build stages (#1189)
 * [8eb4c666](https://github.com/argoproj/argo-workflows/commit/8eb4c66639c5fd1a607c73a4d765468a99c43da1) Issue #1123 - Fix 'kubectl get' failure if resource namespace is different from workflow namespace (#1171)
 * [eaaad7d4](https://github.com/argoproj/argo-workflows/commit/eaaad7d47257302f203bab24bce1b7d479453351) Increased S3 artifact retry time and added log (#1138)
 * [f07b5afe](https://github.com/argoproj/argo-workflows/commit/f07b5afeaf950f49f87cdffb5116e82c8b0d43a1) Issue #1113 - Wait for daemon pods completion to handle annotations (#1177)
 * [2b2651b0](https://github.com/argoproj/argo-workflows/commit/2b2651b0a7f5d6873c8470fad137d42f9b7d7240) Do not mount unnecessary docker socket (#1178)
 * [1fc03144](https://github.com/argoproj/argo-workflows/commit/1fc03144c55f987993c7777b190b1848fc3833cd) Argo users: Equinor (#1175)
 * [e381653b](https://github.com/argoproj/argo-workflows/commit/e381653b6d6d6a6babba2e8f05f6f103e81a191d) Update README. (#1173) (#1176)
 * [5a917140](https://github.com/argoproj/argo-workflows/commit/5a917140cb56a27e7b6f3b1d5068f4838863c273) Update README and preview notice in CLA.
 * [521eb25a](https://github.com/argoproj/argo-workflows/commit/521eb25aeb2b8351d72bad4a3d3aa2d1fa55eb23) Validate ArchiveLocation artifacts (#1167)
 * [528e8f80](https://github.com/argoproj/argo-workflows/commit/528e8f803683ee462ccc05fc9b00dc57858c0e93) Add missing patch in namespace kustomization.yaml (#1170)
 * [0b41ca0a](https://github.com/argoproj/argo-workflows/commit/0b41ca0a2410b01205712a2186dd12851eecb707) Add Preferred Networks to users in README.md (#1172)
 * [649d64d1](https://github.com/argoproj/argo-workflows/commit/649d64d1bd375f779cd150446bddce94582067d2) Add GitHub to users in README.md (#1151)
 * [864c7090](https://github.com/argoproj/argo-workflows/commit/864c7090a0bfcaa12237ff6e894a9d26ab463a7a) Update codegen for network config (#1168)
 * [c3cc51be](https://github.com/argoproj/argo-workflows/commit/c3cc51be2e14e931d6e212aa30842a2c514082d1) Support HDFS Artifact (#1159)
 * [8db00066](https://github.com/argoproj/argo-workflows/commit/8db0006667dec74c58cbab744b014c67fda55c65) add support for hostNetwork & dnsPolicy config (#1161)
 * [149d176f](https://github.com/argoproj/argo-workflows/commit/149d176fdf3560d74afa91fe91a0ee38bf7ec3bd) Replace exponential retry with poll (#1166)
 * [31e5f63c](https://github.com/argoproj/argo-workflows/commit/31e5f63cba89b06abc2cdce0d778c6b8d937a23e) Fix tests compilation error (#1157)
 * [6726d9a9](https://github.com/argoproj/argo-workflows/commit/6726d9a961a2c3ed5467430d3631a36cfbf361de) Fix failing TestAddGlobalArtifactToScope unit test
 * [4fd758c3](https://github.com/argoproj/argo-workflows/commit/4fd758c38fc232bf26bb5e1d4e7e23321ba91416) Add slack badge to README (#1164)
 * [3561bff7](https://github.com/argoproj/argo-workflows/commit/3561bff70ad6bfeca8967be6aa4ac24fbbc8ac27) Issue #1136 - Fix metadata for DAG with loops (#1149)
 * [c7fec9d4](https://github.com/argoproj/argo-workflows/commit/c7fec9d41c0e2d3369e111f8b1d0f1d0ca77edae) Reflect minio chart changes in documentation (#1147)
 * [f6ce7833](https://github.com/argoproj/argo-workflows/commit/f6ce78334762cbc3c6de1604c11ea4f5f618c275) add support for other archs (#1137)
 * [cb538489](https://github.com/argoproj/argo-workflows/commit/cb538489a187134577e2146afcf9367f45088ff7) Fix issue where steps with exhausted retires would not complete (#1148)
 * [e400b65c](https://github.com/argoproj/argo-workflows/commit/e400b65c5eca2de2aa891f8489dcd835ef0e161c) Fix global artifact overwriting in nested workflow (#1086)
 * [174eb20a](https://github.com/argoproj/argo-workflows/commit/174eb20a6a110c9bf647b040460df83b6ab031c4) Issue #1040 - Kill daemoned step if workflow consist of single daemoned step (#1144)
 * [e078032e](https://github.com/argoproj/argo-workflows/commit/e078032e469effdfc492c8eea97eb2701ceda0c2) Issue #1132 - Fix panic in ttl controller (#1143)
 * [e09d9ade](https://github.com/argoproj/argo-workflows/commit/e09d9ade25535ae7e78ca23636e4d158a98bba84) Issue #1104 - Remove container wait timeout from 'argo logs --follow' (#1142)
 * [0f84e514](https://github.com/argoproj/argo-workflows/commit/0f84e5148dd34c225a35eab7a1f5953afb45e724) Allow owner reference to be set in submit util (#1120)
 * [3484099c](https://github.com/argoproj/argo-workflows/commit/3484099c856716f6da5e02ad75a48b568f547695) Update generated swagger to fix verify-codegen (#1131)
 * [587ab1a0](https://github.com/argoproj/argo-workflows/commit/587ab1a02772cd9b7ae7cd94f91b815ac4774297) Fix output artifact and parameter conflict (#1125)
 * [6bb3adbc](https://github.com/argoproj/argo-workflows/commit/6bb3adbc596349100c4f19155cfe976f4ea0e6fb) Adding Quantibio in Who uses Argo (#1111)
 * [1ae3696c](https://github.com/argoproj/argo-workflows/commit/1ae3696c27f343c947d9225c5cc2294c8b7c45e5) Install mime-support in argoexec to set proper mime types for S3 artifacts (resolves #1119)
 * [515a9005](https://github.com/argoproj/argo-workflows/commit/515a9005057dfd260a8b60c4ba1ab8c3aa614f48) add support for ppc64le and s390x (#1102)
 * [78142837](https://github.com/argoproj/argo-workflows/commit/78142837836cb100f6858d246d84100b74794cc6) Remove docker_lib mount volume which is not needed anymore (#1115)
 * [e59398ad](https://github.com/argoproj/argo-workflows/commit/e59398adf39b8ef1d0ce273263e80d49e370c510) Fix examples docs of parameters. (#1110)
 * [ec20d94b](https://github.com/argoproj/argo-workflows/commit/ec20d94b6f1d0d88d579c8a27b964f6e9915ff55) Issue #1114 - Set FORCE_NAMESPACE_ISOLATION env variable in namespace install manifests (#1116)
 * [49c1fa4f](https://github.com/argoproj/argo-workflows/commit/49c1fa4f42e1c19ce3b8f4ac2c339894e1ed90d7) Update docs with examples using the K8s REST API
 * [bb8a6a58](https://github.com/argoproj/argo-workflows/commit/bb8a6a58fee8170d6db65c73a50c5fe640f3cb7d) Update ROADMAP.md
 * [46855dcd](https://github.com/argoproj/argo-workflows/commit/46855dcde1d9ba904a1c94a97e602d0510f5e0d4) adding logo to be used by the OS Site (#1099)
 * [438330c3](https://github.com/argoproj/argo-workflows/commit/438330c38da69a68d6b0b0b24f6aae0053fc35ee) #1081 added retry logic to s3 load and save function (#1082)
 * [cb8b036b](https://github.com/argoproj/argo-workflows/commit/cb8b036b8db3ebeb6ef73d9f2070a1ddaf0d2150) Initialize child node before marking phase. Fixes panic on invalid `When` (#1075)
 * [60b508dd](https://github.com/argoproj/argo-workflows/commit/60b508dd9ec36ef45013d72ec6166dd9a30d77fe) Drop reference to removed `argo install` command. (#1074)
 * [62b24368](https://github.com/argoproj/argo-workflows/commit/62b24368a93d57eb505bf226e042a8eb0bf72da4) Fix typo in demo.md (#1089)
 * [b5dfa021](https://github.com/argoproj/argo-workflows/commit/b5dfa0217470c97d8e83716a22cf3bd274c4a2d5) Use relative links on README file (#1087)
 * [95b72f38](https://github.com/argoproj/argo-workflows/commit/95b72f38c94d12735e79bb8bec1a46b10514603c) Update docs to outline bare minimum set of privileges for a workflow
 * [d4ef6e94](https://github.com/argoproj/argo-workflows/commit/d4ef6e944c302b5d2b75d4c49e1833c3a28c1f9a) Add new article and minor edits. (#1083)
 * [afdac9bb](https://github.com/argoproj/argo-workflows/commit/afdac9bb34fe8a01ad511323a00ccf6c07e41137) Issue #740 - System level workflow parallelism limits & priorities (#1065)
 * [a53a76e9](https://github.com/argoproj/argo-workflows/commit/a53a76e9401fab701eaa150307b21a28825c97ce) fix #1078 Azure AKS authentication issues (#1079)
 * [79b3e307](https://github.com/argoproj/argo-workflows/commit/79b3e30746f779e3cec3a28beaecb9c0df7024e1) Fix string format arguments in workflow utilities. (#1070)
 * [76b14f54](https://github.com/argoproj/argo-workflows/commit/76b14f54520a92b81ced78d4cae2632655f396fc) Auto-complete workflow names (#1061)
 * [f2914d63](https://github.com/argoproj/argo-workflows/commit/f2914d63e9c8b41a13b5932f7962f208b7e5a0da) Support nested steps workflow parallelism (#1046)
 * [eb48c23a](https://github.com/argoproj/argo-workflows/commit/eb48c23a2525a62bbc1b8b4c94e3d50fd91014bd) Raise not implemented error when artifact saving is unsupported (#1062)
 * [036969c0](https://github.com/argoproj/argo-workflows/commit/036969c0f4f6ce6a3c948b5d161c0367cf07176b) Add Cratejoy to list of users (#1063)
 * [a07bbe43](https://github.com/argoproj/argo-workflows/commit/a07bbe431cecbb1d50356f94111d3bd2dbc48bb6) Adding SAP Hybris in Who uses Argo (#1064)
 * [7ef1cea6](https://github.com/argoproj/argo-workflows/commit/7ef1cea68c94f7f0e1e2f8bd75bedc5a7df8af90) Update dependencies to K8s v1.12 and client-go 9.0
 * [23d733ba](https://github.com/argoproj/argo-workflows/commit/23d733bae386db44ec80639daf91b29dbf86b335) Add namespace explicitly to pod metadata (#1059)
 * [79ed7665](https://github.com/argoproj/argo-workflows/commit/79ed7665d7419e7fbfe8b120c4cbcd486bebee57) Parameter and Argument names should support snake case (#1048)
 * [6e6c59f1](https://github.com/argoproj/argo-workflows/commit/6e6c59f13ff84fd6b4f1e7f836c783941c434ce7) Submodules are dirty after checkout -- need to update (#1052)
 * [f18716b7](https://github.com/argoproj/argo-workflows/commit/f18716b74c6f52d0c8bf4d64c05eae9db75bfb1f) Support for K8s API based Executor (#1010)
 * [e297d195](https://github.com/argoproj/argo-workflows/commit/e297d19501a8116b5a18c925a3c72d7c7e106ea0) Updated examples/README.md (#1051)
 * [19d6cee8](https://github.com/argoproj/argo-workflows/commit/19d6cee8149917c994b737510d9c8dbfc6dbdd27) Updated ARTIFACT_REPO.md (#1049)
 * [0a928e93](https://github.com/argoproj/argo-workflows/commit/0a928e93dac6d8522682931a0a68c52add310cdb) Update installation manifests to use v2.2.1
 * [3b52b261](https://github.com/argoproj/argo-workflows/commit/3b52b26190163d1f72f3aef1a39f9f291378dafb) Fix linter warnings and update swagger
 * [7d0e77ba](https://github.com/argoproj/argo-workflows/commit/7d0e77ba74587d913b1f4aceb1443228a04d35de) Update changelog and bump version to 2.2.1
 * [b402e12f](https://github.com/argoproj/argo-workflows/commit/b402e12feefe5cd1380e9479b2cc9bae838357bf) Issue #1033 - Workflow executor panic: workflows.argoproj.io/template workflows.argoproj.io/template not found in annotation file (#1034)
 * [3f2e986e](https://github.com/argoproj/argo-workflows/commit/3f2e986e130ca136514767fb1593d745ca418236) fix typo in examples/README.md (#1025)
 * [9c5e056a](https://github.com/argoproj/argo-workflows/commit/9c5e056a858a9b510cdacdbc5deb5857a97662f8) Replace tabs with spaces (#1027)
 * [091f1407](https://github.com/argoproj/argo-workflows/commit/091f1407180990c745e981b24169c3bb4868dbe3) Update README.md (#1030)
 * [159fe09c](https://github.com/argoproj/argo-workflows/commit/159fe09c99c16738c0897f9d74087ec1b264954d) Fix format issues to resolve build errors (#1023)
 * [363bd97b](https://github.com/argoproj/argo-workflows/commit/363bd97b72ae5cb7fc52a560b6f7939248cdb72d) Fix error in env syntax (#1014)
 * [ae7bf0a5](https://github.com/argoproj/argo-workflows/commit/ae7bf0a5f7ddb1e5211e724bef15951198610942) Issue #1018 - Workflow controller should save information about archived logs in step outputs (#1019)
 * [15d006c5](https://github.com/argoproj/argo-workflows/commit/15d006c54ee7149b0d86e6d60453ecc8c071c953) Add example of workflow using imagePullSecrets (resolves #1013)
 * [2388294f](https://github.com/argoproj/argo-workflows/commit/2388294fa412e153d8366910e4d47ba564f29856) Fix RBAC roles to include workflow delete for GC to work properly (resolves #1004)
 * [6f611cb9](https://github.com/argoproj/argo-workflows/commit/6f611cb9383610471f941b5cab4227ce8bfea7c5) Fix issue where resubmission of a terminated workflow creates a terminated workflow (issue #1011)
 * [4a7748f4](https://github.com/argoproj/argo-workflows/commit/4a7748f433f888fdc50b592db1002244ea466bdb) Disable Persistence in the demo example (#997)
 * [55ae0cb2](https://github.com/argoproj/argo-workflows/commit/55ae0cb242a9cf6b390822ca6c0aa0868f5b06e3) Fix example pod name (#1002)
 * [c275e7ac](https://github.com/argoproj/argo-workflows/commit/c275e7acb7b5e8f9820a09d8b0cb635f710b8674) Add imagePullPolicy config for executors (#995)
 * [b1eed124](https://github.com/argoproj/argo-workflows/commit/b1eed124e6d943c453d87a9b4291ba10198d0bc6) `tar -tf` will detect compressed tars correctly. (#998)
 * [03a7137c](https://github.com/argoproj/argo-workflows/commit/03a7137c9ca9459727b57fb0a0e95584c5305844) Add new organization using argo (#994)
 * [83884528](https://github.com/argoproj/argo-workflows/commit/8388452870ed9a2d2e348a2844d3d7d1c4d61b05) Update argoproj/pkg to trim leading/trailing whitespace in S3 credentials (resolves #981)
 * [978b4938](https://github.com/argoproj/argo-workflows/commit/978b49383d30cdbc7c9708eb281b7800ee5412df) Add syntax highlighting for all YAML snippets and most shell snippets (#980)
 * [60d5dc11](https://github.com/argoproj/argo-workflows/commit/60d5dc11c73e888898160b4cc329e87747cee4d2) Give control to decide whether or not to archive logs at a template level
 * [8fab73b1](https://github.com/argoproj/argo-workflows/commit/8fab73b142b96f943592c66932ae0c5183e8c3db) Detect and indicate when container was OOMKilled
 * [47a9e556](https://github.com/argoproj/argo-workflows/commit/47a9e5560229c789b70a6624f23fb4433412fbc4) Update config map doc with instructions to enable log archiving
 * [79dbbaa1](https://github.com/argoproj/argo-workflows/commit/79dbbaa1ed30cae6279eabd9a84650107f4387b3) Add instructions to match git URL format to auth type in git example (issue #979)
 * [429f03f5](https://github.com/argoproj/argo-workflows/commit/429f03f5b26db42f1857a93b7599b545642c2f0a) Add feature list to README.md. Tweaks to getting started.
 * [36fd1948](https://github.com/argoproj/argo-workflows/commit/36fd19482c6bebfb21076cba81b924deaff14f52) Update getting started guide with v2.2.0 instructions
 * [af636ddd](https://github.com/argoproj/argo-workflows/commit/af636ddd8455660f307d835814d3112b90815dfd) Update installation manifests to use v2.2.0
 * [7864ad36](https://github.com/argoproj/argo-workflows/commit/7864ad36788dc78d035d59ddb27ecd979f7216f4) Introduce `withSequence` to iterate a range of numbers in a loop (resolves #527)
 * [99e9977e](https://github.com/argoproj/argo-workflows/commit/99e9977e4ccf61171ca1e347f6a182ba1d8dba83) Introduce `argo terminate` to terminate a workflow without deleting it (resolves #527)
 * [f52c0450](https://github.com/argoproj/argo-workflows/commit/f52c045087abff478603db4817de1933bddce5e7) Reorganize codebase to make CLI functionality available as a library
 * [311169f7](https://github.com/argoproj/argo-workflows/commit/311169f7e71c58fe9bf879a94681ee274ddf623c) Fix issue where sidecars and daemons were not reliably killed (resolves #879)
 * [67ffb6eb](https://github.com/argoproj/argo-workflows/commit/67ffb6eb7519936e1149f36e11dc9fda0f70a242) Add a reason/message for Unschedulable Pending pods
 * [69c390f2](https://github.com/argoproj/argo-workflows/commit/69c390f288ccaaeefba1d5a7961acebfe2e7771a) Support for workflow level timeouts (resolves #848)
 * [f88732ec](https://github.com/argoproj/argo-workflows/commit/f88732ec09413716bf14927bef10355b21b88516) Update docs to use keyFormat field
 * [0df022e7](https://github.com/argoproj/argo-workflows/commit/0df022e777f35bf0ea39ebbacfe4e5f92f099a62) Rename keyPattern to keyFormat. Remove pending pod query during pod reconciliation
 * [75a9983b](https://github.com/argoproj/argo-workflows/commit/75a9983b17869b76a93621f108ee85c70b8d8533) Fix potential panic in `argo watch`
 * [9cb46449](https://github.com/argoproj/argo-workflows/commit/9cb4644975d16dbebc3607ffb91364c93bc14e30) Add TTLSecondsAfterFinished field and controller to garbage collect completed workflows (resolves #911)
 * [7540714a](https://github.com/argoproj/argo-workflows/commit/7540714a47f04f664362c7083c886058c62408f8) Add ability to archive container logs to the artifact repository (resolves #454)
 * [11e57f4d](https://github.com/argoproj/argo-workflows/commit/11e57f4dea93fde60b204a5e7675fec999c66f56) Introduce archive strategies with ability to disable tar.gz archiving (resolves #784)
 * [e180b547](https://github.com/argoproj/argo-workflows/commit/e180b547133aa461bd5cc282a59f8954485d5b8f) Update CHANGELOG.md
 * [5670bf5a](https://github.com/argoproj/argo-workflows/commit/5670bf5a65cbac898b298edd682e603666ed5cb6) Introduce `argo watch` command to watch live workflows from terminal (resolves #969)
 * [57394361](https://github.com/argoproj/argo-workflows/commit/5739436199980ec765b070f8e78669bc37115ad6) Support additional container runtimes through kubelet executor (#952)
 * [a9c84c97](https://github.com/argoproj/argo-workflows/commit/a9c84c97de8f088cd4ee91cd72cf75012fc70438) Error workflows which hit k8s/etcd 1M resource size limit (resolves #913)
 * [67792eb8](https://github.com/argoproj/argo-workflows/commit/67792eb89e5aa678ffc52540dbc232d8598ce43f) Add parameter-file support (#966)
 * [841832a3](https://github.com/argoproj/argo-workflows/commit/841832a3507be3b92e3b2a05fef1052b1cd6e20d) Aggregate workflow RBAC roles to built-in admin/edit/view clusterroles (resolves #960)
 * [35bb7093](https://github.com/argoproj/argo-workflows/commit/35bb70936cf1b76e53f7f6f0e6acaccb9c6d06bf) Allow scaling of workflow and pod workers via controller CLI flags (resolves #962)
 * [b479fa10](https://github.com/argoproj/argo-workflows/commit/b479fa10647bd1c1b86410b7837668c375b327be) Improve workflow configmap documentation for keyPattern
 * [f1802f91](https://github.com/argoproj/argo-workflows/commit/f1802f91d8934b2e4b9d1f64230230bc2a0b5baf) Introduce `keyPattern` workflow config to enable flexibility in archive location path (issue #953)
 * [a5648a96](https://github.com/argoproj/argo-workflows/commit/a5648a9644fcea5f498c24a573a038290b92016f) Fix kubectl proxy link for argo-ui Service (#963)
 * [09f05912](https://github.com/argoproj/argo-workflows/commit/09f0591205ec81b4ec03f0f5c534a13648346f41) Introduce Pending node state to highlight failures when start workflow pods
 * [a3ff464f](https://github.com/argoproj/argo-workflows/commit/a3ff464f67a862d4110848d94a46be39876ce57e) Speed up CI job
 * [88627e84](https://github.com/argoproj/argo-workflows/commit/88627e842c082ddc4d75d15a3e2dc6c7ab4f1db8) Update base images to debian:9.5-slim. Use stable metalinter
 * [753c5945](https://github.com/argoproj/argo-workflows/commit/753c5945b62be209f05025c2e415a0753f5e0b01) Update argo-ci-builder image with new dependencies
 * [674b61bb](https://github.com/argoproj/argo-workflows/commit/674b61bb473787a157e543c10dcf158fa35bb39a) Remove unnecessary dependency on argo-cd and obsolete RBAC constants
 * [60658de0](https://github.com/argoproj/argo-workflows/commit/60658de0cf7403c4be014e92b7a3bb4772f4ad5f) Refactor linting/validation into standalone package. Support linting of .json files
 * [f55d579a](https://github.com/argoproj/argo-workflows/commit/f55d579a9478ed33755874f24656faec04611777) Detect and fail upon unknown fields during argo submit & lint (resolves #892)
 * [edf6a574](https://github.com/argoproj/argo-workflows/commit/edf6a5741de8bdf3a20852a55581883f1ec80d9a) Migrate to using argoproj.io/pkg packages
 * [5ee1e0c7](https://github.com/argoproj/argo-workflows/commit/5ee1e0c7daed4e2c8dca5643a800292ece067fca) Update artifact config docs (#957)
 * [faca49c0](https://github.com/argoproj/argo-workflows/commit/faca49c009bead218ee974bfad2ccc36f84de1fb) Updated README
 * [936c6df7](https://github.com/argoproj/argo-workflows/commit/936c6df7eaae08082c1cc7ad750f664ff8a4c54c) Add table of content to examples (#956)
 * [d2c03f67](https://github.com/argoproj/argo-workflows/commit/d2c03f67c2fd45ff54c04db706c9ebf252fca6f2) Correct image used in install manifests
 * [ec3b7be0](https://github.com/argoproj/argo-workflows/commit/ec3b7be065aa65aae207bd34930001b593009b80) Remove CLI installer/uninstaller. Executor image configured via CLI argument (issue #928) Remove redundant/unused downward API metadata
 * [3a85e242](https://github.com/argoproj/argo-workflows/commit/3a85e2429154a4d97c8fc7c92f9e8f482de6639f) Rely on `git checkout` instead of go-git checkout for more reliable revision resolution
 * [ecef0e3d](https://github.com/argoproj/argo-workflows/commit/ecef0e3dd506eefc222c1ebed58ab81265ac9638) Rename Prometheus metrics (#948)
 * [b9cffe9c](https://github.com/argoproj/argo-workflows/commit/b9cffe9cd7b347905a42cf3e217cc3b039bdfb3f) Issue #896 - Prometheus metrics and telemetry (#935)
 * [290dee52](https://github.com/argoproj/argo-workflows/commit/290dee52bfb94679870cee94ca9560bbe8bd7813) Support parameter aggregation of map results in scripts
 * [fc20f5d7](https://github.com/argoproj/argo-workflows/commit/fc20f5d787ed11f03a24439c042b9ef45349eb95) Fix errors when submodules are from different URL (#939)
 * [b4f1a00a](https://github.com/argoproj/argo-workflows/commit/b4f1a00ad2862e6545dd4ad16279a49cd4585676) Add documentation about workflow variables
 * [4a242518](https://github.com/argoproj/argo-workflows/commit/4a242518c6ea81cd0d1e5aaab2822231d9b36d46) Update readme.md (#943)
 * [a5baca60](https://github.com/argoproj/argo-workflows/commit/a5baca60d1dfb8fb8c82a936ab383d49e075cff3) Support referencing of global workflow artifacts (issue #900)
 * [9b5c8563](https://github.com/argoproj/argo-workflows/commit/9b5c85631765285b4593b7707ede014178f77679) Support for sophisticated expressions in `when` conditionals (issue #860)
 * [ecc0f027](https://github.com/argoproj/argo-workflows/commit/ecc0f0272f2257600abab8f4779c478957644d7c) Resolve revision added ability to specify shorthand revision and other things like HEAD~2 etc (#936)
 * [11024318](https://github.com/argoproj/argo-workflows/commit/11024318c0e2a9106f8a8b4a719daba12adf9f36) Support conditions with DAG tasks. Support aggregated outputs from scripts (issue #921)
 * [d07c1d2f](https://github.com/argoproj/argo-workflows/commit/d07c1d2f3b7c916887185eea749db2278bf9d043) Support withItems/withParam and parameter aggregation with DAG templates (issue #801)
 * [94c195cb](https://github.com/argoproj/argo-workflows/commit/94c195cb014ba2e5c5943d96dc0a3cc3243edb6a) Bump VERSION to v2.2.0
 * [9168c59d](https://github.com/argoproj/argo-workflows/commit/9168c59dc486f840dc2b9713d92c14bdccebbaf8) Fix outbound node metadata with retry nodes causing disconnected nodes to be rendered in UI (issue #880)
 * [c6ce48d0](https://github.com/argoproj/argo-workflows/commit/c6ce48d086638168b9bd8b998d65a2e3a4801540) Fix outbound node metadata issue with steps template causing incorrect edges to be rendered in UI
 * [520b33d5](https://github.com/argoproj/argo-workflows/commit/520b33d5fc6e7e670c33015fd74c5a2f3bd74a21) Add ability to aggregate and reference output parameters expanded by loops (issue #861)
 * [ece1eef8](https://github.com/argoproj/argo-workflows/commit/ece1eef85ac1f92d2fad8a2fef8c657f04b4599a) Support submission of workflows as json, and from stdin (resolves #926)
 * [4c31d61d](https://github.com/argoproj/argo-workflows/commit/4c31d61da2891e92a3ae0d09b6924655a07fc59f) Add `argo delete --older` to delete completed workflows older than specified duration (resolves #930)
 * [c87cd33c](https://github.com/argoproj/argo-workflows/commit/c87cd33c1bc46c06314129c882fec80269af8133) Update golang version to v1.10.3
 * [618b7eb8](https://github.com/argoproj/argo-workflows/commit/618b7eb84678e177a38e5aa81fa59ed891459aa5) Proper fix for assessing overall DAG phase. Add some DAG unit tests (resolves #885)
 * [f223e5ad](https://github.com/argoproj/argo-workflows/commit/f223e5ad62115399cf1394db4e9e65f05ae6da8b) Fix issue where a DAG would fail even if retry was successful (resolves #885)
 * [143477f3](https://github.com/argoproj/argo-workflows/commit/143477f3d5e0ab0d65dd97774aabdcd736ae4fbe) Start use of argoproj/pkg shared libraries
 * [1220d080](https://github.com/argoproj/argo-workflows/commit/1220d0801b8aa78c5364a4586cd119553d96bca5) Update argo-cluster-role to work with OpenShift (resolves #922)
 * [4744f45a](https://github.com/argoproj/argo-workflows/commit/4744f45a9c110b11fa73070a52e4166406fa5da4) Added SSH clone and proper git clone using go-git (#919)
 * [d657abf4](https://github.com/argoproj/argo-workflows/commit/d657abf4a37c9f2987b5cc2ee337743c981c3e48) Regenerate code and address OpenAPI rule validation errors (resolves #923)
 * [c5ec4cf6](https://github.com/argoproj/argo-workflows/commit/c5ec4cf6194ab5f741eb2e1d4e387dcf32ba3ce7) Upgrade k8s dependencies to v1.10 (resolves #908)
 * [ba8061ab](https://github.com/argoproj/argo-workflows/commit/ba8061abd296895555ea3d1d6ca7418fcd07d633) Redundant verifyResolvedVariables check in controller precluded the ability to use {{ }} in other circumstances
 * [05a61449](https://github.com/argoproj/argo-workflows/commit/05a614496bb921b5fa081605227de1a8832260cd) Added link to community meetings (#912)
 * [f33624d6](https://github.com/argoproj/argo-workflows/commit/f33624d67d0cf348dcdece46832081346c26bf80) Add an example on how to submit and wait on a workflow
 * [aeed7f9d](https://github.com/argoproj/argo-workflows/commit/aeed7f9da490d8dc4ad40c00ac2272a19da4ff17) Added new members
 * [288e4fc8](https://github.com/argoproj/argo-workflows/commit/288e4fc8577890e7fa6cc546f92aef4c954ce18c) Added Argo Events link.
 * [3322506e](https://github.com/argoproj/argo-workflows/commit/3322506e5a1d07e198f69cadd210b0b6cc6cfbc9) Updated README
 * [3ce640a2](https://github.com/argoproj/argo-workflows/commit/3ce640a24509454302a5126c972fd5424673c00e) Issue #889 - Support retryStrategy for scripts (#890)
 * [91c6afb2](https://github.com/argoproj/argo-workflows/commit/91c6afb2cc07c113e4999f114279638aa6809fd6) adding BlackRock as corporate contributor/user (#886)
 * [c8667b5c](https://github.com/argoproj/argo-workflows/commit/c8667b5c81068326638a5e35c20336223b3894db) Fix issue where `argo lint` required spec level arguments to be supplied
 * [ed7dedde](https://github.com/argoproj/argo-workflows/commit/ed7dedde1f8be2a5f7be828a31ac9bb4025919e1) Update influx-ci example to choose a stable InfluxDB branch
 * [135813e1](https://github.com/argoproj/argo-workflows/commit/135813e10e932a2187d007284766a816d9aa4442) Add datadog to the argo users (#882)
 * [f1038948](https://github.com/argoproj/argo-workflows/commit/f103894843e9ed8cbaf4212e765c10311bec5989) Fix `make verify-codegen` build target when run in CI
 * [785f2cbd](https://github.com/argoproj/argo-workflows/commit/785f2cbd114e6d0097e21240d5cacece0b6d071e) Update references to v2.1.1. Add better checks in release Makefile target
 * [d65e1cd3](https://github.com/argoproj/argo-workflows/commit/d65e1cd3e77efbe6fc877ac689fd4cd19bc35093) readme: add Interline Technologies to user list (#867)
 * [c903168e](https://github.com/argoproj/argo-workflows/commit/c903168ee12f296f71f4953cda2163b8fa8cd409) Add documentation on global parameters (#871)
 * [ac241c95](https://github.com/argoproj/argo-workflows/commit/ac241c95c13f08e868cd6f5ee32c9ce273e239ff) Update CHANGELOG for v2.1.1
 * [468e0760](https://github.com/argoproj/argo-workflows/commit/468e07600c5e124c8d2e0737f8c67a3265979952) Retrying failed steps templates could potentially result in disconnected children
 * [8d96ea7b](https://github.com/argoproj/argo-workflows/commit/8d96ea7b1b1ba843eb19a0632bc503d816ab9ef3) Switch to an UnstructuredInformer to guard against malformed workflow manifests (resolves #632)
 * [5bef6cae](https://github.com/argoproj/argo-workflows/commit/5bef6cae26dece96cadad855c9d54c5148f5e917) Suspend templates were not properly being connected to their children (resolves #869)
 * [543e9392](https://github.com/argoproj/argo-workflows/commit/543e9392f44873d1deb0a95fad3e00d67e8a7c70) Fix issue where a failed step in a template with parallelism would not complete (resolves #868)
 * [289000ca](https://github.com/argoproj/argo-workflows/commit/289000cac81b199c2fc9e50d04831e3ccfcc0659) Update argocli Dockerfile and make cli-image part of release
 * [d35a1e69](https://github.com/argoproj/argo-workflows/commit/d35a1e6949beca7cd032e5de5687e4e66869a916) Bump version to v2.1.1
 * [bbcff0c9](https://github.com/argoproj/argo-workflows/commit/bbcff0c94edf2b3270d7afc03b2538f47cb28492) Fix issue where `argo list` age column maxed out at 1d (resolves #857)
 * [d68cfb7e](https://github.com/argoproj/argo-workflows/commit/d68cfb7e585121e38e36c9d9dbd3e9cf8a1d9aac) Fix issue where volumes were not supported in script templates (resolves #852)
 * [fa72b6db](https://github.com/argoproj/argo-workflows/commit/fa72b6dbe4533ed9e2cc2c9f6bb574bcd85c6d16) Fix implementation of DAG task targets (resolves #865)
 * [dc003f43](https://github.com/argoproj/argo-workflows/commit/dc003f43baeba5509bfadfc825ced533715b93c6) Children of nested DAG templates were not correctly being connected to its parent
 * [b8065797](https://github.com/argoproj/argo-workflows/commit/b8065797712a29b0adefa5769cc6ffd2c6c7edd7) Simplify some examples for readability and clarity
 * [7b02c050](https://github.com/argoproj/argo-workflows/commit/7b02c050e86138983b20a38ee9efab52180141d5) Add CoreFiling to "Who uses Argo?" section. (#864)
 * [4f2fde50](https://github.com/argoproj/argo-workflows/commit/4f2fde505d221783bec889f3c9339361f5e8be73) Add windows support for argo-cli (#856)
 * [703241e6](https://github.com/argoproj/argo-workflows/commit/703241e60c7203550ac9f7947284e5d6fde3dc74) Updated ROADMAP.md for v2.2
 * [54f2138e](https://github.com/argoproj/argo-workflows/commit/54f2138ef83f92d2038ebf7b925bd102bc5a7b8d) Spell check the examples README (#855)
 * [f23feff5](https://github.com/argoproj/argo-workflows/commit/f23feff5e9353b4796ad4f0afa33efcb1b9f0d95) Mkbranch (#851)
 * [628b5408](https://github.com/argoproj/argo-workflows/commit/628b540891d1999c708accf064356d4dad22c7e0) DAG docs. (#850)
 * [22f62439](https://github.com/argoproj/argo-workflows/commit/22f624396c3c8cacd288040935feb7da4e4a869d) Small edit to README
 * [edc09afc](https://github.com/argoproj/argo-workflows/commit/edc09afc332c6e2707688a050060548940eca852) Added OWNERS file
 * [530e7244](https://github.com/argoproj/argo-workflows/commit/530e72444e2ced0c3c050e3238431dc32c1645c5) Update release notes and documentation for v2.1.0

### Contributors

 * 0x1D-1983
 * Aaron Curtis
 * Adam Gilat
 * Adam Thornton
 * Aditya Sundaramurthy
 * Adrien Trouillaud
 * Aisuko
 * Akshay Chitneni
 * Alessandro Marrella
 * Alex Capras
 * Alex Collins
 * Alex Stein
 * Alexander Matyushentsev
 * Alexey Volkov
 * Anastasia Satonina
 * Andrei Miulescu
 * Andrew Suderman
 * Anes Benmerzoug
 * Anna Winkler
 * Antoine Dao
 * Antonio Macías Ojeda
 * Appréderisse Benjamin
 * Avi Weit
 * Bastian Echterhölter
 * Ben Wells
 * Ben Ye
 * Brandon Steinman
 * Brian Mericle
 * CWen
 * Caden
 * Caglar Gulseni
 * Chen Zhiwei
 * Chris Chambers
 * Christian Muehlhaeuser
 * Clemens Lange
 * Cristian Pop
 * Daisuke Taniwaki
 * Dan Norris
 * Daniel Duvall
 * Daniel Moran
 * Daniel Sutton
 * David Bernard
 * David Seapy
 * David Van Loon
 * Deepen Mehta
 * Derek Wang
 * Dineshmohan Rajaveeran
 * Divya Vavili
 * Drew Dara-Abrams
 * Dustin Specker
 * EDGsheryl
 * Ed Lee
 * Edward Lee
 * Edwin Jacques
 * Ejiah
 * Elton
 * Eric
 * Erik Parmann
 * Fabio Rigato
 * Feynman Liang
 * Florent Clairambault
 * Fred Dubois
 * Gabriele Santomaggio
 * Galen Han
 * Grant Stephens
 * Greg Roodt
 * Guillaume Hormiere
 * Hamel Husain
 * Heikki Kesa
 * Hideto Inamura
 * Howie Benefiel
 * Huan-Cheng Chang
 * Ian Howell
 * Ilias K
 * Ilias Katsakioris
 * Ilya Sotkov
 * Ismail Alidzhikov
 * Jacob O'Farrell
 * Jaime
 * Jean-Louis Queguiner
 * Jeff Uren
 * Jesse Suen
 * Jialu Zhu
 * Jie Zhang
 * Johannes 'fish' Ziemke
 * John Wass
 * Jonas Fonseca
 * Jonathan Steele
 * Jonathon Belotti
 * Jonny
 * Joshua Carp
 * Juan C. Muller
 * Julian Fahrer
 * Julian Fischer
 * Julian Mazzitelli
 * Julien Balestra
 * Kannappan Sirchabesan
 * Konstantin Zadorozhny
 * Leonardo Luz
 * Marcin Karkocha
 * Marco Sanvido
 * Marek Čermák
 * Markus Lippert
 * Matt Brant
 * Matt Hillsdon
 * Matthew Coleman
 * Matthew Magaldi
 * MengZeLee
 * Michael Crenshaw
 * Mike Seddon
 * Mingjie Tang
 * Miyamae Yuuya
 * Mostapha Sadeghipour Roudsari
 * Mukulikak
 * Naoto Migita
 * Naresh Kumar Amrutham
 * Nasrudin Bin Salim
 * Neutron Soutmun
 * Nick Groszewski
 * Nick Stott
 * Niklas Hansson
 * Niklas Vest
 * Nándor István Krácser
 * Omer Kahani
 * Orion Delwaterman
 * Pablo Osinaga
 * Pascal VanDerSwalmen
 * Patryk Jeziorowski
 * Paul Brit
 * Pavel Kravchenko
 * Peng Li
 * Pengfei Zhao
 * Per Buer
 * Peter Salanki
 * Pierre Houssin
 * Pradip Caulagi
 * Praneet Chandra
 * Pratik Raj
 * Premkumar Masilamani
 * Rafael Rodrigues
 * Rafał Bigaj
 * Remington Breeze
 * Rick Avendaño
 * Rocio Montes
 * Romain Di Giorgio
 * Romain GUICHARD
 * Roman Galeev
 * Saradhi Sreegiriraju
 * Saravanan Balasubramanian
 * Sascha Grunert
 * Sean Fern
 * Semjon Kopp
 * Shubham Koli (FaultyCarry)
 * Simon Behar
 * Snyk bot
 * Song Juchao
 * Stephen Steiner
 * StoneHuang
 * Takashi Abe
 * Takayuki Kasai
 * Tang Lee
 * Theodore Messinezis
 * Tim Schrodi
 * Tobias Bradtke
 * Tom Wieczorek
 * Tomas Valasek
 * Trevor Foster
 * Tristan Colgate-McFarlane
 * Val Sichkovskyi
 * Vardan Manucharyan
 * Vincent Boulineau
 * Vincent Smith
 * Vlad Losev
 * Wei Yan
 * WeiYan
 * Weston Platter
 * William
 * William Reed
 * Xianlu Bird
 * Xie.CS
 * Xin Wang
 * Youngjoon Lee
 * Yuan Tang
 * Yunhai Luo
 * Zach Aller
 * Zach Himsel
 * Zhipeng Wang
 * Ziyang Wang
 * alex weidner
 * almariah
 * candonov
 * commodus-sebastien
 * descrepes
 * dherman
 * dmayle
 * dthomson25
 * fsiegmund
 * gerardaus
 * gerdos82
 * haibingzhao
 * hidekuro
 * houz
 * ianCambrio
 * jacky
 * jdfalko
 * kshamajain99
 * lueenavarro
 * maguowei
 * mark9white
 * maryoush
 * mdvorakramboll
 * nglinh
 * sang
 * shahin
 * shibataka000
 * tkilpela
 * tralexa
 * tunoat
 * vatine
 * vdinesh2461990
 * xubofei1983
 * zhujl1991
 * モハメド

## v2.1.0 (2018-04-30)

 * [93796381](https://github.com/argoproj/argo-workflows/commit/9379638189cc194f1b34ff7295f0832eac1c1651) Avoid `println` which outputs to stderr. (#844)
 * [30e472e9](https://github.com/argoproj/argo-workflows/commit/30e472e9495f264676c00875e4ba5ddfcc23e15f) Add gladly as an official argo user (#843)
 * [cb4c1a13](https://github.com/argoproj/argo-workflows/commit/cb4c1a13b8c92d2bbfb73c2f1d7c8fcc5697ec6b) Add ability to override metadata.name and/or metadata.generateName during submission (resolves #836)
 * [834468a5](https://github.com/argoproj/argo-workflows/commit/834468a5d12598062b870c073f9a0230028c71b0) Command print the logs for a container in a workflow
 * [1cf13f9b](https://github.com/argoproj/argo-workflows/commit/1cf13f9b008ae41bbb23af6b55bf8e982723292f) Issue #825 - fix locating outbound nodes for skipped node (#842)
 * [30034d42](https://github.com/argoproj/argo-workflows/commit/30034d42b4f35729dd4575153c268565efef47be) Bump from debian:9.1 to debian:9.4. (#841)
 * [f3c41717](https://github.com/argoproj/argo-workflows/commit/f3c41717b21339157b6519b86e22a5e20feb2b97) Owner reference example (#839)
 * [191f7aff](https://github.com/argoproj/argo-workflows/commit/191f7aff4b619bc6796c18c39e58ed9636865cf5) Minor edit to README
 * [c8a2e25f](https://github.com/argoproj/argo-workflows/commit/c8a2e25fa6085587018f65a0fc4ec31f012c2653) Fixed typo (#835)
 * [cf13bf0b](https://github.com/argoproj/argo-workflows/commit/cf13bf0b35ebbcefce1138fa77f04b268ccde394) Added users section to README
 * [e4d76329](https://github.com/argoproj/argo-workflows/commit/e4d76329bf13e72f09433a9ab219f9c025d232a9) Updated News in README
 * [b631d0af](https://github.com/argoproj/argo-workflows/commit/b631d0af4dee5ecbe6e70e39ad31b9f708efb6b9) added community meeting (#834)
 * [e34728c6](https://github.com/argoproj/argo-workflows/commit/e34728c66bf37b76cb92f03552a2f2a200f09644) Fix issue where daemoned steps were not terminated properly in DAG templates (resolves #832)
 * [2e9e113f](https://github.com/argoproj/argo-workflows/commit/2e9e113fb3f2b86f75df9669f4bf11fca181a348) Update docs to work with latest minio chart
 * [ea95f191](https://github.com/argoproj/argo-workflows/commit/ea95f191047dd17bbcab8573541d25fbd51829c0) Use octal syntax for mode values (#833)
 * [5fc67d2b](https://github.com/argoproj/argo-workflows/commit/5fc67d2b785ac582a03e7dcdc83fc212839863d1) Updated community docs
 * [8fa4f006](https://github.com/argoproj/argo-workflows/commit/8fa4f0063893d8c419e4a9466abbc608c5c97811) Added community docs
 * [423c8d14](https://github.com/argoproj/argo-workflows/commit/423c8d144eab054acf682127c1ca04c216199db0) Issue #830 - retain Step node children references
 * [73990c78](https://github.com/argoproj/argo-workflows/commit/73990c787b08f2ce72f65b8169e9f1653b5b6877) Moved cricket gifs to a different s3 bucket
 * [ca1858ca](https://github.com/argoproj/argo-workflows/commit/ca1858caade6385f5424e16f53da5d38f2fcb3b2) edit Argo license info so that GitHub recognizes it (#823)
 * [206451f0](https://github.com/argoproj/argo-workflows/commit/206451f066924abf3b4b6756606234150bf10fc9) Fix influxdb-ci.yml example
 * [da582a51](https://github.com/argoproj/argo-workflows/commit/da582a5194056a08d5eef95c2441b562cde08740) Avoid nil pointer for 2.0 workflows. (#820)
 * [0f225cef](https://github.com/argoproj/argo-workflows/commit/0f225cef91f4b276e24270a827c37dcd5292a4f0) ClusterRoleBinding was using incorrect service account namespace reference when overriding install namespace (resolves #814)
 * [66ea711a](https://github.com/argoproj/argo-workflows/commit/66ea711a1c7cc805282fd4065e029287f4617d57) Issue #816 - fix updating outboundNodes field of failed step group node (#817)
 * [00ceef6a](https://github.com/argoproj/argo-workflows/commit/00ceef6aa002199186475350b95ebc2d32debf14) install & uninstall commands use --namespace flag (#813)
 * [fe23c2f6](https://github.com/argoproj/argo-workflows/commit/fe23c2f651a61a2d7aa877a86edff9802d7b5b47) Issue #810 - `argo install`does not install argo ui (#811)
 * [28673ed2](https://github.com/argoproj/argo-workflows/commit/28673ed2f85ca39f5d9b136382ea9a87da0ca716) Update release date in change log
 * [05e8a983](https://github.com/argoproj/argo-workflows/commit/05e8a98386ccc73a02f39357f6faed69f7d11a17) Update change log for 2.1.0-beta1 release
 * [bf38b6b5](https://github.com/argoproj/argo-workflows/commit/bf38b6b509ae3fb123e47da2570906d0262ccf67) Use socket type for hostPath to mount docker.sock (#804) (#809)
 * [37680ef2](https://github.com/argoproj/argo-workflows/commit/37680ef26585f412930694cc809d9870d655bd13) Minimal shell completion support (#807)
 * [c83ad24a](https://github.com/argoproj/argo-workflows/commit/c83ad24a6fb5eb7054af16ae2c4f95de8df3965b) Omit empty status fields. (#806)
 * [d7291a3e](https://github.com/argoproj/argo-workflows/commit/d7291a3ee3b5375f8a079b60c568380e1bb91de9) Issue #660 - Support rendering logs from all steps using 'argo logs' command (#792)
 * [7d3f1e83](https://github.com/argoproj/argo-workflows/commit/7d3f1e83d3e08b13eb705ddd74244ea29e019c1a) Minor edits to README
 * [7a4c9c1f](https://github.com/argoproj/argo-workflows/commit/7a4c9c1f9c4fbd5282c57011c0bdcd48fe10137b) Added a review to README
 * [383276f3](https://github.com/argoproj/argo-workflows/commit/383276f300e666bf133a0355f2da493997ddd6cc) Inlined LICENSE file. Renamed old license to COPYRIGHT
 * [91d0f47f](https://github.com/argoproj/argo-workflows/commit/91d0f47fec82c7cef156ac05287622adc0b0a53b) Build argo cli image (#800)
 * [3b2c426e](https://github.com/argoproj/argo-workflows/commit/3b2c426ee5ba6249fec0d0a59353bfe77cb0966c) Add ability to pass pod annotations and labels at the template level (#798)
 * [d8be0287](https://github.com/argoproj/argo-workflows/commit/d8be0287f04f1d0d3bdee60243e0742594009bc8) Add ability to use IAM role from EC2 instance for AWS S3 credentials
 * [624f0f48](https://github.com/argoproj/argo-workflows/commit/624f0f48306183da33e2ef3aecf9566bb0ad8ad3) Update CHANGELOG.md for v2.1.0-beta1 release
 * [e96a09a3](https://github.com/argoproj/argo-workflows/commit/e96a09a3911f039038ea3038bed3a8cd8d63e269) Allow spec.arguments to be not supplied during linting. Global parameters were not referencable from artifact arguments (resolves #791)
 * [018e663a](https://github.com/argoproj/argo-workflows/commit/018e663a53aeda35149ec9b8de28f26391eb688e) Fix for https://github.com/argoproj/argo/issues/739 Nested stepgroups render correctly (#790)
 * [5c5b35ba](https://github.com/argoproj/argo-workflows/commit/5c5b35ba271fb48c38bf65e386e3d8b574f49373) Fix install issue where service account was not being created
 * [88e9e5ec](https://github.com/argoproj/argo-workflows/commit/88e9e5ecb5fc9e5215033a11abf6f6ddf50db253) packr needs to run compiled in order to cross compile darwin binaries
 * [dcdf9acf](https://github.com/argoproj/argo-workflows/commit/dcdf9acf9c7c3f58b3adfbf1994a5d3e7574dd9c) Fix install tests and build failure
 * [06c0d324](https://github.com/argoproj/argo-workflows/commit/06c0d324bf93a037010186fe54e40590ea39d92c) Rewrite the installer such that manifests are maintainable
 * [a45bf1b7](https://github.com/argoproj/argo-workflows/commit/a45bf1b7558b3eb60ec65d02c166c306e7797a79) Introduce support for exported global output parameters and artifacts
 * [60c48a9a](https://github.com/argoproj/argo-workflows/commit/60c48a9aa4b4dbf4c229e273faa945e0f5982539) Introduce `argo retry` to retry a failed workflow with the same name (resolves #762) onExit and related nodes should never be executed during resubmit/retry (resolves #780)
 * [90c08bff](https://github.com/argoproj/argo-workflows/commit/90c08bffc1b12b4c7941daccbf417772f17e3704) Refactor command structure
 * [101509d6](https://github.com/argoproj/argo-workflows/commit/101509d6b5ebeb957bb7ad6e819a961a26812a0e) Abstract the container runtime as an interface to support mocking and future runtimes Trim a trailing newline from path-based output parameters (resolves #758)
 * [a3441d38](https://github.com/argoproj/argo-workflows/commit/a3441d38b9be1f75506ab91dfbac7d6546d2b900) Add ability to reference global parameters in spec level fields (resolves #749)
 * [cd73a9ce](https://github.com/argoproj/argo-workflows/commit/cd73a9ce18aae35beee5012c68f553ab0c46030d) Fix template.parallelism limiting parallelism of entire workflow (resolves #772) Refactor operator to make template execution method signatures consistent
 * [7d7b74fa](https://github.com/argoproj/argo-workflows/commit/7d7b74fa8a62c43f8891a9af1dcae71f6efdc7e0) Make {{pod.name}} available as a parameter in pod templates (resolves #744)
 * [3cf4bb13](https://github.com/argoproj/argo-workflows/commit/3cf4bb136a9857ea17921a2ec6cfd95b4b95a0d7) parse the artifactory URL before appending the artifact to the path (#774)
 * [ea1257f7](https://github.com/argoproj/argo-workflows/commit/ea1257f717676997f0efcac9086ed348613a28c7) examples: use alpine python image
 * [2114078c](https://github.com/argoproj/argo-workflows/commit/2114078c533db0ab34b2f76fe481f03eba046cc1) fix typo
 * [9f605589](https://github.com/argoproj/argo-workflows/commit/9f6055899fff0b3161bb573159b13fd337e2e35f) Fix retry-container-to-completion example
 * [07422f26](https://github.com/argoproj/argo-workflows/commit/07422f264ed62a428622505e1880d2d5787d50ae) Update CHANGELOG release date. Remove ui-image from release target
 * [5d60d073](https://github.com/argoproj/argo-workflows/commit/5d60d073a1a6c2151ca3a07c15dd2580c92fc11d) Fix make release target
 * [a013fb38](https://github.com/argoproj/argo-workflows/commit/a013fb381b30ecb513def88a0ec3160bdc18a5d1) Fix inability to override LDFLAGS when env variables were supplied to make
 * [f63e552b](https://github.com/argoproj/argo-workflows/commit/f63e552b1c8e191689cfb73751654782de94445c) Minor spell fix for parallelism
 * [88d2ff3a](https://github.com/argoproj/argo-workflows/commit/88d2ff3a7175b0667351d0be611b97c2ebee908c) Add UI changes description for 2.1.0-alpha1 release (#761)
 * [ce4edb8d](https://github.com/argoproj/argo-workflows/commit/ce4edb8dfab89e9ff234b12d3ab4996183a095da) Add contributor credits
 * [cc8f35b6](https://github.com/argoproj/argo-workflows/commit/cc8f35b636558f98cd2bd885142aa1f8fd94cb75) Add note about region discovery.
 * [9c691a7c](https://github.com/argoproj/argo-workflows/commit/9c691a7c88904a50427349b698039ff90b1cf83b) Trim spaces from aws keys
 * [17e24481](https://github.com/argoproj/argo-workflows/commit/17e24481d8b3d8416f3590bb11bbee85123c1eb5) add keyPrefix option to ARTIFACT_REPO.md
 * [57a568bf](https://github.com/argoproj/argo-workflows/commit/57a568bfddc42528cb75580501d0b65264318424) Issue #747 - Support --instanceId parameter in submit a workflow (#748)
 * [81a6cd36](https://github.com/argoproj/argo-workflows/commit/81a6cd3653d1f0708bff4207e8df90c3dec4889a) Move UI code to separate repository (#742)
 * [10c7de57](https://github.com/argoproj/argo-workflows/commit/10c7de57478e13f6a11c77bcdf3ac3b0ae78fda7) Fix rbac resource versions in install
 * [2756e83d](https://github.com/argoproj/argo-workflows/commit/2756e83d7a38bd7307d15ef0328ebc1cf7f40cae) Support workflow pod tolerations
 * [9bdab63f](https://github.com/argoproj/argo-workflows/commit/9bdab63f451a2fff04cd58b55ecb9518f937e512) Add workflow.namespace to global parameters
 * [8bf7a1ad](https://github.com/argoproj/argo-workflows/commit/8bf7a1ad3fde2e24f14a79294dd47cb5dae080b1) Statically link argo linux binary (resolves #735)
 * [813cf8ed](https://github.com/argoproj/argo-workflows/commit/813cf8ed26e2f894b0457ee67cbb8d53e86c32c5) Add NodeStatus.DisplayName to remove CLI/UI guesswork from displaying node names (resolves #731)
 * [e783ccbd](https://github.com/argoproj/argo-workflows/commit/e783ccbd30d1e11e3dcec1912b59c76e738a9d79) Rename some internal template type names for consistency
 * [19dd406c](https://github.com/argoproj/argo-workflows/commit/19dd406cf040041ad15ce1867167902954f0f1d5) Introduce suspend templates for suspending a workflow at a predetermined step (resolves #702). Make suspend part of the workflow spec instead of infering parallism in status.
 * [d6489e12](https://github.com/argoproj/argo-workflows/commit/d6489e12f5af8bbb372bfe077a01972235f219d3) Rename pause to suspend
 * [f1e2f63d](https://github.com/argoproj/argo-workflows/commit/f1e2f63dbdf30895a7829337dcec6bcf4b54b5da) Change definition of WorkflowStep.Item to a struct instead of interface{} (resolves #723) Add better withItems unit testing and validation
 * [cd18afae](https://github.com/argoproj/argo-workflows/commit/cd18afae4932fd29b614a1b399edb84184d7a053) Missed handling of a error during workflow resubmission
 * [a7ca59be](https://github.com/argoproj/argo-workflows/commit/a7ca59be870397271fabf5dba7cdfca7d79a934f) Support resubmission of failed workflows with ability to re-use successful steps (resolves #694)
 * [76b41877](https://github.com/argoproj/argo-workflows/commit/76b41877c8a90b2e5529f9fe305f8ebdbcb72377) Include inputs as part of NodeStatus (resolves #730)
 * [ba683c1b](https://github.com/argoproj/argo-workflows/commit/ba683c1b916fd47bf21028cd1338ef8a7b4b7601) Support for manual pausing and resuming of workflows via Argo CLI (resolves #729)
 * [5a806f93](https://github.com/argoproj/argo-workflows/commit/5a806f93a398faefc276d958d476e77c12989a72) Add DAG gif for argo wiki (#728)
 * [62a3fba1](https://github.com/argoproj/argo-workflows/commit/62a3fba106be6a331ba234614c24562e620154c0) Implement support for DAG templates to have output parameters/artifacts
 * [989e8ed2](https://github.com/argoproj/argo-workflows/commit/989e8ed2c9e87ae4cc33df832f8ae4fb87c69fa7) Support parameter and artifact passing between DAG tasks. Improved template validation
 * [03d409a3](https://github.com/argoproj/argo-workflows/commit/03d409a3ac62a9e631c1f195b53fff70c8dfab7b) Switch back to Updating CRDs (from Patch) to enable better unit testing
 * [2da685d9](https://github.com/argoproj/argo-workflows/commit/2da685d93ff234f79689f40b3123667de81acce3) Fixed typos in examples/README.md
 * [6cf94b1b](https://github.com/argoproj/argo-workflows/commit/6cf94b1bf4d95c1e76a15c7ef36553cc301cf27d) Added output parameter example to examples/README.md
 * [0517096c](https://github.com/argoproj/argo-workflows/commit/0517096c32cd4f2443ae4208012c6110fbd07ab6) Add templateName as part of NodeStatus for UI consumption Simplify and centralize parallelism check into executeTemplate() Improved template validation
 * [deae4c65](https://github.com/argoproj/argo-workflows/commit/deae4c659b3c38f78fe5c8537319ea954fcfa54d) Add parallelism control at the steps template level
 * [c788484e](https://github.com/argoproj/argo-workflows/commit/c788484e1cbbe158c2d7cdddd30b1a8242e2c30c) Remove hard-wired executor limits and make it configurable in the controller (resolves #724)
 * [f27c7ffd](https://github.com/argoproj/argo-workflows/commit/f27c7ffd4e9bed1ddbbcb0e660854f6b2ce2daac) Fix linting issues (ineffassign, errcheck)
 * [98a44c99](https://github.com/argoproj/argo-workflows/commit/98a44c99c2515f2295327ae9572732586ddc3d7b) Embed container type into the script template instead of cherry-picking fields (resolves #711)
 * [c0a8f949](https://github.com/argoproj/argo-workflows/commit/c0a8f949b5ce9048fbc6f9fcc89876c8ad32c85c) Bump VERSION to 2.1.0
 * [207de824](https://github.com/argoproj/argo-workflows/commit/207de82474a3c98411072345f542ebee4d8e7208) Add parallism field to limit concurrent pod execution at a workflow level (issue #666)
 * [460c9555](https://github.com/argoproj/argo-workflows/commit/460c9555b760aa9405e959a96b6c8cf339096573) Do not initialize DAG task nodes if they did not execute
 * [13a60936](https://github.com/argoproj/argo-workflows/commit/13a60936ded42563617ad3d572c0c84d95b6c638) Merge branch 'feature-dag'
 * [931d7723](https://github.com/argoproj/argo-workflows/commit/931d7723cc42b3fc6d937b737735c9985cf91958) Update docs to refer to v2.0.0
 * [0978b9c6](https://github.com/argoproj/argo-workflows/commit/0978b9c61cb7435d31ef8d252b80e03708a70adc) Support setting UI base Url  (#722)
 * [b75cd98f](https://github.com/argoproj/argo-workflows/commit/b75cd98f6c038481ec3d2253e6404952bcaf4bd5) updated argo-user slack link
 * [b3598d84](https://github.com/argoproj/argo-workflows/commit/b3598d845c4cdb9ac7c4ae5eff5024ecd3fc5fd6) Add examples as functional and expected failure e2e tests
 * [83966e60](https://github.com/argoproj/argo-workflows/commit/83966e6095e2468368b0929613e7371074ee972b) Fix regression where executor did not annotate errors correctly
 * [751fd270](https://github.com/argoproj/argo-workflows/commit/751fd27024d9f3bfc40051d2ca694b25a42307ea) Update UI references to v2.0.0. Update changelog
 * [75caa877](https://github.com/argoproj/argo-workflows/commit/75caa877bc08184cad6dd34366b2b9f8b3dccc38) Initial work for dag based cli for everything. get now works (#714)
 * [8420deb3](https://github.com/argoproj/argo-workflows/commit/8420deb30a48839a097d3f5cd089e4b493b5e751) Skipped steps were being re-initialized causing a controller panic
 * [491ed08f](https://github.com/argoproj/argo-workflows/commit/491ed08ffe2f8430fcf35bf36e6dd16707eb5a0a) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [8b7e2e24](https://github.com/argoproj/argo-workflows/commit/8b7e2e24e8cf7ae6b701f08b0702ac045e0336f8) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [17241165](https://github.com/argoproj/argo-workflows/commit/17241165d004329e14bfc948759b38d4e17e5724) Merge branch 'master' into feature-dag
 * [563bda75](https://github.com/argoproj/argo-workflows/commit/563bda756732802caeaa516fd0c493c6e07f6cf9) Fix update-openapigen.sh script to presume bash. Tweak documentation
 * [5b9a602b](https://github.com/argoproj/argo-workflows/commit/5b9a602b4a763ac633f7ede86f13253451855462) Add documentation to types. Add program to generate OpenAPI spec
 * [42726910](https://github.com/argoproj/argo-workflows/commit/4272691035e0588bbd301449c122ee2851e3c87f) Fix retry in dag branch (#709)
 * [97204e64](https://github.com/argoproj/argo-workflows/commit/97204e64c5823a1563a87bd62f56613c0434a8f8) Merge branch 'master' into feature-dag
 * [d929e79f](https://github.com/argoproj/argo-workflows/commit/d929e79f623017a923d1c4e120c363e08fe7a64a) Generate OpenAPI models for the workflow spec (issue #707)
 * [1d5afee6](https://github.com/argoproj/argo-workflows/commit/1d5afee6ea48743bb854e69ffa333f361e52e289) Shortened url
 * [617d848d](https://github.com/argoproj/argo-workflows/commit/617d848da27d0035c20f21f3f6bddbe0e04550db) Added news to README
 * [ae36b22b](https://github.com/argoproj/argo-workflows/commit/ae36b22b6d0d0ce8c230aedcce0814489162ae5b) Fix typo s/Customer/Custom/ (#704)
 * [5a589fcd](https://github.com/argoproj/argo-workflows/commit/5a589fcd932116720411d53aeb6454e297456e06) Add ability to specify imagePullSecrets in the workflow.spec (resolves #699)
 * [2f77bc1e](https://github.com/argoproj/argo-workflows/commit/2f77bc1ed00042388d0492cfd480d7c22599112c) Add ability to specify affinity rules at both the workflow and template level (resolves #701)
 * [c2dd9b63](https://github.com/argoproj/argo-workflows/commit/c2dd9b635657273c3974fc358fcdf797c821ac92) Fix unit test breakages
 * [d38324b4](https://github.com/argoproj/argo-workflows/commit/d38324b46100e6ba07ad1c8ffc957c257aac41d7) Add boundaryID field in NodeStatus to group nodes by template boundaries
 * [639ad1e1](https://github.com/argoproj/argo-workflows/commit/639ad1e15312da5efa88fd62a0f3aced2ac17c52) Introduce Type field in NodeStatus to to assist with visualization
 * [17601c61](https://github.com/argoproj/argo-workflows/commit/17601c618a463edc1d971d462eec5e235835682d) Merge branch 'master' into feature-dag
 * [fdafbe27](https://github.com/argoproj/argo-workflows/commit/fdafbe27e5e2f4f2d58913328ae22db9a6c363b4) Sidecars unable to reference volume claim templates (resolves #697)
 * [0b0b52c3](https://github.com/argoproj/argo-workflows/commit/0b0b52c3b45cbe5ac62da7b26b30d19fc1f9eb3e) Referencing output artifacts from a container with retries was not functioning (resolves #698)
 * [9597f82c](https://github.com/argoproj/argo-workflows/commit/9597f82cd7a8b65cb03e4dfaa3023dcf20619b9d) Initial support for DAG based workflows (#693)
 * [bf2b376a](https://github.com/argoproj/argo-workflows/commit/bf2b376a142ed4fdf70ba4f3702533e7b75fc6b2) Update doc references to point to v2.0.0-beta1. Fix secrets example

### Contributors

 * Adam Pearse
 * Alexander Matyushentsev
 * Andrea Kao
 * Dan Bode
 * David Kale
 * Divya Vavili
 * Dmitry Monakhov
 * Edward Lee
 * Javier Castellanos
 * Jesse Dubay
 * Jesse Suen
 * Johannes 'fish' Ziemke
 * Lukasz Lempart
 * Matt Hillsdon
 * Mukulikak
 * Sean Fitzgerald
 * Sebastien Doido
 * Yang Pan
 * dougsc
 * gaganapplatix

## v2.0.0-beta1 (2018-01-18)

 * [549870c1](https://github.com/argoproj/argo-workflows/commit/549870c1ee08138b20b8a4b0c026569cf1e6c19a) Fix argo-ui download links to point to v2.0.0-beta1
 * [a202049d](https://github.com/argoproj/argo-workflows/commit/a202049d327c64e282a37d7598bddc1faa1a3c1a) Update CHANGELOG for v2.0.0-beta1
 * [a3739035](https://github.com/argoproj/argo-workflows/commit/a3739035f8e1f517721489fc53b58a8e27a575e1) Remove dind requirement from argo-ci test steps
 * [1bdd0c03](https://github.com/argoproj/argo-workflows/commit/1bdd0c03dbb9d82ad841ca19be6e1ea93aeb82f7) Include completed pods when attempting to reconcile deleted pods Switch back to Patch (from Update) for persisting workflow changes
 * [a4a43892](https://github.com/argoproj/argo-workflows/commit/a4a4389219cbe84e3bc7b3731cdfccb9ee5f5730) Sleep 1s after persisting workflow to give informer cache a chance to sync (resolves #686)
 * [5bf49531](https://github.com/argoproj/argo-workflows/commit/5bf49531f99ef9d8b8aefeac26a4a3fa0177e70d) Updated demo.md with link to ARTIFACT_REPO.md
 * [863d547a](https://github.com/argoproj/argo-workflows/commit/863d547a1a2a146a898c06c835187e0595af5689) Rely on controller generated timestamps for node.StartedAt instad of pod.CreationTimestamp
 * [672542d1](https://github.com/argoproj/argo-workflows/commit/672542d1f08c206f89f8747e9b14b675cdd77446) Re-apply workflow changes and reattempt update on resource conflicts. Make completed pod labeling asynchronous
 * [81bd6d3d](https://github.com/argoproj/argo-workflows/commit/81bd6d3d46d2fd7ea57aa095ae134116cfca90f2) Resource state retry (#690)
 * [44dba889](https://github.com/argoproj/argo-workflows/commit/44dba889cb743552557fcd7453ee81a89875142d) Tune controller to 20 QPS, 30 Burst, 8 wf workers, 8 pod workers
 * [178b9d37](https://github.com/argoproj/argo-workflows/commit/178b9d37cc452af214df7c9c41522124c117e7a3) Show running/completed pod counts in `argo list -o wide`
 * [0c565f5f](https://github.com/argoproj/argo-workflows/commit/0c565f5f5e9f69244e9828ced7c3916ac605f460) Switch to Updating workflow resources instead of Patching (resolves #686)
 * [a571f592](https://github.com/argoproj/argo-workflows/commit/a571f592fa131771b8d71126fc27809e24462cfe) Ensure sidecars get killed unequivocally. Final argoexec stats were not getting printed
 * [a0b2d78c](https://github.com/argoproj/argo-workflows/commit/a0b2d78c869f277c20c4cd3ba18b8d2688674e54) Show duration by default in `argo get`. --since flag should always include Running
 * [10110313](https://github.com/argoproj/argo-workflows/commit/101103136287b8ee16a7afda94cc6ff59be07ef6) Executor hardening: add retries and memoization for executor k8s API calls Recover from unexpected panics and annotate the error.
 * [f2b8f248](https://github.com/argoproj/argo-workflows/commit/f2b8f248ab8d483e0ba41a287611393500c7b507) Regenerate deepcopy code after type changes for raw input artifacts
 * [322e0e3a](https://github.com/argoproj/argo-workflows/commit/322e0e3aa3cb2e650f3ad4b7ff9157f71a92e8b4) renamed file as per review comment
 * [0a386cca](https://github.com/argoproj/argo-workflows/commit/0a386ccaf705a1abe1f9239adc966fceb7a808ae) changes from the review - renamed "contents" to "data" - lint issue
 * [d9ebbdc1](https://github.com/argoproj/argo-workflows/commit/d9ebbdc1b31721c8095d3c5426c1c811054a94a7) support for raw input as artifact
 * [a1f821d5](https://github.com/argoproj/argo-workflows/commit/a1f821d589d47ca5b12b94ad09306a706a43d150) Introduce communication channel from workflow-controller to executor through pod annotations
 * [b324f9f5](https://github.com/argoproj/argo-workflows/commit/b324f9f52109b9aa29bc89d63810be6e421eb54f) Artifactory repository was not using correct casing for repoURL field
 * [3d45d25a](https://github.com/argoproj/argo-workflows/commit/3d45d25ac497a09fa291d20f867a75f59b6abf92) Add `argo list --since` to filter workflows newer than a relative duration
 * [cc2efdec](https://github.com/argoproj/argo-workflows/commit/cc2efdec368c2f133c076a9eda9065f64762a9fa) Add ability to set loglevel of controller via CLI flag
 * [60c124e5](https://github.com/argoproj/argo-workflows/commit/60c124e5dddb6ebfee6300d36f6a3877838ec17c) Remove hack.go and use dep to install code-generators
 * [d14755a7](https://github.com/argoproj/argo-workflows/commit/d14755a7c5f583c1f3c8c762ae8628e780f566cf) `argo list` was not handling the default case correctly
 * [472f5604](https://github.com/argoproj/argo-workflows/commit/472f5604e27ca6310e016f846c97fda5d7bca9dd) Improvements to `argo list` * sort workflows by running vs. completed, then by finished time * add --running, --completed, --status XXX filters * add -o wide option to show parameters and -o name to show only the names
 * [b063f938](https://github.com/argoproj/argo-workflows/commit/b063f938f34f650333df6ec5a2e6a325a5b45299) Use minimal ClusterRoles for workflow-controller and argo-ui deployments
 * [21bc2bd0](https://github.com/argoproj/argo-workflows/commit/21bc2bd07ebbfb478c87032e2ece9939ea436030) Added link to configuring artifact repo from main README
 * [b54bc067](https://github.com/argoproj/argo-workflows/commit/b54bc067bda02f95937774fb3345dc2010d3efc6) Added link to configuring artifact repo from main README
 * [58ec5169](https://github.com/argoproj/argo-workflows/commit/58ec51699534e73d82c3f44027326b438cf5c063) Updated ARTIFACT_REPO.md
 * [1057d087](https://github.com/argoproj/argo-workflows/commit/1057d087838bcbdbffc70367e0fc02778907c9af) Added detailed instructions on configuring AWS and GCP artifact rpos
 * [b0a7f0da](https://github.com/argoproj/argo-workflows/commit/b0a7f0da85fabad34814ab129eaba43862a1d2dd) Issue 680 - Argo UI is failing to render workflow which has not been picked up by workflow controller (#681)
 * [e91c227a](https://github.com/argoproj/argo-workflows/commit/e91c227acc1f86b7e341aaac534930f9b529cd89) Document and clarify artifact passing (#676)
 * [290f6799](https://github.com/argoproj/argo-workflows/commit/290f6799752ef602b27c193212495e27f40dd687) Allow containers to be retried. (#661)
 * [80f9b1b6](https://github.com/argoproj/argo-workflows/commit/80f9b1b636704ebad6ebb8df97c5e81dc4f815f9) Improve the error message when insufficent RBAC privileges is detected (resolves #659)
 * [3cf67df4](https://github.com/argoproj/argo-workflows/commit/3cf67df422f34257296d2de09d2ca3c8c87abf84) Regenerate autogenerated code after changes to types
 * [baf37052](https://github.com/argoproj/argo-workflows/commit/baf37052976458401a6c0e44d06f30dc8d819680) Add support for resource template outputs. Remove output.parameters.path in favor of valueFrom
 * [dc1256c2](https://github.com/argoproj/argo-workflows/commit/dc1256c2034f0add4bef3f82ce1a71b454d4eef5) Fix expected file name for issue template
 * [a492ad14](https://github.com/argoproj/argo-workflows/commit/a492ad14177eb43cdd6c2a017c9aec87183682ed) Add a GitHub issues template
 * [55be93a6](https://github.com/argoproj/argo-workflows/commit/55be93a68d8991f76a31adaf49f711436a35a9d0) Add a --dry-run option to `argo install`. Remove CRD creation from controller startup
 * [fddc052d](https://github.com/argoproj/argo-workflows/commit/fddc052df8a3478aede67057f2b06938c2a6a7a4) Fix README.md to contain influxdb-client in the example (#669)
 * [67236a59](https://github.com/argoproj/argo-workflows/commit/67236a5940231f7b9dc2ca2f4cb4cb70b7c18d45) Update getting started doc to use `brew install` and better instructions for RBAC clusters (resolves #654, #530)
 * [5ac19753](https://github.com/argoproj/argo-workflows/commit/5ac19753846566d0069b76e3e6c6dd03f0e6950c) Support rendering retry steps (#670)
 * [3cca0984](https://github.com/argoproj/argo-workflows/commit/3cca0984c169ea59e8e2758a04550320b1981875) OpenID Connect auth support (#663)
 * [c222cb53](https://github.com/argoproj/argo-workflows/commit/c222cb53a168f9bd40b7731d0b2f70db977990c2) Clarify where the Minio secret comes from.
 * [a78e2e8d](https://github.com/argoproj/argo-workflows/commit/a78e2e8d551d6afad2e0fbce7a9f0a1bd023c11b) Remove parallel steps that use volumes.
 * [35517385](https://github.com/argoproj/argo-workflows/commit/355173857f98a9a9704ab23235b3186bde8092b9) Prevent a potential k8s scheduler panic from incomplete setting of pod ownership reference (resolves #656)
 * [1a8bc26d](https://github.com/argoproj/argo-workflows/commit/1a8bc26d40597f2f0475aa9197a6b3912c5bbb56) Updated README
 * [9721fca0](https://github.com/argoproj/argo-workflows/commit/9721fca0e1ae9d1d57aa8d1872450ce8ee7487e2) Updated README
 * [e3177606](https://github.com/argoproj/argo-workflows/commit/e3177606105a936da7eba29924fa49ad497703c9) Fix typos in READMEs
 * [555d50b0](https://github.com/argoproj/argo-workflows/commit/555d50b0ebeef1c753394de974dad2e0d4a5b787) Simplify some getting started instructions. Correct some usages of container resources field
 * [4abc9c40](https://github.com/argoproj/argo-workflows/commit/4abc9c40e7656a5783620e41b33e4ed3bb7249e2) Updated READMEs
 * [a0add24f](https://github.com/argoproj/argo-workflows/commit/a0add24f9778789473b2b097fb31a56ae11bfce9) Switch to k8s-codegen generated workflow client and informer
 * [9b08b6e9](https://github.com/argoproj/argo-workflows/commit/9b08b6e997633d5f2e94392f000079cbe93ee023) Added link for argoproj slack channel
 * [682bbdc0](https://github.com/argoproj/argo-workflows/commit/682bbdc09b66698090d309e91b5caf4483931e34) Update references to point to latest argo release

### Contributors

 * Alexander Matyushentsev
 * Ed Lee
 * Jesse Suen
 * Matt Hillsdon
 * Rhys Parry
 * Sandeep Bhojwani
 * Shri Javadekar
 * gaganapplatix

## v2.0.0-alpha3 (2018-01-02)

 * [940dd56d](https://github.com/argoproj/argo-workflows/commit/940dd56d98c75eb93da3b5de598882754cb74fc7) Fix artifactory unit test and linting issues
 * [e7ba2b44](https://github.com/argoproj/argo-workflows/commit/e7ba2b44114fca8a3cb2b8635dc2fdfeaa440d9e) Update help page links (#651)
 * [53dac4c7](https://github.com/argoproj/argo-workflows/commit/53dac4c74933c333124a0cb1d8cf6c9255f9199d) Add artifactory and UI fixes to 2.0.0-alpha3 CHANGELOG
 * [4b4eff43](https://github.com/argoproj/argo-workflows/commit/4b4eff43f20ed678d34efe567a4d61d1364d7124) Allow disabling web console feature (#649)
 * [90b7f2e6](https://github.com/argoproj/argo-workflows/commit/90b7f2e67dddebba1678e215bde75d68867b4469) Added support for artifactory
 * [849e916e](https://github.com/argoproj/argo-workflows/commit/849e916e5bf98f320f1a65b12ffe246d9ebbb6f6) Adjusted styles for logs stream (#614)
 * [a8a96030](https://github.com/argoproj/argo-workflows/commit/a8a960303423cde2e511d4af9c2c8ae834076b21) Update CHANGELOG for 2.0.0-alpha3
 * [e7c7678c](https://github.com/argoproj/argo-workflows/commit/e7c7678cc605285e5b3224c757e5e4be57ab4d5c) Fix issue preventing ability to pass JSON as a command line param (resolves #646)
 * [7f5e2b96](https://github.com/argoproj/argo-workflows/commit/7f5e2b96bd96e0bccf4778383aa9b94a1768e9c0) Add validation checks for volumeMount/artifact path collision and activeDeadlineSeconds (#620)
 * [dc4a9463](https://github.com/argoproj/argo-workflows/commit/dc4a94633c4d00d78a7ea53272e425962de405ba) Add the ability to specify the service account used by pods in the workflow (resolves #634) Also add argo CLI support for supplying/overriding spec.serviceAccountName from command line.
 * [16f7000a](https://github.com/argoproj/argo-workflows/commit/16f7000aa77b2759fa0a65d6e42456bcb660f824) Workflow operator will recover from unexpected panics and mark the workflow with error (resolves #633)
 * [18dca7fe](https://github.com/argoproj/argo-workflows/commit/18dca7fe21d57e6a5415c53bfdb87a889ac32456) Issue #629 - Add namespace to workflow list and workflow details page (#639)
 * [e656bace](https://github.com/argoproj/argo-workflows/commit/e656bace75aaa859f04121f2c1d95631b462fe62) Issue #637 -  Implement Workflow list and workflow details page live update (#638)
 * [1503ce3a](https://github.com/argoproj/argo-workflows/commit/1503ce3aee40eba741819a1403847df4bbcb7b23) Issue #636 - Upgrade to ui-lib 2.0.3 to fix xterm incompatibility (#642)
 * [f9170e8a](https://github.com/argoproj/argo-workflows/commit/f9170e8abb7121b0d0cbc3e4c07b9bdc2224fb76) Remove manifest-passing.yaml example now that we have resource templates
 * [25be5fd6](https://github.com/argoproj/argo-workflows/commit/25be5fd6368bac3fde8e4392b3cb9d4159983a1a) Implementation for resource templates and resource success/failure conditions
 * [402ad565](https://github.com/argoproj/argo-workflows/commit/402ad565f4a3b95c449ddd4c6dc468947aeb7192) Updated examples/README
 * [8536c7fc](https://github.com/argoproj/argo-workflows/commit/8536c7fc89a0ceb39208efe2076919d0390e3d2e) added secret example to examples/README
 * [e5002b82](https://github.com/argoproj/argo-workflows/commit/e5002b8286af2c1f7ec64953114e1d97c889ca37) Add '--wait' to argo submit.
 * [9646e55f](https://github.com/argoproj/argo-workflows/commit/9646e55f8bb8fbac80d456853aa891c2ae069adb) Installer was not update configmap correctly with new executor image during upgrade
 * [69d72913](https://github.com/argoproj/argo-workflows/commit/69d72913a3a72bbf7b075be847303305b4bef1a5) Support private git repos using secret selector fields in the git artifact (resolves #626)
 * [64e17244](https://github.com/argoproj/argo-workflows/commit/64e17244ef04b9d2aa6abf6f18d4e7ef2d20ff37) Add argo ci workflow (#619)
 * [e8998435](https://github.com/argoproj/argo-workflows/commit/e8998435598e8239d7b77a60cfda43e8f2869b4d) Resolve controller panic when a script template with an input artifact was submitted (resolves #617). Utilize the kubernetes.Interface and fake.Clientset to support unit test mocking. Added a unit test to reproduce the panic. Add an e2e test to verify functionality works.
 * [52075b45](https://github.com/argoproj/argo-workflows/commit/52075b45611783d909609433bb44702888b5db37) Introduce controller instance IDs to support multiple workflow controllers in a cluster (resolves #508)
 * [133a23ce](https://github.com/argoproj/argo-workflows/commit/133a23ce20b4570ded81fac76a430f0399c1eea1) Add ability to timeout a container/script using activeDeadlineSeconds
 * [b5b16e55](https://github.com/argoproj/argo-workflows/commit/b5b16e55260df018cc4de14bf298ce59714b4396) Support for workflow exit handlers
 * [906b3e7c](https://github.com/argoproj/argo-workflows/commit/906b3e7c7cac191f920016362b076a28f18d97c1) Update ROADMAP.md
 * [5047422a](https://github.com/argoproj/argo-workflows/commit/5047422ae71869672c84364d099e1488b29fbbe8) Update CHANGELOG.md
 * [2b6583df](https://github.com/argoproj/argo-workflows/commit/2b6583dfb02911965183ef4b25ed68c867448e10) Add `argo wait` for waiting on workflows to complete. (#618)
 * [cfc9801c](https://github.com/argoproj/argo-workflows/commit/cfc9801c40528b6605823e1f4b4359600b6887df) Add option to print output of submit in json.
 * [c20c0f99](https://github.com/argoproj/argo-workflows/commit/c20c0f9958ceeefd3597120fcb4013d857276076) Comply with semantic versioning. Include build metadata in `argo version` (resolves #594)
 * [bb5ac7db](https://github.com/argoproj/argo-workflows/commit/bb5ac7db52bff613c32b153b82953ec9c73c3b8a) minor change
 * [91845d49](https://github.com/argoproj/argo-workflows/commit/91845d4990ff8fd97bd9404e4b37024be1ee0ba6) Added more documentation
 * [4e8d69f6](https://github.com/argoproj/argo-workflows/commit/4e8d69f630bc0fd107b360ee9ad953ccb0b78f11) fixed install instructions
 * [0557147d](https://github.com/argoproj/argo-workflows/commit/0557147dd4bfeb2688b969293ae858a8391d78ad) Removed empty toolbar (#600)
 * [bb2b29ff](https://github.com/argoproj/argo-workflows/commit/bb2b29ff5e4178e2c8a9dfe666b699d75aa9ab3b) Added limit for number of steps in workflows list (#602)
 * [3f57cc1d](https://github.com/argoproj/argo-workflows/commit/3f57cc1d2ff9c0e7ec40da325c3478a8037a6ac0) fixed typo in examples/README
 * [ebba6031](https://github.com/argoproj/argo-workflows/commit/ebba6031192b0a763bd94b1625a2ff6e242f112e) Updated examples/README.md with how to override entrypoint and parameters
 * [81834db3](https://github.com/argoproj/argo-workflows/commit/81834db3c0bd12758a95e8a5862d6dda6d0dceeb) Example with using an emptyDir volume.
 * [4cd949d3](https://github.com/argoproj/argo-workflows/commit/4cd949d327ddb9d4f4592811c51e07bb53b30ef9) Remove apiserver
 * [6a916ca4](https://github.com/argoproj/argo-workflows/commit/6a916ca447147e4aff364ce032c9db4530d49d11) `argo lint` did not split yaml files. `argo submit` was not ignoring non-workflow manifests
 * [bf7d9979](https://github.com/argoproj/argo-workflows/commit/bf7d997970e967b2b238ce209ce823ea47de01d2) Include `make lint` and `make test` as part of CI
 * [d1639ecf](https://github.com/argoproj/argo-workflows/commit/d1639ecfabf73f73ebe040b832668bd6a7b60d20) Create example workflow using kubernetes secrets (resolves #592)
 * [31c54af4](https://github.com/argoproj/argo-workflows/commit/31c54af4ba4cb2a0db918fadf62cb0b854592ba5) Toolbar and filters on workflows list (#565)
 * [bb4520a6](https://github.com/argoproj/argo-workflows/commit/bb4520a6f65d4e8e765ce4d426befa583721c194) Add and improve the inlined comments in example YAMLs
 * [a0470728](https://github.com/argoproj/argo-workflows/commit/a04707282cdeadf463b22b633fc00dba432f60bf) Fixed typo.
 * [13366e32](https://github.com/argoproj/argo-workflows/commit/13366e32467a34a061435091589c90d04a84facb) Fix some wrong GOPATH assumptions in Makefile. Add `make test` target. Fix unit tests
 * [9f4f1ee7](https://github.com/argoproj/argo-workflows/commit/9f4f1ee75705150a22dc68a3dd16fa90069219ed) Add 'misspell' to linters. Fix misspellings caught by linter
 * [1b918aff](https://github.com/argoproj/argo-workflows/commit/1b918aff29ff8e592247d14c52be06a0537f0734) Address all issues in code caught by golang linting tools (resolves #584)
 * [903326d9](https://github.com/argoproj/argo-workflows/commit/903326d9103fa7dcab37835a9478f58aff51a5d1) Add manifest passing to do kubectl create with dynamic manifests (#588)
 * [b1ec3a3f](https://github.com/argoproj/argo-workflows/commit/b1ec3a3fc90a211f9afdb9090d4396c98ab3f71f) Create the argo-ui service with type ClusterIP as part of installation (resolves #582)
 * [5b6271bc](https://github.com/argoproj/argo-workflows/commit/5b6271bc56b46a82b0ee2bc0784315ffcddeb27f) Add validate names for various workflow specific fields and tests for them (#586)
 * [b6e67131](https://github.com/argoproj/argo-workflows/commit/b6e671318a446f129740ce790f53425d65e436f3) Implementation for allowing access to global parameters in workflow (#571)
 * [c5ac5bfb](https://github.com/argoproj/argo-workflows/commit/c5ac5bfb89274fb5ee85f9cef346b7059b5d7641) Fix error message when key does not exist in secret (resolves #574). Improve s3 example and documentation.
 * [4825c43b](https://github.com/argoproj/argo-workflows/commit/4825c43b3e0c3c54b2313aa54e69520ed1b8a38d) Increate UI build memory limit (#580)
 * [87a20c6b](https://github.com/argoproj/argo-workflows/commit/87a20c6bce9a6bfe2a88edc581746ff5f7f006fc) Update input-artifacts-s3.yaml example to explain concepts and usage better
 * [c16a9c87](https://github.com/argoproj/argo-workflows/commit/c16a9c87102fd5b66406737720204e5f17af0fd1) Rahuldhide patch 2 (#579)
 * [f5d0e340](https://github.com/argoproj/argo-workflows/commit/f5d0e340b3626658b435dd2ddd937e97af7676b2) Issue #549 - Prepare argo v1 build config (#575)
 * [3b3a4c87](https://github.com/argoproj/argo-workflows/commit/3b3a4c87bd3138961c948f869e2c5b7c932c8847) Argo logo
 * [d1967443](https://github.com/argoproj/argo-workflows/commit/d1967443a4943f685f6cb1649480765050bdcdaa) Skip e2e tests if Kubeconfig is not provided.
 * [1ec231b6](https://github.com/argoproj/argo-workflows/commit/1ec231b69a1a7d985d1d587980c34588019b04aa) Create separate namespaces for tests.
 * [5ea20d7e](https://github.com/argoproj/argo-workflows/commit/5ea20d7eb5b9193c19f7c875c8fb2f4af8f68ef3) Add a deadline for workflow operation to prevent workqueue starvation and to enable state resync (#531) Tested with 6 x 1000 pod workflows.
 * [346bafe6](https://github.com/argoproj/argo-workflows/commit/346bafe636281bca94695b285767f41ae71e6a69) Multiple scalability improvements to controller (resolves #531)
 * [bbc56b59](https://github.com/argoproj/argo-workflows/commit/bbc56b59e2ff9635244bcb091e92e257a508d147) Improve argo ui build performance and reduce image size (#572)
 * [cdb1ce82](https://github.com/argoproj/argo-workflows/commit/cdb1ce82bce9b103e433981d94bd911b0769350d) Upgrade ui-lib (#556)
 * [0605ad7b](https://github.com/argoproj/argo-workflows/commit/0605ad7b33fc4f9c0bbff79adf1d509d3b072703) Adjusted tabs content size to see horizontal and vertical scrolls. (#569)
 * [a3316236](https://github.com/argoproj/argo-workflows/commit/a331623697e76a5e3497257e28fabe1995852339) Fix rendering 'Error' node status (#564)
 * [8c3a7a93](https://github.com/argoproj/argo-workflows/commit/8c3a7a9393d619951a676324810d482d28dfe015) Issue #548  - UI terminal window  (#563)
 * [5ec6cc85](https://github.com/argoproj/argo-workflows/commit/5ec6cc85aab63ea2277ce621d5de5b59a510d462) Implement API to ssh into pod (#561)
 * [beeb65dd](https://github.com/argoproj/argo-workflows/commit/beeb65ddcb7d2b5f8286f7881af1f5c00535161e) Don't mess the controller's arguments.
 * [01f5db5a](https://github.com/argoproj/argo-workflows/commit/01f5db5a0c3dc48541577b9d8b1d815399728070) Parameterize Install() and related methods.
 * [85a2e271](https://github.com/argoproj/argo-workflows/commit/85a2e2711beba8f2c891af396a3cc886c7b37542) Fix tests.
 * [56f666e1](https://github.com/argoproj/argo-workflows/commit/56f666e1bf69a7f5d8191637e8c7f384b91d98d0) Basic E2e tests.
 * [9eafb9dd](https://github.com/argoproj/argo-workflows/commit/9eafb9dd59166e76804b71c8df19fdca453cdd28) Issue #547 - Support filtering by status in API GET /workflows (#550)
 * [37f41eb7](https://github.com/argoproj/argo-workflows/commit/37f41eb7bf366cfe007d3ecce7b21f003d381e34) Update demo.md
 * [ea8d5c11](https://github.com/argoproj/argo-workflows/commit/ea8d5c113d9245f47fe7b3d3f45e7891aa5f50e8) Update README.md
 * [373f0710](https://github.com/argoproj/argo-workflows/commit/373f07106ab14e3772c94af5cc11f7f1c7099204) Add support for making a no_ui build. Base all build on no_ui build (#553)
 * [ae65c57e](https://github.com/argoproj/argo-workflows/commit/ae65c57e55f92fd8ff1edd099f659e9e97ce59f1) Update demo.md
 * [f6f8334b](https://github.com/argoproj/argo-workflows/commit/f6f8334b2b3ed1f498c19e4de25421f41807f893) V2 style adjustments and small fixes (#544)
 * [12d5b7ca](https://github.com/argoproj/argo-workflows/commit/12d5b7ca48c913e53b74708a35727d523dfa5355) Document argo ui service creation (#545)
 * [3202d4fa](https://github.com/argoproj/argo-workflows/commit/3202d4fac2d5d2d2a3ad1d679c1b753b04aca796) Support all namespaces (#543)
 * [b553c1bd](https://github.com/argoproj/argo-workflows/commit/b553c1bd9a00499915dbe5926194d67c7392b944) Update demo.md to qualify the minio endpoint with the default namespace
 * [4df7617c](https://github.com/argoproj/argo-workflows/commit/4df7617c2e97f2336195d6764259537be648b89b) Fix artifacts downloading (#541)
 * [12732200](https://github.com/argoproj/argo-workflows/commit/12732200fb1ed95608cdc0b14bd0802c524c7fa2) Update demo.md with references to latest release

### Contributors

 * Alexander Matyushentsev
 * Anshuman Bhartiya
 * Ed Lee
 * Javier Castellanos
 * Jesse Suen
 * Rafal
 * Rahul Dhide
 * Sandeep Bhojwani
 * Shri Javadekar
 * Wojciech Kalemba
 * gaganapplatix
 * mukulikak

## v2.0.0-alpha2 (2017-12-04)

 * [0e67b861](https://github.com/argoproj/argo-workflows/commit/0e67b8616444cf637d5b68e58eb6e068b721d34c) Add 'release' make target. Improve CLI help and set version from git tag. Uninstaller for UI
 * [8ab1d2e9](https://github.com/argoproj/argo-workflows/commit/8ab1d2e93ff969a1a01a06dcc3ac4aa04d3514aa) Install argo ui along with argo workflow controller (#540)
 * [f4af881e](https://github.com/argoproj/argo-workflows/commit/f4af881e55cff12888867bca9dff940c1bb16c26) Add make command to build argo ui (#539)
 * [5bb85814](https://github.com/argoproj/argo-workflows/commit/5bb858145e1c603494d8202927197d38b121311a) Add example description in YAML.
 * [fc23fcda](https://github.com/argoproj/argo-workflows/commit/fc23fcdaebc9049748d57ab178517d18eed4af7d) edit example README
 * [8dd294aa](https://github.com/argoproj/argo-workflows/commit/8dd294aa003ee1ffaa70cd7735b7d62c069eeb0f) Add example of GIF processing using ImageMagick
 * [ef8e9d5c](https://github.com/argoproj/argo-workflows/commit/ef8e9d5c234b1f889c4a2accbc9f24d58ce553b9) Implement loader (#537)
 * [2ac37361](https://github.com/argoproj/argo-workflows/commit/2ac37361e6620b37af09cd3e50ecc0fb3fb62a12) Allow specifying CRD version (#536)
 * [15b5542d](https://github.com/argoproj/argo-workflows/commit/15b5542d7cff2b0812830b16bcc5ae490ecc7302) Installer was not using the argo serviceaccount with the workflow-controller deployment. Make progress messages consistent
 * [f1471347](https://github.com/argoproj/argo-workflows/commit/f1471347d96838e0e13e47d0bc7fc04b3018d6f7) Add Yaml viewer (#535)
 * [685a576b](https://github.com/argoproj/argo-workflows/commit/685a576bd28bb269d727a10bf617bd1b08ea4ff0) Fix Gopkg.lock file following rewrite of git history at github.com/minio/go-homedir
 * [01ab3076](https://github.com/argoproj/argo-workflows/commit/01ab3076fe68ef62a9e3cc89b0e367cbdb64ff37) Delete clusterRoleBinding and serviceAccount.
 * [7bb99ae7](https://github.com/argoproj/argo-workflows/commit/7bb99ae713da51c9b9818027066f7ddd8efb92bb) Rename references from v1 to v1alpha1 in YAML
 * [32343913](https://github.com/argoproj/argo-workflows/commit/3234391356ae0eaf88d348b564828c2df754a49e) Implement step artifacts tab (#534)
 * [b2a58dad](https://github.com/argoproj/argo-workflows/commit/b2a58dad98942ad06b0431968be00ebe588818ff) Workflow list (#533)
 * [5dd1754b](https://github.com/argoproj/argo-workflows/commit/5dd1754b4a41c7951829dbbd8e70a244cf627331) Guard controller from informer sending non workflow/pod objects (#505)
 * [59e31c60](https://github.com/argoproj/argo-workflows/commit/59e31c60f8675c2c678c50e9694ee993691b6e6a) Enable resync period in workflow/pod informers (resolves #532)
 * [d5b06dcd](https://github.com/argoproj/argo-workflows/commit/d5b06dcd4e52270a24f4f3b19497b9a9afaed4e9) Significantly increase efficiency of workflow control loop (resolves #505)
 * [4b2098ee](https://github.com/argoproj/argo-workflows/commit/4b2098ee271301eca52403e769f82f6d717400af) finished walkthrough sections
 * [eb7292b0](https://github.com/argoproj/argo-workflows/commit/eb7292b02414ef6faca4f424f6b04ea444abb0e0) walkthrough
 * [82b1c7d9](https://github.com/argoproj/argo-workflows/commit/82b1c7d97536baac7514d7cfe72d1be9309bef43) Add -o wide option to `argo get` to display artifacts and durations (resolves #526)
 * [3427955d](https://github.com/argoproj/argo-workflows/commit/3427955d35bf6babc0bfee958a2eb417553ed203) Use PATCH api from k8s go SDK for annotating/labeling pods
 * [4842bbbc](https://github.com/argoproj/argo-workflows/commit/4842bbbc7e40340de12c788cc770eaa811431818) Add support for nodeSelector at both the workflow and step level (resolves #458)
 * [424fba5d](https://github.com/argoproj/argo-workflows/commit/424fba5d4c26c448c8c8131b89113c4c5fbae08d) Rename apiVersion of workflows from v1 to v1alpha1 (resolves #517)
 * [5286728a](https://github.com/argoproj/argo-workflows/commit/5286728a98236c5a8883850389d286d67549966e) Propogate executor errors back to controller. Add error column in `argo get` (#522)
 * [32b5e99b](https://github.com/argoproj/argo-workflows/commit/32b5e99bb194e27a8a35d1d7e1378dd749cc546f) Simplify executor commands to just 'init' and 'wait'. Improve volumes examples
 * [e2bfbc12](https://github.com/argoproj/argo-workflows/commit/e2bfbc127d03f5ef20763fe8a917c82e3f06638d) Update controller config automatically on configmap updates resolves #461
 * [c09b13f2](https://github.com/argoproj/argo-workflows/commit/c09b13f21eaec4bb78c040134a728d8e021b4d1e) Workflow validation detects when arguments were not supplied (#515)
 * [705193d0](https://github.com/argoproj/argo-workflows/commit/705193d053cb8c0c799a0f636fc899e8b7f55bcc) Proper message for non-zero exits from main container. Indicate an Error phase/message when failing to load/save artifacts
 * [e69b7510](https://github.com/argoproj/argo-workflows/commit/e69b7510196daba3a87dca0c8a9677abd8d74675) Update page title and favicon (#519)
 * [4330232f](https://github.com/argoproj/argo-workflows/commit/4330232f51d404a7546cf24b4b0eb608bf3113f5) Render workflow steps on workflow list page (#518)
 * [87c447ea](https://github.com/argoproj/argo-workflows/commit/87c447eaf2ca2230e9b24d6af38f3a0fd3c520c3) Implement kube api proxy. Add workflow node logs tab (#511)
 * [0ab26883](https://github.com/argoproj/argo-workflows/commit/0ab268837cff2a1fd464673a45c3736178917be5) Rework/rename Makefile targets. Bake in image namespace/tag set during build, as part of argo install
 * [3f13f5ca](https://github.com/argoproj/argo-workflows/commit/3f13f5cabe9dc54c7fbaddf7b0cfbcf91c3f26a7) Support for overriding/supplying entrypoint and parameters via argo CLI. Update examples
 * [6f9f2adc](https://github.com/argoproj/argo-workflows/commit/6f9f2adcd017954a72b2b867e6bc2bcba18972af) Support ListOptions in the WorkflowClient. Add flag to delete completed workflows
 * [30d7fba1](https://github.com/argoproj/argo-workflows/commit/30d7fba1205e7f0b4318d6b03064ee647d16ce59) Check Kubernetes version.
 * [a3909273](https://github.com/argoproj/argo-workflows/commit/a3909273c435b23de865089b82b712e4d670a4ff) Give proper error for unamed steps
 * [eed54f57](https://github.com/argoproj/argo-workflows/commit/eed54f5732a61922f6daff9e35073b33c1dc068e) Harden the IsURL check
 * [bfa62afd](https://github.com/argoproj/argo-workflows/commit/bfa62afd857704c53aef32f5ade7df86cf2c0769) Add phase,completed fields to workflow labels. Add startedAt,finishedAt,phase,message to workflow.status
 * [9347619c](https://github.com/argoproj/argo-workflows/commit/9347619c7c125950a9f17acfbd92a1286bca1a57) Create serviceAccount & roleBinding if necessary.
 * [205e5cbc](https://github.com/argoproj/argo-workflows/commit/205e5cbce20a6e5e73c977f1e775671a19bf4434) Introduce 'completed' pod label and label selector so controller can ignore completed pods
 * [199dbcbf](https://github.com/argoproj/argo-workflows/commit/199dbcbf1c3fa2fd452e5c36035d0f0ae8cdde42) 476 jobs list page (#501)
 * [05879294](https://github.com/argoproj/argo-workflows/commit/0587929453ac10d7318a91f2243aece08fe84129) Implement workflow tree tab draft (#494)
 * [a2f034a0](https://github.com/argoproj/argo-workflows/commit/a2f034a063b30b0bb5d9e0f670a8bb38560880b4) Proper error reporting. Add message, startedAt, finishedAt to NodeStatus. Rename status to phase
 * [645fedca](https://github.com/argoproj/argo-workflows/commit/645fedcaf532e052ef0bfc64cb56bfb3307479dd) Support loop step expansion from input parameters and previous step results
 * [75c1c482](https://github.com/argoproj/argo-workflows/commit/75c1c4822b4037176aa6d3702a5cf4eee590c7b7) Help page v2 (#492)
 * [a4af6702](https://github.com/argoproj/argo-workflows/commit/a4af6702d526e775c0aa31ee3612328e5d058c2b) Basic state of  navigation, top-bar, tooltip for UI v2 (#491)
 * [726e9fa0](https://github.com/argoproj/argo-workflows/commit/726e9fa0953fe91eb0401727743a04c8a02668ef) moved the service acct note
 * [3a4cd9c4](https://github.com/argoproj/argo-workflows/commit/3a4cd9c4ba46f586a3d26fbe017d4d3002e6b671) 477 job details page (#488)
 * [8ba7b55c](https://github.com/argoproj/argo-workflows/commit/8ba7b55cb59173ff7470be3451cd38333539b182) Edited the instructions
 * [1e9dbdba](https://github.com/argoproj/argo-workflows/commit/1e9dbdbabbe354f9798162854dd7d6ae4aa8539a) Added influxdb-ci example
 * [bd5c0baa](https://github.com/argoproj/argo-workflows/commit/bd5c0baad83328f13f25ba59e15a5f607d2fb9eb) Added comment for entrypoint field
 * [2fbecdf0](https://github.com/argoproj/argo-workflows/commit/2fbecdf0484a9e3c0d9242bdd7286f83b6e771eb) Argo V2 UI initial commit (#474)
 * [da4ef06e](https://github.com/argoproj/argo-workflows/commit/da4ef06e14c55a3ffc80bcdbd1b637a984f2f0f9) added artifact to ci example
 * [9ce20123](https://github.com/argoproj/argo-workflows/commit/9ce2012303aa30623336f0dde72ad9b80a5409e3) added artifacts
 * [caaa32a6](https://github.com/argoproj/argo-workflows/commit/caaa32a6b3c28c4f5a43514799b26528b55197ee) Minor edit
 * [ae72b583](https://github.com/argoproj/argo-workflows/commit/ae72b583852e43f616d4c021a4e5646235d4c0b4) added more argo/kubectl examples
 * [1db21612](https://github.com/argoproj/argo-workflows/commit/1db21612695a0a9170e265232acc19936b0d7294) merged
 * [8df393ed](https://github.com/argoproj/argo-workflows/commit/8df393ed78d1e4353ee30ba02cec0b12daea7eb0) added 2.0
 * [9e3a51b1](https://github.com/argoproj/argo-workflows/commit/9e3a51b14d78c3622543429a500a7d0367b10787) Update demo.md to have better instructions to restart controller after configuration changes
 * [ba9f9277](https://github.com/argoproj/argo-workflows/commit/ba9f9277a4a9a153a6f5b19862a73364f618e5cd) Add demo markdown file. Delete old demo.txt
 * [d8de40bb](https://github.com/argoproj/argo-workflows/commit/d8de40bb14167f30b17de81d6162d633a62e7a0d) added 2.0
 * [6c617599](https://github.com/argoproj/argo-workflows/commit/6c617599bf4c91ccd3355068967824c1e8d7c107) added 2.0
 * [32af692e](https://github.com/argoproj/argo-workflows/commit/32af692eeec765b13ee3d2b4ede9f5ff45527b4c) added 2.0
 * [802940be](https://github.com/argoproj/argo-workflows/commit/802940be0d4ffd5048dd5307b97af442d82e9a83) added 2.0
 * [1d443415](https://github.com/argoproj/argo-workflows/commit/1d44341553d95ac8192d4a80e178a9d72558829a) added new png

### Contributors

 * Alexander Matyushentsev
 * Ed Lee
 * Jesse Suen
 * Rafal
 * Sandeep Bhojwani
 * Shri Javadekar
 * Wojciech Kalemba
 * cyee88
 * mukulikak

## v2.0.0-alpha1 (2017-11-16)


### Contributors


## v2.0.0 (2018-02-06)

 * [0978b9c6](https://github.com/argoproj/argo-workflows/commit/0978b9c61cb7435d31ef8d252b80e03708a70adc) Support setting UI base Url  (#722)
 * [b75cd98f](https://github.com/argoproj/argo-workflows/commit/b75cd98f6c038481ec3d2253e6404952bcaf4bd5) updated argo-user slack link
 * [b3598d84](https://github.com/argoproj/argo-workflows/commit/b3598d845c4cdb9ac7c4ae5eff5024ecd3fc5fd6) Add examples as functional and expected failure e2e tests
 * [83966e60](https://github.com/argoproj/argo-workflows/commit/83966e6095e2468368b0929613e7371074ee972b) Fix regression where executor did not annotate errors correctly
 * [751fd270](https://github.com/argoproj/argo-workflows/commit/751fd27024d9f3bfc40051d2ca694b25a42307ea) Update UI references to v2.0.0. Update changelog
 * [8b7e2e24](https://github.com/argoproj/argo-workflows/commit/8b7e2e24e8cf7ae6b701f08b0702ac045e0336f8) Check-in the OpenAPI spec. Automate generation as part of `make update-codegen`
 * [563bda75](https://github.com/argoproj/argo-workflows/commit/563bda756732802caeaa516fd0c493c6e07f6cf9) Fix update-openapigen.sh script to presume bash. Tweak documentation
 * [5b9a602b](https://github.com/argoproj/argo-workflows/commit/5b9a602b4a763ac633f7ede86f13253451855462) Add documentation to types. Add program to generate OpenAPI spec
 * [d929e79f](https://github.com/argoproj/argo-workflows/commit/d929e79f623017a923d1c4e120c363e08fe7a64a) Generate OpenAPI models for the workflow spec (issue #707)
 * [1d5afee6](https://github.com/argoproj/argo-workflows/commit/1d5afee6ea48743bb854e69ffa333f361e52e289) Shortened url
 * [617d848d](https://github.com/argoproj/argo-workflows/commit/617d848da27d0035c20f21f3f6bddbe0e04550db) Added news to README
 * [ae36b22b](https://github.com/argoproj/argo-workflows/commit/ae36b22b6d0d0ce8c230aedcce0814489162ae5b) Fix typo s/Customer/Custom/ (#704)
 * [5a589fcd](https://github.com/argoproj/argo-workflows/commit/5a589fcd932116720411d53aeb6454e297456e06) Add ability to specify imagePullSecrets in the workflow.spec (resolves #699)
 * [2f77bc1e](https://github.com/argoproj/argo-workflows/commit/2f77bc1ed00042388d0492cfd480d7c22599112c) Add ability to specify affinity rules at both the workflow and template level (resolves #701)
 * [fdafbe27](https://github.com/argoproj/argo-workflows/commit/fdafbe27e5e2f4f2d58913328ae22db9a6c363b4) Sidecars unable to reference volume claim templates (resolves #697)
 * [0b0b52c3](https://github.com/argoproj/argo-workflows/commit/0b0b52c3b45cbe5ac62da7b26b30d19fc1f9eb3e) Referencing output artifacts from a container with retries was not functioning (resolves #698)
 * [bf2b376a](https://github.com/argoproj/argo-workflows/commit/bf2b376a142ed4fdf70ba4f3702533e7b75fc6b2) Update doc references to point to v2.0.0-beta1. Fix secrets example
 * [549870c1](https://github.com/argoproj/argo-workflows/commit/549870c1ee08138b20b8a4b0c026569cf1e6c19a) Fix argo-ui download links to point to v2.0.0-beta1
 * [a202049d](https://github.com/argoproj/argo-workflows/commit/a202049d327c64e282a37d7598bddc1faa1a3c1a) Update CHANGELOG for v2.0.0-beta1
 * [a3739035](https://github.com/argoproj/argo-workflows/commit/a3739035f8e1f517721489fc53b58a8e27a575e1) Remove dind requirement from argo-ci test steps
 * [1bdd0c03](https://github.com/argoproj/argo-workflows/commit/1bdd0c03dbb9d82ad841ca19be6e1ea93aeb82f7) Include completed pods when attempting to reconcile deleted pods Switch back to Patch (from Update) for persisting workflow changes
 * [a4a43892](https://github.com/argoproj/argo-workflows/commit/a4a4389219cbe84e3bc7b3731cdfccb9ee5f5730) Sleep 1s after persisting workflow to give informer cache a chance to sync (resolves #686)
 * [5bf49531](https://github.com/argoproj/argo-workflows/commit/5bf49531f99ef9d8b8aefeac26a4a3fa0177e70d) Updated demo.md with link to ARTIFACT_REPO.md
 * [863d547a](https://github.com/argoproj/argo-workflows/commit/863d547a1a2a146a898c06c835187e0595af5689) Rely on controller generated timestamps for node.StartedAt instad of pod.CreationTimestamp
 * [672542d1](https://github.com/argoproj/argo-workflows/commit/672542d1f08c206f89f8747e9b14b675cdd77446) Re-apply workflow changes and reattempt update on resource conflicts. Make completed pod labeling asynchronous
 * [81bd6d3d](https://github.com/argoproj/argo-workflows/commit/81bd6d3d46d2fd7ea57aa095ae134116cfca90f2) Resource state retry (#690)
 * [44dba889](https://github.com/argoproj/argo-workflows/commit/44dba889cb743552557fcd7453ee81a89875142d) Tune controller to 20 QPS, 30 Burst, 8 wf workers, 8 pod workers
 * [178b9d37](https://github.com/argoproj/argo-workflows/commit/178b9d37cc452af214df7c9c41522124c117e7a3) Show running/completed pod counts in `argo list -o wide`
 * [0c565f5f](https://github.com/argoproj/argo-workflows/commit/0c565f5f5e9f69244e9828ced7c3916ac605f460) Switch to Updating workflow resources instead of Patching (resolves #686)
 * [a571f592](https://github.com/argoproj/argo-workflows/commit/a571f592fa131771b8d71126fc27809e24462cfe) Ensure sidecars get killed unequivocally. Final argoexec stats were not getting printed
 * [a0b2d78c](https://github.com/argoproj/argo-workflows/commit/a0b2d78c869f277c20c4cd3ba18b8d2688674e54) Show duration by default in `argo get`. --since flag should always include Running
 * [10110313](https://github.com/argoproj/argo-workflows/commit/101103136287b8ee16a7afda94cc6ff59be07ef6) Executor hardening: add retries and memoization for executor k8s API calls Recover from unexpected panics and annotate the error.
 * [f2b8f248](https://github.com/argoproj/argo-workflows/commit/f2b8f248ab8d483e0ba41a287611393500c7b507) Regenerate deepcopy code after type changes for raw input artifacts
 * [322e0e3a](https://github.com/argoproj/argo-workflows/commit/322e0e3aa3cb2e650f3ad4b7ff9157f71a92e8b4) renamed file as per review comment
 * [0a386cca](https://github.com/argoproj/argo-workflows/commit/0a386ccaf705a1abe1f9239adc966fceb7a808ae) changes from the review - renamed "contents" to "data" - lint issue
 * [d9ebbdc1](https://github.com/argoproj/argo-workflows/commit/d9ebbdc1b31721c8095d3c5426c1c811054a94a7) support for raw input as artifact
 * [a1f821d5](https://github.com/argoproj/argo-workflows/commit/a1f821d589d47ca5b12b94ad09306a706a43d150) Introduce communication channel from workflow-controller to executor through pod annotations
 * [b324f9f5](https://github.com/argoproj/argo-workflows/commit/b324f9f52109b9aa29bc89d63810be6e421eb54f) Artifactory repository was not using correct casing for repoURL field
 * [3d45d25a](https://github.com/argoproj/argo-workflows/commit/3d45d25ac497a09fa291d20f867a75f59b6abf92) Add `argo list --since` to filter workflows newer than a relative duration
 * [cc2efdec](https://github.com/argoproj/argo-workflows/commit/cc2efdec368c2f133c076a9eda9065f64762a9fa) Add ability to set loglevel of controller via CLI flag
 * [60c124e5](https://github.com/argoproj/argo-workflows/commit/60c124e5dddb6ebfee6300d36f6a3877838ec17c) Remove hack.go and use dep to install code-generators
 * [d14755a7](https://github.com/argoproj/argo-workflows/commit/d14755a7c5f583c1f3c8c762ae8628e780f566cf) `argo list` was not handling the default case correctly
 * [472f5604](https://github.com/argoproj/argo-workflows/commit/472f5604e27ca6310e016f846c97fda5d7bca9dd) Improvements to `argo list` * sort workflows by running vs. completed, then by finished time * add --running, --completed, --status XXX filters * add -o wide option to show parameters and -o name to show only the names
 * [b063f938](https://github.com/argoproj/argo-workflows/commit/b063f938f34f650333df6ec5a2e6a325a5b45299) Use minimal ClusterRoles for workflow-controller and argo-ui deployments
 * [21bc2bd0](https://github.com/argoproj/argo-workflows/commit/21bc2bd07ebbfb478c87032e2ece9939ea436030) Added link to configuring artifact repo from main README
 * [b54bc067](https://github.com/argoproj/argo-workflows/commit/b54bc067bda02f95937774fb3345dc2010d3efc6) Added link to configuring artifact repo from main README
 * [58ec5169](https://github.com/argoproj/argo-workflows/commit/58ec51699534e73d82c3f44027326b438cf5c063) Updated ARTIFACT_REPO.md
 * [1057d087](https://github.com/argoproj/argo-workflows/commit/1057d087838bcbdbffc70367e0fc02778907c9af) Added detailed instructions on configuring AWS and GCP artifact rpos
 * [b0a7f0da](https://github.com/argoproj/argo-workflows/commit/b0a7f0da85fabad34814ab129eaba43862a1d2dd) Issue 680 - Argo UI is failing to render workflow which has not been picked up by workflow controller (#681)
 * [e91c227a](https://github.com/argoproj/argo-workflows/commit/e91c227acc1f86b7e341aaac534930f9b529cd89) Document and clarify artifact passing (#676)
 * [290f6799](https://github.com/argoproj/argo-workflows/commit/290f6799752ef602b27c193212495e27f40dd687) Allow containers to be retried. (#661)
 * [80f9b1b6](https://github.com/argoproj/argo-workflows/commit/80f9b1b636704ebad6ebb8df97c5e81dc4f815f9) Improve the error message when insufficent RBAC privileges is detected (resolves #659)
 * [3cf67df4](https://github.com/argoproj/argo-workflows/commit/3cf67df422f34257296d2de09d2ca3c8c87abf84) Regenerate autogenerated code after changes to types
 * [baf37052](https://github.com/argoproj/argo-workflows/commit/baf37052976458401a6c0e44d06f30dc8d819680) Add support for resource template outputs. Remove output.parameters.path in favor of valueFrom
 * [dc1256c2](https://github.com/argoproj/argo-workflows/commit/dc1256c2034f0add4bef3f82ce1a71b454d4eef5) Fix expected file name for issue template
 * [a492ad14](https://github.com/argoproj/argo-workflows/commit/a492ad14177eb43cdd6c2a017c9aec87183682ed) Add a GitHub issues template
 * [55be93a6](https://github.com/argoproj/argo-workflows/commit/55be93a68d8991f76a31adaf49f711436a35a9d0) Add a --dry-run option to `argo install`. Remove CRD creation from controller startup
 * [fddc052d](https://github.com/argoproj/argo-workflows/commit/fddc052df8a3478aede67057f2b06938c2a6a7a4) Fix README.md to contain influxdb-client in the example (#669)
 * [67236a59](https://github.com/argoproj/argo-workflows/commit/67236a5940231f7b9dc2ca2f4cb4cb70b7c18d45) Update getting started doc to use `brew install` and better instructions for RBAC clusters (resolves #654, #530)
 * [5ac19753](https://github.com/argoproj/argo-workflows/commit/5ac19753846566d0069b76e3e6c6dd03f0e6950c) Support rendering retry steps (#670)
 * [3cca0984](https://github.com/argoproj/argo-workflows/commit/3cca0984c169ea59e8e2758a04550320b1981875) OpenID Connect auth support (#663)
 * [c222cb53](https://github.com/argoproj/argo-workflows/commit/c222cb53a168f9bd40b7731d0b2f70db977990c2) Clarify where the Minio secret comes from.
 * [a78e2e8d](https://github.com/argoproj/argo-workflows/commit/a78e2e8d551d6afad2e0fbce7a9f0a1bd023c11b) Remove parallel steps that use volumes.
 * [35517385](https://github.com/argoproj/argo-workflows/commit/355173857f98a9a9704ab23235b3186bde8092b9) Prevent a potential k8s scheduler panic from incomplete setting of pod ownership reference (resolves #656)
 * [1a8bc26d](https://github.com/argoproj/argo-workflows/commit/1a8bc26d40597f2f0475aa9197a6b3912c5bbb56) Updated README
 * [9721fca0](https://github.com/argoproj/argo-workflows/commit/9721fca0e1ae9d1d57aa8d1872450ce8ee7487e2) Updated README
 * [e3177606](https://github.com/argoproj/argo-workflows/commit/e3177606105a936da7eba29924fa49ad497703c9) Fix typos in READMEs
 * [555d50b0](https://github.com/argoproj/argo-workflows/commit/555d50b0ebeef1c753394de974dad2e0d4a5b787) Simplify some getting started instructions. Correct some usages of container resources field
 * [4abc9c40](https://github.com/argoproj/argo-workflows/commit/4abc9c40e7656a5783620e41b33e4ed3bb7249e2) Updated READMEs
 * [a0add24f](https://github.com/argoproj/argo-workflows/commit/a0add24f9778789473b2b097fb31a56ae11bfce9) Switch to k8s-codegen generated workflow client and informer
 * [9b08b6e9](https://github.com/argoproj/argo-workflows/commit/9b08b6e997633d5f2e94392f000079cbe93ee023) Added link for argoproj slack channel
 * [682bbdc0](https://github.com/argoproj/argo-workflows/commit/682bbdc09b66698090d309e91b5caf4483931e34) Update references to point to latest argo release
 * [940dd56d](https://github.com/argoproj/argo-workflows/commit/940dd56d98c75eb93da3b5de598882754cb74fc7) Fix artifactory unit test and linting issues
 * [e7ba2b44](https://github.com/argoproj/argo-workflows/commit/e7ba2b44114fca8a3cb2b8635dc2fdfeaa440d9e) Update help page links (#651)
 * [53dac4c7](https://github.com/argoproj/argo-workflows/commit/53dac4c74933c333124a0cb1d8cf6c9255f9199d) Add artifactory and UI fixes to 2.0.0-alpha3 CHANGELOG
 * [4b4eff43](https://github.com/argoproj/argo-workflows/commit/4b4eff43f20ed678d34efe567a4d61d1364d7124) Allow disabling web console feature (#649)
 * [90b7f2e6](https://github.com/argoproj/argo-workflows/commit/90b7f2e67dddebba1678e215bde75d68867b4469) Added support for artifactory
 * [849e916e](https://github.com/argoproj/argo-workflows/commit/849e916e5bf98f320f1a65b12ffe246d9ebbb6f6) Adjusted styles for logs stream (#614)
 * [a8a96030](https://github.com/argoproj/argo-workflows/commit/a8a960303423cde2e511d4af9c2c8ae834076b21) Update CHANGELOG for 2.0.0-alpha3
 * [e7c7678c](https://github.com/argoproj/argo-workflows/commit/e7c7678cc605285e5b3224c757e5e4be57ab4d5c) Fix issue preventing ability to pass JSON as a command line param (resolves #646)
 * [7f5e2b96](https://github.com/argoproj/argo-workflows/commit/7f5e2b96bd96e0bccf4778383aa9b94a1768e9c0) Add validation checks for volumeMount/artifact path collision and activeDeadlineSeconds (#620)
 * [dc4a9463](https://github.com/argoproj/argo-workflows/commit/dc4a94633c4d00d78a7ea53272e425962de405ba) Add the ability to specify the service account used by pods in the workflow (resolves #634) Also add argo CLI support for supplying/overriding spec.serviceAccountName from command line.
 * [16f7000a](https://github.com/argoproj/argo-workflows/commit/16f7000aa77b2759fa0a65d6e42456bcb660f824) Workflow operator will recover from unexpected panics and mark the workflow with error (resolves #633)
 * [18dca7fe](https://github.com/argoproj/argo-workflows/commit/18dca7fe21d57e6a5415c53bfdb87a889ac32456) Issue #629 - Add namespace to workflow list and workflow details page (#639)
 * [e656bace](https://github.com/argoproj/argo-workflows/commit/e656bace75aaa859f04121f2c1d95631b462fe62) Issue #637 -  Implement Workflow list and workflow details page live update (#638)
 * [1503ce3a](https://github.com/argoproj/argo-workflows/commit/1503ce3aee40eba741819a1403847df4bbcb7b23) Issue #636 - Upgrade to ui-lib 2.0.3 to fix xterm incompatibility (#642)
 * [f9170e8a](https://github.com/argoproj/argo-workflows/commit/f9170e8abb7121b0d0cbc3e4c07b9bdc2224fb76) Remove manifest-passing.yaml example now that we have resource templates
 * [25be5fd6](https://github.com/argoproj/argo-workflows/commit/25be5fd6368bac3fde8e4392b3cb9d4159983a1a) Implementation for resource templates and resource success/failure conditions
 * [402ad565](https://github.com/argoproj/argo-workflows/commit/402ad565f4a3b95c449ddd4c6dc468947aeb7192) Updated examples/README
 * [8536c7fc](https://github.com/argoproj/argo-workflows/commit/8536c7fc89a0ceb39208efe2076919d0390e3d2e) added secret example to examples/README
 * [e5002b82](https://github.com/argoproj/argo-workflows/commit/e5002b8286af2c1f7ec64953114e1d97c889ca37) Add '--wait' to argo submit.
 * [9646e55f](https://github.com/argoproj/argo-workflows/commit/9646e55f8bb8fbac80d456853aa891c2ae069adb) Installer was not update configmap correctly with new executor image during upgrade
 * [69d72913](https://github.com/argoproj/argo-workflows/commit/69d72913a3a72bbf7b075be847303305b4bef1a5) Support private git repos using secret selector fields in the git artifact (resolves #626)
 * [64e17244](https://github.com/argoproj/argo-workflows/commit/64e17244ef04b9d2aa6abf6f18d4e7ef2d20ff37) Add argo ci workflow (#619)
 * [e8998435](https://github.com/argoproj/argo-workflows/commit/e8998435598e8239d7b77a60cfda43e8f2869b4d) Resolve controller panic when a script template with an input artifact was submitted (resolves #617). Utilize the kubernetes.Interface and fake.Clientset to support unit test mocking. Added a unit test to reproduce the panic. Add an e2e test to verify functionality works.
 * [52075b45](https://github.com/argoproj/argo-workflows/commit/52075b45611783d909609433bb44702888b5db37) Introduce controller instance IDs to support multiple workflow controllers in a cluster (resolves #508)
 * [133a23ce](https://github.com/argoproj/argo-workflows/commit/133a23ce20b4570ded81fac76a430f0399c1eea1) Add ability to timeout a container/script using activeDeadlineSeconds
 * [b5b16e55](https://github.com/argoproj/argo-workflows/commit/b5b16e55260df018cc4de14bf298ce59714b4396) Support for workflow exit handlers
 * [906b3e7c](https://github.com/argoproj/argo-workflows/commit/906b3e7c7cac191f920016362b076a28f18d97c1) Update ROADMAP.md
 * [5047422a](https://github.com/argoproj/argo-workflows/commit/5047422ae71869672c84364d099e1488b29fbbe8) Update CHANGELOG.md
 * [2b6583df](https://github.com/argoproj/argo-workflows/commit/2b6583dfb02911965183ef4b25ed68c867448e10) Add `argo wait` for waiting on workflows to complete. (#618)
 * [cfc9801c](https://github.com/argoproj/argo-workflows/commit/cfc9801c40528b6605823e1f4b4359600b6887df) Add option to print output of submit in json.
 * [c20c0f99](https://github.com/argoproj/argo-workflows/commit/c20c0f9958ceeefd3597120fcb4013d857276076) Comply with semantic versioning. Include build metadata in `argo version` (resolves #594)
 * [bb5ac7db](https://github.com/argoproj/argo-workflows/commit/bb5ac7db52bff613c32b153b82953ec9c73c3b8a) minor change
 * [91845d49](https://github.com/argoproj/argo-workflows/commit/91845d4990ff8fd97bd9404e4b37024be1ee0ba6) Added more documentation
 * [4e8d69f6](https://github.com/argoproj/argo-workflows/commit/4e8d69f630bc0fd107b360ee9ad953ccb0b78f11) fixed install instructions
 * [0557147d](https://github.com/argoproj/argo-workflows/commit/0557147dd4bfeb2688b969293ae858a8391d78ad) Removed empty toolbar (#600)
 * [bb2b29ff](https://github.com/argoproj/argo-workflows/commit/bb2b29ff5e4178e2c8a9dfe666b699d75aa9ab3b) Added limit for number of steps in workflows list (#602)
 * [3f57cc1d](https://github.com/argoproj/argo-workflows/commit/3f57cc1d2ff9c0e7ec40da325c3478a8037a6ac0) fixed typo in examples/README
 * [ebba6031](https://github.com/argoproj/argo-workflows/commit/ebba6031192b0a763bd94b1625a2ff6e242f112e) Updated examples/README.md with how to override entrypoint and parameters
 * [81834db3](https://github.com/argoproj/argo-workflows/commit/81834db3c0bd12758a95e8a5862d6dda6d0dceeb) Example with using an emptyDir volume.
 * [4cd949d3](https://github.com/argoproj/argo-workflows/commit/4cd949d327ddb9d4f4592811c51e07bb53b30ef9) Remove apiserver
 * [6a916ca4](https://github.com/argoproj/argo-workflows/commit/6a916ca447147e4aff364ce032c9db4530d49d11) `argo lint` did not split yaml files. `argo submit` was not ignoring non-workflow manifests
 * [bf7d9979](https://github.com/argoproj/argo-workflows/commit/bf7d997970e967b2b238ce209ce823ea47de01d2) Include `make lint` and `make test` as part of CI
 * [d1639ecf](https://github.com/argoproj/argo-workflows/commit/d1639ecfabf73f73ebe040b832668bd6a7b60d20) Create example workflow using kubernetes secrets (resolves #592)
 * [31c54af4](https://github.com/argoproj/argo-workflows/commit/31c54af4ba4cb2a0db918fadf62cb0b854592ba5) Toolbar and filters on workflows list (#565)
 * [bb4520a6](https://github.com/argoproj/argo-workflows/commit/bb4520a6f65d4e8e765ce4d426befa583721c194) Add and improve the inlined comments in example YAMLs
 * [a0470728](https://github.com/argoproj/argo-workflows/commit/a04707282cdeadf463b22b633fc00dba432f60bf) Fixed typo.
 * [13366e32](https://github.com/argoproj/argo-workflows/commit/13366e32467a34a061435091589c90d04a84facb) Fix some wrong GOPATH assumptions in Makefile. Add `make test` target. Fix unit tests
 * [9f4f1ee7](https://github.com/argoproj/argo-workflows/commit/9f4f1ee75705150a22dc68a3dd16fa90069219ed) Add 'misspell' to linters. Fix misspellings caught by linter
 * [1b918aff](https://github.com/argoproj/argo-workflows/commit/1b918aff29ff8e592247d14c52be06a0537f0734) Address all issues in code caught by golang linting tools (resolves #584)
 * [903326d9](https://github.com/argoproj/argo-workflows/commit/903326d9103fa7dcab37835a9478f58aff51a5d1) Add manifest passing to do kubectl create with dynamic manifests (#588)
 * [b1ec3a3f](https://github.com/argoproj/argo-workflows/commit/b1ec3a3fc90a211f9afdb9090d4396c98ab3f71f) Create the argo-ui service with type ClusterIP as part of installation (resolves #582)
 * [5b6271bc](https://github.com/argoproj/argo-workflows/commit/5b6271bc56b46a82b0ee2bc0784315ffcddeb27f) Add validate names for various workflow specific fields and tests for them (#586)
 * [b6e67131](https://github.com/argoproj/argo-workflows/commit/b6e671318a446f129740ce790f53425d65e436f3) Implementation for allowing access to global parameters in workflow (#571)
 * [c5ac5bfb](https://github.com/argoproj/argo-workflows/commit/c5ac5bfb89274fb5ee85f9cef346b7059b5d7641) Fix error message when key does not exist in secret (resolves #574). Improve s3 example and documentation.
 * [4825c43b](https://github.com/argoproj/argo-workflows/commit/4825c43b3e0c3c54b2313aa54e69520ed1b8a38d) Increate UI build memory limit (#580)
 * [87a20c6b](https://github.com/argoproj/argo-workflows/commit/87a20c6bce9a6bfe2a88edc581746ff5f7f006fc) Update input-artifacts-s3.yaml example to explain concepts and usage better
 * [c16a9c87](https://github.com/argoproj/argo-workflows/commit/c16a9c87102fd5b66406737720204e5f17af0fd1) Rahuldhide patch 2 (#579)
 * [f5d0e340](https://github.com/argoproj/argo-workflows/commit/f5d0e340b3626658b435dd2ddd937e97af7676b2) Issue #549 - Prepare argo v1 build config (#575)
 * [3b3a4c87](https://github.com/argoproj/argo-workflows/commit/3b3a4c87bd3138961c948f869e2c5b7c932c8847) Argo logo
 * [d1967443](https://github.com/argoproj/argo-workflows/commit/d1967443a4943f685f6cb1649480765050bdcdaa) Skip e2e tests if Kubeconfig is not provided.
 * [1ec231b6](https://github.com/argoproj/argo-workflows/commit/1ec231b69a1a7d985d1d587980c34588019b04aa) Create separate namespaces for tests.
 * [5ea20d7e](https://github.com/argoproj/argo-workflows/commit/5ea20d7eb5b9193c19f7c875c8fb2f4af8f68ef3) Add a deadline for workflow operation to prevent workqueue starvation and to enable state resync (#531) Tested with 6 x 1000 pod workflows.
 * [346bafe6](https://github.com/argoproj/argo-workflows/commit/346bafe636281bca94695b285767f41ae71e6a69) Multiple scalability improvements to controller (resolves #531)
 * [bbc56b59](https://github.com/argoproj/argo-workflows/commit/bbc56b59e2ff9635244bcb091e92e257a508d147) Improve argo ui build performance and reduce image size (#572)
 * [cdb1ce82](https://github.com/argoproj/argo-workflows/commit/cdb1ce82bce9b103e433981d94bd911b0769350d) Upgrade ui-lib (#556)
 * [0605ad7b](https://github.com/argoproj/argo-workflows/commit/0605ad7b33fc4f9c0bbff79adf1d509d3b072703) Adjusted tabs content size to see horizontal and vertical scrolls. (#569)
 * [a3316236](https://github.com/argoproj/argo-workflows/commit/a331623697e76a5e3497257e28fabe1995852339) Fix rendering 'Error' node status (#564)
 * [8c3a7a93](https://github.com/argoproj/argo-workflows/commit/8c3a7a9393d619951a676324810d482d28dfe015) Issue #548  - UI terminal window  (#563)
 * [5ec6cc85](https://github.com/argoproj/argo-workflows/commit/5ec6cc85aab63ea2277ce621d5de5b59a510d462) Implement API to ssh into pod (#561)
 * [beeb65dd](https://github.com/argoproj/argo-workflows/commit/beeb65ddcb7d2b5f8286f7881af1f5c00535161e) Don't mess the controller's arguments.
 * [01f5db5a](https://github.com/argoproj/argo-workflows/commit/01f5db5a0c3dc48541577b9d8b1d815399728070) Parameterize Install() and related methods.
 * [85a2e271](https://github.com/argoproj/argo-workflows/commit/85a2e2711beba8f2c891af396a3cc886c7b37542) Fix tests.
 * [56f666e1](https://github.com/argoproj/argo-workflows/commit/56f666e1bf69a7f5d8191637e8c7f384b91d98d0) Basic E2e tests.
 * [9eafb9dd](https://github.com/argoproj/argo-workflows/commit/9eafb9dd59166e76804b71c8df19fdca453cdd28) Issue #547 - Support filtering by status in API GET /workflows (#550)
 * [37f41eb7](https://github.com/argoproj/argo-workflows/commit/37f41eb7bf366cfe007d3ecce7b21f003d381e34) Update demo.md
 * [ea8d5c11](https://github.com/argoproj/argo-workflows/commit/ea8d5c113d9245f47fe7b3d3f45e7891aa5f50e8) Update README.md
 * [373f0710](https://github.com/argoproj/argo-workflows/commit/373f07106ab14e3772c94af5cc11f7f1c7099204) Add support for making a no_ui build. Base all build on no_ui build (#553)
 * [ae65c57e](https://github.com/argoproj/argo-workflows/commit/ae65c57e55f92fd8ff1edd099f659e9e97ce59f1) Update demo.md
 * [f6f8334b](https://github.com/argoproj/argo-workflows/commit/f6f8334b2b3ed1f498c19e4de25421f41807f893) V2 style adjustments and small fixes (#544)
 * [12d5b7ca](https://github.com/argoproj/argo-workflows/commit/12d5b7ca48c913e53b74708a35727d523dfa5355) Document argo ui service creation (#545)
 * [3202d4fa](https://github.com/argoproj/argo-workflows/commit/3202d4fac2d5d2d2a3ad1d679c1b753b04aca796) Support all namespaces (#543)
 * [b553c1bd](https://github.com/argoproj/argo-workflows/commit/b553c1bd9a00499915dbe5926194d67c7392b944) Update demo.md to qualify the minio endpoint with the default namespace
 * [4df7617c](https://github.com/argoproj/argo-workflows/commit/4df7617c2e97f2336195d6764259537be648b89b) Fix artifacts downloading (#541)
 * [12732200](https://github.com/argoproj/argo-workflows/commit/12732200fb1ed95608cdc0b14bd0802c524c7fa2) Update demo.md with references to latest release
 * [0e67b861](https://github.com/argoproj/argo-workflows/commit/0e67b8616444cf637d5b68e58eb6e068b721d34c) Add 'release' make target. Improve CLI help and set version from git tag. Uninstaller for UI
 * [8ab1d2e9](https://github.com/argoproj/argo-workflows/commit/8ab1d2e93ff969a1a01a06dcc3ac4aa04d3514aa) Install argo ui along with argo workflow controller (#540)
 * [f4af881e](https://github.com/argoproj/argo-workflows/commit/f4af881e55cff12888867bca9dff940c1bb16c26) Add make command to build argo ui (#539)
 * [5bb85814](https://github.com/argoproj/argo-workflows/commit/5bb858145e1c603494d8202927197d38b121311a) Add example description in YAML.
 * [fc23fcda](https://github.com/argoproj/argo-workflows/commit/fc23fcdaebc9049748d57ab178517d18eed4af7d) edit example README
 * [8dd294aa](https://github.com/argoproj/argo-workflows/commit/8dd294aa003ee1ffaa70cd7735b7d62c069eeb0f) Add example of GIF processing using ImageMagick
 * [ef8e9d5c](https://github.com/argoproj/argo-workflows/commit/ef8e9d5c234b1f889c4a2accbc9f24d58ce553b9) Implement loader (#537)
 * [2ac37361](https://github.com/argoproj/argo-workflows/commit/2ac37361e6620b37af09cd3e50ecc0fb3fb62a12) Allow specifying CRD version (#536)
 * [15b5542d](https://github.com/argoproj/argo-workflows/commit/15b5542d7cff2b0812830b16bcc5ae490ecc7302) Installer was not using the argo serviceaccount with the workflow-controller deployment. Make progress messages consistent
 * [f1471347](https://github.com/argoproj/argo-workflows/commit/f1471347d96838e0e13e47d0bc7fc04b3018d6f7) Add Yaml viewer (#535)
 * [685a576b](https://github.com/argoproj/argo-workflows/commit/685a576bd28bb269d727a10bf617bd1b08ea4ff0) Fix Gopkg.lock file following rewrite of git history at github.com/minio/go-homedir
 * [01ab3076](https://github.com/argoproj/argo-workflows/commit/01ab3076fe68ef62a9e3cc89b0e367cbdb64ff37) Delete clusterRoleBinding and serviceAccount.
 * [7bb99ae7](https://github.com/argoproj/argo-workflows/commit/7bb99ae713da51c9b9818027066f7ddd8efb92bb) Rename references from v1 to v1alpha1 in YAML
 * [32343913](https://github.com/argoproj/argo-workflows/commit/3234391356ae0eaf88d348b564828c2df754a49e) Implement step artifacts tab (#534)
 * [b2a58dad](https://github.com/argoproj/argo-workflows/commit/b2a58dad98942ad06b0431968be00ebe588818ff) Workflow list (#533)
 * [5dd1754b](https://github.com/argoproj/argo-workflows/commit/5dd1754b4a41c7951829dbbd8e70a244cf627331) Guard controller from informer sending non workflow/pod objects (#505)
 * [59e31c60](https://github.com/argoproj/argo-workflows/commit/59e31c60f8675c2c678c50e9694ee993691b6e6a) Enable resync period in workflow/pod informers (resolves #532)
 * [d5b06dcd](https://github.com/argoproj/argo-workflows/commit/d5b06dcd4e52270a24f4f3b19497b9a9afaed4e9) Significantly increase efficiency of workflow control loop (resolves #505)
 * [4b2098ee](https://github.com/argoproj/argo-workflows/commit/4b2098ee271301eca52403e769f82f6d717400af) finished walkthrough sections
 * [eb7292b0](https://github.com/argoproj/argo-workflows/commit/eb7292b02414ef6faca4f424f6b04ea444abb0e0) walkthrough
 * [82b1c7d9](https://github.com/argoproj/argo-workflows/commit/82b1c7d97536baac7514d7cfe72d1be9309bef43) Add -o wide option to `argo get` to display artifacts and durations (resolves #526)
 * [3427955d](https://github.com/argoproj/argo-workflows/commit/3427955d35bf6babc0bfee958a2eb417553ed203) Use PATCH api from k8s go SDK for annotating/labeling pods
 * [4842bbbc](https://github.com/argoproj/argo-workflows/commit/4842bbbc7e40340de12c788cc770eaa811431818) Add support for nodeSelector at both the workflow and step level (resolves #458)
 * [424fba5d](https://github.com/argoproj/argo-workflows/commit/424fba5d4c26c448c8c8131b89113c4c5fbae08d) Rename apiVersion of workflows from v1 to v1alpha1 (resolves #517)
 * [5286728a](https://github.com/argoproj/argo-workflows/commit/5286728a98236c5a8883850389d286d67549966e) Propogate executor errors back to controller. Add error column in `argo get` (#522)
 * [32b5e99b](https://github.com/argoproj/argo-workflows/commit/32b5e99bb194e27a8a35d1d7e1378dd749cc546f) Simplify executor commands to just 'init' and 'wait'. Improve volumes examples
 * [e2bfbc12](https://github.com/argoproj/argo-workflows/commit/e2bfbc127d03f5ef20763fe8a917c82e3f06638d) Update controller config automatically on configmap updates resolves #461
 * [c09b13f2](https://github.com/argoproj/argo-workflows/commit/c09b13f21eaec4bb78c040134a728d8e021b4d1e) Workflow validation detects when arguments were not supplied (#515)
 * [705193d0](https://github.com/argoproj/argo-workflows/commit/705193d053cb8c0c799a0f636fc899e8b7f55bcc) Proper message for non-zero exits from main container. Indicate an Error phase/message when failing to load/save artifacts
 * [e69b7510](https://github.com/argoproj/argo-workflows/commit/e69b7510196daba3a87dca0c8a9677abd8d74675) Update page title and favicon (#519)
 * [4330232f](https://github.com/argoproj/argo-workflows/commit/4330232f51d404a7546cf24b4b0eb608bf3113f5) Render workflow steps on workflow list page (#518)
 * [87c447ea](https://github.com/argoproj/argo-workflows/commit/87c447eaf2ca2230e9b24d6af38f3a0fd3c520c3) Implement kube api proxy. Add workflow node logs tab (#511)
 * [0ab26883](https://github.com/argoproj/argo-workflows/commit/0ab268837cff2a1fd464673a45c3736178917be5) Rework/rename Makefile targets. Bake in image namespace/tag set during build, as part of argo install
 * [3f13f5ca](https://github.com/argoproj/argo-workflows/commit/3f13f5cabe9dc54c7fbaddf7b0cfbcf91c3f26a7) Support for overriding/supplying entrypoint and parameters via argo CLI. Update examples
 * [6f9f2adc](https://github.com/argoproj/argo-workflows/commit/6f9f2adcd017954a72b2b867e6bc2bcba18972af) Support ListOptions in the WorkflowClient. Add flag to delete completed workflows
 * [30d7fba1](https://github.com/argoproj/argo-workflows/commit/30d7fba1205e7f0b4318d6b03064ee647d16ce59) Check Kubernetes version.
 * [a3909273](https://github.com/argoproj/argo-workflows/commit/a3909273c435b23de865089b82b712e4d670a4ff) Give proper error for unamed steps
 * [eed54f57](https://github.com/argoproj/argo-workflows/commit/eed54f5732a61922f6daff9e35073b33c1dc068e) Harden the IsURL check
 * [bfa62afd](https://github.com/argoproj/argo-workflows/commit/bfa62afd857704c53aef32f5ade7df86cf2c0769) Add phase,completed fields to workflow labels. Add startedAt,finishedAt,phase,message to workflow.status
 * [9347619c](https://github.com/argoproj/argo-workflows/commit/9347619c7c125950a9f17acfbd92a1286bca1a57) Create serviceAccount & roleBinding if necessary.
 * [205e5cbc](https://github.com/argoproj/argo-workflows/commit/205e5cbce20a6e5e73c977f1e775671a19bf4434) Introduce 'completed' pod label and label selector so controller can ignore completed pods
 * [199dbcbf](https://github.com/argoproj/argo-workflows/commit/199dbcbf1c3fa2fd452e5c36035d0f0ae8cdde42) 476 jobs list page (#501)
 * [05879294](https://github.com/argoproj/argo-workflows/commit/0587929453ac10d7318a91f2243aece08fe84129) Implement workflow tree tab draft (#494)
 * [a2f034a0](https://github.com/argoproj/argo-workflows/commit/a2f034a063b30b0bb5d9e0f670a8bb38560880b4) Proper error reporting. Add message, startedAt, finishedAt to NodeStatus. Rename status to phase
 * [645fedca](https://github.com/argoproj/argo-workflows/commit/645fedcaf532e052ef0bfc64cb56bfb3307479dd) Support loop step expansion from input parameters and previous step results
 * [75c1c482](https://github.com/argoproj/argo-workflows/commit/75c1c4822b4037176aa6d3702a5cf4eee590c7b7) Help page v2 (#492)
 * [a4af6702](https://github.com/argoproj/argo-workflows/commit/a4af6702d526e775c0aa31ee3612328e5d058c2b) Basic state of  navigation, top-bar, tooltip for UI v2 (#491)
 * [726e9fa0](https://github.com/argoproj/argo-workflows/commit/726e9fa0953fe91eb0401727743a04c8a02668ef) moved the service acct note
 * [3a4cd9c4](https://github.com/argoproj/argo-workflows/commit/3a4cd9c4ba46f586a3d26fbe017d4d3002e6b671) 477 job details page (#488)
 * [8ba7b55c](https://github.com/argoproj/argo-workflows/commit/8ba7b55cb59173ff7470be3451cd38333539b182) Edited the instructions
 * [1e9dbdba](https://github.com/argoproj/argo-workflows/commit/1e9dbdbabbe354f9798162854dd7d6ae4aa8539a) Added influxdb-ci example
 * [bd5c0baa](https://github.com/argoproj/argo-workflows/commit/bd5c0baad83328f13f25ba59e15a5f607d2fb9eb) Added comment for entrypoint field
 * [2fbecdf0](https://github.com/argoproj/argo-workflows/commit/2fbecdf0484a9e3c0d9242bdd7286f83b6e771eb) Argo V2 UI initial commit (#474)
 * [da4ef06e](https://github.com/argoproj/argo-workflows/commit/da4ef06e14c55a3ffc80bcdbd1b637a984f2f0f9) added artifact to ci example
 * [9ce20123](https://github.com/argoproj/argo-workflows/commit/9ce2012303aa30623336f0dde72ad9b80a5409e3) added artifacts
 * [caaa32a6](https://github.com/argoproj/argo-workflows/commit/caaa32a6b3c28c4f5a43514799b26528b55197ee) Minor edit
 * [ae72b583](https://github.com/argoproj/argo-workflows/commit/ae72b583852e43f616d4c021a4e5646235d4c0b4) added more argo/kubectl examples
 * [1db21612](https://github.com/argoproj/argo-workflows/commit/1db21612695a0a9170e265232acc19936b0d7294) merged
 * [8df393ed](https://github.com/argoproj/argo-workflows/commit/8df393ed78d1e4353ee30ba02cec0b12daea7eb0) added 2.0
 * [9e3a51b1](https://github.com/argoproj/argo-workflows/commit/9e3a51b14d78c3622543429a500a7d0367b10787) Update demo.md to have better instructions to restart controller after configuration changes
 * [ba9f9277](https://github.com/argoproj/argo-workflows/commit/ba9f9277a4a9a153a6f5b19862a73364f618e5cd) Add demo markdown file. Delete old demo.txt
 * [d8de40bb](https://github.com/argoproj/argo-workflows/commit/d8de40bb14167f30b17de81d6162d633a62e7a0d) added 2.0
 * [6c617599](https://github.com/argoproj/argo-workflows/commit/6c617599bf4c91ccd3355068967824c1e8d7c107) added 2.0
 * [32af692e](https://github.com/argoproj/argo-workflows/commit/32af692eeec765b13ee3d2b4ede9f5ff45527b4c) added 2.0
 * [802940be](https://github.com/argoproj/argo-workflows/commit/802940be0d4ffd5048dd5307b97af442d82e9a83) added 2.0
 * [1d443415](https://github.com/argoproj/argo-workflows/commit/1d44341553d95ac8192d4a80e178a9d72558829a) added new png
 * [1069af4f](https://github.com/argoproj/argo-workflows/commit/1069af4f3f12bae0e7c33e557ef479203d4adb7c) Support submission of manifests via URL
 * [cc1f0caf](https://github.com/argoproj/argo-workflows/commit/cc1f0caf72bb5e10b7ea087294bf48d0c1215c47) Add recursive coinflip example
 * [90f37ad6](https://github.com/argoproj/argo-workflows/commit/90f37ad63f37500a7b661960ccb8367866054c51) Support configuration of the controller to match specified labels
 * [f9c9673a](https://github.com/argoproj/argo-workflows/commit/f9c9673ac8f7dd84eb249e02358ad13ab0a9849f) Filter non-workflow related pods in the controller's pod watch
 * [9555a472](https://github.com/argoproj/argo-workflows/commit/9555a472ba76d63ed4862c1ef2bb78dbc0d1cac3) Add install notes to support cluster with legacy authentication disabled. Add option to specify service account
 * [837e0a2b](https://github.com/argoproj/argo-workflows/commit/837e0a2b5e254218774579a1a9acfdba8af4aad2) Propogate deletion of controller replicaset/pod during uninstall
 * [5a7fcec0](https://github.com/argoproj/argo-workflows/commit/5a7fcec08b86c8c618c5006a2299aa2d75441fab) Add parameter passing example yaml
 * [2a34709d](https://github.com/argoproj/argo-workflows/commit/2a34709da544c77587438b22f41abd14b3fe004a) Passthrough --namespace flag to `kubectl logs`
 * [3fc6af00](https://github.com/argoproj/argo-workflows/commit/3fc6af0046291e9020db496d072d4d702c02550a) Adding passing parameter example yaml
 * [e275bd5a](https://github.com/argoproj/argo-workflows/commit/e275bd5ac52872f5a940085759683c073fcfa021) Add support for output as parameter
 * [5ee1819c](https://github.com/argoproj/argo-workflows/commit/5ee1819c78e65a2686dbc9fc4d66622cfcbdad9c) Restore and formalize sidecar kill functionality as part of executor
 * [dec97891](https://github.com/argoproj/argo-workflows/commit/dec9789115c0b659c3a838ba1d75ea6ee4dfa350) Proper workflow manifest validation during `argo lint` and `argo submit`
 * [6ab0b610](https://github.com/argoproj/argo-workflows/commit/6ab0b610170ae370bde53c62c38a7e6f707c09eb) Uninstall support via `argo uninstall`
 * [3ba84082](https://github.com/argoproj/argo-workflows/commit/3ba84082a80a55abff9bfcd9a29e5444c89eab61) Adding sidecar container
 * [dba29bd9](https://github.com/argoproj/argo-workflows/commit/dba29bd9dec34aa779d53b68206f4cf414c916bc) Support GCP
 * [f3049105](https://github.com/argoproj/argo-workflows/commit/f3049105664999ec29e955c9ac73c8bd1dfd6730) Proper controller support for running workflows in arbitrary namespaces. Install controller into kube-system namespace by default
 * [ffb3d128](https://github.com/argoproj/argo-workflows/commit/ffb3d128070f2c6961d20ba2ea3c0d64f760b1bb) Add support for controller installation via `argo install` and demo instructions
 * [dcfb2752](https://github.com/argoproj/argo-workflows/commit/dcfb2752172ad8c79da97a5a35895eb62f0d52eb) Add `argo delete` command to delete workflows
 * [8e583afb](https://github.com/argoproj/argo-workflows/commit/8e583afb0a2161d3565651abb1cf7d76d50af861) Add `argo logs` command as a convenience wrapper around `kubectl logs`
 * [368193d5](https://github.com/argoproj/argo-workflows/commit/368193d5002cb2d50b02e397e2b98e09b427227c) Add argo `submit`, `list`, `get`, `lint` commands
 * [8ef7a131](https://github.com/argoproj/argo-workflows/commit/8ef7a131c966c080c8651de7bb08424e501f1c3d) Executor to load script source code as an artifact to main. Remove controller hack
 * [736c5ec6](https://github.com/argoproj/argo-workflows/commit/736c5ec64930df2e25ee7698db9c04044c53ba6c) Annotate pod with outputs. Properly handle tar/gz of artifacts
 * [cd415c9d](https://github.com/argoproj/argo-workflows/commit/cd415c9d56fdd211405c7e5a20789e5f37b049db) Introduce Template.ArchiveLocation to store all related step level artifacts to a job, understood by executor
 * [4241cace](https://github.com/argoproj/argo-workflows/commit/4241cacea3f272146192c90322c9f780f55ef717) Support for saving s3 output artifacts
 * [cd3a3f1e](https://github.com/argoproj/argo-workflows/commit/cd3a3f1e57194fe61634a845ddee0be84b446cde) Bind mount docker.sock to wait container to use `docker wait` and `docker cp`
 * [77d64a66](https://github.com/argoproj/argo-workflows/commit/77d64a66a91e3cd39230714b355374a3d72d5233) Support the case where an input artifact path overlaps with a container volume mount
 * [6a54b31f](https://github.com/argoproj/argo-workflows/commit/6a54b31f3619e26fb5fcb98f897eed5392e546bd) Support for automatic termination for daemoned workflow steps
 * [2435e6f7](https://github.com/argoproj/argo-workflows/commit/2435e6f75a94565217423d244a75170c47115cb8) Track children node IDs in workflow status nodes
 * [227c1961](https://github.com/argoproj/argo-workflows/commit/227c19616fc1ebd1567cf483107d9323e04a6cc7) Initial support for daemon workflow steps (no termination yet)
 * [738b02d2](https://github.com/argoproj/argo-workflows/commit/738b02d20495c06ee63b63261fae2b9e815fe578) Support for git/http input artifacts. hack together wait container logic as a shell script
 * [de71cb5b](https://github.com/argoproj/argo-workflows/commit/de71cb5baccff313d8aa372876f79ab1f8044921) Change according to jesse's comments
 * [621d7ca9](https://github.com/argoproj/argo-workflows/commit/621d7ca98649feaacfdfd3a531f9ed45cd07a86c) Argo Executor init container
 * [efe43927](https://github.com/argoproj/argo-workflows/commit/efe439270af68cd1cef44d7b6874f0ef0f195d9d) Switch representation of parallel steps as a list instead of a map. update examples
 * [56ca947b](https://github.com/argoproj/argo-workflows/commit/56ca947bb57fee22b19f3046873ab771a8637859) Introduce ability to add sidecars to run adjacent to workflow steps
 * [b4d77701](https://github.com/argoproj/argo-workflows/commit/b4d777017c5bdd87db1b004aa8623c213acd3840) Controller support for overlapping artifact path to user specified volume mountPaths
 * [3782bade](https://github.com/argoproj/argo-workflows/commit/3782badead84caff944dbe2bfc3a4f53b3113dd4) Get coinflip example to function
 * [065a8f77](https://github.com/argoproj/argo-workflows/commit/065a8f77f5f84bc4e9f5ddacc3fb630a5ea86d0b) Get python script example to function
 * [8973204a](https://github.com/argoproj/argo-workflows/commit/8973204a5a7f88b91b99f711c7e175be20f6dfc6) Move to list style of inputs and arguments (vs. maps). Reuse artifact datastructure
 * [d9838749](https://github.com/argoproj/argo-workflows/commit/d983874969d40058fa7ca648d5bf17f11ea8c0fb) Improve example yamls
 * [f83b2620](https://github.com/argoproj/argo-workflows/commit/f83b26202d4b896e9ac13e8d93109df3a3bc0c82) Support for volumeClaimTemplates (ephemeral volumes) in workflows
 * [be3ad92e](https://github.com/argoproj/argo-workflows/commit/be3ad92e0c420f22abb306eff33f85b2bbf6bffb) Support for using volumes within multiple steps in a workflow
 * [4b4dc4a3](https://github.com/argoproj/argo-workflows/commit/4b4dc4a315a4b36f077a6bcc9647f04be5a083cb) Copy outputs from pod metadata to workflow node outputs
 * [07f2c965](https://github.com/argoproj/argo-workflows/commit/07f2c9654481d52869df41466aead42220765582) Initial support for conditionals as 'when' field in workflow step
 * [fe639edd](https://github.com/argoproj/argo-workflows/commit/fe639edd6dbbdb4a0405d8449cc2b9aa7bbc9dc0) Controller support for "script" templates (workflow step as code)
 * [a896f03e](https://github.com/argoproj/argo-workflows/commit/a896f03e9daf0bdd466ebe21e42ac5af37dc580c) Add example yamls for proposal for scripting steps
 * [c782e2e1](https://github.com/argoproj/argo-workflows/commit/c782e2e1b8ef9dcd1b2fc30d4d1f834ca2a22c70) Support looping with item maps
 * [7dc58fce](https://github.com/argoproj/argo-workflows/commit/7dc58fce04b45c49df953b90971e3138311c3106) Initial withItems loop support
 * [f3010c1d](https://github.com/argoproj/argo-workflows/commit/f3010c1da94be33712941c7cba0a6820d4ffd762) Support for argument passing and substitution in templates
 * [5e8ba870](https://github.com/argoproj/argo-workflows/commit/5e8ba8701993bb3a1c86317d641ab5c98d69c0bf) Split individual workflow operation logic from controller
 * [63a2c20c](https://github.com/argoproj/argo-workflows/commit/63a2c20c20b1adfc6b3082a341faa72127ab84fd) Introduce sirupsen/logrus logging package
 * [2058342f](https://github.com/argoproj/argo-workflows/commit/2058342f7f8a48337f7dce8e45c22a1fed71babe) Annotate the template used by executor to include destination artifact information
 * [52f8db21](https://github.com/argoproj/argo-workflows/commit/52f8db217581fde487c21dee09821d2c27878d0f) Sync workflow controller configuration from a configmap. Add config validation
 * [d0a1748a](https://github.com/argoproj/argo-workflows/commit/d0a1748afa3c69886a55408d72024fdcecf25c97) Upgrade to golang 1.9.1. Get `make lint` target to function
 * [ac58d832](https://github.com/argoproj/argo-workflows/commit/ac58d8325fc253af0cd00e0d397a5ab60ade5188) Speed up rebuilds from within build container by bind mounting $GOPATH/pkg:/root/go/pkg
 * [71445675](https://github.com/argoproj/argo-workflows/commit/714456753ae81e62f4cf3a563eed20d1b0d1be1a) Add installation manifests. Initial stubs for controller configuration
 * [10372091](https://github.com/argoproj/argo-workflows/commit/103720917b689713ba9b963d00e4578fd6d21fb2) Introduce s3, git, http artifact sources in inputs.artifacts
 * [a68001d3](https://github.com/argoproj/argo-workflows/commit/a68001d31fc4c2d55686a29abe7ace8f0bdf4644) Add debug tools to argoexec image. Remove privileged mode from sidekick. Disable linting
 * [dc530232](https://github.com/argoproj/argo-workflows/commit/dc530232d4595feb0ad01ef45a25bfec23db43a8) Create shared 'input-artifacts' volume and mount between init/main container
 * [6ba84eb5](https://github.com/argoproj/argo-workflows/commit/6ba84eb5285efcacd1f460e11892bce175246799) Expose various pod metadata to argoexec via K8s downward API
 * [1fc079de](https://github.com/argoproj/argo-workflows/commit/1fc079de2fddf992e8d42abf3fe0e556ae7973c2) Add `argo yaml validate` command and `argoexec artifacts load` stub
 * [9125058d](https://github.com/argoproj/argo-workflows/commit/9125058db7c3c45b907c767d040867b3e9c37063) Include scheduling of argoexec (init and sidekick) containers to the user's main
 * [67f8353a](https://github.com/argoproj/argo-workflows/commit/67f8353a045c6fcb713f8b6f534e1caf6fee2be2) Initial workflow operator logic
 * [8137021a](https://github.com/argoproj/argo-workflows/commit/8137021adc20adbb39debbbcdb41332eed7a5451) Reorganize all CLIs into a separate dir. Add stubs for executor and apiserver
 * [74baac71](https://github.com/argoproj/argo-workflows/commit/74baac71754937c4f934be5321a8c24d172a5142) Introduce Argo errors package
 * [37b7de80](https://github.com/argoproj/argo-workflows/commit/37b7de8008ab299e6db3d4616bac2d8af0bcb0fc) Add apiserver skeleton
 * [3ed1dfeb](https://github.com/argoproj/argo-workflows/commit/3ed1dfeb073829d3c4f92b95c9a74118caaec1b4) Initial project structure. CLI and Workflow CRD skeleton

### Contributors

 * Alexander Matyushentsev
 * Anshuman Bhartiya
 * David Kale
 * Ed Lee
 * Edward Lee
 * Javier Castellanos
 * Jesse Suen
 * Matt Hillsdon
 * Rafal
 * Rahul Dhide
 * Rhys Parry
 * Sandeep Bhojwani
 * Shri Javadekar
 * Tianhe Zhang
 * Wojciech Kalemba
 * cyee88
 * gaganapplatix
 * mukulikak

## v0.4.7 (2018-06-07)

 * [e4d0bd39](https://github.com/argoproj/argo-workflows/commit/e4d0bd3926d02fe3e89d6d9b8a02ecbb2db91eff) Take into account number of unavailable replicas to decided if deployment is healthy or not (#270)
 * [18dc82d1](https://github.com/argoproj/argo-workflows/commit/18dc82d14d240485a266350c182560e2d2700ada) Remove hard requirement of initializing OIDC app during server startup (resolves #272)
 * [e720abb5](https://github.com/argoproj/argo-workflows/commit/e720abb58b43f134518ce30239c2a4533effdbc7) Bump version to v0.4.7
 * [a2e9a9ee](https://github.com/argoproj/argo-workflows/commit/a2e9a9ee49052dce05dc9718240dfb8202e5b2c2) Repo names containing underscores were not being accepted (resolves #258)

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.4.6 (2018-06-06)

 * [cf377690](https://github.com/argoproj/argo-workflows/commit/cf3776903d8d52af9c656c740601e53947d79609) Retry `argocd app wait` connection errors from EOF watch. Show detailed state changes

### Contributors

 * Jesse Suen

## v0.4.5 (2018-05-31)

 * [3acca509](https://github.com/argoproj/argo-workflows/commit/3acca5095e1bdd028dfd0424abdeb3e5b3036b2d) Add `argocd app unset` command to unset parameter overrides. Bump version to v0.4.5
 * [5a622861](https://github.com/argoproj/argo-workflows/commit/5a622861273da8ccf27bcfd12471b8a377e558e6) Cookie token was not parsed properly when mixed with other site cookies

### Contributors

 * Jesse Suen

## v0.4.4 (2018-05-30)

 * [5452aff0](https://github.com/argoproj/argo-workflows/commit/5452aff0bebdbba3990f1cc2e300f6f37f634b8b) Add ability to show parameters and overrides in CLI (resolves #240) (#247)
 * [0f4f1262](https://github.com/argoproj/argo-workflows/commit/0f4f1262af8837748da06fdcc9accf4ced273dfd) Add Events API endpoint (#237)
 * [4e7f68cc](https://github.com/argoproj/argo-workflows/commit/4e7f68ccbae9b362178bcdaafc1c0c29fcc1ef19) Update version to 0.4.4
 * [96c05bab](https://github.com/argoproj/argo-workflows/commit/96c05babe026b998fb80033c76594585b869c8a2) Issue #238 - add upsert flag to 'argocd app create' command (#245)
 * [6b78cddb](https://github.com/argoproj/argo-workflows/commit/6b78cddb1921dad6c3f0fe53c85c51711ba8b2de) Add repo browsing endpoint (#229)
 * [12596ff9](https://github.com/argoproj/argo-workflows/commit/12596ff9360366afbadfcd366586318b74e410ca) Issue #233 - Controller does not persist rollback operation result (#234)
 * [a240f1b2](https://github.com/argoproj/argo-workflows/commit/a240f1b2b9e7d870d556fb4420016852a733b9c5) Bump version to 0.5.0
 * [f6da1967](https://github.com/argoproj/argo-workflows/commit/f6da19672e6388ae481dc72b32703973c0ebe921) Support subscribing to settings updates and auto-restart of dex and API server (resolves #174) (#227)
 * [e81d30be](https://github.com/argoproj/argo-workflows/commit/e81d30be9b378312d626a3b5034f2f4d2d1f70d5) Update getting_started.md to point to v0.4.3
 * [13b090e3](https://github.com/argoproj/argo-workflows/commit/13b090e3bd96dc984bc266c49c536511dff793d1) Issue #147 - App sync frequently fails due to concurrent app modification (#226)
 * [d0479e6d](https://github.com/argoproj/argo-workflows/commit/d0479e6ddcba5fe66ed2137935bcec51dedb4f27) Issue # 223 - Remove app finalizers during e2e fixture teardown (#225)
 * [14328270](https://github.com/argoproj/argo-workflows/commit/1432827006855aa526966de93c88551ce049b5ce) Add error fields to cluster/repo, shell output (#200)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.4.3 (2018-05-21)

 * [89bf4eac](https://github.com/argoproj/argo-workflows/commit/89bf4eac7105ced9279203b7085f07ac76a13ee5) Bump version to 0.4.3
 * [07aac0bd](https://github.com/argoproj/argo-workflows/commit/07aac0bdae285201e36e73b88bd16f2318a04be8) Move local branch deletion as part of git Reset() (resolves #185) (#222)
 * [61220b8d](https://github.com/argoproj/argo-workflows/commit/61220b8d0d5b217866e5c2fa6f6d739eea234225) Fix exit code for app wait (#219)

### Contributors

 * Andrew Merenbach
 * Jesse Suen

## v0.4.2 (2018-05-21)

 * [4e470aaf](https://github.com/argoproj/argo-workflows/commit/4e470aaf096b7acadf646063781af811168276ea) Remove context name prompt during login. (#218)
 * [76922b62](https://github.com/argoproj/argo-workflows/commit/76922b620b295897f8f86416cea1b41d558a0d24) Update version to 0.4.2

### Contributors

 * Jesse Suen

## v0.4.1 (2018-05-18)

 * [ac0f623e](https://github.com/argoproj/argo-workflows/commit/ac0f623eda0cd7d6adb5f8be8655a22e910a120d) Add `argocd app wait` command (#216)
 * [afd54508](https://github.com/argoproj/argo-workflows/commit/afd5450882960f4f723197e56ea7c67dc65b8d10) Bump version to v0.4.1
 * [c17266fc](https://github.com/argoproj/argo-workflows/commit/c17266fc2173246775cecfb6625d6d60eac2d2b8) Add documentation on how to configure SSO and Webhooks
 * [f62c8254](https://github.com/argoproj/argo-workflows/commit/f62c825495211a738d11f9e95e1aec59a5031be0) Manifest endpoint (#207)
 * [45f44dd4](https://github.com/argoproj/argo-workflows/commit/45f44dd4be375002300f96386ffb3383c2119ff8) Add v0.4.0 changelog
 * [9c0daebf](https://github.com/argoproj/argo-workflows/commit/9c0daebfe088a1ac5145417df14d11769f266e82) Fix diff falsely reporting OutOfSync due to namespace/annotation defaulting
 * [f2a0ca56](https://github.com/argoproj/argo-workflows/commit/f2a0ca560971680e21b20645d62462a29ac25721) Add intelligence in diff libray to perform three-way diff from last-applied-configuration annotation (resolves #199)
 * [e04d3158](https://github.com/argoproj/argo-workflows/commit/e04d315853ec9ed25d8359136d6141e821fae5e1) Issue #118 - app delete should be done through controller using finalizers (#206)
 * [daec6976](https://github.com/argoproj/argo-workflows/commit/daec697658352b9a607f5d4cc777eae24db0ed33) Update ksonnet to v0.10.2 (resolves #208)
 * [7ad56707](https://github.com/argoproj/argo-workflows/commit/7ad56707102a31d64214f8fb47ab840fd2550826) Make sure api server started during fixture setup (#209)
 * [80364233](https://github.com/argoproj/argo-workflows/commit/8036423373e79b48a52a34bd524f1cdf8bf2fd46) Implement App management and repo management e2e tests (#205)
 * [8039228a](https://github.com/argoproj/argo-workflows/commit/8039228a9d31a445461231de172425e911e9eaea) Add last update time to operation status, fix operation status patching (#204)
 * [b1103af4](https://github.com/argoproj/argo-workflows/commit/b1103af4290e6e6134f2d4f62df32f90aa8448d5) Rename recent deployments to history (#201)
 * [d67ad5ac](https://github.com/argoproj/argo-workflows/commit/d67ad5acfd598712c153f14a1c7946759dbc733c) Add connect timeouts when interacting with SSH git repos (resolves #131) (#203)
 * [c9df9c17](https://github.com/argoproj/argo-workflows/commit/c9df9c17b77688ac5725a9fa00222006a5fd9f4f) Default Spec.Source.TargetRevision to HEAD server-side if unspecified (issue #190)
 * [8fa46b02](https://github.com/argoproj/argo-workflows/commit/8fa46b02b0784a9922aa93be5896e65732a1729d) Remove SyncPolicy (issue #190)
 * [92c48133](https://github.com/argoproj/argo-workflows/commit/92c481330d655697a6630813b63617de6789f403) App creation was not defaulting to server and namespace defined in app.yaml
 * [2664db3e](https://github.com/argoproj/argo-workflows/commit/2664db3e4072b96176d286f7a91f03d08e5cc715) Refactor application controller sync/apply loop (#202)
 * [6b554e5f](https://github.com/argoproj/argo-workflows/commit/6b554e5f4efa3473be217ebbcaf89acb22ded628) Add 0.3.0 to 0.4.0 migration utility (#186)
 * [2bc0dff1](https://github.com/argoproj/argo-workflows/commit/2bc0dff1359031cc335769c3a742987cb1c4e7ba) Issue #146 - Render health status information in 'app list' and 'app get' commands (#198)
 * [c61795f7](https://github.com/argoproj/argo-workflows/commit/c61795f71afd5705d75a4377c9265023aa7cec2c) Add 'database' library for CRUD operations against repos and clusters. Redact sensitive information (#196)
 * [a8a7491b](https://github.com/argoproj/argo-workflows/commit/a8a7491bf0b0534bbf63c08291a4966aa81403fa) Handle potential panic when `argo install settings` run against an empty configmap

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.4.0-alpha1 (2018-05-11)


### Contributors


## v0.4.0 (2018-05-17)

 * [9c0daebf](https://github.com/argoproj/argo-workflows/commit/9c0daebfe088a1ac5145417df14d11769f266e82) Fix diff falsely reporting OutOfSync due to namespace/annotation defaulting
 * [f2a0ca56](https://github.com/argoproj/argo-workflows/commit/f2a0ca560971680e21b20645d62462a29ac25721) Add intelligence in diff libray to perform three-way diff from last-applied-configuration annotation (resolves #199)
 * [e04d3158](https://github.com/argoproj/argo-workflows/commit/e04d315853ec9ed25d8359136d6141e821fae5e1) Issue #118 - app delete should be done through controller using finalizers (#206)
 * [daec6976](https://github.com/argoproj/argo-workflows/commit/daec697658352b9a607f5d4cc777eae24db0ed33) Update ksonnet to v0.10.2 (resolves #208)
 * [7ad56707](https://github.com/argoproj/argo-workflows/commit/7ad56707102a31d64214f8fb47ab840fd2550826) Make sure api server started during fixture setup (#209)
 * [80364233](https://github.com/argoproj/argo-workflows/commit/8036423373e79b48a52a34bd524f1cdf8bf2fd46) Implement App management and repo management e2e tests (#205)
 * [8039228a](https://github.com/argoproj/argo-workflows/commit/8039228a9d31a445461231de172425e911e9eaea) Add last update time to operation status, fix operation status patching (#204)
 * [b1103af4](https://github.com/argoproj/argo-workflows/commit/b1103af4290e6e6134f2d4f62df32f90aa8448d5) Rename recent deployments to history (#201)
 * [d67ad5ac](https://github.com/argoproj/argo-workflows/commit/d67ad5acfd598712c153f14a1c7946759dbc733c) Add connect timeouts when interacting with SSH git repos (resolves #131) (#203)
 * [c9df9c17](https://github.com/argoproj/argo-workflows/commit/c9df9c17b77688ac5725a9fa00222006a5fd9f4f) Default Spec.Source.TargetRevision to HEAD server-side if unspecified (issue #190)
 * [8fa46b02](https://github.com/argoproj/argo-workflows/commit/8fa46b02b0784a9922aa93be5896e65732a1729d) Remove SyncPolicy (issue #190)
 * [92c48133](https://github.com/argoproj/argo-workflows/commit/92c481330d655697a6630813b63617de6789f403) App creation was not defaulting to server and namespace defined in app.yaml
 * [2664db3e](https://github.com/argoproj/argo-workflows/commit/2664db3e4072b96176d286f7a91f03d08e5cc715) Refactor application controller sync/apply loop (#202)
 * [6b554e5f](https://github.com/argoproj/argo-workflows/commit/6b554e5f4efa3473be217ebbcaf89acb22ded628) Add 0.3.0 to 0.4.0 migration utility (#186)
 * [2bc0dff1](https://github.com/argoproj/argo-workflows/commit/2bc0dff1359031cc335769c3a742987cb1c4e7ba) Issue #146 - Render health status information in 'app list' and 'app get' commands (#198)
 * [c61795f7](https://github.com/argoproj/argo-workflows/commit/c61795f71afd5705d75a4377c9265023aa7cec2c) Add 'database' library for CRUD operations against repos and clusters. Redact sensitive information (#196)
 * [a8a7491b](https://github.com/argoproj/argo-workflows/commit/a8a7491bf0b0534bbf63c08291a4966aa81403fa) Handle potential panic when `argo install settings` run against an empty configmap
 * [d1c7c4fc](https://github.com/argoproj/argo-workflows/commit/d1c7c4fcafb66bac6553247d16a03863d25910e6) Issue #187 - implement `argo settings install` command (#193)
 * [3dbbcf89](https://github.com/argoproj/argo-workflows/commit/3dbbcf891897f3c3889189016ae1f3fabcddca1f) Move sync logic to contoller (#180)
 * [0cfd1ad0](https://github.com/argoproj/argo-workflows/commit/0cfd1ad05fe8ec0c78dfd85ba0f91027522dfe70) Update feature list with SSO and Webhook integration
 * [bfa4e233](https://github.com/argoproj/argo-workflows/commit/bfa4e233b72ef2863d1bfb010ba95fad519a9c43) cli will look to spec.destination.server and namespace when displaying apps
 * [dc662da3](https://github.com/argoproj/argo-workflows/commit/dc662da3d605bd7189ce6c06b0dbc1661d4bf2fb) Support OAuth2 login flow from CLI (resolves #172) (#181)
 * [4107d242](https://github.com/argoproj/argo-workflows/commit/4107d2422bb6331833f360f2cab01eb24500e173) Fix linting errors
 * [b83eac5d](https://github.com/argoproj/argo-workflows/commit/b83eac5dc2f9c026ad07258e4c01d5217e2992fe) Make ApplicationSpec.Destination non-optional, non-pointer (#177)
 * [bb51837c](https://github.com/argoproj/argo-workflows/commit/bb51837c56a82e486d68a350b3b4397ff930ec37) Do not delete namespace or CRD during uninstall unless explicitly stated (resolves #167) (#173)
 * [5bbb4fe1](https://github.com/argoproj/argo-workflows/commit/5bbb4fe1a131ed3380a857af3db5e9d708f3b7f6) Cache kubernetes API resource discovery (resolves #170) (#176)
 * [b5c20e9b](https://github.com/argoproj/argo-workflows/commit/b5c20e9b46ea19b63f3f894d784d5a25b97f0ebb) Trim spaces server-side in GitHub usernames (#171)
 * [1e1ab636](https://github.com/argoproj/argo-workflows/commit/1e1ab636e042da4d5f1ee4e47a01f301d6a458a7) Don't fail when new app has same spec as old (#168)
 * [73485538](https://github.com/argoproj/argo-workflows/commit/7348553897af89b9c4366f2d445dd2d96fe4d655) Improve CI build stability
 * [5f65a512](https://github.com/argoproj/argo-workflows/commit/5f65a5128a3fa42f12a60908eee3fa5d11624305) Introduce caching layer to repo server to improve query response times (#165)
 * [d9c12e72](https://github.com/argoproj/argo-workflows/commit/d9c12e72719dffaf6951b5fb71e4bae8a8ddda0d) Issue #146 - ArgoCD applications should have a rolled up health status (#164)
 * [fb2d6b4a](https://github.com/argoproj/argo-workflows/commit/fb2d6b4afff1ba66880691d188c284a77f6ac99e) Refactor repo server and git client (#163)
 * [3f4ec0ab](https://github.com/argoproj/argo-workflows/commit/3f4ec0ab2263038ba91d3b594b2188fc108fc8d7) Expand Git repo URL normalization (#162)
 * [ac938fe8](https://github.com/argoproj/argo-workflows/commit/ac938fe8a3af46f7aac07d607bfdd0a375e74103) Add GitHub webhook handling to fast-track controller application reprocessing (#160)
 * [dc1e8796](https://github.com/argoproj/argo-workflows/commit/dc1e8796fb40013a7980e8bc18f8b2545c6e6cca) Disable authentication for settings service
 * [8c5d59c6](https://github.com/argoproj/argo-workflows/commit/8c5d59c60c679ab6d35f8a6e51337c586dc4fdde) Issue #157 - If argocd token is expired server should return 401 instead of 500 (#158)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.3.3 (2018-05-03)

 * [13558b7c](https://github.com/argoproj/argo-workflows/commit/13558b7ce8d7bd9f8707a6a18f45af8662b1c60d) Revert change to redact credentials since logic is reused by controller
 * [3b2b3dac](https://github.com/argoproj/argo-workflows/commit/3b2b3dacf50f9b51dde08f1d1e1e757ed30c24a4) Update version
 * [1b2f8999](https://github.com/argoproj/argo-workflows/commit/1b2f89995c970eb9fb5fe7bce4ac0253bddb9d7d) Issue #155 - Application update failes due to concurrent access (#156)
 * [0479fcdf](https://github.com/argoproj/argo-workflows/commit/0479fcdf82b1719fd97767ea74509063e9308b0a) Add settings endpoint so frontend can show/hide SSO login button. Rename config to settings (#153)
 * [a0446546](https://github.com/argoproj/argo-workflows/commit/a04465466dfa4dc039222732cd9dbb84f9fdb3dd) Add workflow for blue-green deployments (#148)
 * [670921df](https://github.com/argoproj/argo-workflows/commit/670921df902855b209094b59f32ce3e051a847fd) SSO Support (#152)
 * [18f7e17d](https://github.com/argoproj/argo-workflows/commit/18f7e17d7a200a0dd1c8447acc2815981c0093a6) Added OWNERS file
 * [a2aede04](https://github.com/argoproj/argo-workflows/commit/a2aede04412380b7853041fbce6dd6d377e483e9) Redact sensitive repo/cluster information upon retrieval (#150)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Edward Lee
 * Jesse Suen

## v0.3.2 (2018-05-01)

 * [1d876c77](https://github.com/argoproj/argo-workflows/commit/1d876c77290bbfc830790bff977c8a65a0432e0c) Fix compilation error
 * [70465a05](https://github.com/argoproj/argo-workflows/commit/70465a0520410cd4466d1feb4eb9baac98e94688) Issue #147 - Use patch to update recentDeployments field (#149)
 * [3c984571](https://github.com/argoproj/argo-workflows/commit/3c9845719f643948a5f1be83ee7039e7f33b8c65)  Issue #139 - Application sync should delete 'unexpected' resources (#144)
 * [a36cc894](https://github.com/argoproj/argo-workflows/commit/a36cc8946c8479745f63c24df4a9289d70f0a773) Issue #136 - Use custom formatter to get desired state of deployment and service (#145)
 * [9567b539](https://github.com/argoproj/argo-workflows/commit/9567b539d1d2fcb9535cdb7c91f9060a7ac06d8f) Improve comparator to fall back to looking up a resource by name
 * [fdf9515d](https://github.com/argoproj/argo-workflows/commit/fdf9515de2826d53f8b138f99c8896fdfa5f919e) Refactor git library: * store credentials in files (instead of encoded in URL) to prevent leakage during git errors * fix issue where HEAD would not track updates from origin/HEAD (resolves #133) * refactor git library to promote code reuse, and remove shell invocations
 * [b3202384](https://github.com/argoproj/argo-workflows/commit/b320238487c339186f1e0be5e1bfbb35fa0036a4) ksonnet util was not locating a ksonnet app dir correctly
 * [7872a604](https://github.com/argoproj/argo-workflows/commit/7872a60499ebbda01cd31f859eba8e7209f16b9c) Update ksonnet to v0.10.1
 * [5fea3846](https://github.com/argoproj/argo-workflows/commit/5fea3846d1c09bca9d0e68f1975598b29b5beb91) Adding clusters should always go through argocd-manager service account creation
 * [86a4e0ba](https://github.com/argoproj/argo-workflows/commit/86a4e0baaa8932daeba38ac74535497e773f24b9) RoleBindings do not need to specify service account namespace in subject
 * [917f1df2](https://github.com/argoproj/argo-workflows/commit/917f1df250013ec462f0108bfb85b54cb56c53c4) Populated 'unexpected' resources while comparing target and live states (#137)
 * [11260f24](https://github.com/argoproj/argo-workflows/commit/11260f24763dab2e2364d8cb4c5789ac046666a8) Don't ask for user credentials if username and password are specified as arguments (#129)
 * [38d20d0f](https://github.com/argoproj/argo-workflows/commit/38d20d0f0406e354c6ca4d9f2776cbb8a322473c) Add `argocd ctx` command for switching between contexts. Better CLI descriptions (resolves #103)
 * [938f40e8](https://github.com/argoproj/argo-workflows/commit/938f40e817a44eb1c806102dc90593af2adb5d88) Prompting for repo credentials was accepting newline as username
 * [5f9c8b86](https://github.com/argoproj/argo-workflows/commit/5f9c8b862edbcba5d079621f0c4bba0e942add9b) Error properly when server address is unspecified (resolves #128)
 * [d96d67bb](https://github.com/argoproj/argo-workflows/commit/d96d67bb9a4eae425346298d513a1cf52e89da62) Generate a temporary kubeconfig instead of using kubectl flags when applying resources
 * [19c3b876](https://github.com/argoproj/argo-workflows/commit/19c3b876767571257fbadad35971d8f6eecd2d74) Bump version to 0.4.0. `argocd app sync --dry-run` was incorrectly appending items to history (resolves #127)

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.3.1 (2018-04-24)

 * [7d08ab4e](https://github.com/argoproj/argo-workflows/commit/7d08ab4e2b5028657c6536dc9007ac5b9da13b8d) Bump version to v0.3.1
 * [efea09d2](https://github.com/argoproj/argo-workflows/commit/efea09d2165e35b6b2176fd0ff6f5fcd0c4699e4) Fix linting issue in `app rollback`
 * [2adaef54](https://github.com/argoproj/argo-workflows/commit/2adaef547be26b9911676ff048b0ea38d8e87df2) Introduce `argocd app history` and `argocd app rollback` CLI commands (resolves #125)
 * [d71bbf0d](https://github.com/argoproj/argo-workflows/commit/d71bbf0d9a00046622498200754f7ae6639edfc4) Allow overriding server or namespace separately (#126)
 * [36b3b2b8](https://github.com/argoproj/argo-workflows/commit/36b3b2b8532142d50c3ada0d8d3cb2328c8a32e4) Switch to gogo/protobuf for golang code generation in order to use gogo extensions
 * [63dafa08](https://github.com/argoproj/argo-workflows/commit/63dafa08ccdef6141f83f26157bd32192c62f052) Issue #110 - Rollback ignores parameter overrides (#117)
 * [afddbbe8](https://github.com/argoproj/argo-workflows/commit/afddbbe875863c8d33a85d2d2874f0703153c195) Issue #123 - Create .argocd directory before saving config file (#124)
 * [34811caf](https://github.com/argoproj/argo-workflows/commit/34811cafca3df45952677407ce5458d50f23e0fd) Update download instructions to getting started

### Contributors

 * Alexander Matyushentsev
 * Jesse Suen

## v0.3.0 (2018-04-23)

 * [8a285116](https://github.com/argoproj/argo-workflows/commit/8a2851169c84741d774818ec8943a444d523f082) Enable auth by default. Decrease app resync period from 10m to 3m
 * [1a85a2d8](https://github.com/argoproj/argo-workflows/commit/1a85a2d8051ee64ad16b0487e2a3d14cf4fb01e6) Bump version file to 0.3.0. Add release target and cli-linux/darwin targets
 * [cf2d00e1](https://github.com/argoproj/argo-workflows/commit/cf2d00e1e04219ed99195488740189fbd6af997d) Add ability to set a parameter override from the CLI (`argo app set -p`)
 * [266c948a](https://github.com/argoproj/argo-workflows/commit/266c948adddab715ba2c60f082bd7e37aec6f814) Add documentation about ArgoCD tracking strategies
 * [dd564ee9](https://github.com/argoproj/argo-workflows/commit/dd564ee9dd483f3e19bceafd30e5842a005e04f1) Introduce `app set` command for updating an app (resolves #116)
 * [b9d48cab](https://github.com/argoproj/argo-workflows/commit/b9d48cabb99e336ea06e1a7af56f2e74e740a9cf) Add ability to set the tracking revision during app creation
 * [276e0674](https://github.com/argoproj/argo-workflows/commit/276e0674c37a975d903404b3e3bf747b7e99a787) Deployment of resources is performed using `kubectl apply` (resolves #106)
 * [f3c4a693](https://github.com/argoproj/argo-workflows/commit/f3c4a6932730c53ae1cf9de2df9e62c89e54ea53) Add watch verb to controller role
 * [1c60a698](https://github.com/argoproj/argo-workflows/commit/1c60a69866dae95c7bf4a0f912292a5a6714611f) Rename `argocd app add/rm` to `argocd app create/delete` (resolves #114)
 * [050f937a](https://github.com/argoproj/argo-workflows/commit/050f937a2409111194f6c4ff7cc75a3f2ed3fa0b) Update ksonnet to v0.10.0-alpha.3
 * [b24e4782](https://github.com/argoproj/argo-workflows/commit/b24e478224a359c883425f2640f4327f29b3ab80) Add application validation
 * [e34380ed](https://github.com/argoproj/argo-workflows/commit/e34380ed765bc8b802d60ab30c25a1389ebd33a8) Expose port 443 to proxy to port 8080 (#113)
 * [338a1b82](https://github.com/argoproj/argo-workflows/commit/338a1b826fd597eafd0a654ca424a0c90b4647e0) `argo login` was not able to properly update boolean connection flags (insecure/plaintext)
 * [b87c63c8](https://github.com/argoproj/argo-workflows/commit/b87c63c897dc0e7c11b311d9f6de6f6436186aeb) Re-add workaround for ksonnet bug
 * [f6ed150b](https://github.com/argoproj/argo-workflows/commit/f6ed150bb7e9f50854fe4f7e4d00cc7ab1ccd581) Issue #108 - App controller incorrectly report that app is out of sync (#109)
 * [d5c683bc](https://github.com/argoproj/argo-workflows/commit/d5c683bc76f6e3eb1b5570b50d795b387481087f) Add syncPolicy field to application CRD (#107)
 * [3ac95f3f](https://github.com/argoproj/argo-workflows/commit/3ac95f3f84c6b85aa8e0ff0c9c68e2ccbbaa8875) Fix null pointer error in controller (#105)
 * [3be872ad](https://github.com/argoproj/argo-workflows/commit/3be872ad32891cc7628b3717bff31deb687a556f) Rework local config to support multiple servers/credentials
 * [80964a79](https://github.com/argoproj/argo-workflows/commit/80964a79b2b8cd1383eb1cbf03eddb608c13b771) Set session cookies, errors appropriately (#100)
 * [e719035e](https://github.com/argoproj/argo-workflows/commit/e719035ea5ba3d08bc4118151989071befb127ac) Allow ignoring recource deletion related errors while deleting application (#98)
 * [f2bcf63b](https://github.com/argoproj/argo-workflows/commit/f2bcf63b26257bb83220d3a94ddbb394b591b659) Fix linting breakage in session mock from recent changes to session interface
 * [2c9843f1](https://github.com/argoproj/argo-workflows/commit/2c9843f1a083ce41ec3fa9aebf14fb5028a17765) Update ksonnet to v0.10.0-alpha.2
 * [0560406d](https://github.com/argoproj/argo-workflows/commit/0560406d815f7012f4c45bda8d2a3d940457bd3a) Add server auth cookies (#96)
 * [db8083c6](https://github.com/argoproj/argo-workflows/commit/db8083c6573ba4a514bbad11d73f5e65e9ed06a6) Lowercase repo names before using in secret (#94)
 * [fcc9f50b](https://github.com/argoproj/argo-workflows/commit/fcc9f50b3fe35f71ab2ead6181517bf16e06ac7f) Fix issue preventing uppercased repo and cluster URLs (resolves #81)
 * [c1ffbad8](https://github.com/argoproj/argo-workflows/commit/c1ffbad8d89ed0aad0ce680463fe38297afb09b8) Support manual token use for CLI commands (#90)
 * [d7cdb1a5](https://github.com/argoproj/argo-workflows/commit/d7cdb1a5af3aae50d67ff4d2346375ffe3bbf1af) Convert Kubernetes errors to gRPC errors (#89)
 * [6c41ce5e](https://github.com/argoproj/argo-workflows/commit/6c41ce5e086822529a37002878ab780778df26b9) Add session gateway (#84)
 * [685a814f](https://github.com/argoproj/argo-workflows/commit/685a814f3870237c560c83724af5fc214af158b8) Add `argocd login` command (#82)
 * [06b64047](https://github.com/argoproj/argo-workflows/commit/06b64047a4b5e6d7728ac6ca2eac03327f42ca37) Issue #69 - Auto-sync option in application CRD instance (#83)
 * [8a90b324](https://github.com/argoproj/argo-workflows/commit/8a90b324461ecc35a6d94296154e5aaa86e0adc5) Show more relevant information in `argocd cluster add`
 * [7e47b1eb](https://github.com/argoproj/argo-workflows/commit/7e47b1ebae32b01b927c76c120cdab7be8084d13) TLS support. HTTP/HTTPS/gRPC all serving on single port
 * [150b51a3](https://github.com/argoproj/argo-workflows/commit/150b51a3ac43cac00aae886fe2c3ac5b1fb0a588) Fix linter warning
 * [0002f8db](https://github.com/argoproj/argo-workflows/commit/0002f8db9e9e96f2601ee4bd005864cd88e0ee50) Issue #75 - Implement delete pod API
 * [59ed50d2](https://github.com/argoproj/argo-workflows/commit/59ed50d230d86946ed8a1d881771f24897dba305) Issue #74 - Implement stream logs API
 * [820b4bac](https://github.com/argoproj/argo-workflows/commit/820b4bac1afc7ce5c42779c80fc36fbe5fbf9893) Remove obsolete pods api
 * [19c5ecdb](https://github.com/argoproj/argo-workflows/commit/19c5ecdbfabd83a83f2b83a34b0b66b984c5cfa8) Check app label on client side before deleting app resource
 * [66b0702c](https://github.com/argoproj/argo-workflows/commit/66b0702c2437421a414b72b29d1322ad49be7884) Issue #65 - Delete all the kube object once app is removed
 * [5b5dc0ef](https://github.com/argoproj/argo-workflows/commit/5b5dc0efc40637279d070cf5eb004a9378d25433) Issue #67 - Application controller should persist ksonnet app parameters in app CRD (#73)
 * [0febf051](https://github.com/argoproj/argo-workflows/commit/0febf0516005bbfd5de455d7a32c47b94bd1ca60) Issue #67 - Persist resources tree in application CRD (#68)
 * [ee924bda](https://github.com/argoproj/argo-workflows/commit/ee924bda6ecdc1076db564252d95d5b1e9a0f365) Update ksonnet binary in image to ks tip. Begin using ksonnet as library instead of parsing stdout
 * [ecfe571e](https://github.com/argoproj/argo-workflows/commit/ecfe571e758228f8e63c98c9d529941be31a0a20) update ksonnet dependency to tip. override some of ksonnet's dependencies
 * [173ecd93](https://github.com/argoproj/argo-workflows/commit/173ecd9397a6a91c85931675874b0a9550be1346) Installer and settings management refactoring:
 * [ba3db35b](https://github.com/argoproj/argo-workflows/commit/ba3db35ba08e8b1c625c94107023f3c15235636a) Add authentication endpoints (#61)
 * [074053da](https://github.com/argoproj/argo-workflows/commit/074053dac77c67913a33f1cc894beccb9cc0553d) Update go-grpc-middleware version (#62)
 * [6bc98f91](https://github.com/argoproj/argo-workflows/commit/6bc98f91b146ab56cd9cbdd66d756cb281730c59) Add JWT support (#60)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Jesse Suen

## v0.2.0 (2018-03-28)

 * [59dbe8d7](https://github.com/argoproj/argo-workflows/commit/59dbe8d7eace6f9b82fda59a0590f0f3e24cc514) Maintain list of recent deployments in app CRD (#59)
 * [6d793617](https://github.com/argoproj/argo-workflows/commit/6d793617399a2b1abed8e6cb561115f9311eafae) Issue #57 - Add configmaps into argocd server role (#58)
 * [e1c7f9d6](https://github.com/argoproj/argo-workflows/commit/e1c7f9d6f86f4a489c79e921f38f15ba02de6472) Fix deleting resources which do not support 'deletecollection' method but support 'delete' (#56)
 * [5febea22](https://github.com/argoproj/argo-workflows/commit/5febea22354eb8b6b56e22096a3cddefcded34ad) Argo server should not fail if configmap name is not provided or config map does not exist (#55)
 * [d093c8c3](https://github.com/argoproj/argo-workflows/commit/d093c8c3a17d51a83514c7a355239409409d1e78) Add password hashing (#51)
 * [10a8d521](https://github.com/argoproj/argo-workflows/commit/10a8d521ef5b21ee139128dad33e0ad160cc56fd) Add application source and component parameters into recentDeployment field of application CRD (#53)
 * [234ace17](https://github.com/argoproj/argo-workflows/commit/234ace173ed1b8de4ca1010e9b583cdb5ce6bf40) Replace ephemeral environments with override parameters (#52)
 * [817b13cc](https://github.com/argoproj/argo-workflows/commit/817b13ccbed93f41a851d2dd71040e2e2bc975a0) Add license and copyright. #49
 * [b1682cc4](https://github.com/argoproj/argo-workflows/commit/b1682cc44be8069642d7d0a0edab0137e69a15c7) Add install configmap override flag (#47)
 * [74797a2a](https://github.com/argoproj/argo-workflows/commit/74797a2ac80ca0375a02c4a8b38a972bfa19c9f2) Delete child dependents while deleting app resources (#48)
 * [ca570c7a](https://github.com/argoproj/argo-workflows/commit/ca570c7aeeb70df1c7d4ec75b1571038142ef714) Use ksonnet release version and fix app copy command (#46)
 * [92b7c6b5](https://github.com/argoproj/argo-workflows/commit/92b7c6b5f8773f1504f12245d5f77854621d2c2c) Disable strict host key checking while cloning repo in repo-server (#45)
 * [4884c20d](https://github.com/argoproj/argo-workflows/commit/4884c20d2bfaaf65c5e6a222d22fb684c9f72788) Issue #43 - Don't setup RBAC resources for clusters with basic authentication (#44)
 * [363b9b35](https://github.com/argoproj/argo-workflows/commit/363b9b352c1de1e6a84d516e6812ed6fdac3f013) Don't overwrite application status in tryRefreshAppStatus (#42)
 * [5c062bd3](https://github.com/argoproj/argo-workflows/commit/5c062bd3e51bab46979040c79795c4872c2c0d2f) Support deploying/destroying ephemeral environments (#40)
 * [98754c7f](https://github.com/argoproj/argo-workflows/commit/98754c7fe1cbfc2f39890c976949d1540af75d9c) Persist parameters during deployment (Sync) (#39)
 * [3927cc07](https://github.com/argoproj/argo-workflows/commit/3927cc0799456518f889dd9c53a40a2c746d546e) Add new dependency to CONTRIBUTING.md (#38)
 * [611b0e48](https://github.com/argoproj/argo-workflows/commit/611b0e48d7be40f6cb1b30d3e3da180a443e872f) Issue #34 - Support ssh git URLs and ssh key authentication (#37)
 * [0368c2ea](https://github.com/argoproj/argo-workflows/commit/0368c2eadfe34a979973e0b40b6cb4c288e55f38) Allow use of public repos without prior registration (#36)
 * [e7e3c509](https://github.com/argoproj/argo-workflows/commit/e7e3c5095c0a1b4312993a234aceb0b90d69f90e) Support -f/--file flag in `argocd app add` (#35)
 * [d256256d](https://github.com/argoproj/argo-workflows/commit/d256256defbf6dcc733424df9374a2dc32069875) Update CONTRIBUTING.md (#32)

### Contributors

 * Alexander Matyushentsev
 * Andrew Merenbach
 * Edward Lee

