# Lutece Snippets for NetBeans

## Usage
Type part of a snippet, press <code>enter</code> or <code>tab</code>, and the snippet unfolds.

### Lutece Snippets

#### Structure code templates 

**rw** : Lutece row macro
```
<@row>
    <@columns>
    </@columns> 
</@row> 
```
    

**bx** : Lutece box macro
```
<@box>
	<@boxHeader title='#i18n{}' />
	<@boxBody>
    </@boxBody>
</@box>  
```

**bh** : Lutece boxHeader macro
```
<@boxHeader title='#i18n{}' />
```

**tbl** : Lutece table macro
```
<@table>
    <@tr>
        <@th hide=['xs','sm']>${cursor}</@th>
    </@tr>
    <@tr>
        <@td hide=['xs','sm']></@td>
    </@tr>
</@table>            
```

**th** : Lutece table header macro
```
<@th hide=['xs','sm']>${cursor}</@th>
```

**td** : Lutece table data macro
```
<@td hide=['xs','sm']>${cursor}</@td>
```


#### Forms code templates 

**frm** : Lutece form
```
<@tform name='' action=''>
    <@messages errors=errors />

</@tform>
```

**fi** : Lutece input into formGroup
```
<@formGroup labelKey='#i18n{${cursor}}' helpKey='#i18n{}' mandatory=true>
                         <@input type='text' name='' value='!\'\'}' />
</@formGroup>
```

**fc** : Lutece checkbox into formGroup
```
<@formGroup labelKey='#i18n{${cursor}}'>
    <@checkBox labelKey='#i18n{}' name='' value='1' />
</@formGroup>
```

**fs** : Lutece select into formGroup
```
<@formGroup labelKey='#i18n{${cursor}}' helpKey='#i18n{}' mandatory=true>
    <@select name='' items= default_value='' />
</@formGroup>
```

**bt** : Lutece button
```
@button color='primary' title='#i18n{${cursor}}' />
```

#### Standard Freemarker code templates

**if** : Freemarker If
```        
<#if >
    <#else>
</#if>
```
        
**ls**  : Freemarker List    
``` 
<#list  as   >
                         
</#list>
```         

## How to install

Install the plugin.

Test it into an HTML file 
