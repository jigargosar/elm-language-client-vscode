# Change Log

## 0.4.1

- Revert determination of used elm compiler version, as it was causing file open to go unnoticed

## 0.4.0

- Updated the language server
	- Use WASM version of tree-sitter and updated tree-sitter - This mean multiple parsing improvements
	- Added completions for methods defined in a let scope
	- Added completions from case branches
	- Added code actions for some rename suggestions from elm make
	- Removed the ability to run elm-test for now, as it was problematic
	- Determine the used elm version, so that we're ready for 0.19.1
	- Cleaned up the symbols that we show in the outline or when searching
	- Fixed multiple problems with multi workspace useage
	- Fixed type references including (..) on search or rename
	- Fixed elm make not reporting the correct path in some edgecases
- Don't reveal the output channel on each log
- Better names for output channels in multi workspace projects

## 0.3.0

- Initial release
