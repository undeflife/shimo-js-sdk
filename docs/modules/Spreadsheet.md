[shimo-js-sdk](../README.md) / [Exports](../modules.md) / Spreadsheet

# Namespace: Spreadsheet

## Table of contents

### Interfaces

- [DepartmentPermission](../interfaces/Spreadsheet.DepartmentPermission.md)
- [Editor](../interfaces/Spreadsheet.Editor.md)
- [EventMap](../interfaces/Spreadsheet.EventMap.md)
- [Range](../interfaces/Spreadsheet.Range.md)
- [UserPermission](../interfaces/Spreadsheet.UserPermission.md)

### Type aliases

- [CellValue](Spreadsheet.md#cellvalue)
- [PermissionLevel](Spreadsheet.md#permissionlevel)

## Type aliases

### CellValue

Ƭ **CellValue**: `string` \| `number` \| `boolean` \| ``null``

单元格值类型

#### Defined in

[src/types/Spreadsheet.ts:61](https://github.com/shimohq/shimo-js-sdk/blob/8db8072/src/types/Spreadsheet.ts#L61)

___

### PermissionLevel

Ƭ **PermissionLevel**: ``0`` \| ``1`` \| ``2``

锁定权限等级
0 - 可编辑
1 - 只能查看
2 - 禁止查看

#### Defined in

[src/types/Spreadsheet.ts:21](https://github.com/shimohq/shimo-js-sdk/blob/8db8072/src/types/Spreadsheet.ts#L21)
