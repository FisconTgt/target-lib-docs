[@target-lib/tgt-components](../README.md) / [Exports](../modules.md) / TgtDatepickerTrimestresComponent

# Class: TgtDatepickerTrimestresComponent

## Hierarchy

- [`TgtDatepickerBaseComponent`](TgtDatepickerBaseComponent.md)

  ↳ **`TgtDatepickerTrimestresComponent`**

## Implements

- `OnInit`

## Table of contents

### Constructors

- [constructor](TgtDatepickerTrimestresComponent.md#constructor)

### Properties

- [anoAtual](TgtDatepickerTrimestresComponent.md#anoatual)
- [arrayDeAnos](TgtDatepickerTrimestresComponent.md#arraydeanos)
- [arrayDeBotoesTrimestres](TgtDatepickerTrimestresComponent.md#arraydebotoestrimestres)
- [dataFimControlName](TgtDatepickerTrimestresComponent.md#datafimcontrolname)
- [dataInicioControlName](TgtDatepickerTrimestresComponent.md#datainiciocontrolname)
- [dateForm](TgtDatepickerTrimestresComponent.md#dateform)
- [datepickerExibido](TgtDatepickerTrimestresComponent.md#datepickerexibido)
- [emitirData](TgtDatepickerTrimestresComponent.md#emitirdata)
- [formBuilder](TgtDatepickerTrimestresComponent.md#formbuilder)
- [labelVisible](TgtDatepickerTrimestresComponent.md#labelvisible)
- [maxIntervalo](TgtDatepickerTrimestresComponent.md#maxintervalo)
- [menorDataFimSelecionavel](TgtDatepickerTrimestresComponent.md#menordatafimselecionavel)
- [moment](TgtDatepickerTrimestresComponent.md#moment)
- [ngUnsubscribe](TgtDatepickerTrimestresComponent.md#ngunsubscribe)
- [panelClass](TgtDatepickerTrimestresComponent.md#panelclass)
- [panelClassArray](TgtDatepickerTrimestresComponent.md#panelclassarray)
- [placeholder](TgtDatepickerTrimestresComponent.md#placeholder)
- [rangedDatepicker](TgtDatepickerTrimestresComponent.md#rangeddatepicker)
- [tempFim](TgtDatepickerTrimestresComponent.md#tempfim)
- [tempInicio](TgtDatepickerTrimestresComponent.md#tempinicio)
- [ultimoBotaoSelected](TgtDatepickerTrimestresComponent.md#ultimobotaoselected)
- [unidadeIntervalo](TgtDatepickerTrimestresComponent.md#unidadeintervalo)
- [widthDatepicker](TgtDatepickerTrimestresComponent.md#widthdatepicker)

### Accessors

- [dataFim](TgtDatepickerTrimestresComponent.md#datafim)
- [dataInicio](TgtDatepickerTrimestresComponent.md#datainicio)
- [maiorData](TgtDatepickerTrimestresComponent.md#maiordata)
- [menorData](TgtDatepickerTrimestresComponent.md#menordata)

### Methods

- [atualizaPanelClass](TgtDatepickerTrimestresComponent.md#atualizapanelclass)
- [atualizaVisualizacao](TgtDatepickerTrimestresComponent.md#atualizavisualizacao)
- [cancelaSelecao](TgtDatepickerTrimestresComponent.md#cancelaselecao)
- [confirmaIntervalo](TgtDatepickerTrimestresComponent.md#confirmaintervalo)
- [enviarPeriodo](TgtDatepickerTrimestresComponent.md#enviarperiodo)
- [getErrorMessageDataFim](TgtDatepickerTrimestresComponent.md#geterrormessagedatafim)
- [getErrorMessageDataInicio](TgtDatepickerTrimestresComponent.md#geterrormessagedatainicio)
- [getMaiorDataFimSelecionavel](TgtDatepickerTrimestresComponent.md#getmaiordatafimselecionavel)
- [iniciaComponenteSelecao](TgtDatepickerTrimestresComponent.md#iniciacomponenteselecao)
- [isInvalidDataFim](TgtDatepickerTrimestresComponent.md#isinvaliddatafim)
- [isInvalidDataInicio](TgtDatepickerTrimestresComponent.md#isinvaliddatainicio)
- [mostraDatepicker](TgtDatepickerTrimestresComponent.md#mostradatepicker)
- [ngOnChanges](TgtDatepickerTrimestresComponent.md#ngonchanges)
- [ngOnDestroy](TgtDatepickerTrimestresComponent.md#ngondestroy)
- [ngOnInit](TgtDatepickerTrimestresComponent.md#ngoninit)
- [selecionarData](TgtDatepickerTrimestresComponent.md#selecionardata)
- [setDataFim](TgtDatepickerTrimestresComponent.md#setdatafim)
- [setDataInicio](TgtDatepickerTrimestresComponent.md#setdatainicio)
- [setPlaceholder](TgtDatepickerTrimestresComponent.md#setplaceholder)

## Constructors

### constructor

• **new TgtDatepickerTrimestresComponent**(`formBuilder`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `formBuilder` | `FormBuilder` |

#### Overrides

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[constructor](TgtDatepickerBaseComponent.md#constructor)

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:23

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

### arrayDeBotoesTrimestres

• **arrayDeBotoesTrimestres**: [`ITgtBotoesTrimestresSemestres`](../interfaces/ITgtBotoesTrimestresSemestres.md)[] = `[]`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:17

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

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:24

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

### placeholder

• **placeholder**: `string` = `''`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:21

___

### rangedDatepicker

• **rangedDatepicker**: `boolean` = `false`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[rangedDatepicker](TgtDatepickerBaseComponent.md#rangeddatepicker)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:79

___

### tempFim

• `Private` **tempFim**: ``null`` \| `number` = `null`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:20

___

### tempInicio

• `Private` **tempInicio**: ``null`` \| `number` = `null`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:19

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

___

### widthDatepicker

• **widthDatepicker**: `string` = `'170px'`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:16

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

### atualizaVisualizacao

▸ `Private` **atualizaVisualizacao**(`inicio`, `fim`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `inicio` | ``null`` \| `number` |
| `fim` | ``null`` \| `number` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:131

___

### cancelaSelecao

▸ **cancelaSelecao**(): `void`

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:99

___

### confirmaIntervalo

▸ **confirmaIntervalo**(): `void`

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:94

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

### iniciaComponenteSelecao

▸ `Private` **iniciaComponenteSelecao**(`ano`, `restauraValorAnterior`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `ano` | `number` |
| `restauraValorAnterior` | `boolean` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:104

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

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:48

___

### selecionarData

▸ **selecionarData**(`event`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `event` | `MatButtonToggleGroup` |

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:74

___

### setDataFim

▸ `Protected` **setDataFim**(`data`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `Moment` |

#### Returns

`void`

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[setDataFim](TgtDatepickerBaseComponent.md#setdatafim)

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

#### Inherited from

[TgtDatepickerBaseComponent](TgtDatepickerBaseComponent.md).[setDataInicio](TgtDatepickerBaseComponent.md#setdatainicio)

#### Defined in

lib/components/tgt-datepicker/tgt-shared/tgt-datepicker-base.component.ts:177

___

### setPlaceholder

▸ `Private` **setPlaceholder**(): `void`

#### Returns

`void`

#### Defined in

lib/components/tgt-datepicker/tgt-datepicker-trimestres/tgt-datepicker-trimestres.component.ts:142
