# Hi Im Quack!
Owner and Founder of Quacked.Solutions
https://discord.com/channels/1143047298293698600/1419384283226701824

namespace Security {
    class Developer {
    private:
        const std::string name = "QuackLUA";

    public:
        // Core languages (medium-level)
        std::array<const char*, 5> fluent = {
            "LUA", "JS", "Assembly", "TypeScript"
        };

        // KINDA Professional toolkit
        std::vector<std::string> production_ready = {
            "Lua", "JavaScript",
            "HTML/CSS", "Java", "SQL",
            "Python", "PHP"
        };

        // What Do I Do Mostly When Modding
        std::array<const char*, 5> expertise = {
            "Reverse Engineering (x86, embedded firmware)",
            "Offensive Security (pentesting, exploit discovery)",
            "Defensive Security (incident response, architecture)"
        };

        inline const char* getFavoriteStack() const {
            return "LUA";
        }

        // FLEXS 
        struct Experience {
            std::string role = "Head Of Quacked.Solutions";
            std::string scale = "One Of The Only Exploit/Backdoor Modders";
            std::string built = "Code Obfuscation and Code Decompiling";
            std::string impact = "Protect Users who use PenTester Mods For Games";
            std::string leadership = "Develope Systems to allow Code To Operate";
        };
    };
}
