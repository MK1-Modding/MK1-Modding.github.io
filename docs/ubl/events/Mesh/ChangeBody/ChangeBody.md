# ChangeBody event
This event replaces the target character's body with the provided mesh.

![ChangeBody](changebody.png)

## Parameters

| Parameter | Type | Description |
|-----------|------|-------------|
| **`Character Name`** | `FString` | The name of the character you are targeting |
| **`Skin Name` (Optional)** | `FString` | The name of the skin you are targeting |
| **`Palette Name` (Optional)** | `FString` | The name of the palette you are targeting |
| **`New Body`** | `FString` | The name of the new body mesh. A value of 'None' will completely remove the mesh. |

## Example usage
![Example](example.png)

!!! warning "Loading"
	Any new referenced body must be first loaded through the LoadAssets event!