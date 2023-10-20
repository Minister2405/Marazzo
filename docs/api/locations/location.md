# Location

The Location interface is a union of the ways to refer to a specific location in a Slate document: paths, points or ranges. Methods will often accept a Location instead of requiring only a Path, Point or Range.

```typescript
type Location = Path | Point | Range
```

- [Static methods](location.md#static-methods)
  - [Check methods](location.md#check-methods)

## Static methods

### Check methods

#### `Location.isLocation(value: any): value is Location`

Check if a value implements the `Location` interface.
This is for testing purpose to see whether if the sync is working
Testing 123
Testing 23455
Testing ZDfsdgfsgg
