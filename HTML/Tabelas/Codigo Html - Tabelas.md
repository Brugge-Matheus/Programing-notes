#### Tabelas em Html

#Table = Tabela em htm
#thead = Área do cabeçalho da tabela
#tbody = Corpo da tabela
#th = cabeçalho de uma coluna
#td Códigos Hml.= Célula de uma tabela
#tr = Define a linha de uma tabela
#tfoot = Rodapé da tabela

Css
<border-collapse: collapese> = Forma as linhas da tabela
![[Pasted image 20231130173755.png]]
<colspan="#"> = Define quantas celulas vão ser divididas por linha
![[Pasted image 20231206114037.png]]
<rowspan= "#"> = Define a união de celulas
![[Pasted image 20231206114137.png]]


```HTML
<table>
        <thead>
            <tr>
                <th>Coluna 1 </th>

                <th>Coluna 2 </th>

                <th>Coluna 3 </th>

            </tr>

        </thead>

        <tbody>

            <tr>

                <td>Coluna 1 - Linha 1</td>

                <td>Coluna 2 - Linha 1</td>

                <td>Coluna 3 - Linha 1</td>

            </tr>

            <tr>

                <td>Coluna 1 - Linha 2</td>

                <td>Coluna 2 - Linha 2</td>

                <td>Coluna 3 - Linha 2</td>

            </tr>

        </tbody>

        <tfoot>
            <tr>

                <td>Rodapé 1</td>

                <td>Rodapé 2</td>

                <td>Rodapé 3</td>

            </tr>

        </tfoot>
    </table>

