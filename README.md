# EdiTable.js
Inline table editing

Habilita la edición de tablas con ámplio soporte de teclado al estilo de hojas de cálculo.
### Tipos de columnas

#### EdiTable.Const.Types.Text
	Indica un editor input(type="text") para todas las celdas de la columna.
	El texto se contiene en una sola linea finita.
#### EdiTable.Const.Types.Number
	Indica un editor input(type="number") para todas las celdas de la columna.
	No se adminten caracteres alfabeticos o caracteres especiales.
	
#### EdiTable.Const.Types.Date
	Indica un editor input(type="Date") para todas las celdas de la columna.
	Se indica una fecha.
	
#### EdiTable.Const.Types.DateTime
	Indica un editor input(type="DateTime") para todas las celdas de la columna.
	Se indica fecha y hora.
	
#### EdiTable.Const.Types.Memo
	Indica un editor textarea para todas las celdas de la columna.
	El texto se contiene en multiples lineas.
	
#### EdiTable.Const.Types.Check
	Indica un editor input(type="checkbox") para todas las celdas de la columna.
	
#### EdiTable.Const.Types.Select
	Indica un editor Select para todas las celdas de la columna.
	Se configura previamente para mostrar las opciones para realizar la seleccion del valor a contener.
	
#### EdiTable.Const.Types.Custom
	Indica un editor personalizado para todas las celdas de la columna.
	
#### EdiTable.Const.Types.NoEditable
	 Todas las celdas de la columna no se pueden editar.



### Eventos

#### EdiTable.Const.Events.EnterCell
	Ocurre cuando una celda toma el foco, justo cuando es seleccionada.
	
	Argumentos suministrados por el evento
	* sender - Representa la instancia de la tabla que lo está generando.
	* colDef-Contiene el objeto de definición de columna correspondiente a la celda que generó el evento
	
#### EdiTable.Const.Events.LeaveCell
	Ocurre cuando una celda pierde el foco, se reliza un cambio de celda o se selecciona un objeto diferente.

#### EdiTable.Const.Events.StartEdition
	Ocurre al momento de seleccionar la celda y permite realizar la edicion de esta, puede ser precedida por el evento EnterCell.

#### EdiTable.Const.Events.ConfirmEdition
	El evento se dispara al confirmar con la tecla "ENTER", cambiar o quitar el foco de la celda que se esta editando.

#### EdiTable.Const.Events.CancelEdition
	El evento se dispara al no confirmar el contenido de la celda con la tecla "ESC".

#### EdiTable.Const.Events.InputCreated
	Ocurre al generarse el componente  editor "INPUT" dentro de la celda.

#### EdiTable.Const.Events.BeforeUpdateCell
	Ocurre antes de definir el nuevo contenido de la celda.

#### EdiTable.Const.Events.BeforeSetInput
	Ocurre antes de definir el contenido de la celda.

#### EdiTable.Const.Events.FieldUpdated

#### EdiTable.Const.Events.RowAdded
	Agrega una nueva fila a la tabla
	


### Eventos

#### EdiTable.Const.Events.EnterCell
	Ocurre cuando una celda toma el foco, justo cuando es seleccionada.
	
	Argumentos suministrados por el evento
	* sender - Representa la instancia de la tabla que lo está generando.
	* colDef-Contiene el objeto de definición de columna correspondiente a la celda que generó el evento
	
#### EdiTable.Const.Events.LeaveCell
	Ocurre cuando una celda pierde el foco, se reliza un cambio de celda o se selecciona un objeto diferente.

#### EdiTable.Const.Events.StartEdition
	Ocurre al momento de seleccionar la celda y permite realizar la edicion de esta, puede ser precedida por el evento EnterCell.

#### EdiTable.Const.Events.ConfirmEdition
	El evento se dispara al confirmar con la tecla "ENTER", cambiar o quitar el foco de la celda que se esta editando.

#### EdiTable.Const.Events.CancelEdition
	El evento se dispara al no confirmar el contenido de la celda con la tecla "ESC".

#### EdiTable.Const.Events.InputCreated
	Ocurre al generarse el componente  editor "INPUT" dentro de la celda.

#### EdiTable.Const.Events.BeforeUpdateCell
	Ocurre antes de definir el nuevo contenido de la celda.

#### EdiTable.Const.Events.BeforeSetInput
	Ocurre antes de definir el contenido de la celda.

#### EdiTable.Const.Events.FieldUpdated

#### EdiTable.Const.Events.RowAdded
	Agrega una nueva fila a la tabla
	
## Métodos

### Initialize()
	Inicializa el objeto EdiTable.
		
### GetTHead()

### GetTBody()

### ColumnsCount()
	Devuelve el numero de columnas en la tabla. 
### NavToHome()
	Mueve el cursor a la celda ubicada en la primera fila y primera columna.
		
### NavToEnd() 
	Mueve el cursor a la celda ubicada en la ultima fila y ultima columna.
		
### NavToFirstCell(row)
	Mueve el cursor a la celda ubicada en laprimer columna de la fila indicada (ROW).

### NavToLastCell(row)
	Mueve el cursor a la celda ubicada en laprimer columna de la fila indicada (ROW).

### NavTo(row,col)
	Mueve el cursor a la celda ubicada en la columna y fila indicada.

### GetTrByIndex(row)

### DeleteCurrentRow()
	Elimina la fila actual.

### DeleteRow(row)
	Elimina la fila seleccionada en ROW.

### UpdateRow(row)
	Actualiza  la fila seleccionada en ROW.

### UpdateData()

### UpdateDataRow(row)
	Devuelve "TRUE" o "FALSE"

### UpdateDataMember(row, field, value)

### AddRow()
	Agrega una nueva fila a la tabla.

### InsertRow(rw, nofocus=false)

### TRCount()

### THCount()

### TDCount(td)

### CurrentTd()

### TrOfTd(td)

### RowIndexOfTd(td)

### CurrentRowIndex()

### ColIndexOfTd(td)

### CurrentColIndex()

### LeaveCell(td) 

### EnterCell(td)

### GetColumnDef()

### GetColumnDefOfTd(td)

### StartEdit(td,text,clear)

### ConfirmEdit(td, displaytext)

### CancelEdit(td)

### CellFocus(td)

### NavUp(active_cell)

### NavLeft(active_cell)

### NavRight(active_cell)

### NavDown(active_cell)

