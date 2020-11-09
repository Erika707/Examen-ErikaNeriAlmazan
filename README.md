# Examen-ErikaNeriAlmazan
CREATE TABLA 'cliente'
(
'id' INT(11),
'nombre' VACHAR(45),
);

CREATE TABLA'factura'
(
'numero' INT (11),
'fecha' DATE,
'id_cliente' INT (11),
);

CREATE 'detalle_fatura'
(
'num_detalle' INT (11),
'numero_detalle' INT (11),
'numero_fatura' INT (11),
'id_producto' INT(11),
'cantidad' INT(11),
);

CREATE TABLA 'producto'
(
'id' INT(11),
'nombre' VARCHAR(45),
'precio' DECIMAL (6,2),
'stock' INT(11),
);

