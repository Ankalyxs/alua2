# alua2
const sequelize = require ('sequelize');
const sequelize = new sequelize ({
    dialect: 'sqlite',
    Storage: ' ./datebase.sqlite'
})
module.exports = sequelize;
