# `dataExternal` Submodule <a name="`dataExternal` Submodule" id="@cdktn/provider-external.dataExternal"></a>

## Constructs <a name="Constructs" id="Constructs"></a>

### DataExternal <a name="DataExternal" id="@cdktn/provider-external.dataExternal.DataExternal"></a>

Represents a {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external external}.

#### Initializers <a name="Initializers" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer"></a>

```java
import io.cdktn.providers.external.data_external.DataExternal;

DataExternal.Builder.create(Construct scope, java.lang.String id)
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .program(java.util.List<java.lang.String>)
//  .query(java.util.Map<java.lang.String, java.lang.String>)
//  .workingDir(java.lang.String)
    .build();
```

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.scope">scope</a></code> | <code>software.constructs.Construct</code> | The scope in which to define this construct. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.id">id</a></code> | <code>java.lang.String</code> | The scoped construct ID. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.program">program</a></code> | <code>java.util.List<java.lang.String></code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir">workingDir</a></code> | <code>java.lang.String</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.id"></a>

- *Type:* java.lang.String

The scoped construct ID.

Must be unique amongst siblings in the same scope

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.connection"></a>

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.count"></a>

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.dependsOn"></a>

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.forEach"></a>

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.lifecycle"></a>

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.provisioners"></a>

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.program"></a>

- *Type:* java.util.List<java.lang.String>

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#program DataExternal#program}

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.query"></a>

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#query DataExternal#query}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktn/provider-external.dataExternal.DataExternal.Initializer.parameter.workingDir"></a>

- *Type:* java.lang.String

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#working_dir DataExternal#working_dir}

---

#### Methods <a name="Methods" id="Methods"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.toString">toString</a></code> | Returns a string representation of this construct. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.with">with</a></code> | Applies one or more mixins to this construct. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.addOverride">addOverride</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.overrideLogicalId">overrideLogicalId</a></code> | Overrides the auto-generated logical ID with a specific ID. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.resetOverrideLogicalId">resetOverrideLogicalId</a></code> | Resets a previously passed logical Id to use the auto-generated logical id again. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.toHclTerraform">toHclTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.toMetadata">toMetadata</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.toTerraform">toTerraform</a></code> | Adds this resource to the terraform JSON output. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getAnyMapAttribute">getAnyMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getBooleanAttribute">getBooleanAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getBooleanMapAttribute">getBooleanMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getListAttribute">getListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getNumberAttribute">getNumberAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getNumberListAttribute">getNumberListAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getNumberMapAttribute">getNumberMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getStringAttribute">getStringAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.getStringMapAttribute">getStringMapAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.interpolationForAttribute">interpolationForAttribute</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.resetQuery">resetQuery</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.resetWorkingDir">resetWorkingDir</a></code> | *No description.* |

---

##### `toString` <a name="toString" id="@cdktn/provider-external.dataExternal.DataExternal.toString"></a>

```java
public java.lang.String toString()
```

Returns a string representation of this construct.

##### `with` <a name="with" id="@cdktn/provider-external.dataExternal.DataExternal.with"></a>

```java
public IConstruct with(IMixin... mixins)
```

Applies one or more mixins to this construct.

Mixins are applied in order. The list of constructs is captured at the
start of the call, so constructs added by a mixin will not be visited.
Use multiple `with()` calls if subsequent mixins should apply to added
constructs.

###### `mixins`<sup>Required</sup> <a name="mixins" id="@cdktn/provider-external.dataExternal.DataExternal.with.parameter.mixins"></a>

- *Type:* software.constructs.IMixin...

The mixins to apply.

---

##### `addOverride` <a name="addOverride" id="@cdktn/provider-external.dataExternal.DataExternal.addOverride"></a>

```java
public void addOverride(java.lang.String path, java.lang.Object value)
```

###### `path`<sup>Required</sup> <a name="path" id="@cdktn/provider-external.dataExternal.DataExternal.addOverride.parameter.path"></a>

- *Type:* java.lang.String

---

###### `value`<sup>Required</sup> <a name="value" id="@cdktn/provider-external.dataExternal.DataExternal.addOverride.parameter.value"></a>

- *Type:* java.lang.Object

---

##### `overrideLogicalId` <a name="overrideLogicalId" id="@cdktn/provider-external.dataExternal.DataExternal.overrideLogicalId"></a>

```java
public void overrideLogicalId(java.lang.String newLogicalId)
```

Overrides the auto-generated logical ID with a specific ID.

###### `newLogicalId`<sup>Required</sup> <a name="newLogicalId" id="@cdktn/provider-external.dataExternal.DataExternal.overrideLogicalId.parameter.newLogicalId"></a>

- *Type:* java.lang.String

The new logical ID to use for this stack element.

---

##### `resetOverrideLogicalId` <a name="resetOverrideLogicalId" id="@cdktn/provider-external.dataExternal.DataExternal.resetOverrideLogicalId"></a>

```java
public void resetOverrideLogicalId()
```

Resets a previously passed logical Id to use the auto-generated logical id again.

##### `toHclTerraform` <a name="toHclTerraform" id="@cdktn/provider-external.dataExternal.DataExternal.toHclTerraform"></a>

```java
public java.lang.Object toHclTerraform()
```

Adds this resource to the terraform JSON output.

##### `toMetadata` <a name="toMetadata" id="@cdktn/provider-external.dataExternal.DataExternal.toMetadata"></a>

```java
public java.lang.Object toMetadata()
```

##### `toTerraform` <a name="toTerraform" id="@cdktn/provider-external.dataExternal.DataExternal.toTerraform"></a>

```java
public java.lang.Object toTerraform()
```

Adds this resource to the terraform JSON output.

##### `getAnyMapAttribute` <a name="getAnyMapAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getAnyMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getAnyMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getAnyMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanAttribute` <a name="getBooleanAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getBooleanAttribute"></a>

```java
public IResolvable getBooleanAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getBooleanAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getBooleanMapAttribute` <a name="getBooleanMapAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getBooleanMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Boolean> getBooleanMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getBooleanMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getListAttribute` <a name="getListAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getListAttribute"></a>

```java
public java.util.List<java.lang.String> getListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberAttribute` <a name="getNumberAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberAttribute"></a>

```java
public java.lang.Number getNumberAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberListAttribute` <a name="getNumberListAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberListAttribute"></a>

```java
public java.util.List<java.lang.Number> getNumberListAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberListAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getNumberMapAttribute` <a name="getNumberMapAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.Number> getNumberMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getNumberMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringAttribute` <a name="getStringAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getStringAttribute"></a>

```java
public java.lang.String getStringAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getStringAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `getStringMapAttribute` <a name="getStringMapAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getStringMapAttribute"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getStringMapAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.getStringMapAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `interpolationForAttribute` <a name="interpolationForAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.interpolationForAttribute"></a>

```java
public IResolvable interpolationForAttribute(java.lang.String terraformAttribute)
```

###### `terraformAttribute`<sup>Required</sup> <a name="terraformAttribute" id="@cdktn/provider-external.dataExternal.DataExternal.interpolationForAttribute.parameter.terraformAttribute"></a>

- *Type:* java.lang.String

---

##### `resetQuery` <a name="resetQuery" id="@cdktn/provider-external.dataExternal.DataExternal.resetQuery"></a>

```java
public void resetQuery()
```

##### `resetWorkingDir` <a name="resetWorkingDir" id="@cdktn/provider-external.dataExternal.DataExternal.resetWorkingDir"></a>

```java
public void resetWorkingDir()
```

#### Static Functions <a name="Static Functions" id="Static Functions"></a>

| **Name** | **Description** |
| --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.isConstruct">isConstruct</a></code> | Checks if `x` is a construct. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.isTerraformElement">isTerraformElement</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.isTerraformDataSource">isTerraformDataSource</a></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport">generateConfigForImport</a></code> | Generates CDKTN code for importing a DataExternal resource upon running "cdktn plan <stack-name>". |

---

##### `isConstruct` <a name="isConstruct" id="@cdktn/provider-external.dataExternal.DataExternal.isConstruct"></a>

```java
import io.cdktn.providers.external.data_external.DataExternal;

DataExternal.isConstruct(java.lang.Object x)
```

Checks if `x` is a construct.

Use this method instead of `instanceof` to properly detect `Construct`
instances, even when the construct library is symlinked.

Explanation: in JavaScript, multiple copies of the `constructs` library on
disk are seen as independent, completely different libraries. As a
consequence, the class `Construct` in each copy of the `constructs` library
is seen as a different class, and an instance of one class will not test as
`instanceof` the other class. `npm install` will not create installations
like this, but users may manually symlink construct libraries together or
use a monorepo tool: in those cases, multiple copies of the `constructs`
library can be accidentally installed, and `instanceof` will behave
unpredictably. It is safest to avoid using `instanceof`, and using
this type-testing method instead.

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-external.dataExternal.DataExternal.isConstruct.parameter.x"></a>

- *Type:* java.lang.Object

Any object.

---

##### `isTerraformElement` <a name="isTerraformElement" id="@cdktn/provider-external.dataExternal.DataExternal.isTerraformElement"></a>

```java
import io.cdktn.providers.external.data_external.DataExternal;

DataExternal.isTerraformElement(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-external.dataExternal.DataExternal.isTerraformElement.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `isTerraformDataSource` <a name="isTerraformDataSource" id="@cdktn/provider-external.dataExternal.DataExternal.isTerraformDataSource"></a>

```java
import io.cdktn.providers.external.data_external.DataExternal;

DataExternal.isTerraformDataSource(java.lang.Object x)
```

###### `x`<sup>Required</sup> <a name="x" id="@cdktn/provider-external.dataExternal.DataExternal.isTerraformDataSource.parameter.x"></a>

- *Type:* java.lang.Object

---

##### `generateConfigForImport` <a name="generateConfigForImport" id="@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport"></a>

```java
import io.cdktn.providers.external.data_external.DataExternal;

DataExternal.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId),DataExternal.generateConfigForImport(Construct scope, java.lang.String importToId, java.lang.String importFromId, TerraformProvider provider)
```

Generates CDKTN code for importing a DataExternal resource upon running "cdktn plan <stack-name>".

###### `scope`<sup>Required</sup> <a name="scope" id="@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.scope"></a>

- *Type:* software.constructs.Construct

The scope in which to define this construct.

---

###### `importToId`<sup>Required</sup> <a name="importToId" id="@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importToId"></a>

- *Type:* java.lang.String

The construct id used in the generated config for the DataExternal to import.

---

###### `importFromId`<sup>Required</sup> <a name="importFromId" id="@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.importFromId"></a>

- *Type:* java.lang.String

The id of the existing DataExternal that should be imported.

Refer to the {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#import import section} in the documentation of this resource for the id to use

---

###### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-external.dataExternal.DataExternal.generateConfigForImport.parameter.provider"></a>

- *Type:* io.cdktn.cdktn.TerraformProvider

? Optional instance of the provider where the DataExternal to import is found.

---

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.node">node</a></code> | <code>software.constructs.Node</code> | The tree node. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.cdktfStack">cdktfStack</a></code> | <code>io.cdktn.cdktn.TerraformStack</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.fqn">fqn</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.friendlyUniqueId">friendlyUniqueId</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.terraformMetaArguments">terraformMetaArguments</a></code> | <code>java.util.Map<java.lang.String, java.lang.Object></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.terraformResourceType">terraformResourceType</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata">terraformGeneratorMetadata</a></code> | <code>io.cdktn.cdktn.TerraformProviderGeneratorMetadata</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.dependsOn">dependsOn</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.id">id</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.result">result</a></code> | <code>io.cdktn.cdktn.StringMap</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.programInput">programInput</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.queryInput">queryInput</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.workingDirInput">workingDirInput</a></code> | <code>java.lang.String</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.program">program</a></code> | <code>java.util.List<java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `node`<sup>Required</sup> <a name="node" id="@cdktn/provider-external.dataExternal.DataExternal.property.node"></a>

```java
public Node getNode();
```

- *Type:* software.constructs.Node

The tree node.

---

##### `cdktfStack`<sup>Required</sup> <a name="cdktfStack" id="@cdktn/provider-external.dataExternal.DataExternal.property.cdktfStack"></a>

```java
public TerraformStack getCdktfStack();
```

- *Type:* io.cdktn.cdktn.TerraformStack

---

##### `fqn`<sup>Required</sup> <a name="fqn" id="@cdktn/provider-external.dataExternal.DataExternal.property.fqn"></a>

```java
public java.lang.String getFqn();
```

- *Type:* java.lang.String

---

##### `friendlyUniqueId`<sup>Required</sup> <a name="friendlyUniqueId" id="@cdktn/provider-external.dataExternal.DataExternal.property.friendlyUniqueId"></a>

```java
public java.lang.String getFriendlyUniqueId();
```

- *Type:* java.lang.String

---

##### `terraformMetaArguments`<sup>Required</sup> <a name="terraformMetaArguments" id="@cdktn/provider-external.dataExternal.DataExternal.property.terraformMetaArguments"></a>

```java
public java.util.Map<java.lang.String, java.lang.Object> getTerraformMetaArguments();
```

- *Type:* java.util.Map<java.lang.String, java.lang.Object>

---

##### `terraformResourceType`<sup>Required</sup> <a name="terraformResourceType" id="@cdktn/provider-external.dataExternal.DataExternal.property.terraformResourceType"></a>

```java
public java.lang.String getTerraformResourceType();
```

- *Type:* java.lang.String

---

##### `terraformGeneratorMetadata`<sup>Optional</sup> <a name="terraformGeneratorMetadata" id="@cdktn/provider-external.dataExternal.DataExternal.property.terraformGeneratorMetadata"></a>

```java
public TerraformProviderGeneratorMetadata getTerraformGeneratorMetadata();
```

- *Type:* io.cdktn.cdktn.TerraformProviderGeneratorMetadata

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-external.dataExternal.DataExternal.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-external.dataExternal.DataExternal.property.dependsOn"></a>

```java
public java.util.List<java.lang.String> getDependsOn();
```

- *Type:* java.util.List<java.lang.String>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-external.dataExternal.DataExternal.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-external.dataExternal.DataExternal.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-external.dataExternal.DataExternal.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `id`<sup>Required</sup> <a name="id" id="@cdktn/provider-external.dataExternal.DataExternal.property.id"></a>

```java
public java.lang.String getId();
```

- *Type:* java.lang.String

---

##### `result`<sup>Required</sup> <a name="result" id="@cdktn/provider-external.dataExternal.DataExternal.property.result"></a>

```java
public StringMap getResult();
```

- *Type:* io.cdktn.cdktn.StringMap

---

##### `programInput`<sup>Optional</sup> <a name="programInput" id="@cdktn/provider-external.dataExternal.DataExternal.property.programInput"></a>

```java
public java.util.List<java.lang.String> getProgramInput();
```

- *Type:* java.util.List<java.lang.String>

---

##### `queryInput`<sup>Optional</sup> <a name="queryInput" id="@cdktn/provider-external.dataExternal.DataExternal.property.queryInput"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQueryInput();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `workingDirInput`<sup>Optional</sup> <a name="workingDirInput" id="@cdktn/provider-external.dataExternal.DataExternal.property.workingDirInput"></a>

```java
public java.lang.String getWorkingDirInput();
```

- *Type:* java.lang.String

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktn/provider-external.dataExternal.DataExternal.property.program"></a>

```java
public java.util.List<java.lang.String> getProgram();
```

- *Type:* java.util.List<java.lang.String>

---

##### `query`<sup>Required</sup> <a name="query" id="@cdktn/provider-external.dataExternal.DataExternal.property.query"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQuery();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

---

##### `workingDir`<sup>Required</sup> <a name="workingDir" id="@cdktn/provider-external.dataExternal.DataExternal.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

---

#### Constants <a name="Constants" id="Constants"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternal.property.tfResourceType">tfResourceType</a></code> | <code>java.lang.String</code> | *No description.* |

---

##### `tfResourceType`<sup>Required</sup> <a name="tfResourceType" id="@cdktn/provider-external.dataExternal.DataExternal.property.tfResourceType"></a>

```java
public java.lang.String getTfResourceType();
```

- *Type:* java.lang.String

---

## Structs <a name="Structs" id="Structs"></a>

### DataExternalConfig <a name="DataExternalConfig" id="@cdktn/provider-external.dataExternal.DataExternalConfig"></a>

#### Initializer <a name="Initializer" id="@cdktn/provider-external.dataExternal.DataExternalConfig.Initializer"></a>

```java
import io.cdktn.providers.external.data_external.DataExternalConfig;

DataExternalConfig.builder()
//  .connection(SSHProvisionerConnection|WinrmProvisionerConnection)
//  .count(java.lang.Number|TerraformCount)
//  .dependsOn(java.util.List<ITerraformDependable>)
//  .forEach(ITerraformIterator)
//  .lifecycle(TerraformResourceLifecycle)
//  .provider(TerraformProvider)
//  .provisioners(java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner>)
    .program(java.util.List<java.lang.String>)
//  .query(java.util.Map<java.lang.String, java.lang.String>)
//  .workingDir(java.lang.String)
    .build();
```

#### Properties <a name="Properties" id="Properties"></a>

| **Name** | **Type** | **Description** |
| --- | --- | --- |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.connection">connection</a></code> | <code>io.cdktn.cdktn.SSHProvisionerConnection\|io.cdktn.cdktn.WinrmProvisionerConnection</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.count">count</a></code> | <code>java.lang.Number\|io.cdktn.cdktn.TerraformCount</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.dependsOn">dependsOn</a></code> | <code>java.util.List<io.cdktn.cdktn.ITerraformDependable></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.forEach">forEach</a></code> | <code>io.cdktn.cdktn.ITerraformIterator</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.lifecycle">lifecycle</a></code> | <code>io.cdktn.cdktn.TerraformResourceLifecycle</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.provider">provider</a></code> | <code>io.cdktn.cdktn.TerraformProvider</code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.provisioners">provisioners</a></code> | <code>java.util.List<io.cdktn.cdktn.FileProvisioner\|io.cdktn.cdktn.LocalExecProvisioner\|io.cdktn.cdktn.RemoteExecProvisioner></code> | *No description.* |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.program">program</a></code> | <code>java.util.List<java.lang.String></code> | A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.query">query</a></code> | <code>java.util.Map<java.lang.String, java.lang.String></code> | A map of string values to pass to the external program as the query arguments. |
| <code><a href="#@cdktn/provider-external.dataExternal.DataExternalConfig.property.workingDir">workingDir</a></code> | <code>java.lang.String</code> | Working directory of the program. If not supplied, the program will run in the current directory. |

---

##### `connection`<sup>Optional</sup> <a name="connection" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.connection"></a>

```java
public SSHProvisionerConnection|WinrmProvisionerConnection getConnection();
```

- *Type:* io.cdktn.cdktn.SSHProvisionerConnection|io.cdktn.cdktn.WinrmProvisionerConnection

---

##### `count`<sup>Optional</sup> <a name="count" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.count"></a>

```java
public java.lang.Number|TerraformCount getCount();
```

- *Type:* java.lang.Number|io.cdktn.cdktn.TerraformCount

---

##### `dependsOn`<sup>Optional</sup> <a name="dependsOn" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.dependsOn"></a>

```java
public java.util.List<ITerraformDependable> getDependsOn();
```

- *Type:* java.util.List<io.cdktn.cdktn.ITerraformDependable>

---

##### `forEach`<sup>Optional</sup> <a name="forEach" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.forEach"></a>

```java
public ITerraformIterator getForEach();
```

- *Type:* io.cdktn.cdktn.ITerraformIterator

---

##### `lifecycle`<sup>Optional</sup> <a name="lifecycle" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.lifecycle"></a>

```java
public TerraformResourceLifecycle getLifecycle();
```

- *Type:* io.cdktn.cdktn.TerraformResourceLifecycle

---

##### `provider`<sup>Optional</sup> <a name="provider" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.provider"></a>

```java
public TerraformProvider getProvider();
```

- *Type:* io.cdktn.cdktn.TerraformProvider

---

##### `provisioners`<sup>Optional</sup> <a name="provisioners" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.provisioners"></a>

```java
public java.util.List<FileProvisioner|LocalExecProvisioner|RemoteExecProvisioner> getProvisioners();
```

- *Type:* java.util.List<io.cdktn.cdktn.FileProvisioner|io.cdktn.cdktn.LocalExecProvisioner|io.cdktn.cdktn.RemoteExecProvisioner>

---

##### `program`<sup>Required</sup> <a name="program" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.program"></a>

```java
public java.util.List<java.lang.String> getProgram();
```

- *Type:* java.util.List<java.lang.String>

A list of strings, whose first element is the program to run and whose subsequent elements are optional command line arguments to the program.

Terraform does not execute the program through a shell, so it is not necessary to escape shell metacharacters nor add quotes around arguments containing spaces.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#program DataExternal#program}

---

##### `query`<sup>Optional</sup> <a name="query" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.query"></a>

```java
public java.util.Map<java.lang.String, java.lang.String> getQuery();
```

- *Type:* java.util.Map<java.lang.String, java.lang.String>

A map of string values to pass to the external program as the query arguments.

If not supplied, the program will receive an empty object as its input.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#query DataExternal#query}

---

##### `workingDir`<sup>Optional</sup> <a name="workingDir" id="@cdktn/provider-external.dataExternal.DataExternalConfig.property.workingDir"></a>

```java
public java.lang.String getWorkingDir();
```

- *Type:* java.lang.String

Working directory of the program. If not supplied, the program will run in the current directory.

Docs at Terraform Registry: {@link https://registry.terraform.io/providers/hashicorp/external/2.4.0/docs/data-sources/external#working_dir DataExternal#working_dir}

---



