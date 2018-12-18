[typedoc-tests](../README.md) > ["tsdoctest/OtherModule"](../modules/_tsdoctest_othermodule_.md) > [OtherClass](../classes/_tsdoctest_othermodule_.otherclass.md)

# Class: OtherClass

This class is inherited from the [DerivedClass](_mymodule_.derivedclass.md) class.

## Hierarchy

↳  [DerivedClass](_mymodule_.derivedclass.md)

**↳ OtherClass**

## Index

### Events

* [myField](_tsdoctest_othermodule_.otherclass.md#myfield)

### Accessors

* [mainProp](_tsdoctest_othermodule_.otherclass.md#mainprop)
* [mainPropActual](_tsdoctest_othermodule_.otherclass.md#mainpropactual)
* [numberOrString](_tsdoctest_othermodule_.otherclass.md#numberorstring)

### Methods

* [complexTypeMethod](_tsdoctest_othermodule_.otherclass.md#complextypemethod)
* [theMethod](_tsdoctest_othermodule_.otherclass.md#themethod)
* [theOtherMethod](_tsdoctest_othermodule_.otherclass.md#theothermethod)

---

## Events

<a id="myfield"></a>

###  myField

**myField**: *`number`*

*Inherited from [MyClass](_mymodule_.myclass.md).[myField](_mymodule_.myclass.md#myfield)*

*Defined in MyModule.ts:32*

This is an event.

___

## Accessors

<a id="mainprop"></a>

###  mainProp

**mainProp**: 

*Inherited from [MyClass](_mymodule_.myclass.md).[mainProp](_mymodule_.myclass.md#mainprop)*

*Defined in MyModule.ts:48*
*Defined in MyModule.ts:51*

This is the main property of the [MyClass](_mymodule_.myclass.md) class.

___
<a id="mainpropactual"></a>

###  mainPropActual

**mainPropActual**: 

*Inherited from [DerivedClass](_mymodule_.derivedclass.md).[mainPropActual](_mymodule_.derivedclass.md#mainpropactual)*

*Defined in MyModule.ts:98*

Returns an actual value of the [MyClass.mainProp](_mymodule_.myclass.md#mainprop) property.

___
<a id="numberorstring"></a>

###  numberOrString

**numberOrString**: 

*Inherited from [MyClass](_mymodule_.myclass.md).[numberOrString](_mymodule_.myclass.md#numberorstring)*

*Defined in MyModule.ts:67*
*Defined in MyModule.ts:70*

This is a property with the complex return type, as opposite to the [mainProp](_tsdoctest_othermodule_.otherclass.md#mainprop) property return type.

We don't use complex types in Wijmo now but would like to start doing this.

___

## Methods

<a id="complextypemethod"></a>

###  complexTypeMethod

▸ **complexTypeMethod**(value: * `boolean` &#124; [MyClass](_mymodule_.myclass.md)*):  `string` &#124; [DerivedClass](_mymodule_.derivedclass.md)

*Inherited from [DerivedClass](_mymodule_.derivedclass.md).[complexTypeMethod](_mymodule_.derivedclass.md#complextypemethod)*

*Defined in MyModule.ts:117*

This is a method with complex type parameter and return class.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| value |  `boolean` &#124; [MyClass](_mymodule_.myclass.md)|  Boolean or [MyClass](_mymodule_.myclass.md) instance. |

**Returns:**  `string` &#124; [DerivedClass](_mymodule_.derivedclass.md)

A string or [[DerivedClass]] instance.

___
<a id="themethod"></a>

###  theMethod

▸ **theMethod**(theNumber: *`number`*, theString: *`string`*): `boolean`

*Inherited from [DerivedClass](_mymodule_.derivedclass.md).[theMethod](_mymodule_.derivedclass.md#themethod)*

*Overrides [MyClass](_mymodule_.myclass.md).[theMethod](_mymodule_.myclass.md#themethod)*

*Defined in MyModule.ts:108*

Overrides the base [MyClass.theMethod](_mymodule_.myclass.md#themethod) method.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| theNumber | `number` |  This is a parameter of the numeric type. |
| theString | `string` |  This is a parameter of the string type. |

**Returns:** `boolean`
A boolean result value.

___
<a id="theothermethod"></a>

###  theOtherMethod

▸ **theOtherMethod**(value: *`myMd.DerivedClass`*): `myMd.MyClass`

*Defined in tsdoctest/OtherModule.ts:21*

This is an alternative to the [DerivedClass.theMethod](_mymodule_.derivedclass.md#themethod) method and the [mainProp](_tsdoctest_othermodule_.otherclass.md#mainprop) property.

**Parameters:**

| Name | Type | Description |
| ------ | ------ | ------ |
| value | `myMd.DerivedClass` |  A [DerivedClass](_mymodule_.derivedclass.md) instance to [DerivedClass](_mymodule_.derivedclass.md) process. |

**Returns:** `myMd.MyClass`
The resulting [[MyClass]] instance.

___

