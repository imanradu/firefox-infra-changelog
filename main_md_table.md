###  Last commits from every repository
|      Repository      |                   Last commit               |    Deploy time       | 
|:--------------------:|:-------------------------------------------:|:--------------------:| 
|[autoland](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/autoland.md)|Bug 1499465 - Don't collect KillHard crashes on Beta or Release. r=jld,gsvelto  Differential Revision: https://phabricator.services.mozilla.com/D10968|2018-11-20 23:34:36|
|[beta](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/beta.md)|No bug - Tagging 571a146f0732aeab505743a97ad176e5d7e673dc with DEVEDITION_64_0b11_RELEASE a=release CLOSED TREE DONTBUILD|2018-11-20 17:25:33|
|[braindump](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/braindump.md)|add params-required-signoffs for bug 1501878|2018-11-12 21:19:42|
|[ci-admin](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/ci-admin.md)|Bug 1492665 - add support for environments.yml r=Callek,bstack  Differential Revision: https://phabricator.services.mozilla.com/D6932|2018-10-22 20:52:13|
|[ci-configuration](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/ci-configuration.md)|Bug 1503894 - disable taskcluster-cron for comm-central repos r=tomprince  The cron hook expects that it is checking out a gecko tree.  Robustcheckout kind of loses its mind when it clones mozilla-unified, then finds no ancestor in common with a comm-central pull.  Differential Revision: https://phabricator.services.mozilla.com/D10595|2018-11-01 20:52:02|
|[comm-esr60](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/comm-esr60.md)|Backed out changeset c597411fe241 for accidentally landing with DONTBUILD. a=jorgk|2018-11-20 14:47:36|
|[inbound](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/inbound.md)|Bug 1508399 - Use dom.ipc.processCount to determine how many tabs to open. r=bc|2018-11-20 01:24:20|
|[mozilla-build](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/mozilla-build.md)|Bug 1501403 - Update UPX to version 3.95.|2018-10-23 22:08:31|
|[mozilla-central](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/mozilla-central.md)|Bug 1507680 - Record detailed statistics about slow WebRender frames in about:support. r=jrmuizel  MozReview-Commit-ID: 84SjN1RvvAA  Differential Revision: https://phabricator.services.mozilla.com/D12372|2018-11-16 04:13:56|
|[mozilla-esr60](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/mozilla-esr60.md)|Bug 1445943 - Add Enterprise Policy support for macOS to ESR. This includes patches in bug 1445943, bug 1497408, bug 1497948, bug 1498032. r=mstange,felipe,glandium,spohl, a=lizzard|2018-11-20 09:48:00|
|[mozilla-release](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/mozilla-release.md)|Automatic version bump CLOSED TREE NO BUG a=release|2018-11-16 00:24:12|
|[try](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/hg_files/try.md)|[mq]: assertion|2018-11-21 04:01:05|
|[addonscript](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/addonscript.md)|Merge pull request #185 from Callek/pyup_schedule  Run pyup on a schedule|2018-11-20 18:45:45|
|[build-puppet](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/build-puppet.md)|Merge pull request #298 from mozilla-releng/dlabici-backout  BUG: 1507497 - Downgrade Cryptography back to 2.3.1|2018-11-15 15:12:06|
|[mozapkpublisher](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/mozapkpublisher.md)|Scheduled weekly dependency update for week 45 (#134)    Update coverage from 4.5.1 to 4.5.2    Update requests from 2.20.0 to 2.20.1    Update cryptography from 2.3.1 to 2.4.1    Update google-auth from 1.5.1 to 1.6.1    Update httplib2 from 0.11.3 to 0.12.0    Update matplotlib from 3.0.1 to 3.0.2    Update mozilla-version from 0.3.0 to 0.3.1    Update pytest from 3.10.0 to 3.10.1|2018-11-19 12:54:00|
|[OpenCloudConfig](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/OpenCloudConfig.md)|Bug 1406354 - support deployment of beta workers from beta branch|2018-11-20 08:40:12|
|[services](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/services.md)|staticanalysis/bot: Filter clang-format publishable issues by their path. (#1689)|2018-11-20 15:36:16|
|[ship-it](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/ship-it.md)|Bug 1508140 - Add 'trs' to product-details (#243)|2018-11-19 02:14:35|
|[treescript](https://github.com/Akhliskun/firefox-infra-changelog/blob/master/git_files/treescript.md)|Merge pull request #149 from Callek/pip-compile-multi  Pip compile multi|2018-11-20 13:42:22|