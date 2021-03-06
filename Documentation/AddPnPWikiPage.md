# Add-PnPWikiPage

## SYNOPSIS
Adds a wiki page

## SYNTAX 

### WithContent
```powershell
Add-PnPWikiPage -Content <String>
                -ServerRelativePageUrl <String>
                [-Web <WebPipeBind>]
```

### WithLayout
```powershell
Add-PnPWikiPage -Layout <WikiPageLayout>
                -ServerRelativePageUrl <String>
                [-Web <WebPipeBind>]
```

## EXAMPLES

### ------------------EXAMPLE 1------------------
```powershell
PS:> Add-PnPWikiPage -PageUrl '/sites/demo1/pages/wikipage.aspx' -Content 'New WikiPage'
```

Creates a new wiki page '/sites/demo1/pages/wikipage.aspx' and sets the content to 'New WikiPage'

## PARAMETERS

### -Content


```yaml
Type: String
Parameter Sets: WithContent

Required: True
Position: Named
Accept pipeline input: False
```

### -Layout


```yaml
Type: WikiPageLayout
Parameter Sets: WithLayout

Required: True
Position: Named
Accept pipeline input: False
```

### -ServerRelativePageUrl
The server relative page URL

```yaml
Type: String
Parameter Sets: (All)
Aliases: PageUrl

Required: True
Position: Named
Accept pipeline input: False
```

### -Web
The GUID, server relative url (i.e. /sites/team1) or web instance of the web to apply the command to. Omit this parameter to use the current web.

```yaml
Type: WebPipeBind
Parameter Sets: (All)

Required: False
Position: Named
Accept pipeline input: False
```

# RELATED LINKS

[SharePoint Developer Patterns and Practices](http://aka.ms/sppnp)