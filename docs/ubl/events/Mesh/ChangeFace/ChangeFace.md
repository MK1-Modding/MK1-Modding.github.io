# ChangeFace event
This event replaces the target character's face with the provided mesh.

![ChangeFace](changeface.png)

## Parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| **`Character Name`** | `FString` | The name of the character you are targeting |
| **`Skin Name` (Optional)** | `FString` | The name of the skin you are targeting |
| **`Palette Name` (Optional)** | `FString` | The name of the palette you are targeting |
| **`New Face`** | `FString` | The name of the new face mesh. A value of 'None' will completely remove the mesh. |

## Example usage
![Example](example.png)

!!! warning "Loading"
	Any new referenced face must be first loaded through the [LoadAssets](../../LoadAssets/LoadAssets.md) event!