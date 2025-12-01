# CHANGELOG

## [1.0.1] – 2025-12-01
### Added
- Disabled **“Add to group”** when the selected friend already has an assigned `#group`.
  Prevents duplicate group assignments and improves menu clarity.

### Improved
- Cleaned up menu-building logic for better MoP Classic compatibility.
- Minor internal consistency tweaks in the dropdown initialization.

---

## [1.0.0] – 2025-12-01
### Initial Release
- Introduced **SocialPlus / FriendsGrouping** addon.
- Added right-click friend menu extensions:
  - Create new group  
  - Assign to group  
  - Remove from group  
- Group assignment handled automatically via friend notes using `#GroupName`.
- Full support for Battle.net and WoW friends.
- Functional sorting, refreshing, and group-based separation in the friends list.
