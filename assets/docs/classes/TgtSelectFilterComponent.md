[@target-lib/tgt-components](../README.md) / [Exports](../modules.md) / TgtSelectFilterComponent

# Class: TgtSelectFilterComponent<Type\>

## Type parameters

| Name |
| :------ |
| `Type` |

## Implements

- `OnChanges`
- `OnInit`
- `OnDestroy`

## Table of contents

### Constructors

- [constructor](TgtSelectFilterComponent.md#constructor)

### Properties

- [arrayDeOpcoes](TgtSelectFilterComponent.md#arraydeopcoes)
- [cdkVirtualScrollViewPort](TgtSelectFilterComponent.md#cdkvirtualscrollviewport)
- [desabilitado](TgtSelectFilterComponent.md#desabilitado)
- [elementRef](TgtSelectFilterComponent.md#elementref)
- [ngUnsubscribe](TgtSelectFilterComponent.md#ngunsubscribe)
- [obrigatorio](TgtSelectFilterComponent.md#obrigatorio)
- [opcaoDefault](TgtSelectFilterComponent.md#opcaodefault)
- [opcaoSelecionada](TgtSelectFilterComponent.md#opcaoselecionada)
- [opcoesFiltradas](TgtSelectFilterComponent.md#opcoesfiltradas)
- [options](TgtSelectFilterComponent.md#options)
- [panelClass](TgtSelectFilterComponent.md#panelclass)
- [select](TgtSelectFilterComponent.md#select)
- [selectForm](TgtSelectFilterComponent.md#selectform)
- [selected](TgtSelectFilterComponent.md#selected)

### Methods

- [clickout](TgtSelectFilterComponent.md#clickout)
- [emiteSelecao](TgtSelectFilterComponent.md#emiteselecao)
- [ngOnChanges](TgtSelectFilterComponent.md#ngonchanges)
- [ngOnDestroy](TgtSelectFilterComponent.md#ngondestroy)
- [ngOnInit](TgtSelectFilterComponent.md#ngoninit)
- [selectFocado](TgtSelectFilterComponent.md#selectfocado)

## Constructors

### constructor

• **new TgtSelectFilterComponent**<`Type`\>(`elementRef`)

#### Type parameters

| Name |
| :------ |
| `Type` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `elementRef` | `ElementRef`<`any`\> |

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:61

## Properties

### arrayDeOpcoes

• **arrayDeOpcoes**: [`ITgtSelectFilter`](../interfaces/ITgtSelectFilter.md)<`Type`\>[] = `[]`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:34

___

### cdkVirtualScrollViewPort

• **cdkVirtualScrollViewPort**: `CdkVirtualScrollViewport`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:54

___

### desabilitado

• **desabilitado**: `boolean` = `false`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:36

___

### elementRef

• `Private` **elementRef**: `ElementRef`<`any`\>

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:62

___

### ngUnsubscribe

• **ngUnsubscribe**: `Subject`<`void`\>

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:28

___

### obrigatorio

• **obrigatorio**: `boolean` = `false`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:37

___

### opcaoDefault

• **opcaoDefault**: `string` = `''`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:35

___

### opcaoSelecionada

• **opcaoSelecionada**: `EventEmitter`<[`ITgtSelectFilter`](../interfaces/ITgtSelectFilter.md)<`Type`\>\>

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:45

___

### opcoesFiltradas

• **opcoesFiltradas**: [`ITgtSelectFilter`](../interfaces/ITgtSelectFilter.md)<`Type`\>[] = `[]`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:32

___

### options

• **options**: `QueryList`<`MatOption`<`any`\>\>

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:57

___

### panelClass

• **panelClass**: `string` \| `string`[] = `''`

A classe personalizada a ser adicionada ao elemento do painel de sobreposição(CDK overlay).

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:43

___

### select

• **select**: `any`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:59

___

### selectForm

• **selectForm**: `FormGroup`<`any`\>

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:31

___

### selected

• **selected**: ``null`` \| `Type` = `null`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:38

## Methods

### clickout

▸ **clickout**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `Object` |
| `event.target` | `any` |

#### Returns

`void`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:47

___

### emiteSelecao

▸ **emiteSelecao**(`value`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `value` | [`ITgtSelectFilter`](../interfaces/ITgtSelectFilter.md)<`Type`\> |

#### Returns

`void`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:132

___

### ngOnChanges

▸ **ngOnChanges**(`changes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `changes` | `SimpleChanges` |

#### Returns

`void`

#### Implementation of

OnChanges.ngOnChanges

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:105

___

### ngOnDestroy

▸ **ngOnDestroy**(): `void`

#### Returns

`void`

#### Implementation of

OnDestroy.ngOnDestroy

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:121

___

### ngOnInit

▸ **ngOnInit**(): `void`

#### Returns

`void`

#### Implementation of

OnInit.ngOnInit

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:71

___

### selectFocado

▸ **selectFocado**(`$event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `$event` | `boolean` |

#### Returns

`void`

#### Defined in

lib/components/tgt-select-filter/tgt-select-filter.component.ts:126
