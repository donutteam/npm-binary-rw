# Changelog
## 2.0.0

* Rewrote the `BinaryReader` class to use a DataView.
* Rewrote the `BinaryWriter` class to use a DataView.
* Removed the `BitConverter` class.
* Removed the `UInt64` class. This library now uses the native `BigInt` type.
* Removed the `padString` function.
* Removed the `shuffle` function.

## 1.3.0

* Renamed BinaryReader.readDouble to BinaryReader.readFloat64.
	* The old name is still available for backwards compatibility but is deprecated.

## 1.2.0

* Renamed BinaryReader.readFloat to BinaryReader.readFloat32.
	* The old name is still available for backwards compatibility but is deprecated.
* Added BinaryWriter.writeFloat32.
* Added BinaryWriter.writeFloat64.

## 1.1.0
Made `BinaryWriter.writeBytes` support taking an `ArrayBuffer`.

## 1.0.1
Fixed a mistake that caused the initial version to not actually contain the compiled JavaScript.

## 1.0.0
Initial release.