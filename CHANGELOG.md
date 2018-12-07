CHANGELOG for 4.0.x
===================

This changelog references the relevant changes (bug and security fixes) done
in 4.0 minor versions.

To get the diff for a specific change, go to https://github.com/symfony/symfony/commit/XXX where XXX is the change hash
To get the diff between two versions, go to https://github.com/symfony/symfony/compare/v4.0.0...v4.0.1

* 4.0.14 (2018-08-01)

 * security #cve-2018-14774 [HttpKernel] fix trusted headers management in HttpCache and InlineFragmentRenderer (nicolas-grekas)
 * security #cve-2018-14773 [HttpFoundation] Remove support for legacy and risky HTTP headers (nicolas-grekas)
 * bug #28003 [HttpKernel] Fixes invalid REMOTE_ADDR in inline subrequest when configuring trusted proxy with subnet (netiul)
 * bug #28007 [FrameworkBundle] fixed guard event names for transitions (destillat)
 * bug #28045 [HttpFoundation] Fix Cookie::isCleared (ro0NL)
 * bug #28080 [HttpFoundation] fixed using _method parameter with invalid type (Phobetor)
 * bug #28052 [HttpKernel] Fix merging bindings for controllers' locators (nicolas-grekas)
