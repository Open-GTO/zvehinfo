# zvehinfo
Vehicle information functions.

# Functions
#### Get vehicle model type
```Pawn
GetVehicleModelType(model)
```

#### Get vehicle type
```Pawn
GetVehicleType(vehicleid)
```

#### Get vehicle model category
```Pawn
GetVehicleModelCategory(model)
```

#### Get vehicle category
```Pawn
GetVehicleCategory(vehicleid)
```

#### Get vehicle model max velocity
```Pawn
GetVehicleModelMaxVelocity(model)
```

#### Get vehicle max velocity
```Pawn
GetVehicleMaxVelocity(vehicleid)
```

#### Get vehicle model name
```Pawn
GetVehicleModelName(model, name[], size = sizeof(name))
```

#### Get vehicle name
```Pawn
GetVehicleName(vehicleid, name[], size = sizeof(name))
```

# Usage

```Pawn
if (GetVehicleCategory(vehicleid) == VEHICLE_CATEGORY_SPORT && GetVehicleType(vehicleid) == VEHICLE_TYPE_CAR) {
	SendClientMessage(playerid, -1, "You should be in sport car!");
	return 1;
}
```
