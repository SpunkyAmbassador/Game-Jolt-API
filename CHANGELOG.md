# 1.2.0

### New
- Added [Scores API](https://gamejolt.com/game-api/doc/scores)

### Updated
- Some URL constructors (4615a8522edd30ca991e3fe09c4b121ba699e1e2)
- "Trophies - Fetch" command (5454da7fc503818c5349c8aa5e947a544645d8a9)

---

# 1.1.0

### New
- Added [Time](https://gamejolt.com/game-api/doc/time) feature in API.
- New `successVariableID` parameter to check the result of API call. `true` for success and `false` for unsuccess.

### Updated
- Response logic of any request came from Game Jolt server.

### Fixed
- `undefined` and `Signature Error` when sending request for fetching achieved, unachieved and selective trophies.

---

# 1.0.0 - Initial release of Game Jolt API
- This release includes addition and removal of trophies/achivements in your game
