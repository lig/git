* [Documentation/gitprotocol-http.txt:366](Documentation/gitprotocol-http.txt#L366): Document this further.
* [Documentation/gitprotocol-http.txt:443](Documentation/gitprotocol-http.txt#L443): Define error if no "want" lines are requested.
* [Documentation/gitprotocol-http.txt:446](Documentation/gitprotocol-http.txt#L446): Define error if an invalid "want" is requested.
* [Documentation/gitprotocol-http.txt:462](Documentation/gitprotocol-http.txt#L462): Document the pack based response
* [Documentation/gitprotocol-http.txt:476](Documentation/gitprotocol-http.txt#L476): Document the non-pack response
* [Documentation/gitprotocol-http.txt:479](Documentation/gitprotocol-http.txt#L479): Document parsing response
* [Documentation/gitprotocol-http.txt:527](Documentation/gitprotocol-http.txt#L527): Document this further.
* [builtin/commit.c:1018](builtin/commit.c#L1018): audit for interaction with sparse-index. */
* [builtin/commit.c:270](builtin/commit.c#L270): audit for interaction with sparse-index. */
* [builtin/difftool.c:594](builtin/difftool.c#L594): audit for interaction with sparse-index. */
* [builtin/fsck.c:825](builtin/fsck.c#L825): audit for interaction with sparse-index. */
* [builtin/ls-remote.c:98](builtin/ls-remote.c#L98): This is buggy, but required for transport helpers. When a
* [builtin/merge-index.c:100](builtin/merge-index.c#L100): audit for interaction with sparse-index. */
* [builtin/merge-index.c:68](builtin/merge-index.c#L68): audit for interaction with sparse-index. */
* [builtin/replay.c:338](builtin/replay.c#L338): In the future we might want to either die(), or allow
* [builtin/show-branch.c:37](builtin/show-branch.c#L37): convert this use of commit->object.flags to commit-slab
* [builtin/show-index.c:46](builtin/show-index.c#L46): Figure out and implement a way to detect the hash algorithm in use by the
* [builtin/stash.c:1562](builtin/stash.c#L1562): audit for interaction with sparse-index. */
* [builtin/submodule--helper.c:2761](builtin/submodule--helper.c#L2761): allow exempting it via
* [builtin/submodule--helper.c:3402](builtin/submodule--helper.c#L3402): audit for interaction with sparse-index. */
* [bundle.c:260](bundle.c#L260): preserve this verbose language. */
* [compat/mingw.c:2322](compat/mingw.c#L2322): translate more errors */
* [compat/regex/regexec.c:2434](compat/regex/regexec.c#L2434): This isn't efficient.
* [compat/regex/regexec.c:2854](compat/regex/regexec.c#L2854): This function isn't efficient...
* [compat/regex/regexec.c:3039](compat/regex/regexec.c#L3039): This function is similar to the functions transit_state*(),
* [compat/regex/regexec.c:3267](compat/regex/regexec.c#L3267): It is still inefficient...  */
* [contrib/credential/netrc/git-credential-netrc.perl:51](contrib/credential/netrc/git-credential-netrc.perl#L51): maybe allow the token map $options{tmap} to be configurable.
* [contrib/mw-to-git/git-remote-mediawiki.perl:1250](contrib/mw-to-git/git-remote-mediawiki.perl#L1250): we could detect rename, and encode them with a #redirect on the wiki.
* [contrib/mw-to-git/git-remote-mediawiki.perl:1251](contrib/mw-to-git/git-remote-mediawiki.perl#L1251): for now, it's just a delete+add
* [contrib/mw-to-git/git-remote-mediawiki.perl:822](contrib/mw-to-git/git-remote-mediawiki.perl#L822): why?
* [diffcore-rename.c:849](diffcore-rename.c#L849): The following loops mirror the code/logic from
* [dir.c:4026](dir.c#L4026): audit for interaction with sparse-index. */
* [entry.c:454](entry.c#L454): audit for interaction with sparse-index. */
* [environment.h:108](environment.h#L108): All the below state either explicitly or implicitly relies on
* [git-archimport.perl:474](git-archimport.perl#L474): handle removed_directories and renamed_directories:
* [git-cvsexportcommit.perl:299](git-cvsexportcommit.perl#L299): we need to handle removed in cvs
* [git-cvsserver.perl:1122](git-cvsserver.perl#L1122): Convert -D value into the form 2011.04.10.04.46.57,
* [git-cvsserver.perl:1312](git-cvsserver.perl#L1312): If it has been modified in the sandbox, error out
* [git-cvsserver.perl:2152](git-cvsserver.perl#L2152): Use --label instead of -L because -L is no longer
* [git-cvsserver.perl:2159](git-cvsserver.perl#L2159): Real CVS seems to include a date in the label, before
* [git-cvsserver.perl:2329](git-cvsserver.perl#L2329): if we got a revision from the client, use that instead
* [git-cvsserver.perl:2764](git-cvsserver.perl#L2764): Convert -D value into the form 2011.04.10.04.46.57,
* [git-cvsserver.perl:2808](git-cvsserver.perl#L2808): When/if we actually pick versions by {date} properly,
* [git-cvsserver.perl:3861](git-cvsserver.perl#L3861): log processing is memory bound
* [git-cvsserver.perl:4513](git-cvsserver.perl#L4513): date, state, or by specific logins filters?
* [git-cvsserver.perl:4514](git-cvsserver.perl#L4514): Handle comma-separated list of revFilter items, each item
* [git-cvsserver.perl:4517](git-cvsserver.perl#L4517): Adjust $db_query WHERE clause based on revFilter, instead of
* [git-cvsserver.perl:4561](git-cvsserver.perl#L4561): Also allow it to
* [git-cvsserver.perl:4635](git-cvsserver.perl#L4635): Rework database somehow to make up and remember
* [git-cvsserver.perl:4738](git-cvsserver.perl#L4738): Possible optimization strategies:
* [git-cvsserver.perl:4765](git-cvsserver.perl#L4765): Include file hash in dirmap cache.
* [git-cvsserver.perl:5036](git-cvsserver.perl#L5036): Perhaps use git check-ref-format, with an in-process cache of
* [git-filter-branch.sh:539](git-filter-branch.sh#L539): This should possibly go, with the semantics that all positive given
* [git-gui/git-gui.sh:910](git-gui/git-gui.sh#L910): this option should be added to the git-config documentation
* [git-p4.py:4071](git-p4.py#L4071): should always look at previous commits,
* [git-p4.py:4324](git-p4.py#L4324): use common prefix of args?
* [git-send-email.perl:1422](git-send-email.perl#L1422): Authentication may fail not because credentials were
* [git-svn.perl:1417](git-svn.perl#L1417): handle combining properties better
* [git-svn.perl:1437](git-svn.perl#L1437): don't simply append here if $file already has svn-properties
* [git-svn.perl:1870](git-svn.perl#L1870): set *:merge properties or like...
* [gitweb/gitweb.perl:6657](gitweb/gitweb.perl#L6657): Allow a readme in some safe format.
* [grep.c:1534](grep.c#L1534): allowing text conversion to run in parallel with object
* [khash.h:184](khash.h#L184): to implement automatically shrinking; resize() already support shrinking */ \
* [merge-ort.c:2977](merge-ort.c#L2977): For renames we normally remove the path at the
* [merge-recursive.c:2798](merge-recursive.c#L2798): refactor, so that 1/2 are not needed */
* [merge-recursive.c:541](merge-recursive.c#L541): audit for interaction with sparse-index. */
* [midx.c:967](midx.c#L967): Measure QSORT() progress */
* [notes-merge.c:627](notes-merge.c#L627): How to handle multiple merge-bases? */
* [object-store-ll.h:438](object-store-ll.h#L438): oid_object_info_extended()'s call stack has a recursive behavior. If
* [object.h:14](object.h#L14): migrate alloc_states to mem-pool? */
* [oidmap.c:30](oidmap.c#L30): make oidmap itself not depend on struct layouts */
* [oidmap.h:81](oidmap.h#L81): this API could be reworked to do compile-time type checks */
* [oidmap.h:89](oidmap.h#L89): this API could be reworked to do compile-time type checks */
* [perl/Git.pm:89](perl/Git.pm#L89): In the future, we might also do
* [perl/Git.pm:918](perl/Git.pm#L918): Support for passing FILEHANDLE instead of FILENAME
* [perl/Git.pm:934](perl/Git.pm#L934): Support for passing FILEHANDLE instead of FILENAME
* [perl/Git/SVN.pm:2272](perl/Git/SVN.pm#L2272): move this to Git.pm?
* [perl/Git/SVN/Editor.pm:303](perl/Git/SVN/Editor.pm#L303): get existing properties to compare to
* [perl/Git/SVN/Editor.pm:307](perl/Git/SVN/Editor.pm#L307): caching svn properties or storing them in .gitattributes
* [perl/Git/SVN/Log.pm:32](perl/Git/SVN/Log.pm#L32): make $c->{l} not have a trailing newline in the future
* [read-cache.c:2277](read-cache.c#L2277): does creating more threads than cores help? */
* [read-cache.c:2557](read-cache.c#L2557): audit for interaction with sparse-index. */
* [read-cache.c:3835](read-cache.c#L3835): audit for interaction with sparse-index. */
* [refs.c:2955](refs.c#L2955): we should really be passing the caller-provided repository to
* [refs/files-backend.c:2998](refs/files-backend.c#L2998): currently we skip creating reflogs for dangling
* [refs/reftable-backend.c:1120](refs/reftable-backend.c#L1120): it's dubious whether we should reload the stack that "HEAD"
* [refs/reftable-backend.c:1512](refs/reftable-backend.c#L1512): currently we skip creating reflogs for dangling
* [refs/reftable-backend.c:2144](refs/reftable-backend.c#L2144): we should adapt this callsite to reload the stack. There is no
* [refs/reftable-backend.c:2193](refs/reftable-backend.c#L2193): we should adapt this callsite to reload the stack. There is no
* [reftable/writer.c:320](reftable/writer.c#L320): it would be great to have `block_writer_add()` return proper
* [resolve-undo.c:163](resolve-undo.c#L163): audit for interaction with sparse-index. */
* [revision.c:1837](revision.c#L1837): audit for interaction with sparse-index. */
* [sequencer.c:4327](sequencer.c#L4327): Should use merge_incore_recursive() and
* [sequencer.c:790](sequencer.c#L790): merge_switch_to_result will update index/working tree;
* [shallow.c:125](shallow.c#L125): use "int" elemtype instead of "int *" when/if commit-slab
* [submodule.c:2127](submodule.c#L2127): determine if this might overwright untracked files */
* [submodule.c:706](submodule.c#L706): other options may need to be passed here. */
* [t/t0200-gettext-basic.sh:42](t/t0200-gettext-basic.sh#L42): When we have more locales, generalize this to test them
* [t/t0450-txt-doc-vs-help.sh:157](t/t0450-txt-doc-vs-help.sh#L157): $builtin ===" &&
* [t/t1800-hook.sh:163](t/t1800-hook.sh#L163): We should emit the same (or at least a more similar)
* [t/t4107-apply-ignore-whitespace.sh:66](t/t4107-apply-ignore-whitespace.sh#L66): this testcase should be
* [t/t5750-bundle-uri-parse.sh:75](t/t5750-bundle-uri-parse.sh#L75): We would prefer if parsing a bundle list would not cause
* [t/t6404-recursive-merge.sh:90](t/t6404-recursive-merge.sh#L90): fragile test, relies on ambiguous merge-base resolution
* [t/t9402-git-cvsserver-refs.sh:510](t/t9402-git-cvsserver-refs.sh#L510): Validate that the .# file was saved properly, and then
* [t/t9402-git-cvsserver-refs.sh:532](t/t9402-git-cvsserver-refs.sh#L532): test cvs status
* [t/unit-tests/test-lib.c:106](t/unit-tests/test-lib.c#L106): handle newlines */
* [t/unit-tests/test-lib.c:399](t/unit-tests/test-lib.c#L399): improve handling of \a, \b, \f ... */
* [templates/hooks/sendemail-validate.sample:27](templates/hooks/sendemail-validate.sample#L27): Replace with appropriate checks (e.g. spell checking).
* [templates/hooks/sendemail-validate.sample:35](templates/hooks/sendemail-validate.sample#L35): Replace with appropriate checks for this patch
* [templates/hooks/sendemail-validate.sample:41](templates/hooks/sendemail-validate.sample#L41): Replace with appropriate checks for the whole series
* [unpack-trees.c:2285](unpack-trees.c#L2285): We should actually invalidate o->internal.result, not src_index [1].
* [utf8.c:230](utf8.c#L230): fix the interface of this function and `utf8_strwidth()` to
