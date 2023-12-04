
$name = "\033[1;35mYour Name\033[0m"; // \033 is the escape character for ASCII codes
$skills = [
    "\033[0;32mPHP\033[0m", 
    "\033[0;31mLaravel\033[0m", 
    "\033[0;36mSQL\033[0m", 
    // Add other skills with corresponding ASCII escape codes
];

echo "👋 Hi there! I'm $name, a backend developer passionate about crafting robust solutions and delivering seamless user experiences.\n\n";
echo "🚀 **Skills**:\n" . implode("\n", array_map(fn($skill) => "- $skill", $skills));
