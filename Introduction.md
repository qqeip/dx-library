# Documentation #

DX.Library contains the following units:

  * DX.Apple.Utils (various helper functions)
**DX.Rest.Client (an abstract REST Client)** DX.Types.GeoLocation (GeoLocation datatype that maps to MS SQL Server's Geography type)
**DX.Types.Nullable (A Nullable type for Delphi. Credits: Stefan Glienke )** DX.Utils.Json (a helper unit for JSON processing with DBXJson)


More docs and samples will follow.

# DX.Apple.Utils #
  * procedure NSLog2(const AMessage: string); - Logs to the device console. Directly maps to NSLog() of iOS / MacOSX
  * function VendorIdentifier: string; - Retrieves the vendor specific device ID
  * function CanOpenURL(AURL: string): boolean; - checks if a given scheme URL can be opened with its associated App