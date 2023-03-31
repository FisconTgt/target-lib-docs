[@target-lib/tgt-components](../README.md) / [Exports](../modules.md) / TgtDatepickerBaseComponent

# Class: TgtDatepickerBaseComponent

## Hierarchy

- **`TgtDatepickerBaseComponent`**

  ↳ [`TgtDatepickerDiasComponent`](TgtDatepickerDiasComponent.md)

  ↳ [`TgtDatepickerMesesComponent`](TgtDatepickerMesesComponent.md)

  ↳ [`TgtDatepickerTrimestresComponent`](TgtDatepickerTrimestresComponent.md)

  ↳ [`TgtDatepickerSemestresComponent`](TgtDatepickerSemestresComponent.md)

  ↳ [`TgtDatepickerAnosComponent`](TgtDatepickerAnosComponent.md)

## Implements

- `OnChanges`
- `OnDestroy`

## Table of contents

### Constructors

- [constructor](TgtDatepickerBaseComponent.md#constructor)

### Properties

- [\_dataFim](TgtDatepickerBaseComponent.md#_datafim)
- [\_dataInicio](TgtDatepickerBaseComponent.md#_datainicio)
- [\_maiorData](TgtDatepickerBaseComponent.md#_maiordata)
- [\_menorData](TgtDatepickerBaseComponent.md#_menordata)
- [anoAtual](TgtDatepickerBaseComponent.md#anoatual)
- [arrayDeAnos](TgtDatepickerBaseComponent.md#arraydeanos)
- [dataFimControlName](TgtDatepickerBaseComponent.md#datafimcontrolname)
- [dataInicioControlName](TgtDatepickerBaseComponent.md#datainiciocontrolname)
- [dateForm](TgtDatepickerBaseComponent.md#dateform)
- [datepickerExibido](TgtDatepickerBaseComponent.md#datepickerexibido)
- [emitirData](TgtDatepickerBaseComponent.md#emitirdata)
- [labelVisible](TgtDatepickerBaseComponent.md#labelvisible)
- [maxIntervalo](TgtDatepickerBaseComponent.md#maxintervalo)
- [menorDataFimSelecionavel](TgtDatepickerBaseComponent.md#menordatafimselecionavel)
- [moment](TgtDatepickerBaseComponent.md#moment)
- [ngUnsubscribe](TgtDatepickerBaseComponent.md#ngunsubscribe)
- [panelClass](TgtDatepickerBaseComponent.md#panelclass)
- [panelClassArray](TgtDatepickerBaseComponent.md#panelclassarray)
- [rangedDatepicker](TgtDatepickerBaseComponent.md#rangeddatepicker)
- [ultimoBotaoSelected](TgtDatepickerBaseComponent.md#ultimobotaoselected)
- [unidadeIntervalo](TgtDatepickerBaseComponent.md#unidadeintervalo)

### Accessors

- [dataFim](TgtDatepickerBaseComponent.md#datafim)
- [dataInicio](TgtDatepickerBaseComponent.md#datainicio)
- [maiorData](TgtDatepickerBaseComponent.md#maiordata)
- [menorData](TgtDatepickerBaseComponent.md#menordata)

### Methods

- [atualizaPanelClass](TgtDatepickerBaseComponent.md#atualizapanelclass)
- [enviarPeriodo](TgtDatepickerBaseComponent.md#enviarperiodo)
- [getErrorMessage](TgtDatepickerBaseComponent.md#geterrormessage)
- [getErrorMessageDataFim](TgtDatepickerBaseComponent.md#geterrormessagedatafim)
- [getErrorMessageDataInicio](TgtDatepickerBaseComponent.md#geterrormessagedatainicio)
- [getMaiorDataFimSelecionavel](TgtDatepickerBaseComponent.md#getmaiordatafimselecionavel)
- [isInvalid](TgtDatepickerBaseComponent.md#isinvalid)
- [isInvalidDataFim](TgtDatepickerBaseComponent.md#isinvaliddatafim)
- [isInvalidDataInicio](TgtDatepickerBaseComponent.md#isinvaliddatainicio)
- [mostraDatepicker](TgtDatepickerBaseComponent.md#mostradatepicker)
- [ngOnChanges](TgtDatepickerBaseComponent.md#ngonchanges)
- [ngOnDestroy](TgtDatepickerBaseComponent.md#ngondestroy)
- [setDataFim](TgtDatepickerBaseComponent.md#setdatafim)
- [setDataInicio](TgtDatepickerBaseComponent.md#setdatainicio)

## Constructors

### constructor

• **new TgtDatepickerBaseComponent**(`unidadeIntervalo`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `unidadeIntervalo` | `DurationConstructor` |

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:88

## Properties

### \_dataFim

• `Private` **\_dataFim**: ``null`` \| `Date` = `null`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:67

___

### \_dataInicio

• `Private` **\_dataInicio**: ``null`` \| `Date` = `null`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:54

___

### \_maiorData

• `Private` **\_maiorData**: `Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:43

___

### \_menorData

• `Private` **\_menorData**: `Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:32

___

### anoAtual

• **anoAtual**: `number`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:18

___

### arrayDeAnos

• **arrayDeAnos**: `number`[] = `[]`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:17

___

### dataFimControlName

• `Protected` `Readonly` **dataFimControlName**: `string` = `"dataFim"`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:11

___

### dataInicioControlName

• `Protected` `Readonly` **dataInicioControlName**: `string` = `"dataInicio"`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:10

___

### dateForm

• **dateForm**: `FormGroup`<`any`\>

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:13

___

### datepickerExibido

• **datepickerExibido**: `boolean` = `false`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:16

___

### emitirData

• **emitirData**: `EventEmitter`<``null`` \| [`ITgtDatepicker`](../interfaces/ITgtDatepicker.md)\>

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:86

___

### labelVisible

• **labelVisible**: `boolean` = `true`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:28

___

### maxIntervalo

• **maxIntervalo**: `number` = `0`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:29

___

### menorDataFimSelecionavel

• **menorDataFimSelecionavel**: ``null`` \| `Date` = `null`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:24

___

### moment

• **moment**: typeof `moment` = `_moment`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:22

___

### ngUnsubscribe

• **ngUnsubscribe**: `Subject`<`void`\>

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:98

___

### panelClass

• **panelClass**: `string` \| `string`[] = `''`

A classe personalizada a ser adicionada ao elemento do painel de sobreposição(CDK overlay).

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:84

___

### panelClassArray

• **panelClassArray**: `string`[] = `[]`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:26

___

### rangedDatepicker

• **rangedDatepicker**: `boolean` = `false`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:79

___

### ultimoBotaoSelected

• **ultimoBotaoSelected**: `undefined` \| `number` = `undefined`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:19

___

### unidadeIntervalo

• **unidadeIntervalo**: `DurationConstructor`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:25

## Accessors

### dataFim

• `get` **dataFim**(): ``null`` \| `Date`

#### Returns

``null`` \| `Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:68

• `set` **dataFim**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | ``null`` \| `Date` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:71

___

### dataInicio

• `get` **dataInicio**(): ``null`` \| `Date`

#### Returns

``null`` \| `Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:55

• `set` **dataInicio**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | ``null`` \| `Date` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:58

___

### maiorData

• `get` **maiorData**(): `Date`

#### Returns

`Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:44

• `set` **maiorData**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Date` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:47

___

### menorData

• `get` **menorData**(): `Date`

#### Returns

`Date`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:33

• `set` **menorData**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Date` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:36

## Methods

### atualizaPanelClass

▸ **atualizaPanelClass**(): `void`

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:142

___

### enviarPeriodo

▸ `Protected` **enviarPeriodo**(): `void`

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:180

___

### getErrorMessage

▸ `Private` **getErrorMessage**(`controlName`): ``null`` \| `string`

#### Parameters

| Name | Type |
| :------ | :------ |
| `controlName` | `string` |

#### Returns

``null`` \| `string`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:163

___

### getErrorMessageDataFim

▸ **getErrorMessageDataFim**(): ``null`` \| `string`

#### Returns

``null`` \| `string`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:138

___

### getErrorMessageDataInicio

▸ **getErrorMessageDataInicio**(): ``null`` \| `string`

#### Returns

``null`` \| `string`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:130

___

### getMaiorDataFimSelecionavel

▸ **getMaiorDataFimSelecionavel**(): ``null`` \| `Moment`

#### Returns

``null`` \| `Moment`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:117

___

### isInvalid

▸ `Private` **isInvalid**(`controlName`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `controlName` | `string` |

#### Returns

`boolean`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:151

___

### isInvalidDataFim

▸ **isInvalidDataFim**(): `boolean`

#### Returns

`boolean`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:134

___

### isInvalidDataInicio

▸ **isInvalidDataInicio**(): `boolean`

#### Returns

`boolean`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:126

___

### mostraDatepicker

▸ **mostraDatepicker**(): `void`

Controla exibição da modal exibida no datepicker Trimestre/Semestre

#### Returns

`void`

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

#### Implementation of

OnChanges.ngOnChanges

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:100

___

### ngOnDestroy

▸ **ngOnDestroy**(): `void`

#### Returns

`void`

#### Implementation of

OnDestroy.ngOnDestroy

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:106

___

### setDataFim

▸ `Protected` **setDataFim**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Moment` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:178

___

### setDataInicio

▸ `Protected` **setDataInicio**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Moment` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:177
