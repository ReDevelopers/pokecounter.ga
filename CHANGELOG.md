# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
- Need to add working keyboard shortcuts.
- Move donate.html into modal instead.
- Implement Night Mode without breaking anything? lol
- Add more mobile (Bootstrap) functionality.
- Maybe add a dismissible modal/message when counterValue === 255 as a warning?
- Make reset button reset counter and not refresh page.
- Make default chain number 0 through JS.
- Make counter not drop below 0 (Why do we even need negatives? TIME TRAVEL?!)
- Remove MAX_SAFE_INTEGER and MIN_SAFE_INTEGER because they are not currently being used properly.
- Need to add Shiny Charm odds vs full odds option.

## [0.0.3] - 2017-12-04

### Added
- Boostrap ahoy!
- Bigger buttons!
- A nav menu?!

### Changed
- Moved more.html into a modal instead.
- Nightmode is triggered via JavaScript instead of redirecting to it's own page.
- Changed divs to use bootstrap classes.

### Removed
- Pokesprite mumbo jumbo.
- Unnecessary JS files/references.
- Crazy CSS classes and divs.

## [0.0.2?] - 2017-12-03
### Added
- Added a changelog, doh!
- Missing semicolons ??? ??? (I cri eritim)

### Changed
- First round of refactoring.
- Added some DRY into the mix.
- Replaced getMessageFor if/elseif conditionals and used cases instead (much cleaner!).
- Added more seasoning.
- Moved footer into body because HTML5 standards.
- Put JQuery before Bootstrap because das wat do.
- Action URL's relative for cloning and local dev purposes.

### Removed
- Removed unused variables.
