+++
title = 'Shortcode'
date = 2023-09-25T10:32:40+02:00
weight = 200
+++

#### Attachments
 
 {{% attachments sort="asc" title="Archivos de ejemplo" style="info" color="green"/%}}


#### Badges
{{% badge color="fuchsia" icon="skull-crossbones" %}}Pirate King{{% /badge %}}
{{% badge color="black" style="info" title=" "%}}Hito Hito no Mi, Model: Nika{{% /badge %}}

#### Buttons
{{% button href="/" color="dark-blue" icon="dragon" %}}Home{{% /button %}}

#### Expand
{{% expand title="Menos" open="true" %}}  Hola  {{% /expand %}}

#### Hightlights
{{< highlight lineNos="true" type="c++" title="c++" >}}
#include <iostream>

using namespace std;

int main(){
    cout << "Hola Mundo";  
    return 0;
}
{{< /highlight >}}

#### Icons
{{% icon dragon %}} {{% icon tint %}}
https://fontawesome.com/v5/search?m=free 

#### Include
{{% include "shortcode/include.txt" %}}

#### Math
{{< math align="left" >}}
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
{{< /math >}}

#### Mermaid
{{< mermaid >}}
%%{init:{"fontFamily":"monospace", "sequence":{"showSequenceNumbers":true}}}%%
sequenceDiagram
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
{{< /mermaid >}}

#### Notice
{{% notice style="primary" icon="skull-crossbones" title="One Piece" %}}
Zoro fanboys
{{% /notice %}}

#### Site Params 
Texto del parámetro: {{% siteparam name="siteparam.test.text" %}}

#### Tabs
{{% tab title="Consulta notas" %}}
```sql
SELECT notas FROM alumnos WHERE curso = 2 AND ciclo = 'DAW' AND modulo = 'servidor';
```
{{% /tab %}}

{{< tabs title="Hola Mundo" >}}
{{% tab title="Java" %}}
```java
System.out.println("Hello World!");
```
{{% /tab %}}    
{{% tab title="Bash" %}}
```bash
echo "Hello World!"
```
{{% /tab %}}
{{% tab title="c++" %}}
```c++
cout << "Hello World!";
```
{{% /tab %}}
{{< /tabs >}}

<!---#### APIs--->


## Shortcodes personalizados
{{< red >}} UwU {{< /red >}}  
{{< red >}} <u>Este shortcode interpreta el html</u> {{< /red >}}  
{{% red %}} <u>Este no</u> {{% /red %}}