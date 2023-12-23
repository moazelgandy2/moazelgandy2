<code><?php
$name = "Moaz";
$skills = ["PHP", "Laravel", "SQL", "HTML", "CSS", "JS", "Git", "WordPress"];
echo "👋 Hi there! I'm $name, a backend developer passionate about crafting robust solutions and delivering seamless user experiences.\n\n";
echo "🚀 **Skills**:\n" . implode("\n", array_map(fn($skill) => "- $skill", $skills));</code>
