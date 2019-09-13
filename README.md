# PhpStorm Live Templates для API Bitrix

## Установка

Разместите файл Bitrix.xml в папке шаблонов PhpStorm
- Windows: *USER_HOME_DIR*\\.PhpStorm*VERSION*\config\templates<br/>
<sup>*USER_HOME_DIR* в WindowsXP - C:\Documents and Settings\\*YOUR_USER*, в Windows Vista и Windows 10 - C:\Users\\*YOUR_USER*</sup>
- Linux: ~/.PhpStorm*VERSION*/config/templates
- Mac OS: ~/Library/Preferences/PhpStorm*VERSION*/templates

## API

### CEvent

- *bxes* - CEvent::Send

### CIBlockElement

- *bxibea* - CIBlockElement::Add
- *bxibed* - CIBlockElement::Delete
- *bxibegbi* - CIBlockElement::GetByID
- *bxibegl* - CIBlockElement::GetList
- *bxibegp* - CIBlockElement::GetProperty
- *bxibespve* - CIBlockElement::SetPropertyValuesEx
- *bxibeu* - CIBlockElement::Update

### CIBlockSection

- *bxibsa* - CIBlockSection::Add
- *bxibsd* - CIBlockSection::Delete
- *bxibsgbi* - CIBlockSection::GetByID
- *bxibsgl* - CIBlockSection::GetList
- *bxibsgnc* - CIBlockSection::GetNavChain
- *bxibsu* - CIBlockSection::Update

### CModule

- *bxmim* - CModule::IncludeModule

### COption

- *bxogos* - COption::GetOptionString
- *bxoro* - COption::RemoveOption
- *bxosos* - COption::SetOptionString

### Диагностика/отладка

- *bxdiagd* - Bitrix\Main\Diag\Debug::dump
- *bxdiaggbt* - Bitrix\Main\Diag\Helper::getBackTrace
- *bxdiagst* - Bitrix\Main\DB\Connection::startTracker
- *bxdiagtl* - Bitrix\Main\Diag\Debug::getTimeLabels
- *bxdiagwtf* - Bitrix\Main\Diag\Debug::writeToFile
