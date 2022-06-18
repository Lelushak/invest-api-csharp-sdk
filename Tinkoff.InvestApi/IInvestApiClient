using Tinkoff.InvestApi.V1;

namespace Tinkoff.InvestApi;

public interface IInvestApiClient
{
    InstrumentsService.InstrumentsServiceClient           Instruments      { get; }
    MarketDataService.MarketDataServiceClient             MarketData       { get; }
    MarketDataStreamService.MarketDataStreamServiceClient MarketDataStream { get; }
    OperationsService.OperationsServiceClient             Operations       { get; }
    OrdersService.OrdersServiceClient                     Orders           { get; }
    OrdersStreamService.OrdersStreamServiceClient         OrdersStream     { get; set; }
    SandboxService.SandboxServiceClient                   Sandbox          { get; }
    StopOrdersService.StopOrdersServiceClient             StopOrders       { get; }
    UsersService.UsersServiceClient                       Users            { get; }
}
