[@target-lib/tgt-components](../README.md) / [Exports](../modules.md) / TgtDatepickerDiasComponent

# Class: TgtDatepickerDiasComponent

## Hierarchy

- [`TgtDatepickerBaseComponent`](TgtDatepickerBaseComponent.md)

  ↳ **`TgtDatepickerDiasComponent`**

## Implements

- `OnInit`

## Table of contents

### Constructors

- [constructor](TgtDatepickerDiasComponent.md#constructor)

### Properties

- [anoAtual](TgtDatepickerDiasComponent.md#anoatual)
- [arrayDeAnos](TgtDatepickerDiasComponent.md#arraydeanos)
- [dataFimControlName](TgtDatepickerDiasComponent.md#datafimcontrolname)
- [dataInicioControlName](TgtDatepickerDiasComponent.md#datainiciocontrolname)
- [dateForm](TgtDatepickerDiasComponent.md#dateform)
- [datepickerExibido](TgtDatepickerDiasComponent.md#datepickerexibido)
- [emitirData](TgtDatepickerDiasComponent.md#emitirdata)
- [formBuilder](TgtDatepickerDiasComponent.md#formbuilder)
- [labelVisible](TgtDatepickerDiasComponent.md#labelvisible)
- [maxIntervalo](TgtDatepickerDiasComponent.md#maxintervalo)
- [menorDataFimSelecionavel](TgtDatepickerDiasComponent.md#menordatafimselecionavel)
- [moment](TgtDatepickerDiasComponent.md#moment)
- [ngUnsubscribe](TgtDatepickerDiasComponent.md#ngunsubscribe)
- [panelClass](TgtDatepickerDiasComponent.md#panelclass)
- [panelClassArray](TgtDatepickerDiasComponent.md#panelclassarray)
- [rangedDatepicker](TgtDatepickerDiasComponent.md#rangeddatepicker)
- [ultimoBotaoSelected](TgtDatepickerDiasComponent.md#ultimobotaoselected)
- [unidadeIntervalo](TgtDatepickerDiasComponent.md#unidadeintervalo)

### Accessors

- [dataFim](TgtDatepickerDiasComponent.md#datafim)
- [dataInicio](TgtDatepickerDiasComponent.md#datainicio)
- [maiorData](TgtDatepickerDiasComponent.md#maiordata)
- [menorData](TgtDatepickerDiasComponent.md#menordata)

### Methods

- [atualizaPanelClass](TgtDatepickerDiasComponent.md#atualizapanelclass)
- [enviarPeriodo](TgtDatepickerDiasComponent.md#enviarperiodo)
- [getErrorMessageDataFim](TgtDatepickerDiasComponent.md#geterrormessagedatafim)
- [getErrorMessageDataInicio](TgtDatepickerDiasComponent.md#geterrormessagedatainicio)
- [getMaiorDataFimSelecionavel](TgtDatepickerDiasComponent.md#getmaiordatafimselecionavel)
- [isInvalidDataFim](TgtDatepickerDiasComponent.md#isinvaliddatafim)
- [isInvalidDataInicio](TgtDatepickerDiasComponent.md#isinvaliddatainicio)
- [mostraDatepicker](TgtDatepickerDiasComponent.md#mostradatepicker)
- [ngOnChanges](TgtDatepickerDiasComponent.md#ngonchanges)
- [ngOnDestroy](TgtDatepickerDiasComponent.md#ngondestroy)
- [ngOnInit](TgtDatepickerDiasComponent.md#ngoninit)
- [setDataFim](TgtDatepickerDiasComponent.md#setdatafim)
- [setDataInicio](TgtDatepickerDiasComponent.md#setdatainicio)

## Constructors

### constructor

• **new TgtDatepickerDiasComponent**(`formBuilder`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `formBuilder` | `FormBuilder` |

#### Overrides

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[constructor](TgtDatepickerBaseComponent.md#constructor)

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-dias/tgt-datepicker-dias.component.ts:18

## Properties

### anoAtual

• **anoAtual**: `number`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[anoAtual](TgtDatepickerBaseComponent.md#anoatual)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:18

___

### arrayDeAnos

• **arrayDeAnos**: `number`[] = `[]`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[arrayDeAnos](TgtDatepickerBaseComponent.md#arraydeanos)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:17

___

### dataFimControlName

• `Protected` `Readonly` **dataFimControlName**: `string` = `"dataFim"`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[dataFimControlName](TgtDatepickerBaseComponent.md#datafimcontrolname)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:11

___

### dataInicioControlName

• `Protected` `Readonly` **dataInicioControlName**: `string` = `"dataInicio"`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[dataInicioControlName](TgtDatepickerBaseComponent.md#datainiciocontrolname)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:10

___

### dateForm

• **dateForm**: `FormGroup`<`any`\>

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[dateForm](TgtDatepickerBaseComponent.md#dateform)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:13

___

### datepickerExibido

• **datepickerExibido**: `boolean` = `false`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[datepickerExibido](TgtDatepickerBaseComponent.md#datepickerexibido)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:16

___

### emitirData

• **emitirData**: `EventEmitter`<``null`` \| [`ITgtDatepicker`](../interfaces/ITgtDatepicker.md)\>

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[emitirData](TgtDatepickerBaseComponent.md#emitirdata)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:86

___

### formBuilder

• `Private` **formBuilder**: `FormBuilder`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-dias/tgt-datepicker-dias.component.ts:18

___

### labelVisible

• **labelVisible**: `boolean` = `true`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[labelVisible](TgtDatepickerBaseComponent.md#labelvisible)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:28

___

### maxIntervalo

• **maxIntervalo**: `number` = `0`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[maxIntervalo](TgtDatepickerBaseComponent.md#maxintervalo)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:29

___

### menorDataFimSelecionavel

• **menorDataFimSelecionavel**: ``null`` \| `Date` = `null`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[menorDataFimSelecionavel](TgtDatepickerBaseComponent.md#menordatafimselecionavel)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:24

___

### moment

• **moment**: typeof `moment` = `_moment`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[moment](TgtDatepickerBaseComponent.md#moment)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:22

___

### ngUnsubscribe

• **ngUnsubscribe**: `Subject`<`void`\>

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[ngUnsubscribe](TgtDatepickerBaseComponent.md#ngunsubscribe)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:98

___

### panelClass

• **panelClass**: `string` \| `string`[] = `''`

A classe personalizada a ser adicionada ao elemento do painel de sobreposição(CDK overlay).

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[panelClass](TgtDatepickerBaseComponent.md#panelclass)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:84

___

### panelClassArray

• **panelClassArray**: `string`[] = `[]`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[panelClassArray](TgtDatepickerBaseComponent.md#panelclassarray)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:26

___

### rangedDatepicker

• **rangedDatepicker**: `boolean` = `false`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[rangedDatepicker](TgtDatepickerBaseComponent.md#rangeddatepicker)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:79

___

### ultimoBotaoSelected

• **ultimoBotaoSelected**: `undefined` \| `number` = `undefined`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[ultimoBotaoSelected](TgtDatepickerBaseComponent.md#ultimobotaoselected)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:19

___

### unidadeIntervalo

• **unidadeIntervalo**: `DurationConstructor`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[unidadeIntervalo](TgtDatepickerBaseComponent.md#unidadeintervalo)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:25

## Accessors

### dataFim

• `get` **dataFim**(): ``null`` \| `Date`

#### Returns

``null`` \| `Date`

#### Inherited from

TgtDatepickerBaseComponent.dataFim

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:68

• `set` **dataFim**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | ``null`` \| `Date` |

#### Returns

`void`

#### Inherited from

TgtDatepickerBaseComponent.dataFim

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:71

___

### dataInicio

• `get` **dataInicio**(): ``null`` \| `Date`

#### Returns

``null`` \| `Date`

#### Inherited from

TgtDatepickerBaseComponent.dataInicio

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:55

• `set` **dataInicio**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | ``null`` \| `Date` |

#### Returns

`void`

#### Inherited from

TgtDatepickerBaseComponent.dataInicio

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:58

___

### maiorData

• `get` **maiorData**(): `Date`

#### Returns

`Date`

#### Inherited from

TgtDatepickerBaseComponent.maiorData

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:44

• `set` **maiorData**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Date` |

#### Returns

`void`

#### Inherited from

TgtDatepickerBaseComponent.maiorData

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:47

___

### menorData

• `get` **menorData**(): `Date`

#### Returns

`Date`

#### Inherited from

TgtDatepickerBaseComponent.menorData

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:33

• `set` **menorData**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Date` |

#### Returns

`void`

#### Inherited from

TgtDatepickerBaseComponent.menorData

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:36

## Methods

### atualizaPanelClass

▸ **atualizaPanelClass**(): `void`

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[atualizaPanelClass](TgtDatepickerBaseComponent.md#atualizapanelclass)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:142

___

### enviarPeriodo

▸ `Protected` **enviarPeriodo**(): `void`

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[enviarPeriodo](TgtDatepickerBaseComponent.md#enviarperiodo)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:180

___

### getErrorMessageDataFim

▸ **getErrorMessageDataFim**(): ``null`` \| `string`

#### Returns

``null`` \| `string`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[getErrorMessageDataFim](TgtDatepickerBaseComponent.md#geterrormessagedatafim)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:138

___

### getErrorMessageDataInicio

▸ **getErrorMessageDataInicio**(): ``null`` \| `string`

#### Returns

``null`` \| `string`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[getErrorMessageDataInicio](TgtDatepickerBaseComponent.md#geterrormessagedatainicio)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:130

___

### getMaiorDataFimSelecionavel

▸ **getMaiorDataFimSelecionavel**(): ``null`` \| `Moment`

#### Returns

``null`` \| `Moment`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[getMaiorDataFimSelecionavel](TgtDatepickerBaseComponent.md#getmaiordatafimselecionavel)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:117

___

### isInvalidDataFim

▸ **isInvalidDataFim**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[isInvalidDataFim](TgtDatepickerBaseComponent.md#isinvaliddatafim)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:134

___

### isInvalidDataInicio

▸ **isInvalidDataInicio**(): `boolean`

#### Returns

`boolean`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[isInvalidDataInicio](TgtDatepickerBaseComponent.md#isinvaliddatainicio)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:126

___

### mostraDatepicker

▸ **mostraDatepicker**(): `void`

Controla exibição da modal exibida no datepicker Trimestre/Semestre

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[mostraDatepicker](TgtDatepickerBaseComponent.md#mostradatepicker)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:114

___

### ngOnChanges

▸ **ngOnChanges**(`changes`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `changes` | `SimpleChanges` |

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[ngOnChanges](TgtDatepickerBaseComponent.md#ngonchanges)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:100

___

### ngOnDestroy

▸ **ngOnDestroy**(): `void`

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[ngOnDestroy](TgtDatepickerBaseComponent.md#ngondestroy)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:106

___

### ngOnInit

▸ **ngOnInit**(): `void`

#### Returns

`void`

#### Implementation of

OnInit.ngOnInit

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-dias/tgt-datepicker-dias.component.ts:33

___

### setDataFim

▸ `Protected` **setDataFim**(`data`): `undefined` \| `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Moment` |

#### Returns

`undefined` \| `void`

#### Overrides

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[setDataFim](TgtDatepickerBaseComponent.md#setdatafim)

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-dias/tgt-datepicker-dias.component.ts:50

___

### setDataInicio

▸ `Protected` **setDataInicio**(`data`): `undefined` \| `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Moment` |

#### Returns

`undefined` \| `void`

#### Overrides

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[setDataInicio](TgtDatepickerBaseComponent.md#setdatainicio)

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-dias/tgt-datepicker-dias.component.ts:49
