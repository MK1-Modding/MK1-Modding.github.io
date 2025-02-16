# ChangeMoveset event
This event replaces the target character's moveset with the provided one.

![ChangeMoveset](changemoveset.png)

## Parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| **`Character Name`** | `FString` | The name of the character you are targeting |
| **`Skin Name` (Optional)** | `FString` | The name of the skin you are targeting |
| **`Palette Name` (Optional)** | `FString` | The name of the palette you are targeting |
| **`New Moveset`** | `FString` | The name of the new moveset asset |

## Example usage
![Example](example.png)

!!! warning "Loading"
	Any new referenced moveset must be first loaded through the LoadAssets event!
	
	Tip: Moveset assets are located in the "/Game/Disk/Shared/Game/GeneratedScripts/" folder