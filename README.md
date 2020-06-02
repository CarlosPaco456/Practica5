# Practica5
![index](https://user-images.githubusercontent.com/65795550/83579740-1cd0f880-a508-11ea-808b-b6632df4d1c1.JPG)
![editar](https://user-images.githubusercontent.com/65795550/83579736-1b9fcb80-a508-11ea-93e8-52a67b3cc8a3.JPG)
![nuevo](https://user-images.githubusercontent.com/65795550/83579738-1c386200-a508-11ea-82f1-8b2919f22abf.JPG)
![eliminar](https://user-images.githubusercontent.com/65795550/83579742-1e022580-a508-11ea-81ef-64ddbee3d9bf.JPG)
![indexfin](https://user-images.githubusercontent.com/65795550/83579741-1cd0f880-a508-11ea-8a18-b3cfb967e721.JPG)
[bd_almacen.txt](https://github.com/CarlosPaco456/Practica5/files/4720196/bd_almacen.txt)
/*
Navicat MySQL Data Transfer

Source Server         : base emergentes
Source Server Version : 100408
Source Host           : localhost:3306
Source Database       : bd_almacen

Target Server Type    : MYSQL
Target Server Version : 100408
File Encoding         : 65001

Date: 2020-06-02 19:35:55
*/

SET FOREIGN_KEY_CHECKS=0;

-- ----------------------------
-- Table structure for productos
-- ----------------------------
DROP TABLE IF EXISTS `productos`;
CREATE TABLE `productos` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `descripcion` varchar(255) DEFAULT NULL,
  `stock` int(10) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=utf8;

-- ----------------------------
-- Records of productos
-- ----------------------------
INSERT INTO `productos` VALUES ('1', 'Celular Samsung J7', '105');
INSERT INTO `productos` VALUES ('2', 'Laptop Sony', '100');
INSERT INTO `productos` VALUES ('3', '                            Ipad pro 10\r\n                        ', '50');
INSERT INTO `productos` VALUES ('4', 'Tablet huawey', '150');
INSERT INTO `productos` VALUES ('6', ' Laptop HP                           \r\n                        ', '150');
SET FOREIGN_KEY_CHECKS=1;
