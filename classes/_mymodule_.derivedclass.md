[typedoc-tests](../README.md) > ["MyModule"](../modules/_mymodule_.md) > [DerivedClass](../classes/_mymodule_.derivedclass.md)

# Class: DerivedClass

This class is derived from the [MyClass](_mymodule_.myclass.md) class.

## Hierarchy

 [MyClass](_mymodule_.myclass.md)

**↳ DerivedClass**

↳  [OtherClass](_tsdoctest_othermodule_.otherclass.md)

## Index

### Events

* [myField](_mymodule_.derivedclass.md#myfield)

### Accessors

* [mainProp](_mymodule_.derivedclass.md#mainprop)
* [mainPropActual](_mymodule_.derivedclass.md#mainpropactual)
* [numberOrString](_mymodule_.derivedclass.md#numberorstring)

### Methods

* [complexTypeMethod](_mymodule_.derivedclass.md#complextypemethod)
* [theMethod](_mymodule_.derivedclass.md#themethod)

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

*Defined in MyModule.ts:98*

Returns an actual value of the [MyClass.mainProp](_mymodule_.myclass.md#mainprop) property.

___
<a id="numberorstring"></a>

###  numberOrString

**numberOrString**: 

*Inherited from [MyClass](_mymodule_.myclass.md).[numberOrString](_mymodule_.myclass.md#numberorstring)*

*Defined in MyModule.ts:67*
*Defined in MyModule.ts:70*

This is a property with the complex return type, as opposite to the [mainProp](_mymodule_.derivedclass.md#mainprop) property return type.

We don't use complex types in Wijmo now but would like to start doing this.

___

## Methods

<a id="complextypemethod"></a>

###  complexTypeMethod

▸ **complexTypeMethod**(value: * `boolean` &#124; [MyClass](_mymodule_.myclass.md)*):  `string` &#124; [DerivedClass](_mymodule_.derivedclass.md)

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

