mutt-sidebar-patches-jplenz
===========================

Julius plenz's excellent cleanup and rework of the sidebar patches (kudos
Julius!).  

See <http://blog.plenz.com/2012-01/mutt-sidebar-patch-improvements.html> for the
complete story.

The consolidated patch available here is an amalgam of 20 distinct patches that
Julius wrote which essentially make sidebar performant and usable. An
additional patch from me fixes a build squiggle with homebrew. 

Why this consolidated patch ? Well, it's for homebrew primarily.

The commit logs from the patch series is as under:

01. applying debian/patches/mutt-patched/multiple-fcc
02. applying debian/patches/mutt-patched/sidebar
03. applying debian/patches/mutt-patched/sidebar-dotted
04. applying debian/patches/mutt-patched/sidebar-sorted
05. Fix sidebar compilation errors on IRIX systems
06. Fix counting of flagged mails in mboxes
07. Fix various sidebar drawing issues
08. Fix setting CurrBuffy when invoking mutt via -f
09. cache time when sidebar last counted all the mails
10. only count mail if sidebar is active
11. buffy: check msg_unread if sidebar is active
12. fix sidebar and buffy updates
13. introduce sidebar_format option
14. introduce sidebar_folderindent option
15. keep buffer-like temp file in memory
16. Bugfix: use realpath() on initial folder
17. Sidebar: Copy numbers before leaving mailbox
18. Fix Buffy/Sidebar and mail_check_recent issues
19. Copy number of flagged messages when leaving mbox
20. use-PATH_MAX-instead-of-_POSIX_PATH_MAX-when-realpat
21. remove-outdated-am_c_prototypes_from_configure

All credit for these patches goes to Julius alone.

Robin
