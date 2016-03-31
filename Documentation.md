# Documentation #

DX.Library contains the following units:

  * DX.Apple.Utils (Various helper functions)
  * DX.Types.GeoLocation (Provides a TGeoLocation datatype that maps to MS SQL Server's Geography type)
  * DX.Types.Nullable (Provides a Nullable type for Delphi. Credits: Stefan Glienke )


Note: REST support has been removed until further notice!

More docs and samples will follow.

# DX.Apple.Utils #
  * procedure NSLog2(const AMessage: string); - Logs to the device console. Directly maps to NSLog() of iOS / MacOSX
  * function VendorIdentifier: string; - Retrieves the vendor specific device ID
  * function CanOpenURL(AURL: string): boolean; - checks if a given scheme URL can be opened with its associated App