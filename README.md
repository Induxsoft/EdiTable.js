# EdiTable.js
Inline table editing

Habilita la edición de tablas con ámplio soporte de teclado al estilo de hojas de cálculo.
## Tipos de columnas

### EdiTable.Const.Types.Text
	Indica un editor input(type="text") para todas las celdas de la columna.
	
### EdiTable.Const.Types.Number
	Indica un editor input(type="number") para todas las celdas de la columna.
	
### EdiTable.Const.Types.Date
	Indica un editor input(type="Date") para todas las celdas de la columna.
	
### EdiTable.Const.Types.DateTime
	Indica un editor input(type="DateTime") para todas las celdas de la columna.
	
### EdiTable.Const.Types.Memo
	Indica un editor textarea para todas las celdas de la columna.
	
### EdiTable.Const.Types.Check
	Indica un editor input(type="checkbox") para todas las celdas de la columna.
	
### EdiTable.Const.Types.Select
	Indica un editor Select para todas las celdas de la columna.
	
### EdiTable.Const.Types.Custom
	Indica un editor personalizado para todas las celdas de la columna.
	
### EdiTable.Const.Types.NoEditable
	 Todas las celdas de la columna no se pueden editar.



## Eventos

### EdiTable.Const.Events.EnterCell
	Ocurre cuando una celda toma el foco
	
	Argumentos suministrados por el evento
	* sender - Representa la instancia de la tabla que lo está generando.
	* colDef-Contiene el objeto de definición de columna correspondiente a la celda que generó el evento
	
### EdiTable.Const.Events.LeaveCell
	Ocurre caudno una celda pierde el foco

### EdiTable.Const.Events.StartEdition
	ocurre al momento de seleccionar la celda

### EdiTable.Const.Events.ConfirmEdition


### EdiTable.Const.Events.CancelEdition

### EdiTable.Const.Events.InputCreated

### EdiTable.Const.Events.BeforeUpdateCell
	Ocurre antes de definir el nuevo contenido de la celda

### EdiTable.Const.Events.BeforeSetInput
	Ocurre antes de definir el contenido de la celda

### EdiTable.Const.Events.FieldUpdated

### EdiTable.Const.Events.RowAdded
	Agrega una nueva fila a la tabla
	
	
	











## Métodos

	### Initialize()
		Inicializa la edición de la tabla.
		
	### GetTHead()

	### GetTBody()

	### ColumnsCount()

	### NavToHome()
		Mueve el cursor a la celda ubicada en la primera fila y primera columna.
	### NavToEnd()

	### NavToFirstCell()

	### NavToLastCell()

	### NavTo()

	### GetTrByIndex()

	### DeleteCurrentRow()

	### DeleteRow()

	### UpdateRow()

	### UpdateData()

	### UpdateDataRow()

	### UpdateDataMember()

	### AddRow()

	### InsertRow()

	### TRCount()

	### THCount()

	### TDCount()

	### CurrentTd()

	### TrOfTd()

	### RowIndexOfTd()

	### CurrentRowIndex()

	### ColIndexOfTd()

	### CurrentColIndex()

	### LeaveCell() * 

	### EnterCell()

	### GetColumnDef()

	### GetColumnDefOfTd()

	### StartEdit()

	### ConfirmEdit()

	### CancelEdit()

	### CellFocus()

	### NavUp()

	### NavLeft()

	### NavRight()

	### NavDown()
