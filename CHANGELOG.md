# Change Log

All notable changes to the "crates" extension will be documented in this file.

## 0.4.5

- Github basic authentication support for increasing api rates 5000req/h [#60](https://github.com/serayuzgur/crates/issues/60)

## 0.4.4

- Dependencies updated.
- Certain version numbers cause fetch errors. [#37](https://github.com/serayuzgur/crates/issues/37)
- Buggy rendering for parameterized dependencies [#52](https://github.com/serayuzgur/crates/issues/52)
- ^ versions handled incorrectly [#39](https://github.com/serayuzgur/crates/issues/39)
- Splitting vscode package into @types/vscode and vscode-test [#57](https://github.com/serayuzgur/crates/issues/57)
- Uppercase key seems to be causing an error [#56](https://github.com/serayuzgur/crates/issues/56)

## 0.4.3

- Dependencies updated.
- Number parsing fixed [#50](https://github.com/serayuzgur/crates/issues/50)
- PR [#48](https://github.com/serayuzgur/crates/pull/48) merged. Thanks to [@RensAlthuis](https://github.com/RensAlthuis)

## 0.4.2

- Sorting is now uses version compare. [#45](https://github.com/serayuzgur/crates/issues/45) Thanks to [kupiakos](https://github.com/kupiakos)
- Yanked versions fixed. [#44](https://github.com/serayuzgur/crates/issues/44)

## 0.4.1

- Sorting of the versions fixed. [#43](https://github.com/serayuzgur/crates/issues/43)

## 0.4.0

- All fetches will be done from github api to crates.io-index repository. [#42](https://github.com/serayuzgur/crates/issues/42)
- Dependencies updated.
- Quoted dependency names are supported now. [#40](https://github.com/serayuzgur/crates/issues/40)

## 0.3.7

- Fetch errors for crates with package alias. [#38](https://github.com/serayuzgur/crates/issues/38)

## 0.3.6

- Fetch errors for crate from git link and version. [#36](https://github.com/serayuzgur/crates/issues/36)

## 0.3.5

- User-Agent header added on crates.io requests. [#31](https://github.com/serayuzgur/crates/issues/31)

## 0.3.4

- A bug which caused loop on parsing fixed. [#29](https://github.com/serayuzgur/crates/issues/29)
- Version confuse after inline table version fixed. [#30](https://github.com/serayuzgur/crates/issues/30)

## 0.3.3

- Confuse on table dependencies with boolean attributes fixed. [#28](https://github.com/serayuzgur/crates/issues/28)

## 0.3.2

- Spacing issues with inline dependencies. [#26](https://github.com/serayuzgur/crates/issues/26).
- New settings: crates.latestDecorator. For changing latest version decoration. [#27](https://github.com/serayuzgur/crates/issues/27)

## 0.3.1

- Dependencies updated.
- Command descriptions are better now.
- Emojis added for critical status messages.
- **Update All** command added.
- Some small performance improvements.
- Better README with more gifs :D
- New icon. (Wow, this really changes everything!)

## 0.3.0

- This is the most complete release so far.
- Retry command added for reloading versions.
- RegExps removed and migrated to a custom parser. [#17](https://github.com/serayuzgur/crates/issues/17)
- Additional depencency case added for the test. [#22](https://github.com/serayuzgur/crates/issues/22)
- All failed fetchs will be reported via status mesage and notification with a _retry_ command. [#23](https://github.com/serayuzgur/crates/issues/23)
- A bug at caching fixed.
- Thanks to [@userzimmermann](https://github.com/userzimmermann) for this release.

## 0.2.4

- Regexp bug fixed by [@userzimmermann](https://github.com/userzimmermann)

## 0.2.3

- Extension listener is back to onchange but with a dirty control. [#15](https://github.com/serayuzgur/crates/issues/15)
- Out of line dependencies supported. [#8](https://github.com/serayuzgur/crates/issues/8)
- No dependency case handled by [@userzimmermann](https://github.com/userzimmermann)

## 0.2.2

- "-" is the controlidentifier for pre-release check.
- crates now decorates the toml file on each save. Not on every change.
- Invalid toml files caused a glitch on version decorations. Now all will be cleared with a toolbar and error message. Also commented sections handled correctly. [#9](https://github.com/serayuzgur/crates/issues/9)

### 0.2.1

- Patreon link changed to a badge.
- Marketplace badges are linked to marketplace. [#13](https://github.com/serayuzgur/crates/issues/13).
- Package json improved.
- The up to date decorator (👍) is now customizable from setting crates.upToDateDecorator [#12](https://github.com/serayuzgur/crates/issues/12).
- Listing pre-releases is now customizable from setting crates.listPreReleases [#10](https://github.com/serayuzgur/crates/issues/10).

### 0.2.0

- Version resolution support improved [#6](https://github.com/serayuzgur/crates/issues/6).
- Yanked versions removed from the version list [#7](https://github.com/serayuzgur/crates/issues/7).

### 0.1.1

- build-dependencies support.
- dev-dependencies support.

### 0.1.0

- Dependencies updated.
- Readme Updated.
- Version updated due to increased stability.

### 0.0.12

- Version List error fixed [#4](https://github.com/serayuzgur/crates/issues/4).

### 0.0.11

- Null control fix for "target". Thanks to [braunse](https://github.com/braunse).

### 0.0.10

- Complex Cargo.toml error fixed. [#1](https://github.com/serayuzgur/crates/issues/1)
- Support for target dependencies. (not all usage cases)
- Re-decorates on edit. (It was on save before)

### 0.0.9

- Version list (hover) is clickable now. Easier to navigate between versions.

### 0.0.8

- Better activation event. Listens for "Cargo.toml" as a rool level file.
- Refreshes after each save.
- fetch caching for performance

### 0.0.7

- If latest version is same with the current, a nice 👍 for you. No more unnecessary info.
- Hover tooltip is more readable now.
- Better gif at readme

### 0.0.6

- Activates on rust or toml.
- Only listens for Cargo.toml file

### 0.0.5

- Last version bug fixed

### 0.0.4

- travis integration
- gif resized
- readme edited
- badges added for marketplace and travis.
- parsing fixed for

### 0.0.3

- Console errors fixed.

### 0.0.2

- Logo added

### 0.0.1

- The first release, an alpha.
